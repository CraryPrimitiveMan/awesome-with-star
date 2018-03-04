# Information comes from [herrbischoff/awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line)
<h1><img src="https://cdn.rawgit.com/herrbischoff/awesome-macos-command-line/master/assets/logo.svg" alt="Awesome OS X Command Line" width="600"></h1>

> A curated list of shell commands and tools specific to OS X.
>
> _“You don’t have to know everything. You simply need to know where to find it when necessary.” (John Brunner)_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/herrbischoff/awesome-macos-command-line.svg?branch=master)](https://travis-ci.org/herrbischoff/awesome-macos-command-line)

If you want to contribute, you are highly encouraged to do so. Please read the [contribution guidelines](contributing.md).

For more terminal shell goodness, please also see this list's sister list [Awesome Command Line Apps](https://github.com/herrbischoff/awesome-command-line-apps).

## Contents

- [Appearance](#appearance)
    - [Transparency](#transparency)
    - [Wallpaper](#wallpaper)
- [Applications](#applications)
    - [App Store](#app-store)
    - [Apple Remote Desktop](#apple-remote-desktop)
    - [Contacts](#contacts)
    - [Google](#google)
    - [iTunes](#itunes)
    - [Mail](#mail)
    - [Safari](#safari)
    - [Sketch](#sketch)
    - [Skim](#skim)
    - [Terminal](#terminal)
    - [TextEdit](#textedit)
    - [Visual Studio Code](#visual-studio-code)
- [Backup](#backup)
    - [Time Machine](#time-machine)
- [Developer](#developer)
    - [Vim](#vim)
    - [Xcode](#xcode)
- [Dock](#dock)
- [Documents](#documents)
- [Files, Disks and Volumes](#files-disks-and-volumes)
    - [APFS](#apfs)
    - [Disk Images](#disk-images)
- [Finder](#finder)
    - [Files and Folders](#files-and-folders)
    - [Layout](#layout)
    - [Metadata Files](#metadata-files)
    - [Opening Things](#opening-things)
- [Fonts](#fonts)
- [Functions](#functions)
- [Hardware](#hardware)
    - [Bluetooth](#bluetooth)
    - [Harddisks](#harddisks)
    - [Hardware Information](#hardware-information)
    - [Infrared Receiver](#infrared-receiver)
    - [Power Management](#power-management)
- [Input Devices](#input-devices)
    - [Keyboard](#keyboard)
- [Launchpad](#launchpad)
- [Media](#media)
    - [Audio](#audio)
    - [Video](#video)
- [Networking](#networking)
    - [Bonjour](#bonjour)
    - [DHCP](#dhcp)
    - [DNS](#dns)
    - [Hostname](#hostname)
    - [Network Preferences](#network-preferences)
    - [Networking Tools](#networking-tools)
    - [SSH](#ssh)
    - [TCP/IP](#tcpip)
    - [TFTP](#tftp)
    - [Wi-Fi](#wi-fi)
- [Package Managers](#package-managers)
- [Printing](#printing)
- [Security](#security)
    - [Application Firewall](#application-firewall)
    - [Gatekeeper](#gatekeeper)
    - [Passwords](#passwords)
    - [Physical Access](#physical-access)
    - [Wiping Data](#wiping-data)
- [Search](#search)
    - [Find](#find)
    - [Locate](#locate)
- [System](#system)
    - [AirDrop](#airdrop)
    - [AppleScript](#applescript)
    - [Basics](#basics)
    - [Clipboard](#clipboard)
	- [Date and Time](#date-and-time)
    - [FileVault](#filevault)
    - [Information/Reports](#informationreports)
    - [Install OS](#install-os)
    - [Kernel Extensions](#kernel-extensions)
    - [LaunchAgents](#launchagents)
    - [LaunchServices](#launchservices)
    - [Login Window](#login-window)
    - [Memory Management](#memory-management)
    - [Notification Center](#notification-center)
    - [QuickLook](#quicklook)
    - [Remote Apple Events](#remote-apple-events)
    - [Root User](#root-user)
    - [Safe Mode Boot](#safe-mode-boot)
    - [Screenshots](#screenshots)
    - [Software Installation](#software-installation)
    - [Software Update](#software-update)
    - [Software Version](#software-version)
    - [Spotlight](#spotlight)
    - [System Integrity Protection](#system-integrity-protection)
- [Terminal](#terminal)
    - [Alternative Terminals](#alternative-terminals)
    - [Shells](#shells)
    - [Terminal Fonts](#terminal-fonts)


## Appearance

### Transparency

#### Transparency in Menu and Windows
```bash
# Reduce Transparency
defaults write com.apple.universalaccess reduceTransparency -bool true

# Restore Default Transparency
defaults write com.apple.universalaccess reduceTransparency -bool false
```


### Wallpaper

#### Set Wallpaper
```bash
# Up to Mountain Lion
osascript -e 'tell application "Finder" to set desktop picture to POSIX file "/path/to/picture.jpg"'

# Since Mavericks
sqlite3 ~/Library/Application\ Support/Dock/desktoppicture.db "update data set value = '/path/to/picture.jpg'" && killall Dock
```


## Applications

### App Store

#### List All Apps Downloaded from App Store

```bash
# Via find
find /Applications -path '*Contents/_MASReceipt/receipt' -maxdepth 4 -print |\sed 's#.app/Contents/_MASReceipt/receipt#.app#g; s#/Applications/##'

# Via Spotlight
mdfind kMDItemAppStoreHasReceipt=1
```

#### Show Debug Menu
Works up to Yosemite.
```bash
# Enable
defaults write com.apple.appstore ShowDebugMenu -bool true

# Disable (Default)
defaults write com.apple.appstore ShowDebugMenu -bool false
```


### Apple Remote Desktop

#### Kickstart Manual Pages
```bash
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -help
```

#### Activate And Deactivate the ARD Agent and Helper
```bash
# Activate And Restart the ARD Agent and Helper
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -activate -restart -agent -console

# Deactivate and Stop the Remote Management Service
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -stop 
```

#### Enable and Disable Remote Desktop Sharing
```bash
# Allow Access for All Users and Give All Users Full Access
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -configure -allowAccessFor -allUsers -privs -all

# Disable ARD Agent and Remove Access Privileges for All Users
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -configure -access -off
```

#### Remove Apple Remote Desktop Settings
```bash
sudo rm -rf /var/db/RemoteManagement ; \
sudo defaults delete /Library/Preferences/com.apple.RemoteDesktop.plist ; \
defaults delete ~/Library/Preferences/com.apple.RemoteDesktop.plist ; \
sudo rm -r /Library/Application\ Support/Apple/Remote\ Desktop/ ; \
rm -r ~/Library/Application\ Support/Remote\ Desktop/ ; \
rm -r ~/Library/Containers/com.apple.RemoteDesktop
```

### Contacts

#### Debug Mode
```bash
# Enable
defaults write com.apple.addressbook ABShowDebugMenu -bool true

# Disable (Default)
defaults write com.apple.addressbook ABShowDebugMenu -bool false
```

### Google

#### Uninstall Google Update
```bash
~/Library/Google/GoogleSoftwareUpdate/GoogleSoftwareUpdate.bundle/Contents/Resources/ksinstall --nuke
```

### iTunes

#### Keyboard Media Keys
This works up to Yosemite. System Integrity Protection was introduced in El Capitan which prevents system Launch Agents from being unloaded.
```bash
# Stop Responding to Key Presses
launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist

# Respond to Key Presses (Default)
launchctl load -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

From El Capitan onwards, you can either disable SIP or resort to a kind of hack, which will make iTunes inaccessible to any user, effectively preventing it from starting itself or its helpers. Be aware that for all intents and purposes this will trash your iTunes installation and may conflict with OS updates down the road.
```bash
sudo chmod 0000 /Applications/iTunes.app
```

### Mail

#### Show Attachments as Icons

```bash
defaults write com.apple.mail DisableInlineAttachmentViewing -bool yes
```

#### Vacuum Mail Index
The AppleScript code below will quit Mail, vacuum the SQLite index, then re-open Mail. On a large email database that hasn't been optimized for a while, this can provide significant improvements in responsiveness and speed.
```applescript
(*
Speed up Mail.app by vacuuming the Envelope Index
Code from: http://web.archive.org/web/20071008123746/http://www.hawkwings.net/2007/03/03/scripts-to-automate-the-mailapp-envelope-speed-trick/
Originally by "pmbuko" with modifications by Romulo
Updated by Brett Terpstra 2012
Updated by Mathias Törnblom 2015 to support V3 in El Capitan and still keep backwards compatibility
Updated by Andrei Miclaus 2017 to support V4 in Sierra
*)

tell application "Mail" to quit
set os_version to do shell script "sw_vers -productVersion"
set mail_version to "V2"
considering numeric strings
    if "10.10" <= os_version then set mail_version to "V3"
    if "10.12" < os_version then set mail_version to "V4"
end considering

set sizeBefore to do shell script "ls -lnah ~/Library/Mail/" & mail_version & "/MailData | grep -E 'Envelope Index$' | awk {'print $5'}"
do shell script "/usr/bin/sqlite3 ~/Library/Mail/" & mail_version & "/MailData/Envelope\\ Index vacuum"

set sizeAfter to do shell script "ls -lnah ~/Library/Mail/" & mail_version & "/MailData | grep -E 'Envelope Index$' | awk {'print $5'}"

display dialog ("Mail index before: " & sizeBefore & return & "Mail index after: " & sizeAfter & return & return & "Enjoy the new speed!")

tell application "Mail" to activate
```

### Safari

#### Change Default Fonts
```bash
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily Georgia
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFontSize 16
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily Menlo
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFixedFontSize 14
```

#### Enable Develop Menu and Web Inspector
```bash
defaults write com.apple.Safari IncludeInternalDebugMenu -bool true && \
defaults write com.apple.Safari IncludeDevelopMenu -bool true && \
defaults write com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey -bool true && \
defaults write com.apple.Safari com.apple.Safari.ContentPa

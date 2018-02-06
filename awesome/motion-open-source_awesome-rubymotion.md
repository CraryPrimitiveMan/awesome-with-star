# Information comes from [motion-open-source/awesome-rubymotion](https://github.com/motion-open-source/awesome-rubymotion)
<h1 align="center">
	<img width="1024" src="https://github.com/motion-open-source/awesome-rubymotion/raw/master/awesome-rubymotion2x.png" alt="Awesome RubyMotion">
	<br>
	<br>
</h1>

[RubyMotion](https://en.wikipedia.org/wiki/RubyMotion) is an implementation of the Ruby programming language that compiles into native app's that run on iOS, macOS and Android. RubyMotion is a commercial product created by Laurent Sansonetti for HipByte and is based on MacRuby for macOS. RubyMotion works exclusively on macOS.

This list categorized community-driven collection of awesome RubyMotion example apps, libraries, tools, frameworks, software and resources.  Sharing, suggestions and contributions are always welcome!

Please take a look at the [contribution guidelines and quality standard](https://github.com/motion-open-source/awesome-rubymotion/blob/master/CONTRIBUTING.md) first.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


## Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


  - [Apps](#apps)
    - [Example Android Apps](#example-android-apps)
    - [Example iOS Apps](#example-ios-apps)
    - [Example Hybrid (iOS/Andriod) App's](#example-hybrid-iosandriod-apps)
    - [Example macOS Apps](#example-os-x-apps)
    - [Example tvOS Apps](#example-tvos-apps)
    - [Open Source macOS Apps](#open-source-os-x-apps)
    - [Open Source iOS Apps](#open-source-ios-apps)
    - [Propriety macOS Apps](#propriety-os-x-apps)
    - [Propriety iOS Apps](#propriety-ios-apps)
  - [Developer Tools](#developer-tools)
  - [Editors & RM](#editors--rm)
  - [Libraries, Frameworks and Wrappers](#libraries-frameworks-and-wrappers)
    - [Android](#android)
    - [Apple API Wrappers](#apple-api-wrappers)
    - [Authorization](#authorization)
    - [Data Protocols](#data-protocols)
    - [Database](#database)
    - [Debugging & Error Reporting](#debugging--error-reporting)
    - [Dependencies Management](#dependencies-management)
    - [Device support](#device-support)
    - [Encryption](#encryption)
    - [Frameworks](#frameworks)
    - [Game Development](#game-development)
    - [Graphical User Interface](#graphical-user-interface)
      - [GUI Frameworks](#gui-frameworks)
      - [Autolayout](#autolayout)
      - [Input](#input)
      - [iOS](#ios)
      - [Forms](#forms)
      - [Menu's & Toolbars](#menus--toolbars)
      - [Icons](#icons)
      - [Hybrid](#hybrid)
      - [Element Wrappers](#element-wrappers)
    - [Graphic Libraries](#graphic-libraries)
    - [Localization](#localization)
    - [Models & Core Data](#models--core-data)
    - [Networking](#networking)
    - [Project Management](#project-management)
    - [SaaS API Wrappers](#saas-api-wrappers)
    - [Scheduling](#scheduling)
    - [Screenshots](#screenshots)
    - [Software Design Patterns](#software-design-patterns)
    - [Templates](#templates)
    - [Testing](#testing)
    - [Updates](#updates)
  - [Books](#books)
  - [Tutorials](#tutorials)
    - [iOS Tutorials](#ios-tutorials)
    - [macOS Tutorials](#os-x-tutorials)
    - [Tutorial Screencasts](#tutorial-screencasts)
  - [Presentations](#presentations)
  - [Resources](#resources)
  - [Thanks](#thanks)
- [Other Awesome Lists](#other-awesome-lists)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Apps

### Example Android Apps
* [Android RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/android) - Collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [Rubymotion-android-cookbook](https://github.com/IconoclastLabs/rubymotion-android-cookbook) - Awesome rm cookbook examples for android. :star:27


### Example iOS Apps
* [IOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/ios) - Collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [Custom Table View Cell with IB and RM](https://github.com/hackedunit/custom-cell) - Custom Table View Cell using Interface Builder with RubyMotion.
* [MotionKit iOS Samples](https://github.com/motion-kit/motion-kit/tree/master/samples/ios) - iOS Example Apps made with MotionKit.
* [Motion Dropbox Example](https://github.com/mipmip/motion-dropbox-example) - App for demonstrating how to use official Dropbox API v2 SDK.
* [Big Nerd Ranch Guide to iOS Programming Example in RubyMotion](https://github.com/jimweirich/bnr-ios-rubymotion) - RubyMotion code examples from the book. :star:41
* [Motion-webview](https://github.com/tvandervossen/motion-webview) - Simple RubyMotion example project to wrap a full-screen HTML5 app into an iOS app. :star:52


### Example Hybrid (iOS/Andriod) App's
[RubyMotion Hybrid Sample](https://github.com/HipByte/rubymotion-hybrid-sample) - Example from HipByte of a RubyMotion hybrid (iOS + Android) app.


### Example macOS Apps
* [MacOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/osx) - Collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [Mctv-mac-osx](https://github.com/Motioncasts/mctv-mac-osx) - Demo Pomodoro Technique Timer App. :star:4
* [Motion-osx-ib](https://github.com/MarkVillacampa/motion-osx-ib) - This is an example on how to use the ib gem in a macOS RubyMotion 2.0 application. :star:4
* [Motion-treeview-coredata](https://github.com/mipmip/motion-treeview-coredata) - Port of the example from Connecting NSOutlineView to Core Data in 10.6 Part 1: Ordered Trees to RubyMotion. :star:5
* [Rm-osx-kartta](https://github.com/masal/rm-osx-kartta) - RubyMotion / macOS map viewer for Finnish topographical maps. :star:1
* [MotionKit macOS Samples](https://github.com/motion-kit/motion-kit/tree/master/samples/osx) - macOS Example Apps made with MotionKit.
* [Rubymotion-avfoundation](https://github.com/superplussed/rubymotion-avfoundation) - Simple OSX app using AVFoundation to stream, record, and transcode video. :star:6
* [Motion SourceList Boilerplate](https://github.com/mipmip/motion-sourcelist-boilerplate) - RubyMotion boilerplate app for Mac macOS implementing a view based Source List. :star:9
* [Menubar-popover](https://github.com/JonasNielsen/menubar-popover) - Example app to show how to use NSPopopver from the menubar. :star:10


### Example tvOS Apps
* [TvOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/tvos) - Collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.


### Open Source macOS Apps
* [Timer-for-tick](https://codelation.com/timer-for-tick) [GitHub project](https://github.com/codelation/tick-timer) - RubyMotion menu bar app for tracking time with http://tickspot.com. :star:3
* [Presence](https://github.com/calmyournerves/presence) - Desktop Menu Bar for [Uberzeit](https://github.com/ninech/uberzeit), a self hosted time tracking platform. :star:4
* [MemoryTamer](https://github.com/henderea/MemoryTamer) - RubyMotion application for keeping memory usage in check. [http://www.memorytamer.com/](http://www.memorytamer.com/). :star:11


### Open Source iOS Apps
* [Buku-live-ios-rubymotion](https://github.com/mswezey/buku-live-ios-rubymotion) - iOS app built in rubymotion for music festival RFID activation. :star:1
* [BeerJudge](https://github.com/OTGApps/BeerJudge) - iOS app for identifing different off flavors and aromas in a beer. :star:21


### Propriety macOS Apps
* [Versatil Markdown](http://versatilapp.com) - Note taking app built around Markdown and geared for power users.


### Propriety iOS Apps



## Developer Tools
* [Objc2rubymotion](https://github.com/bensheldon/objc2rubymotion) - convert objective-c code to rubymotion. :star:26
* [MLogger](https://motionobj.com/mlogger/) - Simple, log server for development.


## Editors & RM
* [Vim tab completion for RubyMotion](http://crypt.codemancers.com/posts/2013-05-01-vim-tabcompletion-for-rubymotion/) - a quick rundown on setting up tab completion in vim for RubyMotion.
* [Atom-objc-2-rubymotion](https://github.com/ahmetabdi/atom-objc-2-rubymotion) - Objective-C to RubyMotion converter for atom. :star:5
* [Emacs motion-mode.el](https://github.com/ainame/motion-mode) - a package to provide emacs' major mode for RubyMotion enviroment. :star:41
* [SublimeRubyMotionBuilder](https://github.com/RubyMotionJP/SublimeRubyMotionBuilder) - Sublime Text 2 and 3 plugin to simplify RubyMotion developing. :star:159
* [RubyMine & RubyMotion](https://www.jetbrains.com/ruby/help/rubymotion.html) - RubyMine integrates with RubyMotion and helps create applications for iOS.


## Libraries, Frameworks and Wrappers

### Android

Because Android support is quite new we're keeping the libraries together in this section.

* [BluePotion](https://github.com/infinitered/bluepotion) - BluePotion is the Android version of RedPotion. (ALPHA). :star:68
* [Toaster](https://github.com/jamonholmgren/toaster) - RubyMotion-android 'Toast' gem. Makes working with Android toasts really easy. :star:1
* [Motion-maven](https://github.com/HipByte/motion-maven) - motion-maven lets you automatically manage 3rd-party Java dependencies in RubyMotion for Android projects using Maven. :star:17


### Apple API Wrappers
* [Motion.h](https://github.com/kastiglione/motion.h) - Expose iOS and macOS system libraries in RubyMotion. :star:58
* [MapKitWrapper](https://github.com/weibel/MapKitWrapper) - Make dealing with MapKit less painful for RubyMotion. :star:46
* [Medic](https://github.com/ryanlntn/medic) - Is HealthKit's verbose and convoluted API driving you mad? Quick! You need a medic. :star:22
* [Motion-accessibility](https://github.com/austinseraphin/motion-accessibility) - Making accessibility accessible. RubyMotion Wrappers around the UIAccessibility protocols. Easily interact with Apple's impressive array of assistive technologies, including VoiceOver. :star:43
* [Vendor](https://github.com/holgersindbaek/Vendor) - RubyMotion StoreKit Wrapper that allows you to buy, restore and get product info on your in app purchases and subscriptions. :star:19
* [Motion-addressbook](https://github.com/alexrothenberg/motion-addressbook) - RubyMotion wrapper around the iOS & macOS Address Book frameworks. :star:93
* [Helu](https://github.com/ivanacostarubio/helu) - RubyMotion wrapper for the Store Kit Framework. :star:54
* [Motion-speech](https://github.com/macfanatic/motion-speech) - Easy text-to-speech wrapper for AVSpeechSynthesizer in iOS 7. :star:11
* [Motion-keychain](https://github.com/IconoclastLabs/motion-keychain) - The motion-keychain gem is a simple wrapper for Keychain on iOS and macOS. Makes using Keychain APIs as easy as NSUserDefaults. :star:36
* [Motion-settings-bundle](https://github.com/qrush/motion-settings-bundle) - Create a Settings.bundle for your RubyMotion app. :star:116
* [Motion-Social](https://github.com/ivanacostarubio/motion-social) - Wrapper around the Social Framework. :star:12


### Authorization
* [Can_i](https://github.com/macfanatic/can_i) - RubyMotion wrapper providing a simple DSL for role authorization, similar to the CanCan gem. :star:15


### Data Protocols
* [Motion-csv](https://github.com/OTGApps/motion-csv) - RubyMotion friendly CSV parser gem. :star:20
* [Meteor-motion](https://github.com/whitesmith/meteor-motion) - Wrapper for Meteor DDP with support for Motion Model. :star:10


### Database
* [Motion-firebase](https://github.com/colinta/motion-firebase) - RubyMotion wrapper for the Firebase SDK. :star:45
* [Yapper](https://github.com/kareemk/yapper) - ORM for YapDatabase which is schemaless, very fast (thanks to YapDatabase's architecture), has chainable criteria, one-many relationships, on-the-fly reindexing and is thread-safe. :star:30
* [Couchmotion](https://github.com/jannishuebl/couchmotion) - API for using Couchbase(CouchDB) a schemaless database with Rubymotion for Android and iOS. :star:17
* [Motion-sqlite3](https://github.com/mattgreen/motion-sqlite3) - Minimal wrapper over the SQLite 3 C API for RubyMotion. :star:33


### Debugging & Error Reporting
* [Motion-reveal](https://github.com/diogoandre/motion-reveal) - Easy way to add the Reveal framework to your Rubymotion project. :star:18
* [Crittercism](https://github.com/andrewhavens/crittercism) - Easily add crash reporting to your RubyMotion app with Crittercism. :star:4
* [Motion_print](https://github.com/OTGApps/motion_print) - RubyMotion friendly console logger and debugging tool. Use it to output pretty formatted objects to the REPL. :star:31
* [Awesome_print_motion](https://github.com/michaeldv/awesome_print_motion) - Port of the awesome_print gem to RubyMotion. :star:49
* [Motion-colorize](https://github.com/clayallsopp/motion-colorize) - Add some color to your RubyMotion output. :star:19
* [Motion-xray](https://github.com/colinta/motion-xray) - iOS Inspector that runs inside your app, so you can debug and analyze from your device in real-world situations. :star:575


### Dependencies Management
* [MotionBundler](https://github.com/archan937/motion-bundler) - Require and mock Ruby gems (including their dependencies) within RubyMotion applications. :star:103
* [Motion-acknowledgements](https://github.com/OTGApps/motion-acknowledgements) - This gem makes it easy to include the CocoaPods acknowledgements file in your application. :star:33


### Device support
* [Motion-distance](https://github.com/willrax/motion-distance) - Easy distance tracking for RubyMotion projects. :star:22
* [Motion-capture](https://github.com/dblandin/motion-capture) - AVFoundation wrapper to support custom camera controllers. :star:12


### Encryption
* [Motion-bitmask](https://github.com/buffpojken/motion-bitmask) - Simple implementation of generic bitmasks for RubyMotion.
* [Rm-digest](https://github.com/tmeinlschmidt/rm-digest) - MD5 and SHA1 digest for RubyMotion (gem). :star:5


### Frameworks
* [BubbleWrap](http://rubymotion.github.io/BubbleWrap) - Collection of (tested) helpers and wrappers used to wrap CocoaTouch code and provide more Ruby like APIs.
* [Sugarcube](https://github.com/rubymotion/sugarcube) - These extensions hope to make development in RubyMotion more enjoyable by tacking 'UI' methods onto the base classes (String, Fixnum, Numeric). With sugarcube, you can create a color from an integer or symbol, or create a UIFont or UIImage from a string. :star:437
* [RubyMotionQuery - RMQ](http://infinitered.com/rmq) - UI Library for RubyMotion. Fast, non-polluting, & chaining; it’s like jQuery for RubyMotion + stylesheets, animations, events, and more.
* [MotionPrime](http://prime.droidlabs.pro) - MotionPrime is yet another framework written on RubyMotion for creating really fast iOS applications.
* [Elevate](https://github.com/mattgreen/elevate) - Stop scattering your domain logic across your view controller. Consolidate it to a single conceptual unit with Elevate. :star:135
* [RedPotion](https://github.com/infinitered/redpotion) - RedPotion combines RMQ, ProMotion, CDQ, AFMotion, and more for the perfect mix to develop in RubyMotion fast. :star:229
* [Motion-support](https://github.com/rubymotion/motion-support) - Port of ActiveSupport to RubyMotion. :star:135
* [ProMotion](https://github.com/infinitered/ProMotion) - Full featured RubyMotion framework that makes iPhone development less like Objective-C and more like Ruby, designed to get up and running fast. :star:1272
* [ProMotion-XLForm](https://github.com/bmichotte/ProMotion-XLForm) - ProMotion-XLForm is a ProMotion plugin for XLForm. :star:21
* [ProMotion-form](https://github.com/infinitered/ProMotion-form) - ProMotion::FormScreen - forms the ProMotion way. :star:21
* [ProMotion-iap](https://github.com/infinitered/ProMotion-iap) - ProMotion-iap is in-app purchase notification support for the popular RubyMotion gem ProMotion. :star:19
* [ProMotion-menu](https://github.com/infinitered/ProMotion-menu) - RubyMotion gem allowing you to easily setup a facebook or Path style hidden slide menu easily with the ProMotion gem. :star:78
* [ProMotion-push](https://github.com/infinitered/ProMotion-push) - Push notification support for ProMotion. :star:17
* [ProMotion-map](https://github.com/infinitered/ProMotion-map) - ProMotion::MapScreen gem. Extracted from ProMotion core. :star:13


### Game Development
* [Joybox](https://github.com/rubymotion/Joybox) - Cocos2D & Box2D Wrapper for RubyMotion. :star:298


### Graphical User Interface


#### GUI Frameworks
* [IB](https://github.com/rubymotion/ib) - RubyMotion Interface Builder support, including outlets and actions. :star:266
* [Teacup](https://github.com/colinta/teacup) - Community-driven DSL for creating user interfaces on the iPhone. :star:637
* [MotionKit](https://github.com/motion-kit/motion-kit) - The RubyMotion layout and styling gem. :star:323
* [Motion-stylez](https://github.com/FluffyJack/motion-stylez) - RubyMotion stylesheet library based off RMQ. :star:4
* [Purplish-frame](https://github.com/hboon/purplish-frame) - Make working with rects, sizes and points more convenient with RubyMotion for iOS & macOS. :star:2


#### Autolayout
* [Purplish-layout](http://hboon.com/purplish-layout/) - RubyMotion wrapper for Auto Layout on iOS and macOS
* [Motion-layout](https://github.com/qrush/motion-layout) - Nice way to use Auto Layout in your RubyMotion app. :star:227


#### Input
* [MIMInputToolbar](https://github.com/FluffyJack/MIMInputToolbar) - Input accessory view for your UITextFields and UITextViews. :star:9
* [Motion-Wiretap](https://github.com/colinta/motion-wiretap) - Wrapper for KVO, gestures, UIControl events, and procs. Okay okay it's pretty much ReactiveCocoa in RubyMotion. :star:67


#### iOS
* [Geomotion](https://github.com/clayallsopp/geomotion) - Better iOS Geometry with RubyMotion. :star:97
* [Walt](https://github.com/clayallsopp/Walt) - Frictionless, hash-based iOS animations. :star:150
* [AccordionView](https://github.com/toamitkumar/AccordionView) - Create and add Accordions to your UIViews. :star:15
* [Motion-wizard](https://github.com/ijpiantanida/motion-wizard) - Gem to create wizard like view controllers in iOS. :star:37
* [Motion-imager](https://github.com/OTGApps/motion-imager) - Interactive iOS image viewer that does it all: double tap to zoom, flick to dismiss, et cetera. :star:26
* [Motion Swipe](https://github.com/dam13n/motion-swipe) - Tinder-like swipe gem. :star:12
* [Motion-dynamic-type](https://github.com/FluffyJack/motion-dynamic-type) - Simplifying even further iOS 7's Dynamic Type. :star:6
* [Indoctrinator](https://github.com/ryanlntn/indoctrinator) - Indoctrinator is a RubyMotion gem that provides a Path style tutorial view for iOS applications. :star:27
* [Motion-egg](https://github.com/GantMan/motion-egg) - Add an Easter egg to your app. :star:25


#### Forms
* [Formotion](https://github.com/clayallsopp/formotion) - Painless, productive views on iOS. :star:636
* [Motion-form](https://github.com/dblandin/motion-form) - RubyMotion forms made easy. :star:16


#### Menu's & Toolbars
* [MenuMotion](https://github.com/codelation/menu-motion) - RubyMotion wrapper for creating macOS menus. :star:45
* [Better_toolbar](https://github.com/FluffyJack/better_toolbars) - Better way to work with toolbars. :star:7
* [EverydayMenu](https://github.com/henderea/everyday-menu) - Easy way to define menu items and visually lay out menus for your macOS apps. :star:11
* [StatusBar](https://github.com/holgersindbaek/status_bar) - Notifications for the statusbar. :star:16


#### Icons
* [Ion_in_Motion](https://github.com/Brian-Egan/ion_in_motion) - Ridiculously easy use of IonIcons in UILabels, UIButtons, UIImages and more. IonIcons: http://ionicons.com/. :star:5
* [Moticons](https://github.com/andrewhavens/moticons) - The easiest way to add icons to your RubyMotion app. :star:16


#### Hybrid
* [Motion Floating Action Button](https://github.com/dam13n/motion-floating-action-button) - Material design floating action button. :star:7
* [Motion-awesome](https://github.com/derailed/motion-awesome) - DSL to easily create buttons and labels using the wonderful font-awesome library. :star:41
* [Motion-hybrid](https://github.com/balvig/motion-hybrid) - RubyMotion framework for easily making hybrid webview-centric iOS apps. :star:36


#### Element Wrappers
* [Simple_si](https://github.com/forrestgrant/simple_si) - RubyMotion wrapper for SIAlertView. :star:20
* [Motion-blitz](https://github.com/dblandin/motion-blitz) - RubyMotion wrapper for SVProgressHUD. :star:27


### Graphic Libraries
* [Motion-Plot](https://github.com/toamitkumar/motion-plot) - RubyMotion wrapper for CorePlot. :star:79
* [Motion-ocr](https://github.com/ferdev/motion-ocr) - RubyMotion wrapper for the OCR engine Tesseract. :star:63


### Localization
* [Motion-localization](https://github.com/akahigeg/motion-localization) - Localization rake task for RubyMotion. :star:2


### Models & Core Data
* [MotionModel](https://github.com/sxross/MotionModel) - Simple Model, Validation, and Input Mixins for RubyMotion. :star:199
* [NanoStoreInMotion](https://github.com/siuying/NanoStoreInMotion) - Wrapper for NanoStore, a lightweight schema-less key-value document database based on sqlite. :star:107
* [MotionDataWrapper](https://github.com/macfanatic/motion_data_wrapper) - Intuitive querying and persistence of Core Data models, using Xcode to define entities, validations, relationships and migrations. :star:69
* [Core Data Query - CDQ](https://github.com/infinitered/cdq) - Easy-to-set-up library for using Core Data without Xcode. :star:177
* [Motion-bindable](https://github.com/nathankot/motion-bindable) - Create two-way bindings between your models and view objects (or any other object.)
* [Turnkey](https://github.com/seldomatt/TurnKey) - Utility for saving custom objects to NSUserDefaults using NSKeyedArchiver and NSKeyedUnarchiver. :star:34
* [PackingPeanut](http://gantman.github.io/PackingPeanut/) - App persistent data for RubyMotion Android and iOS.


### Networking
* [RackMotion](https://github.com/drewbug/RackMotion) - Intercept and alter HTTP requests and responses in RubyMotion. :star:42
* [Motion-net-service](https://github.com/fearoffish/motion-net-service) - RubyMotion wrapper providing a simple DSL for the Bonjour (NSNetService) zero configuration network protocol. :star:27
* [Apex](https://github.com/infinitered/apex) - Apex is a RubyMotion web framework for macOS. It uses GCDWebServer under the hood and provides a Sinatra-like router and DSL. :star:33
* [AFMotion](https://github.com/clayallsopp/afmotion) - RubyMotion wrapper for AFNetworking. :star:221


### Project Management
* [Motion-schemes](https://github.com/siuying/motion-schemes) - Expand RubyMotion build system to support building multiple apps from one project. :star:26
* [Motion-config-vars](https://github.com/jamescallmebrent/motion-config-vars) - Heroku-style environment configuration for RubyMotion. :star:37
* [Motion-env](https://github.comclayallsopp/motion-env) - Sync ENV variables between Rakefile and RubyMotion.
* [Motion-my_env](https://github.com/ainame/motion-my_env) - Simple environment variable solution for RubyMotion. :star:9


### SaaS API Wrappers
* [Motionscan](https://github.com/jjaffeux/Motionscan) - RubyMotion wrapper around the image recognition SDK of Moodstocks.com. :star:18
* [Motion-phrase](https://github.com/phrase/motion-phrase) - Connect your RubyMotion project with PhraseApp for easy app internationalization. Translatable strings are exported while browsing the app and then manageable through the PhraseApp translation editor. :star:11
* [Purple-monkey](https://github.com/hboon/purple-monkey) - Barebones wrapper for working with MailChimp on iOS/macOS using RubyMotion. :star:6
* [Motion-tickspot](https://github.com/codelation/motion-tickspot) - RubyMotion wrapper for the http://tickspot.com API that works on iOS and macOS. :star:2
* [Motion-aws](https://github.com/jamonholmgren/motion-aws) - Provides iOS and macOS connectivity to AWS services. :star:2
* [Motion-ocean](https://github.com/brianpattison/motion-ocean) - RubyMotion wrapper for the http://digitalocean.com API v2.0. :star:5
* [Sox](https://github.com/brilliantfantastic/sox) - RubyMotion wrapper for the Freshbooks API. :star:6
* [Twittermotion](https://github.com/clayallsopp/twittermotion) - RubyMotion wrapper for the iOS Twitter API. :star:42
* [Under-os-image](https://github.com/under-os/under-os-image) - The new simplified images processing API for the http://under-os.com/ project. :star:4
* [Motion-giphy](https://github.com/willrax/motion-giphy) - Nice wrapper around the http://giphy.com API. :star:5
* [Motion-installr](https://github.com/FluffyJack/motion-installr) - Ad-hoc deployment using the amazing Installr service! https://www.installrapp.com/ . :star:14
* [Under-os-image](https://github.com/under-os/under-os-image) - The new simplified images processing API for the http://under-os.com/ project. :star:4
* [MotionPanel](https://github.com/tombroomfield/motion_panel) - Native RubyMotion wrapper around the Mixpanel API. :star:7
* [MotionPaddle](https://github.com/henderea/motion-paddle) - RubyMotion gem for the Paddle framework. :star:1
* [Algolia Offline Search](https://github.com/algolia/motion-algolia-search) - Simple integration of Algolia Offline Search SDK (http://www.algolia.com/) in your RubyMotion application.


### Scheduling
* [Motion-launchpad](https://github.com/macfanatic/motion-launchpad) - Gem providing a DSL allowing you to schedule events on specific launches of your application.  'motion-takeoff' only supplies displaying an alert, this gem executes any code block. :star:14
* [Motion-takeoff](https://github.com/OTGApps/motion-takeoff) - Gem for scheduling stuff. You can use motion-takeoff to display messages at certain launch counts and schedule local notifications. :star:35


### Screenshots
* [Motion-screenshots](https://github.com/clayallsopp/motion-screenshots) - Automatic screenshots for your RubyMotion apps. :star:42
* [Motion-launchimages](https://github.com/brendanjcaffrey/motion-launchimages) - Automate taking your RubyMotion launch images. :star:5


### Software Design Patterns

* [Motion-pool](https://github.com/wooandoo/motion-pool) - Pool for RubyMotion. :star:1
* [Motion-state-machine](https://github.com/opyh/motion-state-machine) - Grand Central-aware, simple syntax for state machines. :star:74
* [Motion-objection](https://github.com/atomicobject/motion-objection) - RubyMotion wrapper for Objection. :star:26
* [Weak_attr_accessor](https://github.com/hboon/weak_attr_accessor) - Adds weak_attr_accessor that wraps objects with WeakRef, for RubyMotion. :star:6


### Templates

App project templates

* [MotionTemplate](https://github.com/IconoclastLabs/MotionTemplate) - Clean RubyMotion project for quickly templating a styled application. :star:65
* [Promotion-template](https://github.com/jamonholmgren/promotion-template) - Utilize the bells and whistles of ProMotion to hit the ground running. :star:11
* [Rubymotion_generators](https://github.com/andyw8/rubymotion_generators) - Provides boilerplate code templates for RubyMotion. :star:80
* [Motion-template-spritekit](https://github.com/meganemura/motion-template-spritekit) - SpriteKit project templates for RubyMotion (iOS/OSX/tvOS). :star:18


### Testing
* [MotionFixtures](https://github.com/farcaller/motion-fixtures) - Simple support for test fixtures. :star:6
* [WebStub](https://github.com/nathankot/webstub) - Easily stub out HTTP responses in RubyMotion specs. :star:96
* [Motion-stump](https://github.com/siuying/motion-stump) - Stubbing and mocking for RubyMotion. :star:47
* [Motion-frank](https://github.com/cyrusinnovation/motion-frank) - Gem to use integrate frank-cucumber into RubyMotion projects. :star:31
* [Motion-crescentia](https://github.com/Shirk/motion-crescentia) - RubyMotion wrapper for the Calabash BDD framework. :star:3
* [Motion-facon](https://github.com/chuyeow/facon) - Port of Facon mocking library to RubyMotion. :star:38
* [Guard-motion](https://github.com/mordaroso/guard-motion) - Guard::Motion automatically run your RubyMotion specs (much like autotest). :star:47
* [Motion-instabug](https://github.com/bmichotte/motion-instabug) - motion-instabug allows RubyMotion projects to easily embed the Instabug SDK and be submitted to the Instabug platform. :star:3
* [Motion-juxtapose](https://github.com/terriblelabs/motion-juxtapose) - Screenshot-driven assertions for testing Rails and RubyMotion applications. :star:52
* [Test Sweet](https://github.com/squidpunch/test_sweet) - Integration testing your RubyMotion applications the simple and sweet way. :star:4


### Updates
* [Motion-sparkle](https://github.com/webcracy/motion-sparkle) - motion-sparkle makes it easy to use Sparkle with your RubyMotion projects. :star:24


## Books
* [RubyMotion, iOS Development with Ruby](http://www.allitebooks.com/rubymotion/) - Author: Clay Allsopp (free download).
* [Building Mac macOS apps with RubyMotion](http://kickcode.com/building-mac-os-x-apps-with-rubymotion/) - Author: Elliott Draper.
* [Instant RubyMotion App Development](https://www.packtpub.com/application-development/instant-rubymotion-app-development) - Author: Gant Laborde.
* [RubyMotion iOS Development Essentials](https://www.packtpub.com/application-development/rubymotion-ios-development-essentials) - Author: Abhishek Nalwaya, Akshat Paul.


## Tutorials

* [Concurrency patterns in RubyMotion](http://blog.arkency.com/2014/08/concurrent-patterns-in-rubymotion/) - Article about working with Grand Central Dispatch in RubyMotion.
* [IBeacons and Rubymotion](https://teamstrobe.com/2014/02/07/ibeacons-with-rubymotion.html) - How to connect iBeacons and Rubymotion iBeacons with ProximityKit and Rubymotion


### iOS Tutorials

* [Rubymotion Tutorial](http://rubymotion-tutorial.com) - Make iOS Apps With Ruby.
* [Fabric & RubyMotion Tutorial](https://medium.com/@sammybauch/making-fabric-play-nice-with-rubymotion-48a593ac22d4#.uxe9mmczw) - Making Fabric Play Nice with RubyMotion.
* [Facebook iOS SDK](http://gavinmorrice.com/blog/posts/30-how-to-use-the-facebook-ios-sdk-in-your-rubymotion-project) - How To Use the Facebook iOS SDK In Your RubyMotion project.
* [RubyMotion Tutorial for Objective C Developers](http://hboon.com/rubymotion-tutorial-for-objective-c-developers/) - Getting experienced Objective C developers on board.


### macOS Tutorials

* [Let's Write a RubyMotion App: Part 1](http://code.tutsplus.com/tutorials/lets-write-a-rubymotion-app-part-1--cms-20612) - In this tutorial, you’ll build a painting application from scratch.
* [Custom Table View Cell with IB and RM](http://blog.nuventure.in/2014/12/19/custom-table-view-cell-using-interface-builder-with-rubymotion/) - Custom Table View Cell using Interface Builder with RubyMotion.

Chapters from the book Building Mac macOS apps with RubyMotion.

* [Working with NSTableView](http://kickcode.com/blog/2015/08/18/working-with-nstableview.html) - Working with NSTableView.
* [Dragging and dropping](http://kickcode.com/blog/2015/05/20/dragging-and-dropping-into-a-rubymotion-mac-os-x-app.html) - Dragging and dropping into your RubyMotion Mac macOS app.
* [Capturing video and audio](http://kickcode.com/blog/2015/05/06/capturing-video-and-audio-on-mac-os-x-with-rubymotion.html) - Capturing video and audio on Mac macOS with RubyMotion.
* [Previewing video and audio when capturing](http://kickcode.com/blog/2015/05/07/previewing-video-and-audio-when-capturing-on-mac-os-x-with-rubymotion.html) - Previewing video and audio when capturing on Mac macOS with RubyMotion.
* [User specified custom key combination for a global hotkey](http://kickcode.com/blog/2015/05/13/custom-user-hotkey-combo.html) - User specified custom key combination for a global hotkey.


### Tutorial Screencasts

* [Motion in Motion](https://motioninmotion.tv) - Paid RubyMotion screencast with an occasional free episode for the masses to enjoy.
* [Motion Casts](http://motioncasts.com) - Learn to create native iOS applications using Ruby.
* [IOS Development with RubyMotion](https://www.youtube.com/playlist?list=PLid95FTT3ehjnlpwXbM0a_pcPW0eiXtky) - YouTube Channel from Kingsley Ijomah.
* [RubyMotion Primer](https://pragmaticstudio.com/screencasts/rubymotion) - Wishing you could create iOS apps using Ruby?


## Presentations
* [Converting Obj-C to RubyMotion](https://www.icloud.com/keynote/000kP6LsvKhzNVp5MO3Z6xKDw#rubymotion_talk) - Keynote presentation about converting Objs to RubyMotion.
* [Introduction to RubyMotion](https://github.com/GantMan/RubyMotion-Intro) - Introduction to RubyMotion - The Cool Way to Build iOS Apps. :star:3
* [Building iOS Apps With RubyMotion](https://speakerdeck.com/rayhightower/building-ios-apps-with-rubymotion) - Building iOS Apps With RubyMotion.
* [Concurrency patterns in RubyMotion](https://speakerdeck.com/seanlilmateus/concurrency-patterns-in-rubymotion) - Presentation about working with Grand Central Dispatch in RubyMotion.
* [Talk about RubyMotion and Low Energy Bleutooth Sensors](https://vimeo.com/groups/199097/videos/69529068)

## Other Resources

Where to learn about RubyMotion and discover new RubyMotion libraries, projects and trends.

* [RubyMotion Official Website](http://www.rubymotion.com) - RubyMotion Official Website.
* [Motion Toolbox](http://motion-toolbox.com) - Collection of RubyMotion libraries and wrappers.
* [App catalog](http://www.rubymotion.com/references/app-catalog/) - There are lots of RubyMotion apps in production.


## Community Resources
* [@rubymotion on Twitter](https://twitter.com/rubymotion)
* [Forum on RubyMotion.com](http://community.rubymotion.com)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/rubymotion)
* [Reddit](https://www.reddit.com/r/RubyMotion/)
* [Slack](https://motioneers.slack.com)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)


## Thanks

Thanks to Clay Allsopp who created the Motion Toolbox list.
Thanks to all [contributors](https://github.com/motion-open-source/awesome-rubymotion/graphs/contributors), you're awesome and wouldn't be possible without you!

# Other Awesome Lists

Other amazingly awesome lists can be found in the [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) list.


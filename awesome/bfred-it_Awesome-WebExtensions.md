# Information comes from [bfred-it/Awesome-WebExtensions](https://github.com/bfred-it/Awesome-WebExtensions)
# Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) development.

WebExtensions are a cross-browser system for developing browser add-ons. To a large extent the system is compatible with the [extension API](https://developer.chrome.com/extensions) supported by Google Chrome and Opera. Extensions written for these browsers will in most cases run in Firefox or [Microsoft Edge](https://developer.microsoft.com/en-us/microsoft-edge/platform/documentation/extensions/) with just [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

## Contents

- [Getting Started](#getting-started)
- [Community](#community)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Tools](#tools)
- [Boilerplates](#boilerplates)
- [Sample Extensions](#sample-extensions)

## Getting started

- [Chrome Extensions documentation](https://developer.chrome.com/extensions) - Documentation for the original Chrome extension model.
- [Chrome Extensions API](https://developer.chrome.com/extensions/api_index) - Comprehensive documentation on the original API provided by Chrome.
- [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) - MDN wiki for the WebExtensions API.
- [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Compatibility table for Chrome, Edge, Firefox, and Opera.
- [Microsoft Edge API support](https://docs.microsoft.com/en-us/microsoft-edge/extensions/api-support/extension-api-roadmap) - Detailed WebExtensions support for Edge.
- [Safari Extensions documentation](https://developer.apple.com/safari/extensions/) - Developer documentation on building Safari extensions
- [Opera API support](https://dev.opera.com/extensions/apis/) - Detailed WebExtensions support for Opera.
- [Porting Chrome Extensions to Firefox](https://hacks.mozilla.org/2015/10/porting-chrome-extensions-to-firefox-with-webextensions/) - Guide to prepare, install, and debug Chrome extensions to be ported in Firefox.
- [Browser Extension Standard](https://browserext.github.io/browserext/) - Standard for the API, supported by Mozilla, Opera and Microsoft.

## Community

- [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - Discussions.
- [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - Discussions.
- [`#webextensions`](https://wiki.mozilla.org/IRC) - IRC channel by Mozilla.
- [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - Relevant questions.
- [`firefox-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-webextensions) - Relevant questions.
- [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - Relevant questions.

## Libraries and Frameworks

Code meant become part of the extension.

- [webext-options-sync](https://github.com/bfred-it/webext-options-sync) - Helps you manage and autosave your extension's options. :star:26
- [webext-inject-on-install](https://github.com/bfred-it/webext-inject-on-install) - Automatically add content scripts to existing tabs when your extension is installed. Chrome + Firefox. :star:6
- [redux-webext](https://github.com/ivantsov/redux-webext) - Uses [redux](https://github.com/reactjs/redux) for managing the state of your WebExtension :star:81
- [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) - Polyfill to support the standardized promise based API in the `browser` namespace. :star:368

## Tools

Apps that help you manage your extensions.

- [Chrome Webstore Upload](https://github.com/DrewML/chrome-webstore-upload-cli) - Upload the extension to the Chrome Web Store via cli (or on Travis, automatically). :star:117
- [mozilla/web-ext](https://github.com/mozilla/web-ext) Command line tool to help build, run, and test WebExtensions.
- [chromepet](https://github.com/ZenHubIO/chromepet) - Get notified when your new version has been published. :star:15
- [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) - Download any extension on Chrome Web Store to see how they do it. :star:25
- [unzip-crx](https://github.com/peerigon/unzip-crx) - Unzips Google Chrome (crx) files. :star:13
- [chrome-store-api](https://github.com/acvetkov/chrome-store-api) - Chrome Web Store API wrapper. :star:10
- [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) - WebExtension to view source code of extensions directly on the store. :star:284
- [@wext/shipit](https://github.com/LinusU/wext-shipit) - Tool to automatically publish to Goole Webstore, Mozilla Addons and Opera Addons. :star:10

## Testing

- [sinon-chrome](https://github.com/acvetkov/sinon-chrome) - Mocks the Chrome Extensions API for testing. :star:256
- [addons-validator](https://github.com/mozilla/addons-validator) - Validate an extension against Mozilla's guidelines. :star:101

## Boilerplates

- [create-webextension](https://github.com/rpl/create-webextension) - Yarn WebExtension generator. :star:9
- [extensionizr.com](http://extensionizr.com) - Web UI that helps you create an initial configuration and files.
- [generator-web-extension](https://github.com/HaNdTriX/generator-web-extension) - WebExtension generator that creates everything you need to get started with cross-browser web-extension development. :star:36
- [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - React boilerplate with Hot reloading. :star:1052

## Sample Extensions

These are simple and modern WebExtensions repositories that could help you figure out where pieces go, including automatic deployment via Travis CI.

- [npmhub](https://github.com/npmhub/npmhub) :star:331
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github) :star:187
- [Refined GitHub](https://github.com/sindresorhus/refined-github) :star:5332
- [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) - Various example extensions curated for the MDN documentation. :star:1288

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Federico Brigante](http://bfred.it) has waived all copyright and related or neighboring rights to this work.


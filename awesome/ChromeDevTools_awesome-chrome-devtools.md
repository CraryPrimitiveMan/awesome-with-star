# Information comes from [ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools)
# Awesome chrome-devtools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

### Learning
- [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.

#### DevTools as an IDE
- [Chrome DevTools App](https://github.com/auchenberg/chrome-devtools-app) - Standalone app which can inspect various targets. :star:1465
- [DevTools Remote](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser. :star:558
- [DevTools Snippets](https://github.com/bahmutov/code-snippets) - Collection of snippets. :star:1359

---

### DevTools tooling and ecosystem

#### Object formatting
- [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values. :star:556

#### Network Inspection
- [betwixt](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel :star:3728

#### CPU profile
- [JSCLegacyProfiler/json2trace](https://github.com/facebook/react-native/blob/master/JSCLegacyProfiler/json2trace) - Converts Safari's JavaScriptCore profiler output into `.cpuprofile`
- [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts. :star:13
- [cpuprofilify](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format. :star:127
- [Wishbone python framework](http://wishbone.readthedocs.org/en/develop/miscellaneous.html#profiling) - Profiling data can export as `.cpuprofile`.

#### Multimedia
- [snapline](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif. :star:310

#### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

#### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - Chrome Debugger for Visual Studio Code
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - Debug Javascript right in the Sublime Text editor
- [WebStorm & JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol) - Issue tracker for protocol bugs :star:173
- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once. :star:65
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments.  :star:35
- [RemoteDebug](https://github.com/RemoteDebug) - Initiative to normalize debugging protocols across today's browsers.
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) - The official Selenium/WebDriver implementation for Chrome is implemented on top of the DevTools Protocol.
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - tool for debugging clients using devtools protocol :star:52
- [Puppeteer](https://github.com/GoogleChrome/puppeteer/) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol

#### Protocol driver libraries (in various languages)
- JavaScript/Node.js: [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - The most-used JavaScript API for the protocol
- TypeScript/Node.js: [chrome-debugging-client](https://github.com/krisselden/chrome-debugging-client) - A TypeScript async/await-friendly debugging client
- Java: [cdp4j](https://github.com/webfolderio/cdp4j) - Java library for CDP
- Python: [PyChromeDevTools](https://github.com/marty90/PyChromeDevTools) - Python wrapper for Google Chrome Dev Protocol
- Python: [chromewhip](https://github.com/chuckus/chromewhip) - Python 3 asyncio driver to manage concurrent requests to Google Chrome Devtools endpoints
- Python: [pychrome](https://github.com/fate0/pychrome) - A Python Package for the Google Chrome Dev Protocol
- Go: [chromedp](https://github.com/knq/chromedp) - High level actions and tasks for driving browsers via the Chrome Debugging Protocol
- Go: [cdp](https://github.com/mafredri/cdp) - A Golang library for the protocol
- Go: [gcd](https://github.com/wirepair/gcd) - A different client library in Go
- Go: [godet](https://github.com/raff/godet) - Also different, also Go.
- C#/dotnet: [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
- Ruby: [ChromeRemote](https://github.com/cavalle/chrome_remote/) - A client implementation of the Chrome DevTools Protocol in Ruby
- Kotlin: [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) - reactive (rxjava 2.x), low-level client library in Kotlin
- Clojure: [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) - A Clojure library for the protocol. The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- PHP: [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - A PHP client library for the protocol.

#### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes
- [Getting Started with Headless Chrome](https://developers.google.com/web/updates/2017/04/headless-chrome)
- [crmux](https://github.com/sidorares/crmux) - Multiplexes protocol connections. :star:97
- [automated-chrome-profiling](https://github.com/paulirish/automated-chrome-profiling#readme) - Node.js recipes for automating JavaScript profiling in Chrome.
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.
- [chrome-timeline-model](https://www.npmjs.com/package/devtools-timeline-model) - Uses frontend as lib to process profiling data.
- [headless-devtools](https://github.com/cowchimp/headless-devtools) - Perform various DevTools actions from code (e.g. get CSS Coverage, JS Heap snapshot). Uses Puppeteer + frontend as lib. :star:390
- [crconsole](https://github.com/sidorares/crconsole) - Terminal based chrome console and debugger. :star:187
- [sloth](https://github.com/denar90/sloth) - Chrome extension allows to enable and save CPU and network throttling for selected tabs. :star:88

#### Browser Adapters
- [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - Translates Firefox's devtools protocol to the CDP :star:111
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP. :star:3543
- [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP :star:649
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 10/11 to CDP. :star:544
- [Edge Diagnostics Adaptor](https://github.com/Microsoft/edge-diagnostics-adaptor) - Protocol adaptor that enables tools to debug Edge using the CDP. :star:108

### Using DevTools frontend with other targets/platforms

##### Android
- [Facebook Stetho](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools :star:9546

##### ClosureScript
- [Dirac](https://github.com/binaryage/dirac) - Debugging of ClojsureScript :star:554

##### Lua
- [Mare](https://github.com/muzuiget/mare) - Lua debugging with Chrome DevTools :star:218

#### iOS
- [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools :star:5565

##### Go
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools) :star:30

##### Node.js
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+
- [devtool](https://github.com/Jam3/devtool) - Debug & profile Node.js apps with Chrome DevTools (using Electron). :star:3783
- [buggerJS](https://github.com/buggerjs/bugger) - Provides Chrome DevTools bindings for node. :star:154


---

## DevTools Extensions

#### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

#### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) - Inspect VueJS components and manipulate their data. :star:7959
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- [Augury](https://augury.angular.io)  - Debugging and Profiling for Angular 2 applications.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- [Insight](https://github.com/3Dparallax/insight/) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework. :star:38
- [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.

#### UX
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.

#### Performance
- [Chrome React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm) - An Operation Interface for react-addons-perf Package.

#### Testing
- [UI-automation-chrome-extension](https://chrome.google.com/webstore/detail/ui-automation/aacdhbhfmngpoiinjmphdcpalpdcmbpf/) - Provides simple DOM selectors with Java code snippets so you can write automated Selenium tests faster.



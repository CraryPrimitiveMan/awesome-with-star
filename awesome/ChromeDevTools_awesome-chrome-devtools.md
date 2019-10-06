# Information comes from [ChromeDevTools/awesome-chrome-devtools](https://github.com/ChromeDevTools/awesome-chrome-devtools)
# Awesome Chrome DevTools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Awesome tooling and resources in the Chrome DevTools ecosystem

## Contents

- [Learning](#learning)
- [DevTools tooling and ecosystem](#devtools-tooling-and-ecosystem)
- [Chrome DevTools Protocol](#chrome-devtools-protocol)
- [Using DevTools frontend with other platforms](#using-devtools-frontend-with-other-platforms)
- [DevTools Extensions](#devtools-extensions)

---

## Learning
- [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.
- [DevTools Snippets](https://github.com/bahmutov/code-snippets) - Collection of snippets. :star:1539

### Multiuser DevTools
- [DevTools Remote](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser. :star:606

---

## DevTools tooling and ecosystem

### Object formatting
- [immutable-devtools](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values. :star:612

### Network Inspection
- [betwixt](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel. :star:4134
- [Weer](https://weerdbg.com/) - A HTTP protocol debugger **(closed source)**

### CPU profile
- [call-trace](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts. :star:17
- [cpuprofilify](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format. :star:142
- [Wishbone python framework](https://wishbone.readthedocs.io/en/latest/misc/profiling.html) - Profiling data can export as `.cpuprofile`.

### Multimedia
- [snapline](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif. :star:348

### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome](https://github.com/Microsoft/vscode-chrome-debug/) - Breakpoint debugging in VS Code. :star:1726
- [VS Code - Elements for Microsoft Edge](https://github.com/microsoft/vscode-edge-devtools) - Elements panel inside VS Code. :star:126
- [ChromeREPL](https://github.com/acarabott/ChromeREPL) - Within Sublime Text, use the Chrome console. :star:339
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - JavaScript Breakpoint debugging right in Sublime Text.
- [WebStorm/JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- [ChromeDevTools/devtools-protocol](https://github.com/chromedevtools/devtools-protocol) - **Canonical location of the protocol JSON**. Issue tracker for protocol bugs. TypeScript types. :star:398
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events.

### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes. :star:2961
- [Chrome Protocol Proxy](https://github.com/wendigo/chrome-protocol-proxy) - Tool for debugging clients using devtools protocol. :star:68
- [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once. :star:73
- [DevTools Backend](https://github.com/christian-bromann/devtools-backend) - Standalone implementation of the Chrome DevTools backend to debug arbitrary web environments. :star:76
- [RemoteDebug](https://github.com/RemoteDebug) - Initiative to normalize debugging protocols across today's browsers.
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) - The official Selenium/WebDriver implementation for Chrome is implemented on top of the DevTools Protocol.

### Automation
- [Puppeteer](https://github.com/GoogleChrome/puppeteer/) - Node.js offering a high-level API to control headless Chrome over the DevTools Protocol. :star:54554
  - Python port: [pyppeteer](https://github.com/miyakogi/pyppeteer)
  - Rust port: [Rust Headless Chrome](https://github.com/atroche/rust-headless-chrome/)
  - .NET port: [Puppeteer Sharp](https://github.com/kblok/puppeteer-sharp)
  - [headless-devtools](https://github.com/cowchimp/headless-devtools) - Puppeteer plugin to get CSS Coverage or JS Heap snapshot. :star:510
- [Taiko](https://github.com/getgauge/taiko/) - A Node.js module to automate the chrome/chromium using DevTools protocol. :star:1434
- Also all `Protocol Driver Libraries` below

### Protocol Driver Libraries
- JavaScript/Node.js: [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) - The most-used JavaScript API for the protocol
- TypeScript/Node.js: [chrome-debugging-client](https://github.com/krisselden/chrome-debugging-client)
- Java: [chrome-devtools-java-client](https://github.com/kklisura/chrome-devtools-java-client)
- Java: [karate](https://intuit.github.io/karate/karate-core/) - Web-service testing framework with a Java API to automate Chrome
- Python: [PyCDP](https://github.com/hyperiongray/python-chrome-devtools-protocol) - Pure-Python, sans-IO wrappers. See also the [Trio CDP driver](https://github.com/hyperiongray/trio-chrome-devtools-protocol)
- Python: [chromewhip](https://github.com/chuckus/chromewhip) - drop-in replacement for the `splash` service
- Python: [pychrome](https://github.com/fate0/pychrome) - low level CDP transport handler
- Python: [ChromeController](https://github.com/fake-name/ChromeController) - high-level browser mgmt
- Go: [chromedp](https://github.com/chromedp/chromedp) - High-level actions and tasks for driving browsers
- Go: [cdp](https://github.com/mafredri/cdp)
- Go: [gcd](https://github.com/wirepair/gcd)
- Go: [godet](https://github.com/raff/godet)
- C#/dotnet: [chrome-dev-tools](https://github.com/BaristaLabs/chrome-dev-tools) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.
- Ruby: [Cuprite](https://github.com/machinio/cuprite) - Capybara driver
- Ruby: [ChromeRemote](https://github.com/cavalle/chrome_remote/)
- Kotlin: [chrome-reactive-kotlin](https://github.com/wendigo/chrome-reactive-kotlin) - reactive (rxjava 2.x), low-level client library in Kotlin
- Clojure: [clj-chrome-devtools](https://github.com/tatut/clj-chrome-devtools) - The CDP wrapper API is autogenerated and will be updated when CDP protocol changes.
- PHP: [chrome-devtools-protocol](https://github.com/jakubkulhan/chrome-devtools-protocol) - A PHP client library for the protocol.

### Browser Adapters
- [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - Translates Firefox's devtools protocol to the CDP. :star:114
- [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP. :star:4544
  - [Remote Debug iOS WebKit adapter](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP. :star:1669
- [IE Diagnostics Adapter](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 11 to CDP. :star:572


## Using DevTools frontend with other platforms

#### Android
- [Facebook Stetho](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools. :star:11477
- [j2v8-debugger](https://github.com/AlexTrotsenko/j2v8-debugger) - Debugging JavaScript running in [J2V8](https://github.com/eclipsesource/J2V8) with Chrome DevTools. :star:26

#### ClojureScript
- [Dirac](https://github.com/binaryage/dirac) - Debugging of ClojsureScript. :star:659

#### Lua
- [Mare](https://github.com/muzuiget/mare) - Lua debugging with Chrome DevTools. :star:239

#### iOS
- [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools. :star:5728

#### Go
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools) :star:39

#### Node.js
- [ndb](https://github.com/GoogleChromeLabs/ndb) - An improved Node.js debugging experience with the DevTools Frontend. :star:9615
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+.
- [thetool](https://github.com/sfninja/thetool) - CPU, memory, coverage, type profiling with Node. :star:123
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.

---

## DevTools Extensions

### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- [VueJS Developer Tools](https://github.com/vuejs/vue-devtools) - Inspect VueJS components and manipulate their data. :star:15100
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- [Augury](https://augury.angular.io) - Debugging and Profiling for Angular 2 applications.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- [Insight](https://github.com/3Dparallax/insight/) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications. :star:824
- [BEM devtools](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework. :star:42
- [Metal.js Developer Tools](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik) - Inspect the Metal component hierarchies.

### UX
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.

### Performance
- [Chrome React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm) - An Operation Interface for react-addons-perf Package.
- [sloth](https://github.com/denar90/sloth) - Chrome extension allows to enable and save CPU and network throttling for selected tabs. :star:184

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This awesome list is licensed into the Public Domain under Creative Commons 0. For more information please see the [license](LICENSE) file.


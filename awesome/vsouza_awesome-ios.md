# Info come from [vsouza/awesome-ios](https://github.com/vsouza/awesome-ios)
<img src="https://raw.githubusercontent.com/vsouza/awesome-ios/master/awesome_logo.png">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Join the chat at https://gitter.im/norio-nomura/SwiftTalkInJapanese](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vsouza/awesome-ios?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master)](https://travis-ci.org/vsouza/awesome-ios)
[![Language](https://awesomelinkcounter.herokuapp.com/swift)]()
[![Language](https://awesomelinkcounter.herokuapp.com/objc)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## We've launched our Newsletter!! ✅🚀📰
* [Check out our new website 🗞](http://weekly.awesomeios.com/)

# About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode extensions and plugins, components and much more.
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).

Projects in Swift will be marked with :large_orange_diamond:, Swift Extensions will be marked with 🔶[e] and ⌚ for Apple Watch projects. Feel free to add your project.

# How to Use
Awesome-iOS is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/awesome_ios) or [Gitter Channel](https://gitter.im/vsouza/awesome-ios)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

## Content
- [About](#about)
- [How to Use](#how-to-use)
- [Getting Started](#getting-started)
- [Library and Frameworks](#libraries-and-frameworks)
    - [Analytics](#analytics)
    - [App Routing](#app--routing)
    - [Apple TV](#apple-tv)
    - [ARKit](#arkit)
    - [Authentication](#authentication)
    - [Bridging](#bridging)
    - [Cache](#cache)
    - [Charts](#charts)
    - [Code Quality](#code-quality)
        - [Linter](#linter)
    - [Color](#color)
    - [Command Line](#command-line)
    - [Concurrency](#concurrency)
    - [Core Data](#core-data)
    - [Database](#database)
    - [Data Structures / Algorithms](#data-structures--algorithms)
    - [Date & Time](#date--time)
    - [Debugging](#debugging)
    - [EventBus](#eventbus)
    - [Files](#files)
    - [Functional Programming](#functional-programming)
    - [Games](#games)
    - [Gesture](#gesture)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
        - [Bluetooth](#bluetooth)
        - [Camera](#camera)
        - [Force Touch](#force-touch)
        - [iBeacon](#ibeacon)
        - [Location](#location)
        - [Other Hardware](#other-hardware)
    - [Layout](#layout)
    - [Logging](#logging)
    - [Localization](#localization)
    - [Machine Learning](#machine-learning)
    - [Maps](#maps)
    - [Math](#math)
    - [Media](#media)
        - [Audio](#audio)
        - [GIF](#gif)
        - [Image](#image)
        - [Media Processing](#media-processing)
        - [PDF](#pdf)
        - [Streaming](#streaming)
        - [Video](#video)
    - [Messaging](#messaging)
    - [Networking](#networking)
    - [Notifications](#notifications)
        - [Push Notifications](#push-notifications)
            - [Push Notification Providers](#push-notification-providers)
        - [Local Notifications](#local-notifications)
    - [Optimization](#optimization)
    - [Parsing](#parsing)
        - [CSV](#csv)
        - [JSON](#json)
        - [XML & HTML](#xml--html)
        - [Other Parsing](#other-parsing)
    - [Passbook](#passbook)
    - [Payments](#payments)
    - [Permissions](#permissions)
    - [Products](#products)
    - [Reactive Programming](#reactive-programming)
        - [React-Like](#react-like)
    - [Reflection](#reflection)
    - [Regex](#regex)
    - [SDK](#sdk)
        - [Official](#official)
        - [Unofficial](#unofficial)
    - [Security](#security)
        - [Encryption](#encryption)
        - [Keychain](#keychain)
    - [Server](#server)
    - [Testing](#testing)
        - [TDD / BDD](#tdd--bdd)
        - [A/B Testing](#ab-testing)
        - [UI Testing](#ui-testing)
        - [Other Testing](#other-testing)
    - [Text](#text)
        - [Font](#font)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert & Action Sheet](#alert--action-sheet)
        - [Animation](#animation)
          - [Transition](#transition)
        - [Badge](#badge)
        - [Button](#button)
        - [Calendar](#calendar)
        - [Form & Settings](#form--settings)
        - [Keyboard](#keyboard)
        - [Label](#label)
        - [Login](#login)
        - [Menu](#menu)
        - [Navigation Bar](#navigation-bar)
        - [PickerView](#pickerview)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [ScrollView](#scrollview)
        - [Segmented Control](#segmented-control)
        - [Slider](#slider)
        - [Splash View](#splash-view)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
        - [Web View](#web--view)
    - [Utility](#utility)
    - [VR](#vr)
    - [Walkthrough / Intro / Tutorial](#walkthrough--intro--tutorial)
    - [Websocket](#websocket)
- [Project setup](#project-setup)
- [Dependency / Package Manager](#dependency--package-manager)
- [Tools](#tools)
- [Rapid Development](#rapid-development)
  - [Injection](#injection)
- [Deployment / Distribution](#deployment--distribution)
- [App Store](#app-store)
- [SDK](#sdk)
    - [Official](#official)
    - [Unofficial](#unofficial)
- [Xcode](#xcode)
    - [Extensions (Xcode 8+)](#extensions-xcode-8)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Other Xcode](#other-xcode)
- [Reference](#reference)
- [Style Guides](#style-guides)
- [Good Websites](#good-websites)
    - [News, Blogs and more](#news-blogs-and-more)
    - [UIKit references](#uikit-references)
    - [Forums and discuss lists](#forums-and-discuss-lists)
    - [Tutorials and Keynotes](#tutorials-and-keynotes)
    - [Prototyping](#prototyping)
    - [Newsletters](#newsletters)
    - [Medium](#medium)
- [Social Media](#social-media)
  - [Twitter](#twitter)
  - [Facebook Groups](#facebook-groups)
- [Podcasts](#podcasts)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing-and-license)

***
# Getting Started
* [Start Developing with iOS](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/) - Apple Guide. :large_orange_diamond:
* [Lifehacker](https://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
* [CodeProject](https://www.codeproject.com/articles/88929/getting-started-with-iphone-and-ios-development) - Getting Started with iPhone and iOS Development.
* [Ray Wenderlich](https://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - Learn to code iOS Apps.
* [Stanford - Developing iOS 7 Apps for iPhone and iPad](https://itunes.apple.com/us/course/developing-ios-7-apps-for-iphone-and-ipad/id733644550)
* [Stanford - Developing iOS 10 Apps with Swift](https://itunes.apple.com/in/course/developing-ios-10-apps-swift/id1198467120) - Stanford's 2017 iTunes U course. :large_orange_diamond:
* [Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [Object-Oriented Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html)
* [Udacity: Start A Career Developing iOS Apps](https://www.udacity.com/course/ios-developer-nanodegree--nd003?v=ios1) - Udacity's intro course on writing iOS apps [Paid Resource] :large_orange_diamond:

# Libraries And Frameworks

## Analytics
* [Mixpanel](https://mixpanel.com/) - Advanced analytics platform.
* [Localytics](https://www.localytics.com/) - Brings app marketing and analytics together.
* [Answers by Fabric](https://answers.io/) - Answers gives you real-time insight into people’s experience in your app.
* [Liquid Analytics](https://onliquid.com) - Identify behaviours through Analytics and react with real-time Personalization.
* [GTrack](https://github.com/gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies. :star:85
* [ARAnalytics](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data. :star:1701
* [Segment](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application. :star:260
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions. :star:2
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing
* [WAAppRouting](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically! :star:561
* [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links. :star:3012
* [IntentKit](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps. :star:1809
* [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API. :star:3904
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :large_orange_diamond: :star:93
* [Compass](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :large_orange_diamond: :star:569
* [Appz](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :large_orange_diamond: :star:876
* [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :large_orange_diamond: :star:1387
* [Marshroute](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful. :large_orange_diamond:  :star:137
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 3 :large_orange_diamond: :star:158
* [Router](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS. :large_orange_diamond: :star:92
* [ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain. :star:219

## Apple TV
* [Voucher](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts. :star:491
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2231
* [TVMLKitchen](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :large_orange_diamond: :star:69
* [BrowserTV](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :large_orange_diamond: :star:206
* [Swift-GA-Tracker-for-Apple-tvOS](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :large_orange_diamond: :star:67
* [ParallaxView](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :large_orange_diamond: :star:338
* [TvOSTextViewer](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :large_orange_diamond: :star:25
* [FocusTvButton](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :large_orange_diamond: :star:32
* [TvOSMoreButton](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :large_orange_diamond: :star:20
* [TvOSPinKeyboard](https://github.com/zattoo/TvOSPinKeyboard) - PIN keyboard for tvOS :large_orange_diamond: :star:91
* [TvOSScribble](https://github.com/dcordero/TvOSScribble) - Handwriting numbers recognizer for Siri Remote :large_orange_diamond: :star:159
* [TvOSCustomizableTableViewCell](https://github.com/zattoo/TvOSCustomizableTableViewCell) - Light wrapper of UITableViewCell that allows extra customization for tvOS :large_orange_diamond: :star:17

## ARKit
* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data. :large_orange_diamond:
* [Virtual Objects](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality. :star:152
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆. :large_orange_diamond: :star:447

## Authentication
* [Heimdallr.swift](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :large_orange_diamond: :star:451
* [OhMyAuth](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :large_orange_diamond: :star:49
* [AuthenticationViewController](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :large_orange_diamond: :star:234
* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift. :large_orange_diamond: :star:628
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :large_orange_diamond: :star:1905
* [SimpleAuth](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS. :star:1162
* [AlamofireOauth2](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :large_orange_diamond: :star:73
* [SwiftyOAuth](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :large_orange_diamond: :star:458
* [Simplicity](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps. :large_orange_diamond: :star:639
* [InstagramAuthViewController](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :large_orange_diamond: :star:33
* [InstagramSimpleOAuth](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app. :star:83
* [DropboxSimpleOAuth](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app. :star:42
* [BoxSimpleOAuth](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app. :star:15
* [InstagramLogin](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS. :large_orange_diamond: :star:18
* [ReCaptcha](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS. :large_orange_diamond: :star:46
* [LinkedInSignIn](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn. :large_orange_diamond: :star:9

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:10160
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews :star:9801
* [MAIKit](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS :star:136

## Cache
* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift) :large_orange_diamond: :star:1090
* [mattress](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content :large_orange_diamond: :star:448
* [Carlos](https://github.com/WeltN24/Carlos) - A simple but flexible cache :large_orange_diamond: :star:453
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :large_orange_diamond: :star:4564
* [YYCache](https://github.com/ibireme/YYCache) - High performance cache framework for iOS. :star:1591
* [Cache](https://github.com/hyperoslo/Cache) - Nothing but Cache. :large_orange_diamond: :star:1000
* [MGCacheManager](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class. :star:8
* [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify :star:1148
* [Track](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :large_orange_diamond: :star:190
* [UITableView Cache](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating. :star:63
* [RocketData](https://github.com/linkedin/RocketData) - A caching and consistency solution for immutable models. :large_orange_diamond: :star:522
* [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS :star:1817
* [Johnny](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift :large_orange_diamond: :star:26
* [Disk](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data. 🔶 :star:1715
* [Cachyr](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift :large_orange_diamond: :star:98

## Charts
* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart). :large_orange_diamond: :star:16629
* [JTChartView](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart. :star:118
* [PNChart](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS :star:8959
* [XJYChart](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight. :star:241
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library). :star:2660
* [JBChartView](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs. :star:3743
* [XYPieChart](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app. :star:1741
* [TEAChart](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart. :star:1146
* [EChart](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported. :star:642
* [FSLineChart](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS. :star:821
* [chartee](https://github.com/zhiyu/chartee) - a charting library for mobile platforms. :star:866
* [ANDLineChartView](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart. :star:412
* [TWRCharts](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code. :star:368
* [SwiftCharts](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :large_orange_diamond: :star:1511
* [FlowerChart](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :large_orange_diamond: :star:8
* [Scrollable-GraphView](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :large_orange_diamond: :star:4123
* [Dr-Charts](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C. :star:68
* [Graphs](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS. :large_orange_diamond: :star:868
* [FSInteractiveMap](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS! :star:461
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation. :star:393
* [TKRadarChart](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift :large_orange_diamond: :star:130
* [MagicPie](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1 :large_orange_diamond: 🎉 ✨✨✨✨✨ :star:531
* [PieCharts](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :large_orange_diamond: :star:328
* [CSPieChart](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :large_orange_diamond: :star:27
* [DDSpiderChart](https://github.com/dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift. :large_orange_diamond: :star:30
* [core-plot](https://github.com/core-plot/core-plot) - a 2D plotting lib which is highly customizable and capable of drawing many types of plots. :star:2515
* [ChartProgressBar](https://github.com/hadiidbouk/ChartProgressBar-iOS) - Draw a chart with progress bar style. :star:25
* [SMDiagramViewSwift](https://github.com/VRGsoftUA/SMDiagramView) - Meet cute and very flexibility library for iOS application for different data view in one circle diagram.  :star:17

## Code Quality
* [Bootstrap](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding. :star:1882
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL. :star:106
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle](https://github.com/Cue/ocstyle) - Objective-C style checker. :star:250
* [spacecommander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying. :star:792
* [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling. :star:565
* [Tailor](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs. :star:1136
* [SwiftCop](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :large_orange_diamond: :star:503
* [Trackable](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :large_orange_diamond: :star:132
* [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time. :star:2853
* [HeapInspector-for-iOS](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments :star:1641
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage. :star:2807
* [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime. :star:2719
* [Buglife](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps :star:356
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets. :star:429
* [Aardvark](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports. :star:199
* [Stats](https://github.com/shu223/Stats) - In-app memory usage monitoring. :star:149
* [GlueKit](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift. :large_orange_diamond: :star:353
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :large_orange_diamond: :star:1657
* [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods. :star:213
* [SwiftyVIPER](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.  :large_orange_diamond: :star:50
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :large_orange_diamond: :star:33
* [ODUIThreadGuard](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :large_orange_diamond: :star:703
* [IBAnalyzer](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :large_orange_diamond: :star:844
* [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :large_orange_diamond: :star:1044
* [DecouplingKit](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project. :star:112
* [Clue](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure. :star:240
* [Viperit](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :large_orange_diamond: :star:209

#### Linter
* [OCLint](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects. :star:2127
* [Taylor](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :large_orange_diamond: :star:189
* [Swiftlint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions. :large_orange_diamond: :star:8169

## Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :large_orange_diamond: :star:10376
* [ColorArt](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11. :star:130
* [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. :large_orange_diamond:[e] :star:1740
* [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. :large_orange_diamond:[e] :star:508
* [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier. :star:2940
* [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :large_orange_diamond: :star:826
* [Hue](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need. :star:2280
* [FlatUIColors](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :large_orange_diamond: :star:141
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :large_orange_diamond: :star:448
* [PFColorHash](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string. :large_orange_diamond: :star:17
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift) :large_orange_diamond: :star:426
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes :star:2886
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm). :large_orange_diamond: :star:147
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :large_orange_diamond: :star:16
* [CostumeKit](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app. :large_orange_diamond: :star:292
* [CSS3ColorsSwift](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :large_orange_diamond: :star:53
* [Colorify](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017. :large_orange_diamond: :star:75
* [ChromaColorPicker](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift. :large_orange_diamond: :star:90
* [Lorikeet](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation. :large_orange_diamond: :star:10

## Command Line
* [Swiftline](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications. :large_orange_diamond: :star:991
* [CommandLine](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :large_orange_diamond: :star:987
* [Commander](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift :large_orange_diamond: :star:998
* [ColorizeSwift](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift. :large_orange_diamond: :star:169
* [Guaka](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :large_orange_diamond: :star:1052
* [Marathon](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :large_orange_diamond: :star:1296
* [CommandCougar](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications. :large_orange_diamond: :star:15

## Concurrency
* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :large_orange_diamond: :star:1337
* [Concurrent](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives :large_orange_diamond: :star:145
* [Flow](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift :large_orange_diamond: :star:194
* [Brisk](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :large_orange_diamond: :star:22
* [Aojet](https://github.com/aojet/Aojet) - An actor model library for swift. :star:20
* [Overdrive](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :large_orange_diamond: :star:818
* [NSLock+Synchronized](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via CocoaPods and Carthage Framework. :large_orange_diamond:[e] :star:2
* [AsyncNinja](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :large_orange_diamond: :star:63
* [Kommander](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand. :large_orange_diamond: :star:111
* [Threadly](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift :large_orange_diamond: :star:42
* [Flow-iOS](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable :large_orange_diamond: :star:10
* [Queuer](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD). :large_orange_diamond: :star:685
* [SwiftQueue](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more. :large_orange_diamond: :star:15

## Core Data
* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework. :star:71
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C. :star:1336
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code. :star:466
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data. :star:237
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data. :star:1552
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping. :star:185
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation. :star:2950
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread. :star:206
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher. :star:658
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data. :star:10563
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond: :star:1287
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond: :star:1724
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond: :star:746
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond: :star:32
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond: :star:2062
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond: :star:731
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond: :star:285
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond: :star:519
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond: :star:446
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond: :star:182
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond: :star:94
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond: :star:6
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond: :star:166
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box. :star:95
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :large_orange_diamond: :star:477
* [Records](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift. :large_orange_diamond: :star:11

## Database
* [Realm](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast. :star:11589
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac. :star:2962
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite. :star:12092
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access. :star:1645
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond: :star:425
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond: :star:443
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond: :star:49
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :large_orange_diamond: :star:2920
* [SugarRecord](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0 :large_orange_diamond: :star:1965
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond: :star:4801
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond: :star:1089
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond: :star:756
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers. :star:2604
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond: :star:109
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond: :star:141
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond: :star:80
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e] :star:100
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond: :star:269
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage. :star:37
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API. :star:35
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond: :star:60
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond: :star:19
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:44
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:19
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:63
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:16
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:29
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:22
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond: :star:208
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond: :star:163
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS. :star:4510
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠 :star:164
* [UserDefaults](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS :large_orange_diamond: :star:795
* [Default](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support :large_orange_diamond: :star:316
* [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit :large_orange_diamond: :star:628

## Data Structures / Algorithms
* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond: :star:4
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond: :star:708
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond: :star:961
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond: :star:1790
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift :large_orange_diamond: :star:83
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond: :star:53
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond: :star:605
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond: :star:56
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond: :star:3768
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :large_orange_diamond: :star:1901
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C. :star:2287
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData. :star:22
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond: :star:330
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond: :star:335
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond: :star:233
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond: :star:72
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond: :star:40
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond: :star:21
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :large_orange_diamond: :star:15355
+* [Impeller](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift :large_orange_diamond:

## Date & Time

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift :large_orange_diamond: :star:2396
* [SwiftDate](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0 :large_orange_diamond: :star:3455
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2 :large_orange_diamond: :star:1504
* [DateTools](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C :star:5887
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer :large_orange_diamond: :star:923
* [DateHelper](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift :large_orange_diamond: :star:878
* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats. :star:599
* [EmojiTimeFormatter](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :large_orange_diamond: :star:73
* [Kronos](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift :large_orange_diamond: :star:234
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :large_orange_diamond: :star:220
* [10Clock](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :large_orange_diamond: :star:442
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad. :star:1703
* [AnyDate](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API. :large_orange_diamond: :star:146
* [TimeZonePicker](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app. :large_orange_diamond: :star:90
* [Time](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. :large_orange_diamond:[e] :star:611
* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library :large_orange_diamond: :star:751

## Debugging
* [Xniffer](https://github.com/vsouza/awesome-ios/issues/1841) - A swift network profiler built on top of URLSession. 🔶
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library! :large_orange_diamond: :star:2017
* [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools. :star:5501
* [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers. :star:575
* [Flex](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS. :star:8640
* [chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps. :star:6404
* [Alpha](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS. :star:664
* [AEConsole](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :large_orange_diamond: :star:77
* [GodEye](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :large_orange_diamond: :star:2802
* [NetworkEye](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request. :star:1027
* [Dotzu](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network. :star:1221
* [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations. :star:594

## EventBus
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8. :large_orange_diamond: :star:594
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS. :star:8559
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links). :star:5220
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.  :large_orange_diamond: :star:1744
* [When](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift. :large_orange_diamond: :star:122
* [then🎬](https://github.com/freshOS/then) - Elegant Async code in Swift. :large_orange_diamond: :star:592
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :large_orange_diamond: :star:1050
* [RWPromiseKit](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C :star:100
* [FutureLib](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :large_orange_diamond: :star:38
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :large_orange_diamond: :star:462
* [FutureKit](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS. :large_orange_diamond: :star:679
* [signals-ios](https://github.com/uber/signals-ios) - Typeful eventing :star:497
* [BrightFutures](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :large_orange_diamond: :star:1573
* [NoticeObserveKit](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :large_orange_diamond: :star:111
* [Hydra](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift :large_orange_diamond: :star:1285
* [Promis](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate. :large_orange_diamond: :star:65
* [Bluebird.swift](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4. :large_orange_diamond: :star:23

## Files
* [FileKit](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift. :large_orange_diamond: :star:1676
* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files. :large_orange_diamond: :star:1144
* [FileBrowser](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :large_orange_diamond: :star:1137
* [Ares](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :large_orange_diamond: :star:113
* [FileProvider](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :large_orange_diamond: :star:202
* [KZFileWatchers](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :large_orange_diamond: :star:788
* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac. :star:3222
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :large_orange_diamond: :star:521
* [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift :large_orange_diamond: :star:836

## Functional Programming
* [Forbind](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift. :large_orange_diamond: :star:43
* [Funky](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift. :large_orange_diamond: :star:12
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :large_orange_diamond: :star:637
* [Oriole](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. :large_orange_diamond:[e] :star:11
* [Prelude](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools. :large_orange_diamond: :star:314
* [Swiftx](https://github.com/typelift/Swiftx) - Functional data types and functions for any project. :large_orange_diamond: :star:182
* [Swiftz](https://github.com/typelift/Swiftz) -  Functional programming in Swift. :large_orange_diamond: :star:3030
* [OptionalExtensions](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. :large_orange_diamond:[e] :star:173
* [Hookah](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project. :large_orange_diamond: :star:56
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift :large_orange_diamond: :star:3237
* [Runes](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift. :large_orange_diamond: :star:670
* [ifAction](https://github.com/trilliwon/ifAction) - Custom if for Optional and Boolean :large_orange_diamond: [e] :star:2

## Games
* [Sage](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift. :large_orange_diamond: :star:332
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :large_orange_diamond: :star:50
* [SKTiled](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :large_orange_diamond: :star:99
* [CollectionNode](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit :large_orange_diamond: :star:42

## Gesture
* [Tactile](https://github.com/delba/Tactile) - A better way to handle gestures on iOS :large_orange_diamond: :star:632
* [SwiftyGestureRecognition](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :large_orange_diamond: :star:143
* [DBPathRecognizer](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :large_orange_diamond: :star:1088
* [Sensitive](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :large_orange_diamond: :star:468
* [SplitViewDragAndDrop](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode. :large_orange_diamond: :star:290

## Graphics
* [Graphicz](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :large_orange_diamond: :star:31
* [PKCoreTechniques](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich. :star:144
* [MPWDrawingContext](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext :star:91
* [DePict](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :large_orange_diamond: :star:29
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :large_orange_diamond: :star:860
* [InkKit](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift! :large_orange_diamond: :star:350
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display. :star:364
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :large_orange_diamond: :star:1011
* [jot](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images. :star:1666
* [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating). :star:2931
* [Snowflake](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift. :large_orange_diamond: :star:814
* [HxSTLParser](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit :star:12

## Hardware
#### Bluetooth
* [Discovery](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background). :star:377
* [LGBluetooth](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code. :star:145
* [PeerKit](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. :large_orange_diamond:
* [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE. :large_orange_diamond: :star:1590
* [Bluetonium](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift :large_orange_diamond: :star:125
* [BlueCap](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework :large_orange_diamond: :star:432
* [Apple Family](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.  :large_orange_diamond: :star:32
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U  :large_orange_diamond: :star:446
* [Bluejay](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps. :large_orange_diamond: :star:613
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS. :star:3286
* [ExtendaBLE](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates. :star:71
* [PeerConnectivity](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :large_orange_diamond: :star:30

#### Camera
* [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects. :star:1410
* [PBJVision](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture. :star:1754
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation. :star:1180
* [SCRecorder](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing. :star:2730
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :large_orange_diamond: :star:1500
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :large_orange_diamond: :star:3342
* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :large_orange_diamond: :star:659
* [RSBarcodes_Swift](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :large_orange_diamond: :star:556
* [LLSimpleCamera](https://github.com/omergul/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS. :star:1106
* [Fusuma](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :large_orange_diamond: :star:1920
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :large_orange_diamond: :star:800
* [JVTImageFilePicker](https://github.com/mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C. :star:52
* [HorizonSDK-iOS](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library. :star:163
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters :star:1740
* [DKCamera](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. 🔶 :star:34
* [NextLevel](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :large_orange_diamond: :star:1002
* [CameraEngine](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :large_orange_diamond: :star:429
* [SwiftyCam](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :large_orange_diamond: :star:1068
* [CameraBackground](https://github.com/yonat/CameraBackground) -  Show camera layer as a background to any UIView. :large_orange_diamond: :star:16
* [Lumina](https://github.com/dokun1/Lumina) - Full service camera that takes photos, videos, streams frames, detects metadata, and streams CoreML predictions :largeorangediamond: :star:80
* [RAImagePicker](https://github.com/rallahaseh/RAImagePicker) - RAImagePicker is a protocol-oriented framework that provides custom features from the built-in Image Picker Edit. :star:5

#### Force Touch
* [QuickActions](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts) :large_orange_diamond: :star:204
* [JustPeek](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :large_orange_diamond: :star:63
* [PeekView](https://github.com/itsmeichigo/PeekView) - PeekView supports peek, pop and preview actions for iOS devices without 3D Touch capibility. 🔶 :star:108

#### iBeacon
* [Proxitee](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences. :star:15
* [OWUProximityManager](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth. :star:359
* [Vicinity](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background. :star:363
* [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon. :star:810
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. 🔶 :star:136

#### Location
* [IngeoSDK](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS. :star:92
* [LocationManager](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously. :star:2166
* [SwiftLocation](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :large_orange_diamond: :star:1524
* [SOMotionDetector](https://github.com/SocialObjects-Software/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration.
* [LocationPicker](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :large_orange_diamond: :star:290
* [BBLocationManager](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS. :star:75
* [set-simulator-location](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :large_orange_diamond: :star:190

#### Other Hardware
* [MotionKit](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple. :star:960
* [DarkLightning](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and macOS. :star:180
* [Deviice](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties) 🔶 :star:21
* [DeviceKit](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :large_orange_diamond: :star:1704
* [Luminous](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :large_orange_diamond: :star:186
* [Device](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :large_orange_diamond: :star:1020
* [WatchShaker](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :large_orange_diamond: :star:149
* [WatchCon](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️ :star:25
* [TapticEngine](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :large_orange_diamond: :star:164
* [UIDeviceComplete](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces. :large_orange_diamond: :star:218
* [NFCNDEFParse](https://github.com/jvk75/NFCNDEFParse) - NFC Forum Well Known Type Data Parser for iOS11 and Core NFC. :large_orange_diamond: :star:3

## Layout
* [FlexboxLayout](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :large_orange_diamond: :star:317
* [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax. :star:15779
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code. :star:1507
* [Façade](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative. :star:710
* [PureLayout](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & macOS Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible. :star:6754
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & macOS. :large_orange_diamond: :star:11485
* [Cartography](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :large_orange_diamond: :star:6059
* [AutoLayoutPlus](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :large_orange_diamond: :star:26
* [Neon](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework. :large_orange_diamond: :star:4150
* [MisterFusion](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :large_orange_diamond: :star:266
* [SwiftBox](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :large_orange_diamond: :star:801
* [ManualLayout](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. :large_orange_diamond:[e] :star:274
* [Stevia](https://github.com/freshOS/Stevia) - Elegant view layout for iOS. :large_orange_diamond: :star:2167
* [Manuscript](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :large_orange_diamond: :star:78
* [FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating :star:8353
* [SwiftAutoLayout](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :large_orange_diamond: :star:646
* [FormationLayout](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily. :large_orange_diamond: :star:52
* [SwiftyLayout](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :large_orange_diamond: :star:15
* [Swiftstraints](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :large_orange_diamond: :star:97
* [SwiftBond](https://github.com/ReactiveKit/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :large_orange_diamond: :star:3340
* [Restraint](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift :large_orange_diamond: :star:74
* [EasyPeasy](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy  :large_orange_diamond: :star:1571
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! :large_orange_diamond:
* [Anchorman](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :large_orange_diamond: :star:62
* [LayoutKit](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :large_orange_diamond: :star:2240
* [MarkupKit](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications :star:443
* [Relayout](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :large_orange_diamond: :star:580
* [Anchorage](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :large_orange_diamond: :star:305
* [Compose](https://github.com/VivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :large_orange_diamond: :star:128
* [BrickKit](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :large_orange_diamond: :star:573
* [Framezilla](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :large_orange_diamond: :star:81
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :large_orange_diamond: :star:2162
* [MyLinearLayout](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. :star:2579
* [SugarAnchor](https://github.com/ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable. :large_orange_diamond: :star:19
* [Anchors](https://github.com/onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+ :large_orange_diamond: :star:106
* [PinLayout](https://github.com/mirego/PinLayout) - Extremely Fast views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable. 🔶 :star:758
* [SnapLayout](https://github.com/sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. 🔶[e] :star:9
* [Cupcake](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS. :large_orange_diamond: :star:174
* [MiniLayout](https://github.com/yonat/MiniLayout) - Minimal AutoLayout convenience layer. Program constraints succinctly. :large_orange_diamond: :star:4
* [Bamboo](https://github.com/wordlessj/Bamboo) - Bamboo makes Auto Layout (and manual layout) elegant and concise. :large_orange_diamond: :star:46
* [FlexLayout](https://github.com/layoutBox/FlexLayout) - FlexLayout gently wraps the highly optimized [facebook/yoga](https://github.com/facebook/yoga) flexbox implementation in a concise, intuitive & chainable syntax. 🔶 :star:162
* [Layout](https://github.com/schibsted/layout) - A declarative UI framework for iOS :large_orange_diamond: :star:1192
* [CGLayout](https://github.com/k-o-d-e-n/CGLayout) - Powerful autolayout framework based on constraints, that can manage UIView(NSView), CALayer and not rendered views. Not Apple Autolayout wrapper. 🔶 :star:21
* [YogaKit](https://github.com/facebook/yoga/tree/master/YogaKit) - Powerful layout engine which implements Flexbox. Developed and maintained by Facebook.
* [FlightLayout](https://github.com/AntonTheDev/FlightLayout) -  Balanced medium between manual layout and auto-layout. Great for calculating frames for complex animations. :star:21
* [QLayout](https://github.com/josejuanqm/QLayout) - AutoLayout Utility for iOS. 🔶 :star:1

## Localization
* [Hodor](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App. :star:494
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :large_orange_diamond: :star:534
* [Rubustrings](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files :star:52
* [BartyCrouch](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :large_orange_diamond: :star:309
* [LocalizationKit](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission. :star:922
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :large_orange_diamond: :star:1578
* [LocalizedView](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file. :star:8
* [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:49
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language. :star:102
* [IBLocalizable](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :large_orange_diamond: :star:399
* [nslocalizer](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings :star:122

## Logging
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :large_orange_diamond: :star:1104
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS. :star:9671
* [NSLogger](https://github.com/fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on macOS, iOS and Android. :star:4125
* [QorumLogs](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. :large_orange_diamond:
* [Log](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :large_orange_diamond: :star:690
* [Rainbow](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers. :large_orange_diamond: :star:943
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :large_orange_diamond: :star:3257
* [SwiftyTextTable](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :large_orange_diamond: :star:105
* [Watchdog](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :large_orange_diamond: :star:1449
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :large_orange_diamond: :star:2737
* [puree](https://github.com/cookpad/puree-ios) - A log collector for iOS :star:151
* [Colors](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! :large_orange_diamond:[e] :star:25
* [Loggerithm](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :large_orange_diamond: :star:266
* [AELog](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :large_orange_diamond: :star:13
* [ReflectedStringConvertible](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :large_orange_diamond: :star:49
* [Evergreen](https://github.com/knly/Evergreen) - Most natural Swift logging :large_orange_diamond: :star:69
* [SwiftTrace](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :large_orange_diamond: :star:125
* [Willow](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :large_orange_diamond: :star:1007
* [Bugfender](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps. :star:36
* [LxDBAnything](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly! :star:421
* [XLTestLog](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console :star:59
* [XLFacility](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for macOS & iOS (includes database, Telnet and HTTP servers)
* [Atlantis](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :large_orange_diamond: :star:201
* [StoryTeller](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important. :star:8
* [LumberMill](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0 :star:2
* [TinyConsole](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :large_orange_diamond: :star:1734
* [Lighty](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :large_orange_diamond: :star:37
* [JustLog](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :large_orange_diamond: :star:196
* [Twitter Logging Service](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients. :star:164
* [Reqres](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :large_orange_diamond: :star:22

## Machine Learning
* [Swift-Brain](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :large_orange_diamond: :star:300
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :large_orange_diamond: :star:639
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/ios) - The official Google-built powerful neural network library port for iOS.
* [Bender](https://github.com/xmartlabs/Bender) - Easily craft fast Neural Networks. Use TensorFlow models. Metal under the hood. :star:1309
* [Caffe2](https://github.com/caffe2/caffe2) - Lightweight, modular, and scalable deep learning framework. :star:6475
* [CoreML-samples](https://github.com/ytakzk/CoreML-samples) - Sample code for Core ML using ResNet50 provided by Apple and a custom model generated by coremltools. :large_orange_diamond: :star:17
* [Revolver](https://github.com/petrmanek/Revolver) - A framework for building fast genetic algorithms in Swift. Comes with modular architecture, pre-implemented operators and loads of examples. :large_orange_diamond: :star:13
* [CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models. :star:1906
* [Serrano](https://github.com/pcpLiu/Serrano) - A deep learning library for iOS and macOS. :large_orange_diamond: :star:26

## Maps
* [Route-me](https://github.com/route-me/route-me) - Open source map library for iOS. :star:1307
* [NAMapKit](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework. :star:254
* [Mapbox GL](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS. :star:2291
* [CMMapLauncher](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications. :star:194
* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine. :large_orange_diamond: :star:871
* [PXGoogleDirections](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :large_orange_diamond: :star:200
* [Cluster](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering. :large_orange_diamond: :star:767
* [JDSwiftHeatMap](https://github.com/jamesdouble/JDSwiftHeatMap) - JDSwiftMap is an IOS Native MapKit Library. You can easily make a highly customized HeatMap. :large_orange_diamond: :star:46
* [ClusterKit](https://github.com/hulab/ClusterKit) - An iOS map clustering framework targeting MapKit, Google Maps and Mapbox. :star:234

## Math
* [Euler](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation :large_orange_diamond: :star:866
* [SwiftMath](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :large_orange_diamond: :star:143
* [Arithmosophi](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :large_orange_diamond: :star:56
* [Surge](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :large_orange_diamond: :star:3849
* [Upsurge](https://github.com/aleph7/Upsurge) - Swift math :large_orange_diamond: :star:125
* [Swift-MathEagle](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :large_orange_diamond: :star:31
* [iosMath](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS. :star:686
* [swift-pons](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :large_orange_diamond: :star:212
* [BigInt](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic in pure Swift :large_orange_diamond: :star:334
* [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :large_orange_diamond: :star:484
* [VectorMath](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :large_orange_diamond: :star:166
* [Expression](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :large_orange_diamond: :star:320
* [Metron](https://github.com/toineheuvelmans/Metron) - Metron is a comprehensive collection of geometric functions and types that extend the 2D geometric primitives provided by CoreGraphics. :large_orange_diamond: :star:927
* [NumericAnnex](https://github.com/xwu/NumericAnnex) - NumericAnnex supplements the numeric facilities provided in the Swift standard library with generic integer algorithms, complex numbers, rational numbers, and pseudorandom number generators (written in, and for, Swift 4) :large_orange_diamond: :star:27

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :large_orange_diamond: :star:4419
* [EZAudio](https://github.com/syedhali/EZAudio) - An iOS/macOS audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations. :star:4152
* [novocaine](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and macOS. :star:2086
* [QHSpeechSynthesizerQueue](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech). :star:26
* [Cephalopod](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :large_orange_diamond: :star:79
* [Chirp](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :large_orange_diamond: :star:305
* [Beethoven](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :large_orange_diamond: :star:299
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. :large_orange_diamond:
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :large_orange_diamond: :star:315
* [TuningFork](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :large_orange_diamond: :star:349
* [MusicKit](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift :large_orange_diamond: :star:464
* [SubtleVolume](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :large_orange_diamond: :star:602
* [NVDSP](https://github.com/bartolsthoorn/NVDSP) - iOS/macOS DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:68
* [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface. :star:440
* [TheAmazingAudioEngine2](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to. :star:354
* [InteractivePlayerView](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :large_orange_diamond: :star:231
* [ESTMusicIndicator](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :large_orange_diamond: :star:356
* [QuietModemKit](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. CocoaPods and Carthage compatible. :large_orange_diamond: :star:532
* [BPMAnalyser](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond: :star:12
* [PandoraPlayer](https://github.com/AppliKeySolutions/PandoraPlayer) - A lightweight music player for iOS, based on AudioKit and completely written in Swift :large_orange_diamond: :star:600
* [BPMAnalyser](https://github.com/Luccifer/SonogramView) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond: :star:6

#### GIF
* [YLGIFImage](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory. :star:1692
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS :star:6267
* [gifu](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond: :star:1878
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling :star:1033
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond: :star:576
* [SwiftGif](https://github.com/bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond: :star:747
* [APNGKit](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond: :star:1305
* [YYImage](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more. :star:1076
* [AImage](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond: :star:919
* [NSGIF2](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url. :star:56
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond: :star:716

#### Image
* [GPU Image](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. :star:16713
* [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - iOS UIImage processing functions using the vDSP/Accelerate framework for speed. :star:376
* [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI. :star:943
* [SDWebImage](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category. :star:19009
* [DFImageManager](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession. :star:1219
* [MapleBacon](https://github.com/JanGorman/MapleBacon) - An image download and caching library for iOS written in Swift. :large_orange_diamond: :star:197
* [NYTPhotoViewer](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer. :star:2251
* [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer. :star:2485
* [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController) - Interactive iOS image viewer. :star:2273
* [Concorde](https://github.com/contentful-labs/Concorde/) - Download and decode progressive JPEGs.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects. :star:1854
* [YXTMotionView](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling. :star:79
* [PINRemoteImage](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher. :star:3206
* [SABlurImageView](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :large_orange_diamond: :star:477
* [FastImageCache](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling. :star:7649
* [BKAsciiImage](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art :star:405
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire. :large_orange_diamond: :star:2756
* [Nuke](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating :large_orange_diamond: :star:2433
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :large_orange_diamond: :star:1945
* [YYWebImage](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF). :star:2977
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation. :star:1899
* [Silo](https://github.com/josejuanqm/Silo) - Image loading framework with loaders. :large_orange_diamond: :star:12
* [Ody](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :large_orange_diamond: :star:43
* [Banana](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface. :large_orange_diamond: :star:16
* [JDSwiftAvatarProgress](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :large_orange_diamond: :star:82
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :large_orange_diamond: :star:10436
* [EBPhotoPages](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser. :star:1624
* [UIImageView-BetterFace-Swift](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :large_orange_diamond: :star:443
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :large_orange_diamond: :star:340
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift :large_orange_diamond: :star:2066
* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :large_orange_diamond: :star:262
* [ImageScout](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :large_orange_diamond: :star:850
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :large_orange_diamond: :star:353
* [Agrume](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :large_orange_diamond: :star:221
* [PASImageView](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :large_orange_diamond: :star:166
* [Navi](https://github.com/nixzhu/Navi) - Focus on avatar caching. :large_orange_diamond: :star:115
* [SwiftPhotoGallery](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :large_orange_diamond: :star:86
* [MetalAcc](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift.:large_orange_diamond: :star:198
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections. :star:7886
* [UIImageColors](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. :large_orange_diamond:[e] :star:1730
* [CDFlipView](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects. :star:94
* [GPUImage2](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :large_orange_diamond: :star:3445
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :large_orange_diamond: :star:401
* [ImageButter](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth :star:382
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift :large_orange_diamond: :star:1403
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework :star:769
* [CLImageViewPopup](https://github.com/vinbhai4u/CLImageViewPopup/) - A simple Image full screen pop up :large_orange_diamond:
* [APKenBurnsView](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :large_orange_diamond: :star:50
* [Moa](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. :large_orange_diamond:[e] :star:267
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :large_orange_diamond: :star:125
* [ImageViewer](https://github.com/MailOnline/ImageViewer) - An image viewer à la Twitter :large_orange_diamond: :star:1618
* [FaceAware](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :large_orange_diamond: :star:2162
* [SwiftyAvatar](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard :star:171
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond: :star:63
* [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :large_orange_diamond: :star:1367
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :large_orange_diamond: :star:538
* [ImageSlideshow](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :large_orange_diamond: :star:721
* [Imaginary](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :large_orange_diamond: :star:374
* [PPAssetsActionController](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :large_orange_diamond: :star:53
* [Vulcan](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :large_orange_diamond: :star:276
* [FacebookImagePicker](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker written in Swift. :large_orange_diamond: :star:95
* [Lightbox](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :large_orange_diamond: :star:475
* [AvatarImageView](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :large_orange_diamond: :star:214
* [Ebblink](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time. :star:3
* [Sharaku](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController. :large_orange_diamond: :star:1287
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :large_orange_diamond: :star:760
* [Twitter Image Pipline](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application. :star:1445
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :large_orange_diamond: :star:1468
* [FlexibleImage](https://github.com/kawoou/FlexibleImage) - A simple way to play with image! :large_orange_diamond: :star:612
* [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook. :large_orange_diamond: :star:1103
* [YapImageManager](https://github.com/yapstudios/YapImageManager) - A high-performance image downloader written in Swift, powered by YapDatabase. :large_orange_diamond: :star:52
* [PhotoEditorSDK](https://www.photoeditorsdk.com) - A fully customizable photo editor for your app. :large_orange_diamond:
* [SimpleImageViewer](https://github.com/aFrogleap/SimpleImageViewer) - A snappy image viewer with zoom and interactive dismissal transition. :large_orange_diamond: :star:208
* [AZImagePreview](https://github.com/Minitour/AZImagePreview) - A framework that makes image viewing easy. :large_orange_diamond: :star:13
* [FaceCropper](https://github.com/KimDarren/FaceCropper) - Crop faces, inside of your image, with iOS 11 Vision api :large_orange_diamond: :star:398
* [Paparazzo](https://github.com/avito-tech/Paparazzo) - Custom iOS camera and photo picker with editing capabilities :large_orange_diamond: :star:508
* [ZImageCropper](https://github.com/ZaidPathan/ZImageCropper) - A Swift  project to crop image in any shape. :large_orange_diamond: :star:31
* [InitialsImageView](https://github.com/bachonk/InitialsImageView) - An UIImageView extension that generates letter initials as a placeholder for user profile images, with a randomized background color. :large_orange_diamond: :star:87
* [DTPhotoViewerController](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController, inspired by Facebook photo viewer. :large_orange_diamond: :star:69
* [LetterAvatarKit](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars written in Swift. :large_orange_diamond: :star:49
* [AXPhotoViewer](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos :large_orange_diamond: :star:248
* [TJProfileImage](https://github.com/tejas-ardeshna/TJProfileImage) - Live rendering of componet’s properties in Interface Builder. :large_orange_diamond: :star:29
* [Viewer](https://github.com/bakkenbaeck/Viewer) - Image viewer (or Lightbox) with support for local and remote videos and images :large_orange_diamond: :star:306
* [OverlayComposite](https://github.com/aaronjsutton/OverlayComposite) - An asynchronous, multithreaded, image compositing framework written in Swift. :large_orange_diamond: :star:7

#### Media Processing
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :large_orange_diamond: :star:2946
* [QR Code Scanner](https://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift. :large_orange_diamond: :star:491
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :large_orange_diamond: :star:2147

#### PDF
* [Reader](https://github.com/vfr/Reader) - PDF Reader Core for iOS. :star:3957
* [UIView 2 PDF](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB :star:27
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond: :star:1510
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond: :star:296
* [SimplePDF](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond: :star:100
* [SwiftPDFGenerator](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond: :star:12
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond: :star:158

#### Streaming
* [HaishinKit.swift](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :large_orange_diamond: :star:847
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for macOS and iOS. :star:1681
* [Jukebox](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :large_orange_diamond: :star:419
* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate :star:2820
* [Airstream](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay. :star:325
* [OTAcceleratorCore](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox. :star:18

#### Video
* [VIMVideoPlayer](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes. :star:267
* [MobilePlayer](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS. :star:2296
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2231
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :large_orange_diamond: :star:473
* [Pip](https://github.com/immrss/Pip) - A video player that support both local and network resource.
* [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery :star:1941
* [PlayerView](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :large_orange_diamond: :star:96
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:68
* [AVPlayerViewController-Subtitles](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e] :star:87
* [MPMoviePlayerController-Subtitles](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e] :star:171
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress. :star:3792
* [Player](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :large_orange_diamond: :star:970
* [BMPlayer](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :large_orange_diamond: :star:834
* [VideoPager](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available. :large_orange_diamond: :star:32
* [ios-360-videos](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer. :star:195
* [swift-360-videos](https://github.com/team-pie/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360. :star:54
* [ABMediaView](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner. :star:38
* [PryntTrimmerView](https://github.com/prynt/PryntTrimmerView) - A set of UI elements to trim, crop and select frames inside a video. :large_orange_diamond: :star:110
* [VGPlayer](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player in Swift,Support play local and network,Background playback mode. :large_orange_diamond: :star:195

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application. :star:138
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS. :star:5312
* [Chatto](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :large_orange_diamond: :star:3065
* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - An elegant messages UI library for iOS. :star:10860
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. :star:8154
* [MessageKit](https://github.com/MessageKit/MessageKit) - Eventually, a Swift re-write of JSQMessagesViewController :large_orange_diamond: :star:1364
* [NoChat](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS. :large_orange_diamond: :star:496
* [NMessenger](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :large_orange_diamond: :star:2127
* [Atlas](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer. :star:3723
* [Messenger](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support. :star:2902
* [OTTextChatAccelerator](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices. :star:10

## Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and macOS networking framework. :star:30362
* [RestKit](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun. :star:10180
* [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library. :star:401
* [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone. :star:5793
* [Overcoat](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun. :star:1138
* [ROADFramework](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible. :star:50
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :large_orange_diamond: :star:26163
* [Transporter](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond: :star:438
* [CDZPinger](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping. :star:46
* [NSRails](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails. :star:528
* [NKMultipeer](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :large_orange_diamond: :star:15
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS. :star:9456
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :large_orange_diamond: :star:4501
* [OctopusKit](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs. :star:1
* [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. :large_orange_diamond: :star:7650
* [TWRDownloadManager](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files. :star:337
* [HappyDns](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record. :star:317
* [Bridge](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond: :star:93
* [TRON](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond: :star:401
* [EVCloudKitDao](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond: :star:514
* [EVURLCache](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond: :star:255
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond: :star:1685
* [Pitaya](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond: :star:853
* [Just](https://github.com/JustHTTP/Just) - Swift HTTP for Humans :large_orange_diamond: :star:1067
* [agent](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS :large_orange_diamond: :star:611
* [Reach](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond: :star:422
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond: :star:1715
* [Netdiag](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS. :star:65
* [AFNetworkingHelper](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively :star:18
* [NetKit](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond: :star:4
* [RealReachability](https://github.com/dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do. :star:2467
* [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond: :star:1910
* [NetworkKit](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond: :star:26
* [APIKit](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond: :star:1309
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond: :star:254
* [SPTDataLoader](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client. :star:582
* [SWNetworking](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, macOS and tvOS networking library. :star:21
* [Networking](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :large_orange_diamond: :star:1073
* [SOAPEngine](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, macOS app and AppleTV app. :star:433
* [Swish](https://github.com/thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond: :star:357
* [Malibu](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond: :star:307
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking. :star:4881
* [UnboxedAlamofire](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond: :star:57
* [MMLanScan](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library :star:226
* [Domainer](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table :star:6
* [Restofire](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond: :star:149
* [AFNetworking+RetryPolicy](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking. :star:154
* [SwiftyZeroMQ](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚ :star:27
* [Nikka](https://github.com/JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚ :star:12
* [XMNetworking](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking. :star:717
* [Merhaba](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices. :star:33
* [DBNetworkStack](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond: :star:19
* [EFInternetIndicator](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond: :star:108
* [AFNetworking-Synchronous](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x. :star:144
* [QwikHttp](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶 :star:1
* [NetClient](https://github.com/intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :large_orange_diamond: :star:69
* [WANetworkRouting](https://github.com/Wasappli/WANetworkRouting) - An iOS library to route API paths to objects on client side with request, mapping, routing and auth layers :star:10
* [Reactor](https://github.com/MailOnline/Reactor) - Powering your RAC architecture :large_orange_diamond: :star:180
* [SWNetworking](https://github.com/isamankumara/skywite) - Powerful high-level iOS, macOS and tvOS networking library. from the creator of SWNetworking 🔶 :star:4
* [Digger](https://github.com/cornerAnt/Digger) - Digger is a lightweight download framework that requires only one line of code to complete the file download task :star:367
. :large_orange_diamond:
* [Ciao](https://github.com/AlTavares/Ciao) - Publish and discover services using mDNS(Bonjour, Zeroconf). :large_orange_diamond: :star:19
* [PerfectAPIClient](https://github.com/SvenTiigi/PerfectAPIClient) - An API Client based on a network abstraction layer for the Perfect Server-Side Swift Framework 🔶 :star:16

#### Email

* [Mail Core 2](https://github.com/MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP. :star:1681
* [Postal](https://github.com/snipsco/Postal) - A swift framework providing simple access to common email providers. :large_orange_diamond: :star:463

#### Representations

 * [apollo-ios](https://github.com/apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :large_orange_diamond: :star:893
 * [JSONRPCKit](https://github.com/bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :large_orange_diamond: :star:91
 * [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift :large_orange_diamond: :star:821

## Notifications

#### Push Notifications
* [Orbiter](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS. :star:698
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS). :star:3956
* [FBNotifications](https://github.com/facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework. :star:461
* [NWPusher](https://github.com/noodlewerk/NWPusher) - macOS and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications](https://github.com/acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator :star:1234

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement )
* [Growth Push](https://growthpush.com) - Popular in Japan.
* [Braze](https://www.braze.com/)
* [Batch](https://batch.com)
* [Boxcar](https://boxcar.io)
* [Carnival](http://www.carnival.io)
* [Catapush](http://www.catapush.com/)
* [Netmera](https://www.netmera.com/)
* [OneSignal](https://onesignal.com) - Free.
* [PushBots](https://pushbots.com/)
* [Pushwoosh](https://www.pushwoosh.com)
* [Pushkin](https://github.com/Nordeus/pushkin) - Free and open-source. :star:163
* [Pusher](https://pusher.com/push-notifications) - Free and unlimited.
* [Swrve](https://www.swrve.com)

#### Local Notifications
* [DLLocalNotifications](https://github.com/d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :large_orange_diamond: :star:69

## Optimization
* [Unreachable](https://github.com/nvzqz/Unreachable) - Unreachable code path optimization hint for Swift. :large_orange_diamond: :star:87

## Parsing

#### CSV
* [CSwiftV](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond: :star:126

#### JSON
* [JSON-Framework](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C. :star:3803
* [Mantle](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch. :star:10825
* [Groot](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects. :star:486
* [PropertyMapper](https://github.com/krzysztofzablocki/PropertyMapper) - Data mapping and validation with minimal amount of code. :star:1117
* [JSONModel](https://github.com/JSONModel/JSONModel) - Magical Data Modeling Framework for JSON. Create rapidly powerful, atomic and smart data model classes. :star:6371
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond: :star:15949
* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast. :star:523
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :large_orange_diamond: :star:6621
* [JASON](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators. :large_orange_diamond: :star:1008
* [Gloss](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift. :large_orange_diamond: :star:1591
* [Cereal](https://github.com/Weebly/Cereal) - Swift object serialization :large_orange_diamond: :star:378
* [SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :large_orange_diamond: :star:663
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :large_orange_diamond: :star:614
* [Tailor](https://github.com/zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :large_orange_diamond: :star:245
* [alexander](https://github.com/hodinkee/alexander) - An extremely simple JSON helper written in Swift. :large_orange_diamond: :star:37
* [Freddy](https://github.com/bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :large_orange_diamond: :star:1113
* [mapper](https://github.com/lyft/mapper) - A JSON deserialization library for Swift :large_orange_diamond: :star:1029
* [AlamofireJsonToObjects](https://github.com/evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :large_orange_diamond: :star:152
* [Jay](https://github.com/DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & macOS ready. :large_orange_diamond: :star:127
* [YYModel](https://github.com/ibireme/YYModel) - High performance model framework for iOS/macOS. :star:3226
* [Alembic](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond: :star:102
* [Wrap](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond: :star:568
* [Arrow 🏹](https://github.com/freshOS/Arrow) - Elegant JSON Parsing in Swift. :large_orange_diamond: :star:256
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :large_orange_diamond: :star:1078
* [Genome](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux) :large_orange_diamond: :star:787
* [Unbox](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond: :star:1779
* [JSONJoy-Swift](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond: :star:348
* [LazyObject](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond: :star:10
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - JSONExport is a desktop application for macOS which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :large_orange_diamond: :star:2966
* [Elevate](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond: :star:612
* [MJExtension](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file. :star:7364
* [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond: :star:2059
* [GuardedSwiftyJSON](https://github.com/wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initalizers for data models. :large_orange_diamond: :star:4
* [JAYSON](https://github.com/muukii/JAYSON) - Strict and Scalable JSON library. :large_orange_diamond: :star:225
* [HandyJSON](https://github.com/alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :large_orange_diamond: :star:1569
* [Marshal](https://github.com/utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based). :star:601
* [Motis](https://github.com/mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC). :star:248
* [NSTEasyJSON](https://github.com/bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON). :star:5
* [Serpent](https://github.com/nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :large_orange_diamond: :star:274
* [MagicMapper](https://github.com/adrianitech/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :large_orange_diamond: :star:25
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - This project brings FlatBuffers (an efficient cross platform serialization library) to Swift. :large_orange_diamond: :star:473
* [CodableAlamofire](https://github.com/Otbivnoe/CodableAlamofire) - An extension for Alamofire that converts JSON data into Decodable objects (Swift 4). :large_orange_diamond: :star:504
* [WAMapping](https://github.com/Wasappli/WAMapping) - A library to turn dictionary into object and vice versa for iOS. Designed for speed! :star:9

#### XML & HTML
* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond: :star:713
* [Ji](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond: :star:737
* [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS :star:2198
* [AlamofireXmlToObjects](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond: :star:62
* [Fuzi](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond: :star:631
* [Kanna](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for macOS/iOS. :large_orange_diamond:
* [SwiftyXMLParser](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :large_orange_diamond: :star:150
* [HTMLKit](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs. :star:110
* [SWXMLHash](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond: :star:890
* [SwiftyXML](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 3 :large_orange_diamond: :star:21

#### Other Parsing
* [WKZombie](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/macOS to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond: :star:883
* [URLPreview](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond: :star:182
* [FeedKit](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond: :star:394
* [Erik](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond: :star:259
* [URLEmbeddedView](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :large_orange_diamond: :star:426
* [SwiftyConfiguration](https://github.com/ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :large_orange_diamond: :star:105
* [JSONFeed](https://github.com/totocaster/JSONFeed) - Swift parser for JSON Feed, a format similar to RSS and Atom but in JSON. :large_orange_diamond: :star:28
* [SwiftCssParser](https://github.com/100mango/SwiftCssParser) - A Powerful , Extensible CSS Parser written in pure Swift. :large_orange_diamond: :star:233

## Passbook
* [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+. :star:212
* [Dubai](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes. :star:317
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :large_orange_diamond: :star:662
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://moltin.com/ios-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit](https://github.com/MosheBerman/PatronKit) - A framework to add patronage to your apps. :large_orange_diamond: :star:358
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and macOS 9.0+ :large_orange_diamond: :star:2613
* [InAppFramework](https://github.com/sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :large_orange_diamond: :star:38
* [SwiftInAppPurchase](https://github.com/rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :large_orange_diamond: :star:17
* [monza](https://github.com/gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions :star:91
* [EasyIAPs](https://github.com/aaalveee/EasyIAPs) - An easy way to manage In App Purchases :star:5
* [PayPal](https://github.com/paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal. :star:888
* [card.io-iOS-SDK](https://github.com/card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps :star:1930
* [SwiftLuhn](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :large_orange_diamond: :star:106
* [ObjectiveLuhn](https://github.com/MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm :star:119
* [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases :star:2057
* [MFCard](https://github.com/mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI :star:276
* [TPInAppReceipt](https://github.com/tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :large_orange_diamond: :star:34
* [iCard](https://github.com/eliakorkmaz/iCard) - Bank Card Generator with Swift using SnapKit DSL :large_orange_diamond: :star:253

## Permissions
* [Proposer](https://github.com/nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :large_orange_diamond: :star:750
* [ICanHas](https://github.com/wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :large_orange_diamond: :star:81
* [VWWPermissionKit](https://github.com/zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS. :star:131
* [ISHPermissionKit](https://github.com/iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions. :star:580
* [JLPermissions](https://github.com/jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request. :star:403
* [ClusterPrePermissions](https://github.com/rsattar/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request. :star:1206
* [Permission](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS :large_orange_diamond: :star:2296
* [STLocationRequest](https://github.com/SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :large_orange_diamond: :star:557
* [PAPermissions](https://github.com/pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :large_orange_diamond: :star:666
* [AREK](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :large_orange_diamond: :star:794
* [RequestPermission](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI :large_orange_diamond: :star:1641

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io](https://github.com/openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google. :star:304

## Reactive Programming
* [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift :large_orange_diamond: :star:11712
* [RxOptional](https://github.com/thanegill/RxOptional) - RxSwift extentions for Swift optionals and "Occupiable" types :large_orange_diamond: :star:7
* [ReactiveTask](https://github.com/Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :large_orange_diamond: :star:122
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Streams of values over time. :star:18147
* [RxMediaPicker](https://github.com/RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :large_orange_diamond: :star:94
* [ReactiveCoreData](https://github.com/apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world. :star:276
* [ReSwift](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :large_orange_diamond: :star:4526
* [ReactiveKit](https://github.com/ReactiveKit/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :large_orange_diamond: :star:913
* [RxPermission](https://github.com/sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :large_orange_diamond: :star:193
* [RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :large_orange_diamond: :star:820
* [RxRealm](https://github.com/RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :large_orange_diamond: :star:565
* [RxMultipeer](https://github.com/RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :large_orange_diamond: :star:48
* [RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit) - iOS & macOS Bluetooth library for RxSwift :large_orange_diamond: :star:657
* [RxGesture](https://github.com/RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :large_orange_diamond: :star:486
* [NSObject-Rx](https://github.com/RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :large_orange_diamond: :star:261
* [RxCoreData](https://github.com/RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :large_orange_diamond: :star:79
* [RxAutomaton](https://github.com/inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :large_orange_diamond: :star:598
* [ReactiveArray](https://github.com/Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :large_orange_diamond: :star:55
* [Interstellar](https://github.com/JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :large_orange_diamond: :star:975
* [ReduxSwift](https://github.com/lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :large_orange_diamond: :star:32
* [Aftermath](https://github.com/hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :large_orange_diamond: :star:57
* [RxKeyboard](https://github.com/RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :large_orange_diamond: :star:622
* [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON. :star:4849
* [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group :star:1644
* [Listenable](https://github.com/msaps/Listenable) - Swift object that provides an observable platform. :large_orange_diamond: :star:3
* [Reactor](https://github.com/ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :large_orange_diamond: :star:136
* [Snail](https://github.com/UrbanCompass/Snail) - An observables framework for Swift :large_orange_diamond: :star:67
* [RxWebSocket](https://github.com/fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :large_orange_diamond: :star:36
* [ACKReactiveExtensions](https://github.com/AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :large_orange_diamond: :star:10
* [ReactiveLocation](https://github.com/AckeeCZ/ReactiveLocation) - CoreLocation made reactive :large_orange_diamond: :star:14
* [Hanson](https://github.com/blendle/Hanson) - Lightweight observations and bindings in Swift, with support for KVO and NotificationCenter. :large_orange_diamond: :star:467
* [Observable](https://github.com/roberthein/Observable) - The easiest way to observe values in Swift. 🔶 :star:146
* [SimpleApiClient](https://github.com/jaychang0917/SimpleApiClient-ios) - A configurable api client based on Alamofire4 and RxSwift4 for iOS. 🔶 :star:65
* [VueFlux](https://github.com/ra1028/VueFlux) - Unidirectional Data Flow State Management Architecture for Swift - Inspired by Vuex and Flux 🔶 :star:118
* [RxAnimated](https://github.com/RxSwiftCommunity/RxAnimated) - Animated RxCocoa bindings :star:311

## React-Like
* [Render](https://github.com/alexdrone/Render) - Swift and UIKit a la React. :large_orange_diamond: :star:1667
* [Katana](https://github.com/BendingSpoons/katana-swift) - Swift apps a la React and Redux. :large_orange_diamond: :star:1639
* [TemplateKit](https://github.com/mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :large_orange_diamond: :star:130
* [Komponents 📦](https://github.com/freshOS/Komponents) - React-inspired UIKit Components. :large_orange_diamond: :star:148
* [Reactant](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS :large_orange_diamond: :star:316

## Reflection
* [Reflection](https://github.com/Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :large_orange_diamond: :star:371
* [Reflect](https://github.com/CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :large_orange_diamond: :star:306
* [EVReflection](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :large_orange_diamond: :star:764
* [JSONNeverDie](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :large_orange_diamond: :star:475
* [SwiftKVC](https://github.com/bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :large_orange_diamond: :star:107

## Regex
* [Regex](https://github.com/sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :large_orange_diamond: :star:453
* [SwiftRegex](https://github.com/kasei/SwiftRegex) - Perl-like Regex =~ operator for Swift :large_orange_diamond: :star:117
* [PySwiftyRegex](https://github.com/cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :large_orange_diamond: :star:206
* [Regex](https://github.com/crossroadlabs/Regex) - Regular expressions for swift :large_orange_diamond: :star:215
* [Regex](https://github.com/brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :large_orange_diamond: :star:62

## SDK

#### Official

* [Spotify](https://github.com/spotify/ios-sdk) Spotify iOS SDK.
* [SpotifyLogin](https://github.com/spotify/SpotifyLogin) Spotify SDK Login in Swift. :large_orange_diamond:
* [Facebook](https://github.com/facebook/facebook-ios-sdk) Facebook iOS SDK.
* [Facebook Swift](https://github.com/facebook/facebook-sdk-swift) Integrate your iOS apps in Swift with Facebook Platform.
* [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) Google Analytics SDK for iOS
* [Paypal iOS SDK](https://github.com/paypal/PayPal-iOS-SDK) The PayPal Mobile SDKs enable native apps to easily accept PayPal and credit card payments.
* [Pocket](https://github.com/Pocket/Pocket-ObjC-SDK) SDK for saving stuff to Pocket.
* [Tumblr](https://github.com/tumblr/TMTumblrSDK) Library for easily integrating Tumblr data into your iOS or macOS application.
* [Evernote](https://github.com/evernote/evernote-cloud-sdk-ios) Evernote SDK for iOS.
* [Box](https://github.com/box/box-ios-sdk) iOS + macOS SDK for the Box API.
* [OneDrive](https://github.com/OneDrive/onedrive-sdk-ios) Live SDK for iOS.
* [Stripe](https://github.com/stripe/stripe-ios) Stripe bindings for iOS and macOS.
* [Venmo](#payments)
* [AWS](https://github.com/aws/aws-sdk-ios) Amazon Web Services Mobile SDK for iOS.
* [Zendesk](https://github.com/zendesk/zendesk_sdk_ios) Zendesk Mobile SDK for iOS.
* [Adobe Creative SDK](https://creativesdk.adobe.com/) Adobe creative tools and Creative Cloud SDK.
* [Dropbox](https://www.dropbox.com/developers) SDKs for Drop-ins and Dropbox Core API.
* [Fabric by Twitter](https://docs.fabric.io/apple/fabric/overview.html) Fabric Twitter Kit for iOS.
* [Liquid Analytics](https://github.com/lqd-io/liquid-sdk-ios) Identify behaviours through Analytics and react with real-time Personalization.
* [ResearchKit](https://github.com/ResearchKit/ResearchKit) ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects.
* [PacketZoom](https://packetzoom.com) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure](https://github.com/Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device :star:52
* [1Password](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps :star:2391
* [CareKit](https://github.com/carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :large_orange_diamond: :star:1385
* [Shopify](https://github.com/Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app. :star:186
* [Pinterest](https://github.com/pinterest/ios-pdk) - Pinterest iOS SDK :star:99
* [playkit-ios](https://github.com/kaltura/playkit-ios) - PlayKit: Kaltura Player SDK for iOS. :star:18
* [algoliasearch-client-swift](https://github.com/algolia/algoliasearch-client-swift) - Algolia Search API Client for Swift :large_orange_diamond: :star:84

#### Unofficial

* [STTwitter](https://github.com/nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine](https://github.com/natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy](https://github.com/heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit](https://github.com/sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API. :star:96
* [InstagramKit](https://github.com/shyambhat/InstagramKit) - Instagram iOS SDK. :star:909
* [DribbbleSDK](https://github.com/agilie/dribbble-ios-sdk) - Dribbble iOS SDK. :star:78
* [objectiveflickr](https://github.com/lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C. :star:726
* [Easy Social](https://github.com/pjebs/EasySocial) - Twitter & Facebook Integration. :star:130
* [das-quadrat](https://github.com/Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and macOS. :large_orange_diamond: :star:169
* [SocialLib](https://github.com/darkcl/SocialLib) - SocialLib handles sharing message to multiple social media. :star:10
* [PokemonKit](https://github.com/ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :large_orange_diamond: :star:76
* [TJDropbox](https://github.com/timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C :star:48
* [Lyft](https://github.com/genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :large_orange_diamond: :star:60
* [Github.swift](https://github.com/onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :large_orange_diamond: :star:160
* [CloudRail SI](https://github.com/CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more. :star:200
* [Medium SDK - Swift](https://github.com/96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project :large_orange_diamond: :star:8
* [Swifter](https://github.com/mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & macOS written in Swift :large_orange_diamond: :star:1866
* [SlackKit](https://github.com/SlackKit/SlackKit) - a Slack client library for iOS and macOS written in Swift :large_orange_diamond: :star:632
* [RandomUserSwift](https://github.com/dingwilson/RandomUserSwift) - Swift 3 Framework to Generate Random Users - An Unofficial SDK for randomuser.me :large_orange_diamond: :star:80
* [PPEventRegistryAPI](https://github.com/pantuspavel/PPEventRegistryAPI/) - Swift 3 Framework for Event Registry API (eventregistry.org). :large_orange_diamond:
* [UnsplashKit](https://github.com/carambalabs/UnsplashKit) - Swift client for Unsplash. :large_orange_diamond: :star:153
* [Swiftly Salesforce](https://github.com/mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :large_orange_diamond: :star:66
* [Spartan](https://github.com/Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :large_orange_diamond: :star:28
* [BigBoard](https://github.com/Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :large_orange_diamond: :star:41
* [SwiftyVK](https://github.com/SwiftyVK/SwiftyVK) Library for easy interact with VK social network API written in Swift 🔶
* [ARKKit](https://github.com/sleepdefic1t/ARKKit) - ARK Ecosystem Cryptocurrency API Framework for iOS & macOS, written purely in Swift 4.0. :large_orange_diamond: :star:11
* [SwiftInstagram](https://github.com/AnderGoig/SwiftInstagram) - Swift Client for Instagram API. :large_orange_diamond: :star:356
* [SwiftyArk](https://github.com/Awalz/SwiftyArk) - A simple, lightweight, fully-asynchronous cryptocurrency framework for the ARK Ecosystem. :large_orange_diamond: :star:8

## Security
* [cocoapods-keys](https://github.com/orta/cocoapods-keys) - A key value store for storing environment and application keys. :star:916
* [simple-touch](https://github.com/simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS. :star:97
* [SwiftPasscodeLock](https://github.com/yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :large_orange_diamond: :star:568
* [Smile-Lock](https://github.com/recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View. :star:476
* [zxcvbn-ios](https://github.com/dropbox/zxcvbn-ios) - A realistic password strength estimator. :star:153
* [TPObfuscatedString](https://github.com/Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :large_orange_diamond: :star:11
* [LTHPasscodeViewController](https://github.com/rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support. :star:601
* [iOS-App-Security-Class](https://github.com/karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment. :star:34
* [BiometricAuth](https://github.com/vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application 🔶 :star:17
* [SAPinViewController](https://github.com/siavashalipour/SAPinViewController) - Simple and easy to use default iOS PIN screen. This simple library allows you to draw a fully customisable PIN screen same as the iOS default PIN view. My inspiration to create this library was form THPinViewController, however SAPinViewController is completely implemented in Swift. Also the main purpose of creating this library was to have simple, easy to use and fully customisable PIN screen. 🔶 :star:15
* [VoiceItAPI1IosSDK](https://github.com/voiceittech/VoiceItAPI1IosSDK) - A super easy way to add Voice Authentication(Biometrics) to your iOS apps, conveniently usable via cocoapods :large_orange_diamond: :star:4
* [TOPasscodeViewController](https://github.com/timoliver/TOPasscodeViewController) - A modal passcode input and validation view controller for iOS :star:224
* [BiometricAuthentication](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication :large_orange_diamond: :star:376

#### Encryption
* [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works. :star:704
* [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :large_orange_diamond: :star:361
* [Arcane](https://github.com/onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :large_orange_diamond: :star:189
* [SwiftMD5](https://github.com/mpurland/SwiftMD5) - A pure Swift implementation of MD5 :large_orange_diamond: :star:12
* [SwiftHash](https://github.com/onmyway133/SwiftHash) - 🍕 Hash in Swift :large_orange_diamond: :star:53
* [SweetHMAC](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :large_orange_diamond: :star:32
* [SwCrypt](https://github.com/soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and macOS :large_orange_diamond: :star:435
* [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :large_orange_diamond: :star:182
* [SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :large_orange_diamond: :star:403
* [EnigmaKit](https://github.com/mikaoj/EnigmaKit) - Enigma encryption in Swift :large_orange_diamond: :star:98
* [Themis](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/macOS, Android and different server side platforms. :star:456
* [Obfuscator-iOS](https://github.com/pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings. :star:417
* [swift-sodium](https://github.com/jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :large_orange_diamond: :star:199
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :large_orange_diamond: :star:4746
* [SCrypto](https://github.com/sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :large_orange_diamond: :star:15
* [SipHash](https://github.com/attaswift/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :large_orange_diamond: :star:195
* [RNCryptor](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift. -- For ObjC, see RNCryptor/RNCryptor-objc. :large_orange_diamond: :star:2740

#### Keychain
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS. :star:2489
* [Valet](https://github.com/square/Valet) - Securely store data in the iOS or macOS Keychain without knowing a thing about how the Keychain works. :star:2798
* [Locksmith](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :large_orange_diamond: :star:2409
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and macOS :large_orange_diamond: :star:3421
* [Keychains](https://github.com/hyperoslo/Keychains) - Because you should care... about the security... of your shit. :large_orange_diamond: :star:60
* [Lockbox](https://github.com/granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain. :star:840
* [SAMKeychain](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS. :star:4632
* [SwiftKeychainWrapper](https://github.com/jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. Written in Swift. :large_orange_diamond: :star:638

## Server
* [Perfect](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :large_orange_diamond: :star:12462
* [Swifter](https://github.com/httpswift/swifter) - Tiny http server engine written in Swift programming language. :large_orange_diamond: :star:2165
* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for macOS or iOS applications. :star:4384
* [Curassow](https://github.com/kylef/Curassow) - Swift HTTP server using the pre-fork worker model. :large_orange_diamond: :star:393
* [Zewo](https://github.com/Zewo/Zewo) - Venice based HTTP server for Swift 2.2 on Linux :large_orange_diamond: :star:1742
* [Vapor](https://github.com/vapor/vapor) - Elegant web framework for Swift that works on iOS, macOS, and Ubuntu. :large_orange_diamond: :star:11875
* [swiftra](https://github.com/takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :large_orange_diamond: :star:274
* [blackfire](https://github.com/elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :large_orange_diamond: :star:948
* [swift-http](https://github.com/huytd/swift-http) - HTTP Implementation for Swift on Linux and macOS :large_orange_diamond: :star:461
* [Trevi](https://github.com/Yoseob/Trevi) - libuv base Swift web HTTP server framework :large_orange_diamond: :star:47
* [Express](https://github.com/crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :large_orange_diamond: :star:851
* [Taylor](https://github.com/izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :large_orange_diamond: :star:925
* [Frank](https://github.com/kylef/Frank) - Frank is a DSL for quickly writing web applications in Swift :large_orange_diamond: :star:381
* [Kitura](https://github.com/IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :large_orange_diamond: :star:6193
* [Swifton](https://github.com/necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and macOS :large_orange_diamond: :star:2056
* [Dynamo](https://github.com/johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :large_orange_diamond: :star:65
* [Redis](https://github.com/vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. macOS + Linux compatible. :large_orange_diamond: :star:348
* [NetworkObjects](https://github.com/colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux) :large_orange_diamond: :star:268
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift. :large_orange_diamond:
* [Edge](https://github.com/skylab-inc/Edge) - A Swift Multiplatform Web and Networking Framework. :large_orange_diamond: :star:293
* [SwiftGD](https://github.com/twostraws/swiftgd) - A simple Swift wrapper for libgd. :large_orange_diamond: :star:178
* [Jobs](https://github.com/BrettRToomey/Jobs) - A job system for Swift backends. :large_orange_diamond: :star:157
* [ApacheExpress](https://github.com/ApacheExpress/ApacheExpress) - Write Apache Modules in Swift! :large_orange_diamond: :star:169
* [GCDWebServer](https://github.com/swisspol/GCDWebServer) - Lightweight GCD based HTTP server for macOS & iOS (includes web based uploader & WebDAV server)

## Text
* [Twitter Text Obj](https://github.com/twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library. :star:1802
* [Nimbus](https://github.com/jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers. :star:6365
* [NSStringEmojize](https://github.com/diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters. :star:607
* [MMMarkdown](https://github.com/mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML. :star:1102
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText. :star:5213
* [DTRichTextEditor](https://github.com/Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS. :star:293
* [NBEmojiSearchView](https://github.com/neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view. :star:80
* [Pluralize.swift](https://github.com/joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :large_orange_diamond: :star:135
* [RichEditorView](https://github.com/cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :large_orange_diamond: :star:968
* [Money](https://github.com/danthorpe/Money) - Swift value types for working with money & currency :large_orange_diamond: :star:802
* [PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :large_orange_diamond: :star:2167
* [YYText](https://github.com/ibireme/YYText) - Powerful text framework for iOS to display and edit rich text. :star:6877
* [Format](https://github.com/marmelroy/Format) - A Swift Formatter Kit. :large_orange_diamond: :star:1149
* [Tribute](https://github.com/zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :large_orange_diamond: :star:57
* [EmojiKit](https://github.com/dasmer/EmojiKit) - Effortless emoji-querying in Swift :large_orange_diamond: :star:85
* [Roman](https://github.com/nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :large_orange_diamond: :star:33
* [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view. :star:2664
* [pangu.Objective-C](https://github.com/Cee/pangu.objective-c) - Paranoid text spacing in Objective-C. :star:106
* [SwiftString](https://github.com/amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :large_orange_diamond: :star:1428
* [Marklight](https://github.com/macteo/Marklight) - Markdown syntax highlighter for iOS :large_orange_diamond: :star:365
* [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :large_orange_diamond: :star:553
* [TextAttributes](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings. :large_orange_diamond:[e] :star:1940
* [Reductio](https://github.com/fdzsergio/Reductio) - Automatic summarizer text in Swift :large_orange_diamond: :star:347
* [SmarkDown](https://github.com/SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :large_orange_diamond: :star:60
* [SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :large_orange_diamond: :star:785
* [SZMentions](https://github.com/szweier/SZMentions) - Library to help handle mentions :star:8
* [SZMentionsSwift](https://github.com/szweier/SZMentionsSwift) - Library to help handle mentions. :star:30
* [Heimdall](https://github.com/henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :large_orange_diamond: :star:295
* [NoOptionalInterpolation](https://github.com/T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.🔶[e] :star:41
* [Smile](https://github.com/onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601](https://github.com/onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift 🔶[e]
* [Translucid](https://github.com/Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :large_orange_diamond: :star:525
* [FormatterKit](https://github.com/mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set :star:4042
* [BonMot](https://github.com/Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :large_orange_diamond: :star:1875
* [SwiftValidators](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator). :star:130
* [StringStylizer](https://github.com/kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :large_orange_diamond: :star:32
* [SwiftyAttributes](https://github.com/eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :large_orange_diamond: :star:894
* [MarkdownKit](https://github.com/ivanbruel/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :large_orange_diamond: :star:114
* [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and macOS. :large_orange_diamond: :star:947
* [Apodimark](https://github.com/loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :large_orange_diamond: :star:440
* [Notepad](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :large_orange_diamond: :star:312
* [KKStringValidator](https://github.com/krizhanovskii/KKStringValidator) - Fast and simple string validation for iOS. With UITextField extension. :large_orange_diamond: :star:15
* [ISO8859](https://github.com/Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :large_orange_diamond: :star:10
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne](https://github.com/emojione/emojione). :large_orange_diamond: :star:42
* [SwiftRichString](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :large_orange_diamond: :star:1267
* [libPhoneNumber-iOS](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library). :star:1747
* [AttributedTextView](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions). :star:220
* [StyleDecorator](https://github.com/dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts :star:9
* [Mustard](https://github.com/mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :large_orange_diamond: :star:668
* [Input Mask](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :large_orange_diamond: :star:119
* [Attributed](https://github.com/Nirma/Attributed) - Modern Swift µframework for attributed strings. :large_orange_diamond: :star:612
* [Atributika](https://github.com/psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :large_orange_diamond: :star:164
* [Guitar](https://github.com/ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :large_orange_diamond: :star:545
* [RealTimeCurrencyFormatter](https://github.com/kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility. :star:11
* [Down](https://github.com/iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. 🔶 :star:573
* [Marky Mark](https://github.com/m2mobi/Marky-Mark) - Highly customizable Markdown parsing and native rendering in Swift. 🔶 :star:64
* [MarkdownView](https://github.com/keitaoouchi/MarkdownView) - Markdown View for iOS. 🔶 :star:1026
* [Highlighter](https://github.com/younatics/Highlighter) - Highlight whatever you want! Highlighter will magically find UI objects such as UILabel, UITextView, UITexTfield, UIButton in your UITableViewCell or other Class. :large_orange_diamond: :star:650

#### Font
* [FontBlaster](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :large_orange_diamond: :star:861
* [GoogleMaterialIconFont](https://github.com/kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :large_orange_diamond: :star:137
* [ios-fontawesome](https://github.com/alexdrone/ios-fontawesome) - NSString+FontAwesome. :star:1746
* [FontAwesome.swift](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :large_orange_diamond: :star:915
* [SwiftFontName](https://github.com/morizotter/SwiftFontName) - OS font complements library. Localized font supported :large_orange_diamond: :star:92
* [SwiftIconFont](https://github.com/0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon) :large_orange_diamond: :star:810
* [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons. :star:2588
* [Iconic](https://github.com/dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS  :large_orange_diamond: :star:1398
* [GoogleMaterialDesignIcons](https://github.com/dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :large_orange_diamond: :star:363
* [OcticonsKit](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond: :star:34
* [IoniconsKit](https://github.com/keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond: :star:296
* [FontAwesomeKit.Swift](https://github.com/qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :large_orange_diamond: :star:157
* [UIFontComplete](https://github.com/Nirma/UIFontComplete) - Make working with UIFont faster and less error-prone. :large_orange_diamond: :star:921
* [Swicon](https://github.com/UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :large_orange_diamond: :star:34
* [SwiftIcons](https://github.com/ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :large_orange_diamond: :star:359

## Testing

#### TDD / BDD
* [Kiwi](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development. :star:3717
* [Specta](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa. :star:2092
* [Quick](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C. :star:7097
* [XcodeCoverage](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects. :star:701
* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers! :star:3491
* [Dixie](https://github.com/Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours. :star:202
* [gh-unit](https://github.com/gh-unit/gh-unit) - Test Framework for Objective-C. :star:1920
* [Nimble](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C :large_orange_diamond: :star:2532
* [Sleipnir](https://github.com/railsware/Sleipnir) - BDD-style framework for Swift :large_orange_diamond: :star:851
* [SwiftCheck](https://github.com/typelift/SwiftCheck) - QuickCheck for Swift :large_orange_diamond: :star:872

#### A/B Testing
* [Switchboard](https://github.com/KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users. :star:267
* [SkyLab](https://github.com/mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac :star:686
* [MSActiveConfig](https://github.com/mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS :star:81
* [ABKit](https://github.com/recruit-mp/ABKit) - AB testing framework for iOS :large_orange_diamond: :star:98

#### UI Testing
* [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS. :star:186
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary](https://github.com/serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework. :star:147
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework. :star:5140
* [Subliminal](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing. :star:788
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any iOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Zucchini](https://github.com/zucchini-src/zucchini) - A visual iOS testing framework that loves your apps. :star:164
* [Remote](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing. :star:655
* [LayoutTest-iOS](https://github.com/linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations. :star:498
* [EarlGrey](https://github.com/google/EarlGrey) - :tea: iOS UI Automation Test Framework. :star:3984
* [UI Testing Cheat Sheet](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :large_orange_diamond: :star:1211
* [Floater_](https://github.com/Buglife/Floater_) - Add a floating fingertip to your app demo :large_orange_diamond: :star:235
* [Bluepill](https://github.com/linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine :star:2505
* [Flawless App](https://flawlessapp.io/) - tool for visual quality check of mobile app in a real-time. It compares initial design with the actual implementation right inside iOS simulator.

#### Other Testing
* [NaughtyKeyboard](https://github.com/Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device. :star:584
* [Fakery](https://github.com/vadymmarkov/Fakery) - Swift fake data generator. :large_orange_diamond: :star:785
* [DVR](https://github.com/venmo/DVR) - Network testing for Swift :large_orange_diamond: :star:513
* [Cuckoo](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :large_orange_diamond: :star:649
* [Parallel iOS Tests](https://github.com/plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :large_orange_diamond:
* [Vinyl](https://github.com/Velhotes/Vinyl) - Network testing à la VCR in Swift :large_orange_diamond: :star:207
* [Mockit](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :large_orange_diamond: :star:62
* [Cribble](https://github.com/maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :large_orange_diamond: :star:273
* [second_curtain](https://github.com/ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3 :star:114
* [trainer](https://github.com/KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports :star:98
* [Buildasaur](https://github.com/buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :large_orange_diamond: :star:723
* [Kakapo](https://github.com/devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :large_orange_diamond: :star:731
* [AcceptanceMark](https://github.com/bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit](https://github.com/metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :large_orange_diamond: :star:19
* [MirrorDiffKit](https://github.com/Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :large_orange_diamond: :star:102
* [SnappyTestCase](https://github.com/tooploox/SnappyTestCase) - iOS Simulator type agnostic snapshot testing, built on top of the FBSnapshotTestCase. :large_orange_diamond: :star:8

## UI
* [FlatUIKit](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS. :star:7677
* [BetweenKit](https://github.com/ice3-software/between-kit) - A robust drag-and-drop framework for iOS. :star:261
* [MDCSwipeToChoose](https://github.com/modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours! :star:2485
* [Motif](https://github.com/erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS. :star:821
* [Texture](https://github.com/TextureGroup/Texture) - Smooth asynchronous user interfaces for iOS apps. :star:2480
* [GaugeKit](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :large_orange_diamond: :star:897
* [MVMaterialView](https://github.com/TheMrugraj/MVMaterialView) - Subclass of UIControls and UIButton to mimic Ripple effect of Material Design concept. :star:66
* [TisprCardStack](https://github.com/tispr/tispr-card-stack) - Library that allows to have cards UI. :large_orange_diamond: :star:659
* [SAHistoryNavigationViewController](https://github.com/marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :large_orange_diamond: :star:1494
* [SAInboxViewController](https://github.com/marty-suzuki/SAInboxViewController) - UIViewController subclass inspired by "Inbox by google" animated transitioning. :large_orange_diamond: :star:284
* [iCarousel](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS. :star:10047
* [Cocoa Controls](https://www.cocoacontrols.com/) - Open source UI components for iOS and macOS.
* [tapkulibrary](https://github.com/devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework. :star:4010
* [HorizontalDial](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :large_orange_diamond: :star:105
* [ComponentKit](http://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [PMTween](https://github.com/poetmountain/PMTween) - An elegant and flexible tweening library for iOS. :star:340
* [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center. :star:2817
* [EatFit](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :large_orange_diamond: :star:612
* [phone-number-picker](https://github.com/hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :large_orange_diamond: :star:115
* [EXTView](https://github.com/recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable. :star:155
* [SFFocusViewLayout](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout with focused content. :star:1598
* [CardAnimation](https://github.com/seedante/CardAnimation) - Card flip animation by pan gesture. :large_orange_diamond: :star:1004
* [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [HorizontalProgress](https://github.com/AliThink/HorizontalProgress) - Simple horizontal progress bar with animation :star:159
* [JRSplitVC](https://github.com/tommypeps/JRSplitVC) - UISplitViewController with adaptative layouts :star:30
* [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :large_orange_diamond: :star:1510
* [Splitflap](https://github.com/yannickl/Splitflap) - A simple split-flap display for your Swift applications :large_orange_diamond: :star:768
* [EZSwipeController](https://github.com/goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :large_orange_diamond: :star:711
* [Koloda](https://github.com/Yalantis/Koloda) - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. :large_orange_diamond: :star:3557
* [XLActionController](https://github.com/xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller written in Swift. :large_orange_diamond: :star:2282
* [StackPageView](https://github.com/noppefoxwolf/StackPageView) - Vertical page view with UIViewControllers stacked on the top of each other :large_orange_diamond: :star:34
* [PageControl](https://github.com/kasper-lahti/PageControl) - ● ○ ○ ○ A nice, animated UIPageControl alternative. :large_orange_diamond: :star:95
* [Curry](https://github.com/devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit. :star:32
* [Pages](https://github.com/hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :large_orange_diamond: :star:373
* [BothamUI](https://github.com/Karumi/BothamUI) - Model View Presenter Framework written in Swift. :large_orange_diamond: :star:341
* [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation) - An easy way to change backgroundColor of UINavigationBar when Push & Pop :large_orange_diamond: :star:661
* [ALTextInputBar](https://github.com/AlexLittlejohn/ALTextInputBar) - An auto growing text input bar for messaging apps. :large_orange_diamond: :star:187
* [APCustomBlurView](https://github.com/collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :large_orange_diamond: :star:155
* [BAFluidView](https://github.com/antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion :star:1277
* [WZDraggableSwitchHeaderView](https://github.com/wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers :star:511
* [MICountryPicker](https://github.com/mustafaibrahim989/MICountryPicker) - Swift country picker with search option. :large_orange_diamond: :star:77
* [SCNavigationControlCenter](https://github.com/SergioChan/SCNavigationControlCenter) - This is an advanced navigation control center on iOS that can allow you to navigate to whichever view controller you want :star:396
* [SCTrelloNavigation](https://github.com/SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation. :star:786
* [FXBlurView](https://github.com/nicklockwood/FXBlurView) - UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above. :star:5013
* [NGAParallaxMotion](https://github.com/michaeljbishop/NGAParallaxMotion) - A tiny category on UIView that allows you to set one property: "parallaxIntensity" to achieve a parallax effect with UIMotionEffect :star:679
* [EPShapes](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder. :large_orange_diamond: :star:374
* [CRParticleEffect](https://github.com/Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects. :star:355
* [Spots](https://github.com/hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :large_orange_diamond: :star:1181
* [APAddressBook](https://github.com/Alterplay/APAddressBook) - Easy access to iOS address book :star:1393
* [AZExpandableIconListView](https://github.com/Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :large_orange_diamond: :star:193
* [greedo-layout-for-ios](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS :star:807
* [FlourishUI](https://github.com/thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :large_orange_diamond: :star:205
* [GranadaLayout](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater. :star:41
* [Navigation Stack](https://github.com/Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :large_orange_diamond: :star:1924
* [UIView-draggable](https://github.com/andreamazz/UIView-draggable) - UIView category that adds dragging capabilities. :star:384
* [PeekPop](https://github.com/marmelroy/PeekPop) - Backwards-compatible Peek and Pop. :star:1874
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. 🔶 :star:77
* [EPSignature](https://github.com/ipraba/EPSignature) - Signature component for iOS in Swift :large_orange_diamond: :star:647
* [CoreDragon](https://github.com/nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :large_orange_diamond: :star:42
* [EVFaceTracker](https://github.com/evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face. :star:221
* [Fashion](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :large_orange_diamond: :star:73
* [LeeGo](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :large_orange_diamond: :star:905
* [MEVHorizontalContacts](https://github.com/manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items. :star:304
* [Ripple](https://github.com/RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :large_orange_diamond: :star:55
* [ScalePicker](https://github.com/kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app. :star:140
* [VisualEffectView](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :large_orange_diamond: :star:455
* [NumPad](https://github.com/efremidze/NumPad) - Number Pad (inspired by Square's design). :large_orange_diamond: :star:46
* [expanding-collection](https://github.com/Ramotion/expanding-collection) - ExpandingCollection is a card peek/pop controller :large_orange_diamond: :star:4037
* [Cacao](https://github.com/PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux) :large_orange_diamond: :star:818
* [LFTimePicker](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :large_orange_diamond: :star:40
* [StateView](https://github.com/sahandnayebaziz/StateView) - Views that automatically update themselves. :large_orange_diamond: :star:496
* [JDFlipNumberView](https://github.com/calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays. :star:721
* [JQSwiftIcon](https://github.com/josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :large_orange_diamond: :star:5
* [FlickToDismiss](https://github.com/jakelawson1/FlickToDismiss) - A basic UIViewController class that presents a UIView which can be dismissed by flicking it off the screen. :large_orange_diamond: :star:207
* [ISTimeline](https://github.com/instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :large_orange_diamond: :star:891
* [JFCardSelectionViewController](https://github.com/atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :large_orange_diamond: :star:394
* [DCKit](https://github.com/agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :large_orange_diamond: :star:90
* [BackgroundVideoiOS](https://github.com/Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views. :star:506
* [NightNight](https://github.com/Draveness/NightNight) - Elegant way to integrate night mode to swift projects :large_orange_diamond: :star:601
* [SwiftTheme](https://github.com/jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :large_orange_diamond: :star:980
* [PinpointKit](https://github.com/Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :large_orange_diamond: :star:985
* [FDStackView](https://github.com/forkingdog/FDStackView) - Use UIStackView directly in iOS6+ :star:2359
* [Popover](https://github.com/corin8823/Popover) - Popover is a balloon library like Facebook app. It is written in pure swift. :large_orange_diamond: :star:1325
* [YangMingShan](https://github.com/yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps. :star:619
* [TOActionSheet](https://github.com/TimOliver/TOActionSheet) - A custom-designed reimplementation of the UIActionSheet control for iOS :star:158
* [nui](https://github.com/tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS :star:3761
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material](https://github.com/CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :large_orange_diamond: :star:8990
* [Blurable](https://github.com/FlexMonkey/Blurable) - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions :large_orange_diamond: :star:821
* [EZYGradientView](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :large_orange_diamond: :star:303
* [DistancePicker](https://github.com/qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :large_orange_diamond: :star:95
* [OAStackView](https://github.com/nsomar/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView. :star:2176
* [StyleKit](https://github.com/146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. Behind the scenes, StyleKit uses UIAppearance and some selector magic to apply the styles. You can also customize the parser for greater flexibility. :large_orange_diamond: :star:1132
* [planet](https://github.com/kwallet/planet) - A country picker :large_orange_diamond: :star:52
* [PageController](https://github.com/hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :large_orange_diamond: :star:208
* [StatusProvider](https://github.com/mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :large_orange_diamond: :star:800
* [ASBubbleDrag](https://github.com/scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :large_orange_diamond: :star:38
* [StackLayout](https://github.com/bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns. :star:78
* [NightView](https://github.com/Boris-Em/NightView) - Dazzling Nights on iOS. :large_orange_diamond: :star:159
* [VENTokenField](https://github.com/venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app. :star:748
* [SwiftVideoBackground](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementing a video background :large_orange_diamond: :star:92
* [MRArticleViewController](https://github.com/mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :large_orange_diamond: :star:102
* [Macaw](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :large_orange_diamond: :star:3237
* [HubFramework](https://github.com/spotify/HubFramework) - Spotify’s component-driven UI framework for iOS. :star:1795
* [ConfettiView](https://github.com/OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :large_orange_diamond: :star:217
* [BouncyPageViewController](https://github.com/BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :large_orange_diamond: :star:624
* [LTHRadioButton](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :large_orange_diamond: :star:196
* [CRRulerControl](https://github.com/Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument. :star:93
* [Macaw-Examples](https://github.com/exyte/Macaw-Examples) - Various usages of the Macaw library. :large_orange_diamond: :star:156
* [KVCardSelectionVC](https://github.com/kunalverma25/KVCardSelectionVC) - Awesome looking Dial like card selection ViewController. :large_orange_diamond: :star:14
* [Reactions](https://github.com/yannickl/Reactions) - Fully customizable Facebook reactions control :large_orange_diamond: :star:448
* [Newly](https://github.com/dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :large_orange_diamond: :star:175
* [CardStackController](https://github.com/jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :large_orange_diamond: :star:342
* [Material Components](https://github.com/material-components/material-components-ios) - Google developed UI components that help developers execute Material Design. :star:1809
* [DMSwipeCards](https://github.com/D-32/DMSwipeCards) - Tinder like card stack that supports lazy loading and generics :large_orange_diamond: :star:199
* [RKMultiUnitRuler](https://github.com/farshidce/RKMultiUnitRuler/) - Simple customizable ruler control that supports multiple units. 🔶
* [FAQView](https://github.com/mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :large_orange_diamond: :star:361
* [CRPageViewController](https://github.com/Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further. :star:374
* [OXPatternLock](https://github.com/oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :large_orange_diamond: :star:18
* [LMArticleViewController](https://github.com/lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts :star:5
* [FSPagerView](https://github.com/WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :large_orange_diamond: :star:2507
* [PanelKit](https://github.com/louisdh/panelkit) - A UI framework that enables panels on iOS. :large_orange_diamond: :star:2913
* [ElongationPreview](https://github.com/Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond: :star:635
* [Pageboy](https://github.com/uias/Pageboy) - A simple, highly informative page view controller. :large_orange_diamond: :star:893
* [IGColorPicker](https://github.com/iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift 🔶 :star:76
* [KPActionSheet](https://github.com/khuong291/KPActionSheet) - 🔶 A replacement of default action sheet, but has very simple usage. 🔶 :star:4
* [SegmentedProgressBar](https://github.com/D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :large_orange_diamond: :star:184
* [CHIPageControl](https://github.com/ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl. :large_orange_diamond: :star:1633
* [Magnetic](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). 🔶 :star:722
* [AmazingBubbles](https://github.com/GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. 🔶 :star:40
* [Haptica](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator. :large_orange_diamond: :star:204
* [GDCheckbox](https://github.com/saeid/GDCheckbox) - An easy to use custom checkbox/radio button component for iOS, with support of IBDesign Inspector. 🔶 :star:4
* [HamsterUIKit](https://github.com/ChromieIsDangerous/HamsterUIKit) - A simple and elegant UIKit(Chart) for iOS.  🔶 :star:12
* [AZEmptyState](https://github.com/Minitour/AZEmptyState) - A UIControl subclass that makes it easy to create empty states. 🔶 :star:67
* [URWeatherView](https://github.com/jegumhon/URWeatherView) - Show the weather effects onto view written in Swift3. 🔶 :star:335
* [LCUIComponents](https://github.com/linhcn/LCUIComponents) - A framework supports creating transient views on top of other content onscreen such as popover with a data list. 🔶 :star:5
* [ViewComposer](https://github.com/Sajjon/ViewComposer) - `let lbl: UILabel = [.text("Hello"), .textColor(.red)]` - Create views using array literal of enum expressing view attributes. :star:14
* [BatteryView](https://github.com/yonat/BatteryView) - Simple battery shaped UIView. 🔶 :star:10
* [ShadowView](https://github.com/PierrePerrin/ShadowView) - Make shadows management easy on UIView :large_orange_diamond: :star:226
* [Pulley](https://github.com/52inc/Pulley) - A library to imitate the iOS 10 Maps UI :large_orange_diamond: :star:847
* [N8iveKit](https://github.com/n8iveapps/N8iveKit) - A set of frameworks making iOS development more fun. :large_orange_diamond: :star:18
* [Panda](https://github.com/wordlessj/Panda) - Create view hierarchies declaratively. :large_orange_diamond: :star:17
* [NotchKit](https://github.com/HarshilShah/NotchKit) - A simple way to hide the notch on the iPhone X :large_orange_diamond: :star:1787
* [Overlay](https://github.com/TintPoint/Overlay) - Overlay is a flexible UI framework designed for Swift. It allows you to write CSS like Swift code. :large_orange_diamond: :star:37
* [SwiftyUI](https://github.com/haoking/SwiftyUI) - High performance and lightweight(one class each UI) UIView, UIImage, UIImageView, UIlabel, UIButton, Promise and more. 🔶 :star:109
* [NotchToolkit](https://github.com/AFathi/NotchToolkit) - A framework for iOS that allow developers use the iPhone X notch in creative ways. 🔶 :star:32
* [PullUpController](https://github.com/MarioIannotta/PullUpController) - Pull up controller with multiple sticky points like in iOS Maps. 🔶 :star:415
* [DrawerKit](https://github.com/Babylonpartners/DrawerKit) - DrawerKit lets an UIViewController modally present another UIViewController in a manner similar to the way Apple's Maps app works. :large_orange_diamond: :star:438
* [TimelineCards](https://github.com/vladaverin24/TimelineCards) - Presenting timelines as cards, single or bundled in scrollable feed!. :star:204
* [Shades](https://github.com/aaronjsutton/Shades) - Easily add drop shadows, borders, and round corners to a UIView. :large_orange_diamond: :star:5
* [ISPageControl](https://github.com/Interactive-Studio/ISPageControl) - A page control similar to that used in Instagram. 🔶 :star:120

#### Activity Indicator

* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :large_orange_diamond: :star:6165
* [TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator) - Rubber Indicator in Swift :large_orange_diamond: :star:1050
* [RPLoadingAnimation](https://github.com/naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :large_orange_diamond: :star:180
* [LiquidLoader](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation :large_orange_diamond: :star:1019
* [iOS-CircleProgressView](https://github.com/CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :large_orange_diamond: :star:396
* [iOS Circle Progress Bar](https://github.com/Eclair/CircleProgressBar) - iOS Circle Progress Bar :star:346
* [LinearProgressBar](https://github.com/PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :large_orange_diamond: :star:90
* [STLoadingGroup](https://github.com/saitjr/STLoadingGroup) - loading views :large_orange_diamond: :star:317
* [ALThreeCircleSpinner](https://github.com/AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :large_orange_diamond: :star:35
* [MHRadialProgressView](https://github.com/mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view. :star:81
* [Loader](https://github.com/Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :large_orange_diamond: :star:88
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. :star:14020
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app. :star:10418
* [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD. :star:990
* [M13ProgressSuite](https://github.com/Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS. :star:3636
* [PKHUD](https://github.com/pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :large_orange_diamond: :star:2607
* [EZLoadingActivity](https://github.com/goktugyil/EZLoadingActivity) - Lightweight loading activity HUD.  :large_orange_diamond: :star:527
* [FFCircularProgressView](https://github.com/elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view :star:1005
* [MRProgress](https://github.com/mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress :star:2589
* [BigBrother](https://github.com/marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :large_orange_diamond: :star:455
* [AlamofireNetworkActivityIndicator](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :large_orange_diamond: :star:429
* [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :large_orange_diamond: :star:678
* [DACircularProgress](https://github.com/danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties. :star:2241
* [KYNavigationProgress](https://github.com/ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. :large_orange_diamond:[e] :star:196
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :large_orange_diamond: :star:564
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module. :star:3794
* [MKRingProgressView](https://github.com/maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. 🔶 :star:664
* [Hexacon](https://github.com/gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. 🔶 :star:254
* [StackViewController](https://github.com/seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :large_orange_diamond: :star:625
* [ParticlesLoadingView](https://github.com/BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :large_orange_diamond: :star:781
* [RPCircularProgress](https://github.com/iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :large_orange_diamond: :star:119
* [MBCircularProgressBar](https://github.com/MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable. :star:712
* [WSProgressHUD](https://github.com/devSC/WSProgressHUD) - This is a beautiful hud view for iPhone & iPad :star:534
* [DBMetaballLoading](https://github.com/dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :large_orange_diamond: :star:57
* [FillableLoaders](https://github.com/polqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond: :star:1774
* [PageControls](https://github.com/popwarsweet/PageControls) - This is a selection of custom page controls to replace UIPageControl, inspired by a dribbble found here :large_orange_diamond: :star:641
* [VHUD](https://github.com/xxxAIRINxxx/VHUD) Simple HUD. :large_orange_diamond:
* [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :large_orange_diamond: :star:1665
* [SnapTimer](https://github.com/andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :large_orange_diamond: :star:255
* [AudioIndicatorBars](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :large_orange_diamond: :star:167
* [LLSpinner](https://github.com/alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :large_orange_diamond: :star:11
* [SVUploader](https://github.com/kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy.  :large_orange_diamond: :star:36
* [YLProgressBar](https://github.com/yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics. :star:1061
* [FlexibleSteppedProgressBar](https://github.com/amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar.  :large_orange_diamond: :star:124
* [GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar. :large_orange_diamond: :star:57
* [DSGradientProgressView](https://github.com/DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :large_orange_diamond: :star:248
* [GradientProgressBar](https://github.com/fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :large_orange_diamond: :star:23
* [BPCircleActivityIndicator](https://github.com/ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :large_orange_diamond: :star:35
* [DottedProgressBar](https://github.com/nikola9core/DottedProgressBar) - Simple and customizable animated progress bar with dots for iOS. :large_orange_diamond: :star:20
* [RSLoadingView](https://github.com/roytornado/RSLoadingView) - Awesome loading animations using 3D engine written with Swift. :large_orange_diamond: :star:247
* [SendIndicator](https://github.com/LeonardoCardoso/SendIndicator) - Yet another task indicator :large_orange_diamond: :star:36
* [StepProgressView](https://github.com/yonat/StepProgressView) - Step-by-step progress view with labels and shapes. A good replacement for UIActivityIndicatorView and UIProgressView. :large_orange_diamond: :star:55
* [BPBlockActivityIndicator](https://github.com/ppth0608/BPBlockActivityIndicator) - A simple and awesome Loading Activity Indicator(with funny block animation) for your iOS app. :large_orange_diamond: :star:27
* [JustHUD](https://github.com/shubh10/JustHUD) - JustHUD is an iOS drop-in class written in Swift that displays a translucent HUD. :large_orange_diamond: :star:13
* [JDBreaksLoading](https://github.com/jamesdouble/JDBreaksLoading) - You can easily start up a little breaking game indicator by one line. :large_orange_diamond: :star:125
* [SkeletonView](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting. :large_orange_diamond: :star:2876
* [Windless](https://github.com/Interactive-Studio/Windless) - Windless makes it easy to implement invisible layout loading view. :large_orange_diamond: :star:541
* [Skeleton](https://github.com/gonzalonunez/Skeleton) - An easy way to create sliding CAGradientLayer animations! Works great for creating skeleton screens for loading content. 🔶 :star:309
+* [StatusBarOverlay](https://github.com/IdleHandsApps/StatusBarOverlay) - Automatically show/hide a "No Internet Connection" bar when your app loses/gains connection. It supports apps which hide the status bar and "The Notch" 🔶

#### Animation
* [Pop](https://github.com/facebook/pop) - An extensible iOS and macOS animation library, useful for physics-based interactions. :star:18422
* [AnimationEngine](https://github.com/intuit/AnimationEngine) - Easily build advanced custom animations on iOS. :star:1034
* [Awesome-iOS-Animation](https://github.com/jackymelb/awesome-ios-animation) - Collection of Animation projects :star:841
* [RZTransitions](https://github.com/Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions. :star:1760
* [DCAnimationKit](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations. :star:735
* [Spring](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift. :large_orange_diamond: :star:11657
* [Canvas](https://github.com/CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io :star:5250
* [Fluent](https://github.com/matthewcheok/Fluent) - Swift animation made easy :large_orange_diamond: :star:305
* [Cheetah](https://github.com/suguru/Cheetah) - Easy animation library on iOS with Swift2. :large_orange_diamond: :star:566
* [RadialLayer](https://github.com/soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :large_orange_diamond: :star:52
* [Pop By Example](https://github.com/hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example. :star:179
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation](https://github.com/icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :large_orange_diamond: :star:2507
* [Animo](https://github.com/eure/Animo) - SpriteKit-like animation builders for CALayers. :large_orange_diamond: :star:187
* [CurryFire](https://github.com/devinross/curry-fire) - A framework for creating unique animations. :star:86
* [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :large_orange_diamond: :star:6922
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :large_orange_diamond: :star:1600
* [DaisyChain](https://github.com/alikaragoz/DaisyChain) - :link: Easy animation chaining :large_orange_diamond: :star:26
* [SYBlinkAnimationKit](https://github.com/shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :large_orange_diamond: :star:103
* [PulsingHalo](https://github.com/shu223/PulsingHalo) - iOS Component for creating a pulsing animation. :star:1618
* [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit) - Chainable animations in Swift :large_orange_diamond: :star:1808
* [JDAnimationKit](https://github.com/JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :large_orange_diamond: :star:561
* [Advance](https://github.com/storehouse/Advance) - A powerful animation framework for iOS. :large_orange_diamond: :star:4056
* [UIView-Shake](https://github.com/andreamazz/UIView-Shake) - UIView category that adds shake animation :star:475
* [Walker](https://github.com/RamonGilabert/Walker) - A new animation engine for your app. :large_orange_diamond: :star:140
* [Morgan](https://github.com/RamonGilabert/Morgan) - An animation set for your app. :large_orange_diamond: :star:95
* [MagicMove](https://github.com/patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :large_orange_diamond: :star:11
* [Shimmer](https://github.com/facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app. :star:8265
* [SAConfettiView](https://github.com/sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :large_orange_diamond: :star:1050
* [CCMRadarView](https://github.com/cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :large_orange_diamond: :star:183
* [Pulsator](https://github.com/shu223/Pulsator) - Pulse animation for iOS :large_orange_diamond: :star:816
* [Interpolate](https://github.com/marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :large_orange_diamond: :star:1539
* [ADPuzzleAnimation](https://github.com/Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :large_orange_diamond: :star:111
* [Wave](https://github.com/onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :large_orange_diamond: :star:68
* [Stellar](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift :large_orange_diamond: :star:2489
* [MotionMachine](https://github.com/poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :large_orange_diamond: :star:336
* [JRMFloatingAnimation](https://github.com/carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views. :star:171
* [AHKBendableView](https://github.com/fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :large_orange_diamond: :star:593
* [FlightAnimator](https://github.com/AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :large_orange_diamond: :star:562
* [ZoomTransitioning](https://github.com/WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :large_orange_diamond: :star:549
* [Ubergang](https://github.com/RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :large_orange_diamond: :star:46
* [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C :star:3028
* [Popsicle](https://github.com/DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :large_orange_diamond: :star:1132
* [WXWaveView](https://github.com/WelkinXie/WXWaveView) - Add a pretty water wave to your view. :star:296
* [Twinkle](https://github.com/piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :large_orange_diamond: :star:447
* [MotionBlur](https://github.com/fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations. :star:1495
* [RippleEffectView](https://github.com/alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :large_orange_diamond: :star:300
* [Keyframes](https://github.com/facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices. :star:4759
* [SwiftyAnimate](https://github.com/rchatham/SwiftyAnimate) - Composable animations in Swift. :large_orange_diamond: :star:150
* [SamuraiTransition](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat “cutting” animations. :large_orange_diamond: :star:207
* [Lottie](https://github.com/airbnb/lottie-ios) - An iOS library for a real time rendering of native vector animations from Adobe After Effects. :star:11723
* [Overlap](https://github.com/ML-Works/Overlap) - Tiny iOS library to achieve overlap visual effect. :large_orange_diamond: :star:119
* [anim](https://github.com/onurersel/anim) - An animation library for iOS with custom easings and easy to follow API. :large_orange_diamond: :star:48
* [AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout) - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView. :large_orange_diamond: :star:2844
* [Dance](https://github.com/saoudrizwan/Dance) - A radical & elegant animation library built for iOS. :large_orange_diamond: :star:614
* [AKVideoImageView](https://github.com/numen31337/AKVideoImageView) - UIImageView subclass which allows you to display a looped video as a background. :star:112
* [Spruce iOS Animation Library](https://github.com/willowtreeapps/spruce-ios) - Swift library for choreographing animations on the screen.:large_orange_diamond: :star:2191
* [CircularRevealKit](https://github.com/T-Pro/CircularRevealKit) - UI framework that implements the material design's reveal effect. 🔶 :star:9
* [TweenKit](https://github.com/SteveBarnegren/TweenKit) - Animation library for iOS in Swift. 🔶 :star:620
* [Water](https://github.com/KrisYu/Water) - Simple calculation to render cheap water effects. 🔶 :star:325
* [CRRefresh](https://github.com/CRAnimation/CRRefresh) - An easy way to use pull-to-refresh. 🔶 :star:401
* [Pastel](https://github.com/cruisediary/Pastel) - Gradient animation effect like Instagram. 🔶 :star:2342
* [YapAnimator](https://github.com/yapstudios/YapAnimator) - Your fast and friendly physics-based animation system. :large_orange_diamond: :star:1755
* [Bubble](https://github.com/goldmoment/Bubble) - Fruit Animation :large_orange_diamond: :star:185
* [Gemini](https://github.com/shoheiyokoyama/Gemini) - Gemini is rich scroll based animation framework for iOS, written in Swift :large_orange_diamond: :star:2054
* [WaterDrops](https://github.com/LeFal/WaterDrops) - Simple water drops animation for iOS in Swift :large_orange_diamond: :star:213
* [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) - ViewAnimator brings your UI to life with just one line. 🔶 :star:2697

##### Transition
* [BlurryModalSegue](https://github.com/Citrrus/BlurryModalSegue) - A custom modal segue for providing a blurred overlay effect. :star:927
* [DAExpandAnimation](https://github.com/ifitdoesntwork/DAExpandAnimation) - A custom modal transition that presents a controller with an expanding effect while sliding out the presenter remnants. :large_orange_diamond: :star:532
* [BubbleTransition](https://github.com/andreamazz/BubbleTransition) - A custom modal transition that presents and dismiss a controller with an expanding bubble effect. :large_orange_diamond: :star:2607
* [RPModalGestureTransition](https://github.com/naoyashiga/RPModalGestureTransition) - You can dismiss modal by using gesture :point_up_2: :iphone: :large_orange_diamond: :star:87
* [RMPZoomTransitionAnimator](https://github.com/recruit-mp/RMPZoomTransitionAnimator) - A custom zooming transition animation for UIViewController :star:1582
* [ElasticTransition](https://github.com/lkzhao/ElasticTransition) - A UIKit custom transition that simulates an elastic drag. Written in Swift. :large_orange_diamond: :star:1813
* [ElasticTransition-ObjC](https://github.com/taglia3/ElasticTransition-ObjC) - A UIKit custom transition that simulates an elastic drag.This is the Objective-C Version of Elastic Transition written in Swift by lkzhao :star:362
* [ZFDragableModalTransition](https://github.com/zoonooz/ZFDragableModalTransition) - Custom animation transition for present modal view controller :star:2321
* [ImageOpenTransition](https://github.com/mcmatan/ImageOpenTransition) - Beautiful and precise transitions between ViewControllers images written in Swift. :large_orange_diamond: :star:796
* [ZOZolaZoomTransition](https://github.com/NewAmsterdamLabs/ZOZolaZoomTransition) - Zoom transition that animates the entire view heirarchy. Used extensively in the Zola iOS application. :star:880
* [JTMaterialTransition](https://github.com/jonathantribouharet/JTMaterialTransition) - An iOS transition for controllers based on material design. :star:891
* [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery) - Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol. :star:2253
* [TransitionTreasury](https://github.com/DianQK/TransitionTreasury) - Easier way to push your viewController. :large_orange_diamond: :star:1936
* [Presenter](https://github.com/muukii/Presenter) - Screen transition with safe and clean code.  :large_orange_diamond: :star:10
* [Kaeru](https://github.com/bannzai/Kaeru) - Switch viewcontroller like iOS task manager :large_orange_diamond: :star:416
* [View2ViewTransition](https://github.com/naru-jpn/View2ViewTransition) - Custom interactive view controller transition from one view to another view. :large_orange_diamond: :star:776
* [AZTransitions](https://github.com/azimin/AZTransitions) - API to make great custom transitions in one method. :large_orange_diamond: :star:365
* [Hero](https://github.com/lkzhao/Hero) - Supercharged transition engine for iOS. Build your custom view transitions with no code at all. Inspired by Keynote's Magic Move. :large_orange_diamond: :star:11537
* [Motion](https://github.com/CosmicMind/Motion) - Seamless animations and transitions in Swift. :large_orange_diamond: :star:787
* [PresenterKit](https://github.com/jessesquires/PresenterKit) - Swifty view controller presentation for iOS :large_orange_diamond: :star:408
* [Transition](https://github.com/Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions. :large_orange_diamond: :star:1809
* [Gagat](https://github.com/Boerworz/Gagat) - A delightful way to transition between visual styles in your iOS applications. :large_orange_diamond: :star:732
* [DeckTransition](https://github.com/HarshilShah/DeckTransition) - A library to recreate the iOS Apple Music now playing transition :large_orange_diamond: :star:1606
* [TransitionableTab](https://github.com/Interactive-Studio/TransitionableTab) - TransitionableTab makes it easy to animate when switching between tab :large_orange_diamond: :star:418

#### Alert & Action Sheet

* [SweetAlert](https://github.com/codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift. :large_orange_diamond: :star:1779
* [NYAlertViewController](https://github.com/nealyoung/NYAlertViewController) - Highly configurable iOS Alert Views with custom content views. :star:519
* [SCLAlertView-Swift](https://github.com/vikmeup/SCLAlertView-Swift) - Beautiful animated Alert View, written in Swift. :large_orange_diamond: :star:4115
* [TTGSnackbar](https://github.com/zekunyan/TTGSnackbar) - Show simple message and action button on the bottom of the screen with multi kinds of animation. :large_orange_diamond: :star:351
* [Swift-Prompts](https://github.com/GabrielAlva/Swift-Prompts) - A Swift library to design custom prompts with a great scope of options to choose from. :large_orange_diamond: :star:714
* [BRYXBanner](https://github.com/bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift. :large_orange_diamond: :star:857
* [LNRSimpleNotifications](https://github.com/LISNR/LNRSimpleNotifications) - Simple Swift in-app notifications. LNRSimpleNotifications is a simplified Swift port of TSMessages :large_orange_diamond: :star:170
* [HDNotificationView](https://github.com/nhdang103/HDNotificationView) - Emulates the native Notification Banner UI for any alert. :star:247
* [JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification) - Easy, customizable notifications displayed on top of the statusbar. :star:3365
* [Notie](https://github.com/thii/Notie) - In-app notification in Swift, with customizable buttons and input text field. :large_orange_diamond: :star:79
* [EZAlertController](https://github.com/thellimist/EZAlertController) - Easy Swift UIAlertController :large_orange_diamond: :star:281
* [GSMessages](https://github.com/wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+. :large_orange_diamond: :star:266
* [OEANotification](https://github.com/OEA/OEANotification) - In-app customizable notification views on top of screen for iOS which is written in Swift 2.1. :large_orange_diamond: :star:18
* [RKDropdownAlert](https://github.com/cwRichardKim/RKDropdownAlert) - Extremely simple UIAlertView alternative. :star:1446
* [TKSwarmAlert](https://github.com/entotsu/TKSwarmAlert) - Animated alert library like Swarm app. :large_orange_diamond: :star:460
* [Whisper](https://github.com/hyperoslo/Whisper) - Whisper is a component that will make the task of display messages and in-app notifications simple. It has three different views inside :large_orange_diamond: :star:3175
* [SimpleAlert](https://github.com/KyoheiG3/SimpleAlert) - Customizable simple Alert and simple ActionSheet for Swift :large_orange_diamond: :star:294
* [Hokusai](https://github.com/ytakzk/Hokusai) - A Swift library to provide a bouncy action sheet :large_orange_diamond: :star:381
* [SwiftNotice](https://github.com/johnlui/SwiftNotice) - SwiftNotice is a GUI library for displaying various popups (HUD) written in pure Swift, fits any scrollview. :large_orange_diamond: :star:622
* [SwiftOverlays](https://github.com/peterprokop/SwiftOverlays) - SwiftOverlays is a Swift GUI library for displaying various popups and notifications :large_orange_diamond: :star:496
* [SwiftyDrop](https://github.com/morizotter/SwiftyDrop) - SwiftyDrop is a lightweight pure Swift simple and beautiful dropdown message. :large_orange_diamond: :star:562
* [LKAlertController](https://github.com/Lightningkite/LKAlertController) - An easy to use UIAlertController builder for swift. :large_orange_diamond: :star:61
* [DOAlertController](https://github.com/okmr-d/DOAlertController) - Simple Alert View written in Swift, which can be used as a UIAlertController. (AlertController/AlertView/ActionSheet) :large_orange_diamond: :star:337
* [CustomizableActionSheet](https://github.com/beryu/CustomizableActionSheet) - Action sheet allows including your custom views and buttons. :large_orange_diamond: :star:129
* [Toast-Swift](https://github.com/scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class. :large_orange_diamond: :star:948
* [PMAlertController](https://github.com/Codeido/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController. 🔶 :star:1694
* [PopupViewController](https://github.com/dimillian/PopupViewController) - UIAlertController drop in replacement with much more customization. 🔶 :star:15
* [AlertViewLoveNotification](https://github.com/PhilippeBoisney/AlertViewLoveNotification) - A simple and attractive AlertView to ask permission to your users for Push Notification. 🔶 :star:26
* [CRToast](https://github.com/cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs :star:3984
* [JLToast](https://github.com/devxoul/Toaster) - Toast for iOS with very simple interface. :large_orange_diamond: :star:895
* [CuckooAlert](https://github.com/rollmind/CuckooAlert) - Multiple use of presentViewController for UIAlertController. 🔶 :star:5
* [KRAlertController](https://github.com/krimpedance/KRAlertController) - A colored alert view for your iOS. :large_orange_diamond: :star:35
* [Dodo](https://github.com/evgenyneu/Dodo) - A message bar for iOS written in Swift. :large_orange_diamond: :star:772
* [MaterialActionSheetController](https://github.com/ntnhon/MaterialActionSheetController) - A Google like action sheet for iOS written in Swift. :large_orange_diamond: :star:84
* [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift. :large_orange_diamond: :star:2717
* [FCAlertView](https://github.com/krispenney/FCAlertView) - A Flat Customizable AlertView for iOS. (Swift) :large_orange_diamond: :star:76
* [FCAlertView](https://github.com/nimati/FCAlertView) - A Flat Customizable AlertView for iOS. (Objective-C)
* [CDAlertView](https://github.com/candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup 🔶 :star:755
* [RMActionController](https://github.com/CooperRS/RMActionController) - Present any UIView in an UIAlertController like manner. :star:369
* [RMDateSelectionViewController](https://github.com/CooperRS/RMDateSelectionViewController) - Select a date using UIDatePicker in a UIAlertController like fashion. :star:1035
* [RMPickerViewController](https://github.com/CooperRS/RMPickerViewController) - Select something using UIPickerView in a UIAlertController like fashion. :star:335
* [Hedwig](https://github.com/dereklimbus/hedwig) - Interactive notification :large_orange_diamond: :star:17
* [Jelly](https://github.com/SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code. :large_orange_diamond: :star:1438
* [Malert](https://github.com/vitormesquita/Malert) - Malert is a simple, easy and custom iOS UIAlertView written in Swift 🔶 :star:163
* [RAlertView](https://github.com/roycms/AlertView) - AlertView, iOS popup window, A pop-up framework, Can be simple and convenient to join your project. :star:43
* [NoticeBar](https://github.com/qiuncheng/NoticeBar) - 😍A simple NoticeBar written by Swift 3, similar with QQ notice view. :large_orange_diamond: :star:227
* [LIHAlert](https://github.com/Lasithih/LIHAlert) - Advance animated banner alerts for iOS :large_orange_diamond: :star:23
* [BPStatusBarAlert](https://github.com/ppth0608/BPStatusBarAlert) - A simple alerts that appear on the status bar and below navigation bar(like Facebook).🔶 :star:72
* [CFAlertViewController](https://github.com/Codigami/CFAlertViewController) -  A library that helps you display and customise alerts and action sheets on iPad and iPhone.🔶 :star:822
* [NotificationBanner](https://github.com/Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS. 🔶 :star:1517
* [Alertift](https://github.com/sgr-ksmt/Alertift) - Swifty, modern UIAlertController wrapper. :large_orange_diamond: :star:74
* [PCLBlurEffectAlert](https://github.com/hryk224/PCLBlurEffectAlert) - Swift AlertController with UIVisualEffectView. :large_orange_diamond: :star:128
* [JDropDownAlert](https://github.com/trilliwon/JDropDownAlert) - Multi dirction dropdown alert view. 🔶 :star:37
* [BulletinBoard](https://github.com/alexaubry/BulletinBoard) - Generate and Display Bottom Card Interfaces on iOS :large_orange_diamond: :star:2146
* [Cards](https://github.com/PaoloCuscela/Cards) - Awesome iOS 11 AppStore's Card Views. :large_orange_diamond: :star:2089
* [CFNotify](https://github.com/hallelujahbaby/CFNotify) - A customizable framework to create draggable views. :large_orange_diamond: :star:373

#### Badge
* [MIBadgeButton](https://github.com/mustafaibrahim989/MIBadgeButton-Swift) - Notification badge for UIButtons. :large_orange_diamond: :star:293
* [EasyNotificationBadge](https://github.com/Minitour/EasyNotificationBadge) - UIView extension that adds a notification badge. :large_orange_diamond:[e] :star:36
* [Sheriff](https://github.com/gemr/Sheriff) - Add badges to anything. :star:239
* [swift-badge](https://github.com/evgenyneu/swift-badge) - Badge view for iOS written in swift :large_orange_diamond: :star:243

#### Button
* [SSBouncyButton](https://github.com/StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component. :star:298
* [DOFavoriteButton](https://github.com/okmr-d/DOFavoriteButton) - Cute Animated Button written in Swift. :large_orange_diamond: :star:2934
* [SDevCircleButton](https://github.com/0x73/SDevCircleButton) - Flat circle button :large_orange_diamond:
* [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) - Flat button with 9 different states animated using Facebook POP. :star:2888
* [HTPressableButton](https://github.com/Famolus/HTPressableButton) - Flat design pressable button. :star:827
* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state :large_orange_diamond: :star:3177
* [JTFadingInfoView](https://github.com/JunichiT/JTFadingInfoView) - An UIButton-based view with fade in/out animation features. :star:126
* [Floaty](https://github.com/kciter/Floaty) - :heart: Floating Action Button for iOS :large_orange_diamond: :star:594
* [TVButton](https://github.com/marmelroy/TVButton) - Recreating the cool parallax icons from Apple TV as iOS UIButtons (in Swift). :large_orange_diamond: :star:948
* [SwiftyButton](https://github.com/TakeScoop/SwiftyButton) - Simple and customizable button in Swift :large_orange_diamond: :star:258
* [AnimatablePlayButton](https://github.com/suzuki-0000/AnimatablePlayButton) - Animated Play and Pause Button using CALayer, CAKeyframeAnimation. :large_orange_diamond: :star:70
* [gbkui-button-progress-view](https://github.com/Guidebook/gbkui-button-progress-view) - Inspired by Apple’s download progress buttons in the App Store. :star:515
* [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) - Custom UIButton effect inspired by Google Material Design :large_orange_diamond: :star:1300
* [JOEmojiableBtn](https://github.com/lojals/JOEmojiableBtn) - Emoji selector like Facebook Reactions. :star:227
* [EMEmojiableBtn](https://github.com/Eke/EMEmojiableBtn) - Option selector that works similar to Reactions by fb. Objective-c version. :star:70
* [WYMaterialButton](https://github.com/Yu-w/WYMaterialButton) - Interactive and fully animated Material Design button for iOS developers. :star:60
* [DynamicButton](https://github.com/yannickl/DynamicButton) - Yet another animated flat buttons in Swift :large_orange_diamond: :star:878
* [OnOffButton](https://github.com/rakaramos/OnOffButton) - Custom On/Off Animated UIButton, written in Swift. By Creativedash :large_orange_diamond: :star:421
* [CRNetworkButton](https://github.com/Cleveroad/CRNetworkButton) - Send Button for iOS :large_orange_diamond: :star:618
* [WCLShineButton](https://github.com/imwcl/WCLShineButton) - This is a UI lib for iOS. Effects like shining. :large_orange_diamond: :star:1002
* [EasySocialButton](https://github.com/Minitour/EasySocialButton) - An easy way to create beautiful social authentication buttons. :large_orange_diamond: :star:131
* [NFDownloadButton](https://github.com/LeonardoCardoso/NFDownloadButton) - Revamped Download Button. 🔶 :star:279
* [LGButton](https://github.com/loregr/LGButton) - A fully customisable subclass of the native UIControl which allows you to create beautiful buttons without writing any line of code. :large_orange_diamond: :star:1521
* [MultiToggleButton](https://github.com/yonat/MultiToggleButton) - A UIButton subclass that implements tap-to-toggle button text (Like the camera flash and timer buttons). :large_orange_diamond: :star:27
* [PMSuperButton](https://github.com/Codeido/PMSuperButton) - A powerful UIButton with super powers, customizable from Storyboard! 🔶 :star:382
* [JSButton](https://github.com/imjog/JSButton) - A fully customisable swift subclass on UIButton which allows you to create beautiful buttons without writing any line of code. 🔶 :star:1
* [TransitionButton](https://github.com/AladinWay/TransitionButton) - UIButton sublass for loading and transition animation :large_orange_diamond: :star:376
* [ButtonProgressBar-iOS](https://github.com/thePsguy/ButtonProgressBar-iOS) - A small and flexible UIButton subclass with animated loading progress, and completion animation. :large_orange_diamond: :star:239
* [SpicyButton](https://github.com/lukecrum/SpicyButton) - Full-featured IBDesignable UIButton class 🔶 :star:1
* [DesignableButton](https://github.com/IdleHandsApps/DesignableButton) - UIButton subclass with centralised and reusable styles. View styles and customise in InterfaceBuilder in real time! 🔶 :star:50

#### Calendar
* [CVCalendar](https://github.com/CVCalendar/CVCalendar) - A custom visual calendar for iOS 8+ written in Swift (2.0). :large_orange_diamond: :star:2804
* [RSDayFlow](https://github.com/ruslanskorb/RSDayFlow) - iOS 7+ Calendar with Infinite Scrolling. :star:761
* [NWCalendarView](https://github.com/nbwar/NWCalendarView) - An availability calendar implementation for iOS :large_orange_diamond: :star:54
* [FSCalendar](https://github.com/WenchaoD/FSCalendar) - A superiorly awesome iOS7+ calendar control, compatible with both Objective-C and Swift2. :star:5682
* [GLCalendarView](https://github.com/Glow-Inc/GLCalendarView) - A fully customizable calendar view acting as a date range picker :star:814
* [JTCalendar](https://github.com/jonathantribouharet/JTCalendar) - A customizable calendar view for iOS. :star:2456
* [JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar) - The Unofficial Swift Apple Calendar Library. View. Control. for iOS & tvOS :large_orange_diamond: :star:4030
* [Daysquare](https://github.com/unixzii/Daysquare) - An elegant calendar control for iOS. :star:618
* [ASCalendar](https://github.com/scamps88/ASCalendar) - A calendar control for iOS written in swift with mvvm pattern :large_orange_diamond: :star:188
* [Calendar](https://github.com/jumartin/Calendar) - A set of views and controllers for displaying and scheduling events on iOS :star:538
* [Koyomi](https://github.com/shoheiyokoyama/Koyomi) - Simple customizable calendar component in Swift :large_orange_diamond: :star:502
* [DateTimePicker](https://github.com/itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time :large_orange_diamond: :star:1291
* [RCalendarPicker](https://github.com/roycms/RCalendarPicker) - RCalendarPicker A date picker control. :star:57
* [CalendarKit](https://github.com/richardtop/CalendarKit) - Fully customizable calendar day view. :large_orange_diamond: :star:799
* [GDPersianCalendar](https://github.com/saeid/GDPersianCalendar) - Customizable and easy to use Persian Calendar component. 🔶 :star:4
* [MBCalendarKit](https://github.com/MosheBerman/MBCalendarKit) - A calendar framework for iOS built with customization, and localization in mind. :star:542
* [PTEventView](https://github.com/amantaneja/PTEventView) - An Event View based on Apple's Event Detail View within Calender.Supports ARC, Autolayout and editing via StoryBoard. 🔶 :star:24
* [KDCalendarView](https://github.com/mmick66/CalendarView) - A calendar component for iOS written in Swift 4.0. It features both vertical and horizontal layout (and scrolling) and the display of native calendar events. :star:98

#### Form & Settings
* [Form](https://github.com/hyperoslo/Form) - The most flexible and powerful way to build a form on iOS :star:1597
* [XLForm](https://github.com/xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms. Fully compatible with Swift & Obj-C. :star:4775
* [Eureka](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder in pure Swift. :large_orange_diamond: :star:7346
* [YALField](https://github.com/Yalantis/YALField) - Custom Field component with validation for creating easier form-like UI from interface builder. :star:454
* [Former](https://github.com/ra1028/Former) - Former is a fully customizable Swift2 library for easy creating UITableView based form. :large_orange_diamond: :star:951
* [SwiftForms](https://github.com/ortuman/SwiftForms) - A small and lightweight library written in Swift that allows you to easily create forms. :large_orange_diamond: :star:1136
* [APValidators](https://github.com/Alterplay/APValidators) - Codeless solution for form validation in iOS! :star:116
* [Formalist](https://github.com/seedco/Formalist) - Declarative form building framework for iOS :large_orange_diamond: :star:127
* [SwiftyFORM](https://github.com/neoneye/SwiftyFORM) - SwiftyFORM is a form framework for iOS written in Swift :large_orange_diamond: :star:716
* [FXForms](https://github.com/nicklockwood/FXForms) - FXForms is an Objective-C library for easily creating table-based forms on iOS. It is ideal for settings pages, or user data entry tasks. :star:3030
* [SwiftValidator](https://github.com/SwiftValidatorCommunity/SwiftValidator) - A rule-based validation library for Swift :large_orange_diamond: :star:982
* [MZFormSheetPresentationController](https://github.com/m1entus/MZFormSheetPresentationController) - MZFormSheetPresentationController provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet. :star:875
* [GenericPasswordRow](https://github.com/EurekaCommunity/GenericPasswordRow) - A row for Eureka to implement password validations. :large_orange_diamond: :star:140
* [SuggestionsBox](https://github.com/manuelescrig/SuggestionsBox) - SuggestionsBox helps you build better a product trough your user suggestions. :large_orange_diamond: :star:99
* [formvalidator-swift](https://github.com/ustwo/formvalidator-swift) - A framework to validate inputs of text fields and text views in a convenient way. :large_orange_diamond: :star:461
* [LightForm](https://github.com/farshidce/LightForm) - A Simple interactive and customizable library to handle form input and validations :star:5
* [ValidationToolkit](https://github.com/nsagora/validation-toolkit) - Lightweight framework for input validation written in Swift. :large_orange_diamond: :star:7

#### Keyboard
* [RSKKeyboardAnimationObserver](https://github.com/ruslanskorb/RSKKeyboardAnimationObserver) - Showing / dismissing keyboard animation in simple UIViewController category. :star:37
* [RFKeyboardToolbar](https://github.com/ruddfawcett/RFKeyboardToolbar) - This is a flexible UIView and UIButton subclass to add customized buttons and toolbars to your UITextFields/UITextViews. :star:405
* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView. :star:10554
* [NgKeyboardTracker](https://github.com/meiwin/NgKeyboardTracker) - Objective-C library for tracking keyboard in iOS apps. :star:774
* [MMNumberKeyboard](https://github.com/matmartinez/MMNumberKeyboard) - A simple keyboard to use with numbers and, optionally, a decimal point. :star:883
* [KeyboardObserver](https://github.com/morizotter/KeyboardObserver) - For less complicated keyboard event handling. :large_orange_diamond: :star:104
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS :star:5445
* [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) - iOS utility class allows you to access keyboard view and track keyboard animation. :star:383
* [KeyboardMan](https://github.com/nixzhu/KeyboardMan) - KeyboardMan helps you make keyboard animation. :large_orange_diamond: :star:333
* [MakemojiSDK](https://github.com/makemoji/MakemojiSDK) - Emoji Keyboard SDK (iOS)
* [Typist](https://github.com/totocaster/Typist) - Small, drop-in Swift UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center. :large_orange_diamond: :star:833
* [KeyboardHideManager](https://github.com/bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS written in Swift :large_orange_diamond: :star:49
* [Toolbar](https://github.com/1amageek/Toolbar) - Awesome autolayout Toolbar. :large_orange_diamond: :star:363
* [IHKeyboardAvoiding](https://github.com/IdleHandsApps/IHKeyboardAvoiding) - A drop-in universal solution for keeping any UIView visible when the keyboard is being shown - no more UIScrollViews! 🔶 :star:1070

#### Label
* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel written in Swift. :large_orange_diamond: :star:6040
* [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift :large_orange_diamond: :star:2061
* [MZTimerLabel](https://github.com/mineschan/MZTimerLabel) - A handy class for iOS to use UILabel as a countdown timer or stopwatch just like in Apple Clock App. :star:1360
* [CountdownLabel](https://github.com/suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function. :large_orange_diamond: :star:343
* [IncrementableLabel](https://github.com/tbaranes/IncrementableLabel) - Incrementable label for iOS, macOS, and tvOS. :large_orange_diamond: :star:37
* [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more :star:7886
* [NumberMorphView](https://github.com/me-abhinav/NumberMorphView) - A label view for displaying numbers which can transition or animate using a technique called number tweening or number morphing. :large_orange_diamond: :star:1328
* [GlitchLabel](https://github.com/kciter/GlitchLabel) - Glitching UILabel for iOS. :large_orange_diamond: :star:692
* [TOMSMorphingLabel](https://github.com/tomknig/TOMSMorphingLabel) - Configurable morphing transitions between text values of a label. :star:1846
* [THLabel](https://github.com/tobihagemann/THLabel) - UILabel subclass, which additionally allows shadow blur, inner shadow, stroke text and fill gradient. :star:549
* [RQShineLabel](https://github.com/zipme/RQShineLabel) - Secret app like text animation :star:1705
* [ZCAnimatedLabel](https://github.com/overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation :star:1832
* [TriLabelView](https://github.com/mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS written in Swift. :large_orange_diamond: :star:113
* [Preloader.Ophiuchus](https://github.com/Yalantis/Preloader.Ophiuchus) - Custom Label to apply animations on whole text or letters. :star:825
* [MTLLinkLabel](https://github.com/recruit-mtl/MTLLinkLabel) - MTLLinkLabel is linkable UILabel. Written in Swift. :large_orange_diamond: :star:69
* [UICountingLabel](https://github.com/dataxpress/UICountingLabel/) - Adds animated counting support to UILabel.
* [SlidingText](https://github.com/dnKaratzas/SlidingText) -  Swift UIView for sliding text with page indicator. :large_orange_diamond: :star:37
* [NumericAnimatedLabel](https://github.com/javalnanda/NumericAnimatedLabel/) -  Swift UIView for showing numeric label with incremental and decremental step animation while changing value. Useful for scenarios like displaying currency. :large_orange_diamond:
* [JSLabel](https://github.com/imjog/JSLabel/) -  A simple designable subclass on UILabel with extra IBDesignable and Blinking features. :large_orange_diamond:

#### Login
* [LFLoginController](https://github.com/awesome-labs/LFLoginController) - Customizable login screen, written in Swift. :large_orange_diamond: :star:92
* [LoginKit](https://github.com/IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.  🔶 :star:429
* [Cely](https://github.com/chaione/Cely) - Plug-n-Play login framework written in Swift. :large_orange_diamond: :star:87

#### Menu
* [ENSwiftSideMenu](https://github.com/evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift. :large_orange_diamond: :star:1714
* [RESideMenu](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect inspired by Dribbble shots. :star:7082
* [SSASideMenu](https://github.com/SSA111/SSASideMenu) - A Swift implementation of RESideMenu. A iOS 7/8 style side menu with parallax effect. :large_orange_diamond: :star:585
* [PagingMenuController](https://github.com/kitasuke/PagingMenuController) - Paging view controller with customizable menu in Swift. :large_orange_diamond: :star:2079
* [RadialMenu](https://github.com/bradjasper/radialmenu) - RadialMenu is a custom control for providing a touch context menu (like iMessage recording in iOS 8) built with Swift & POP :large_orange_diamond: :star:283
* [cariocamenu](https://github.com/arn00s/cariocamenu) - The fastest zero-tap iOS menu. :large_orange_diamond: :star:580
* [VLDContextSheet](https://github.com/vangelov/VLDContextSheet) - Context menu similar to the one in the Pinterest iOS app :star:169
* [GuillotineMenu](https://github.com/Yalantis/GuillotineMenu) - Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine. :large_orange_diamond: :star:2573
* [MediumMenu](https://github.com/pixyzehn/MediumMenu) - A menu based on Medium iOS app. :large_orange_diamond: :star:298
* [SwiftySideMenu](https://github.com/hossamghareeb/SwiftySideMenu) - SwiftySideMenu is a lightweight and easy to use side menu controller to add left menu and center view controllers with scale animation based on Pop framework. :star:79
* [LLSlideMenu](https://github.com/lilei644/LLSlideMenu) - This is a spring slide menu for iOS apps :star:561
* [Swift-Slide-Menu](https://github.com/PhilippeBoisney/Swift-Slide-Menu) - A Slide Menu, written in Swift, inspired by Slide Menu Material Design. :large_orange_diamond: :star:61
* [MenuItemKit](https://github.com/cxa/MenuItemKit) - UIMenuItem with image and block(closure) :large_orange_diamond: :star:335
* [BTNavigationDropdownMenu](https://github.com/PhamBaTho/BTNavigationDropdownMenu) - The elegant dropdown menu, written in Swift, appears underneath navigation bar to display a list of related items when a user click on the navigation title. :large_orange_diamond: :star:2171
* [ALRadialMenu](https://github.com/AlexLittlejohn/ALRadialMenu) - A radial/circular menu featuring spring animations. Written in swift :large_orange_diamond: :star:34
* [AZDropdownMenu](https://github.com/Azuritul/AZDropdownMenu) - An easy to use dropdown menu that supports images. :large_orange_diamond: :star:164
* [CircleMenu](https://github.com/Ramotion/circle-menu) - An animated, multi-option menu button. :large_orange_diamond: :star:2458
* [SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure Swift. :large_orange_diamond: :star:2833
* [SideMenu](https://github.com/jonkykong/SideMenu) - Simple side menu control in Swift inspired by Facebook. Right and Left sides. Lots of customization and animation options. Can be implemented in Storyboard with no code. :large_orange_diamond: :star:2044
* [CategorySliderView](https://github.com/cemolcay/CategorySliderView) - slider view for choosing categories. add any UIView type as category item view. Fully customisable :star:359
* [MKDropdownMenu](https://github.com/maxkonovalov/MKDropdownMenu) - A Dropdown Menu for iOS with many customizable parameters to suit any needs. :star:342
* [ExpandingMenu](https://github.com/monoqlo/ExpandingMenu) - ExpandingMenu is menu button for iOS written in Swift. :large_orange_diamond: :star:273
* [PageMenu](https://github.com/PageMenu/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) :large_orange_diamond: :star:4444
* [XXXRoundMenuButton](https://github.com/zsy78191/XXXRoundMenuButton) - A simple circle style menu. :star:296
* [IGCMenu](https://github.com/sunilsharma08/IGCMenu) - Grid and Circular menu with animation.Easy to customise. :star:89
* [EEJSelectMenu](https://github.com/eejahromi/EEJSelectMenu) - Single selection menu with cool animations, responsive with all screen sizes. :star:16
* [IGLDropDownMenu](https://github.com/bestwnh/IGLDropDownMenu) - An iOS drop down menu with pretty animation and easy to customize. :star:1117
* [Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS) - Animated side menu with customizable UI :large_orange_diamond: :star:2467
* [PopMenu](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app. :star:824
* [FlowingMenu](https://github.com/yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects in Swift :large_orange_diamond: :star:761
* [Persei](https://github.com/Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift :large_orange_diamond: :star:2866
* [DropDown](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS :large_orange_diamond: :star:1010
* [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) - A not bad gooey effects menu. :star:1743
* [SideMenuController](https://github.com/teodorpatras/SideMenuController) - A side menu controller written in Swift :large_orange_diamond: :star:934
* [Context-Menu.iOS](https://github.com/Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app. :star:1800
* [ViewDeck](https://github.com/ViewDeck/ViewDeck) - An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps. :star:5240
* [FrostedSidebar](https://github.com/edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's :large_orange_diamond: :star:435
* [VHBoomMenuButton](https://github.com/Nightonke/VHBoomMenuButton) - A menu which can ... BOOM! :star:427
* [DropDownMenuKit](https://github.com/qmathe/DropDownMenuKit) - A simple, modular and highly customizable UIKit menu, that can be attached to the navigation bar or toolbar, written in Swift. :large_orange_diamond: :star:141
* [RevealMenuController](https://github.com/anatoliyv/RevealMenuController) - Expandable item groups, custom position and appearance animation. Similar to ActionSheet style. :large_orange_diamond: :star:16
* [RHSideButtons](https://github.com/robertherdzik/RHSideButtons) - Library provides easy to implement variation of Android (Material Design) Floating Action Button for iOS. You can use it as your app small side menu. :large_orange_diamond: :star:56
* [Swift-CircleMenu](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) - Rotating circle menu written in Swift 3. :large_orange_diamond: :star:109
* [AKSideMenu](https://github.com/dogo/AKSideMenu) - Beautiful iOS side menu library with parallax effect. :large_orange_diamond: :star:103
* [InteractiveSideMenu](https://github.com/handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu written in Swift 3. :large_orange_diamond: :star:346
* [YNDropDownMenu](https://github.com/younatics/YNDropDownMenu) - Adorable iOS drop down menu with Swift3. :large_orange_diamond: :star:804
* [KWDrawerController](https://github.com/Kawoou/KWDrawerController) - Drawer view controller that easy to use! :large_orange_diamond: :star:56
* [JNDropDownMenu](https://github.com/javalnanda/JNDropDownMenu) - Easy to use tableview style drop down menu with multi-column support written in Swift3. :large_orange_diamond: :star:47
* [FanMenu](https://github.com/exyte/fan-menu) - Menu with a circular layout based on Macaw. :large_orange_diamond: :star:223
* [AirBar](https://github.com/uptechteam/AirBar) - UIScrollView driven expandable menu written in Swift 3. :large_orange_diamond: :star:149
* [FAPanels](https://github.com/fahidattique55/FAPanels) - FAPanels for transition :large_orange_diamond: :star:566
* [SwipeMenuViewController](https://github.com/yysskk/SwipeMenuViewController) - Swipable tab and menu View and ViewController. :large_orange_diamond: :star:362
* [DTPagerController](https://github.com/tungvoduc/DTPagerController) - A fully customizable container view controller to display set of ViewControllers in horizontal scroller 🔶 :star:55
* [PagingKit](https://github.com/kazuhiro4949/PagingKit) - PagingKit provides customizable menu UI It has more flexible layout and design than the other libraries.  🔶 :star:540
* [Dropdowns](https://github.com/hyperoslo/Dropdowns) - 💧 Dropdown in Swift :star:74

#### Navigation Bar
* [HidingNavigationBar](https://github.com/tristanhimmelman/HidingNavigationBar) - Easily hide and show a view controller's navigation bar (and tab bar) as a user scrolls :large_orange_diamond: :star:665
* [TLYShyNavBar](https://github.com/telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars! :star:3447
* [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations. :star:2301
* [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) - UINavigationBar Category which allows you to change its appearance dynamically :star:4270
* [BusyNavigationBar](https://github.com/gmertk/BusyNavigationBar) - A UINavigationBar extension to show loading effects :large_orange_diamond: :star:879
* [KDInteractiveNavigationController](https://github.com/kingiol/KDInteractiveNavigationController) - A UINavigationController subclass that support pop interactive UINavigationbar with hidden or show. :large_orange_diamond: :star:120
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView :large_orange_diamond: :star:5075
* [NavKit](https://github.com/wilbertliu/NavKit) - Simple and integrated way to customize navigation bar experience on iOS app. :large_orange_diamond: :star:26

#### PickerView
* [ActionSheetPicker-3.0](https://github.com/skywinder/ActionSheetPicker-3.0/) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
* [PickerView](https://github.com/filipealva/PickerView) - A customizable alternative to UIPickerView in Swift. :large_orange_diamond: :star:296
* [DatePickerDialog](https://github.com/squimer/DatePickerDialog-iOS-Swift) - Date picker dialog for iOS :large_orange_diamond: :star:317
* [CZPicker](https://github.com/chenzeyu/CZPicker) - A picker view shown as a popup for iOS. :star:483
* [AIDatePickerController](https://github.com/alikaragoz/AIDatePickerController) - :date: UIDatePicker modally presented with iOS 7 custom transitions. :star:86
* [CountryPicker](https://github.com/4taras4/CountryCode) - :date: UIPickerView with Country names flags and phoneCodes 🔶 :star:67
* [McPicker](https://github.com/kmcgill88/McPicker-iOS) - A customizable, closure driven UIPickerView drop-in solution with animations that is rotation ready. :large_orange_diamond: :star:45
* [Mandoline](https://github.com/blueapron/Mandoline) - An iOS picker view to serve all your "picking" needs :large_orange_diamond: :star:602

#### Popup
* [PopupKit](https://github.com/rynecheow/PopupKit) - A simple and flexible class for presenting custom views as a popup in iOS and tvOS, maintained from [KLCPopup](https://github.com/jmascia/KLCPopup). :star:23
* [MMPopupView](https://github.com/adad184/MMPopupView) - Pop-up based view(e.g. alert sheet), can easily customize. :star:1804
* [STPopup](https://github.com/kevin0571/STPopup) - STPopup provides a UINavigationController in popup style, for both iPhone and iPad. :star:2051
* [NMPopUpView](https://github.com/psy2k/NMPopUpView) - Simple iOS class for showing nice popup windows. Swift and Objective-C versions available. :large_orange_diamond: :star:169
* [CNPPopupController](https://github.com/carsonperrotti/CNPPopupController) - Simple and versatile class for presenting a custom popup in a variety of fashions. It includes a many options for controlling how your popup appears and behaves. :star:1589
* [PopupController](https://github.com/daisuke310vvv/PopupController) - A customizable controller for showing temporary popup view. :star:228
* [SubscriptionPrompt](https://github.com/binchik/SubscriptionPrompt) - Subscription View Controller like the Tinder uses :large_orange_diamond: :star:207
* [Presentr](https://github.com/IcaliaLabs/Presentr) - Wrapper for custom ViewController presentations in iOS 8+ :large_orange_diamond: :star:1677
* [PopupDialog](https://github.com/Orderella/PopupDialog) - A simple, customizable popup dialog for iOS written in Swift. Replaces UIAlertControllers alert style. :large_orange_diamond: :star:2210
* [SelectionDialog](https://github.com/kciter/SelectionDialog) - Simple selection dialog. :large_orange_diamond: :star:75
* [AZDialogViewController](https://github.com/Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog. :large_orange_diamond: :star:525
* [MIBlurPopup](https://github.com/MarioIannotta/MIBlurPopup) - MIBlurPopup let you create amazing popups with a blurred background. :star:363
* [LNPopupController](https://github.com/LeoNatan/LNPopupController) - a framework for presenting view controllers as popups of other view controllers, much like the Apple Music and Podcasts apps. :star:2005

#### ProgressView
* [ProgressMeter](https://github.com/khawajafarooq/ProgressMeter) - Display the progress on a meter with customized annotations for iOS developed in Swift :large_orange_diamond: :star:17

#### Pull to Refresh
* [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift :large_orange_diamond: :star:2991
* [PullToBounce](https://github.com/entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView. :large_orange_diamond: :star:1664
* [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) - Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code. http://samvermette.com/314 :star:4836
* [UzysAnimatedGifPullToRefresh](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh) - Add PullToRefresh using animated GIF to any scrollView with just simple code :star:1408
* [PullToRefreshCoreText](https://github.com/cemolcay/PullToRefreshCoreText) - PullToRefresh extension for all UIScrollView type classes with animated text drawing style :star:314
* [BOZPongRefreshControl](https://github.com/boztalay/BOZPongRefreshControl) - A pull-down-to-refresh control for iOS that plays pong, originally created for the MHacks III iOS app :star:900
* [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - Fully customizable pull-to-refresh control inspired by Storehouse iOS app :star:3974
* [SurfingRefreshControl](https://github.com/peiweichen/SurfingRefreshControl) - Inspired by CBStoreHouseRefreshControl.Customizable pull-to-refresh control,written in pure Swift :large_orange_diamond: :star:51
* [mntpulltoreact](https://github.com/mentionapp/mntpulltoreact) - One gesture, many actions. An evolution of Pull to Refresh. :star:780
* [ADChromePullToRefresh](https://github.com/Antondomashnev/ADChromePullToRefresh) - Chrome iOS app style pull to refresh with multiple actions. :star:233
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit. :large_orange_diamond: :star:2185
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) An easy way to use pull-to-refresh.
* [HTPullToRefresh](https://github.com/hoang-tran/HTPullToRefresh) - Easily add vertical and horizontal pull to refresh to any UIScrollView. Can also add multiple pull-to-refesh views at once. :star:28
* [PullToRefreshSwift](https://github.com/dekatotoro/PullToRefreshSwift) - iOS Simple Cool PullToRefresh Library. It is written in pure swift. :large_orange_diamond: :star:493
* [GIFRefreshControl](https://github.com/delannoyk/GIFRefreshControl) - GIFRefreshControl is a pull to refresh that supports GIF images as track animations. :large_orange_diamond: :star:132
* [ReplaceAnimation](https://github.com/fruitcoder/ReplaceAnimation) - Pull-to-refresh animation in UICollectionView with a sticky header flow layout, written in Swift :large_orange_diamond: :large_orange_diamond: :star:818
* [PullToMakeSoup](https://github.com/Yalantis/PullToMakeSoup) - Custom animated pull-to-refresh that can be easily added to UIScrollView :large_orange_diamond: :star:1726
* [RainyRefreshControl](https://github.com/Onix-Systems/RainyRefreshControl) - Simple refresh control for iOS inspired by [concept](https://dribbble.com/shots/2242263--1-Pull-to-refresh-Freebie-Weather-Concept). :large_orange_diamond: :star:607
* [ESPullToRefresh](https://github.com/eggswift/pull-to-refresh) - Customisable pull-to-refresh, including nice animation on the top :large_orange_diamond: :star:750

#### Rating Stars
* [FloatRatingView](https://github.com/glenyi/FloatRatingView) - Whole, half or floating point ratings control written in Swift :large_orange_diamond: :star:399
* [TTGEmojiRate](https://github.com/zekunyan/TTGEmojiRate) - An emoji-liked rating view for iOS, implemented in Swift. :large_orange_diamond: :star:229
* [StarryStars](https://github.com/peterprokop/StarryStars) - StarryStars is iOS GUI library for displaying and editing ratings :large_orange_diamond: :star:139
* [Cosmos](https://github.com/evgenyneu/Cosmos) - A star rating control for iOS / Swift :large_orange_diamond: :star:840
* [HCSStarRatingView](https://github.com/hsousa/HCSStarRatingView) - Simple star rating view for iOS written in Objective-C :star:1044
* [MBRateApp](https://github.com/MatiBot/MBRateApp) - A groovy app rate stars screen for iOS written in Swift :large_orange_diamond: :star:53

#### ScrollView
* [ScrollingFollowView](https://github.com/ktanaka117/ScrollingFollowView) - ScrollingFollowView is a simple view which follows UIScrollView scrolling. :star:140
* [UIScrollView-InfiniteScroll](https://github.com/pronebird/UIScrollView-InfiniteScroll) - UIScrollView infinite scroll category. :star:779
* [GoAutoSlideView](https://github.com/zjmdp/GoAutoSlideView) - GoAutoSlideView extends UIScrollView by featuring infinitely and automatically slide. :star:46
* [AppStoreStyleHorizontalScrollView](https://github.com/terenceLuffy/AppStoreStyleHorizontalScrollView) - App store style horizontal scroll view. :large_orange_diamond: :star:581
* [PullToDismiss](https://github.com/sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar in Swift. :large_orange_diamond: :star:193
* [SpreadsheetView](https://github.com/kishikawakatsumi/SpreadsheetView) - Full configurable spreadsheet view user interfaces for iOS applications. With this framework, you can easily create complex layouts like schedule, gantt chart or timetable as if you are using Excel. :large_orange_diamond: :star:2081
*  [VegaScroll](https://github.com/AppliKeySolutions/VegaScroll) - VegaScroll is a lightweight animation flowlayout for UICollectionView completely written in Swift 4, compatible with iOS 11 and Xcode 9 :large_orange_diamond:
*  [ShelfView-iOS](https://github.com/tdscientist/ShelfView-iOS) - iOS custom view to display books on shelf :large_orange_diamond:

#### Segmented Control
* [BetterSegmentedControl](https://github.com/gmarm/BetterSegmentedControl) - An easy to use, customizable replacement for UISegmentedControl & UISwitch. :large_orange_diamond: :star:912
* [LUNSegmentedControl](https://github.com/Stormotion-Mobile/LUNSegmentedControl) - Customizable segmented control with interactive animation. :star:216
* [AKASegmentedControl](https://github.com/alikaragoz/AKASegmentedControl) - :chocolate_bar: Fully customizable Segmented Control for iOS. :star:404
* [TwicketSegmentedControl](https://github.com/twicketapp/TwicketSegmentedControl) - Custom UISegmentedControl replacement for iOS, written in Swift. :large_orange_diamond: :star:1216
* [SJFluidSegmentedControl](https://github.com/sasojadrovski/SJFluidSegmentedControl) - A segmented control with custom appearance and interactive animations. Written in Swift 3.0. :large_orange_diamond: :star:699
* [HMSegmentedControl](https://github.com/HeshamMegid/HMSegmentedControl) - A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products. :star:3193
* [YUSegment](https://github.com/afishhhhh/YUSegment) - A customizable segmented control for iOS. Supports both text and image. :star:95
* [MultiSelectSegmentedControl](https://github.com/yonat/MultiSelectSegmentedControl) - adds Multiple-Selection to the standard `UISegmentedControl`. :star:77
* [DynamicMaskSegmentSwitch](https://github.com/KittenYang/DynamicMaskSegmentSwitch) - A segment switcher with dynamic text mask effect :large_orange_diamond: :star:291
* [PinterestSegment](https://github.com/TBXark/PinterestSegment) - A Pinterest-like segment control with masking animation. :large_orange_diamond: :star:292

#### Slider
* [VolumeControl](https://github.com/12Rockets/VolumeControl) - Custom volume control for iPhone featuring a well-designed round slider. :star:61
* [WESlider](https://github.com/Ekhoo/WESlider) - Simple and light weight slider with chapter management :star:81
* [IntervalSlider](https://github.com/shushutochako/IntervalSlider) - IntervalSlider is a slider library like ReutersTV app. written in pure swift. :large_orange_diamond: :star:50
* [RangeSlider](https://github.com/warchimede/RangeSlider) - A simple range slider made in Swift :large_orange_diamond: :star:164
* [CircleSlider](https://github.com/shushutochako/CircleSlider) - CircleSlider is a Circular slider library. written in pure Swift. :large_orange_diamond: :star:106
* [MARKRangeSlider](https://github.com/vadymmarkov/MARKRangeSlider) - A custom reusable slider control with 2 thumbs (range slider). :star:138
* [ASValueTrackingSlider](https://github.com/alskipp/ASValueTrackingSlider) - A UISlider subclass that displays the slider value in a popup view :star:1735
* [TTRangeSlider](https://github.com/TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range. :star:651
* [MMSegmentSlider](https://github.com/MedvedevMax/MMSegmentSlider) - Customizable animated slider for iOS. :star:28
* [StepSlider](https://github.com/spromicky/StepSlider) - StepSlider its custom implementation of slider such as UISlider for preset integer values. :star:149
* [JDSlider](https://github.com/JellyDevelopment/JDSlider) - An iOS Slider written in Swift. :large_orange_diamond: :star:75
* [SnappingSlider](https://github.com/rehatkathuria/SnappingSlider) - A beautiful slider control for iOS built purely upon Swift :large_orange_diamond: :star:531
* [MTCircularSlider](https://github.com/EranBoudjnah/MTCircularSlider) - A feature-rich circular slider control. :large_orange_diamond: :star:21
* [VerticalSlider](https://github.com/jonkykong/VerticalSlider) - VerticalSlider is a vertical implementation of the UISlider slider control. :large_orange_diamond: :star:34
* [CircularSlider](https://github.com/taglia3/CircularSlider) - A powerful Circular Slider. It's written in Swift, it's 100% IBDesignable and all parameters are IBInspectable. :large_orange_diamond: :star:164
* [HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application. :large_orange_diamond: :star:1246
* [PivotSlider](https://github.com/dereklimbus/pivot-slider) - Slider that pivots :large_orange_diamond: :star:24
* [RangeSeekSlider](https://github.com/WorldDownTown/RangeSeekSlider) - A customizable range slider for iOS. :large_orange_diamond: :star:158
* [SectionedSlider](https://github.com/LeonardoCardoso/SectionedSlider) - Control Center Slider. :large_orange_diamond: :star:148
* [MultiSlider](https://github.com/yonat/MultiSlider) - UISlider clone with multiple thumbs and values, optional snap intervals, optional value labels. :large_orange_diamond: :star:7
* [AGCircularPicker](https://github.com/agilie/AGCircularPicker) - AGCircularPicker is helpful component for creating a controller aimed to manage any calculated parameter. :large_orange_diamond: :star:425
* [VSVerticalSlider](https://github.com/vsmithers1087/VSVerticalSlider) - An animatable and customizable vertical slider written in Swift4.🔶 :star:12
* [Fluid Slider](https://github.com/Ramotion/fluid-slider) - A slider widget with a popup bubble displaying the precise value selected. :large_orange_diamond: :star:33

#### Splash View
* [CBZSplashView](https://github.com/callumboddy/CBZSplashView) - Twitter style Splash Screen View. Grows to reveal the Initial view behind. :star:1436
* [SKSplashView](https://github.com/sachinkesiraju/SKSplashView) - Create custom animated splash views similar to the ones in the Twitter, Uber and Ping iOS app. :star:454
* [RevealingSplashView](https://github.com/PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by Twitter splash :large_orange_diamond: :star:796

#### Stepper
* [PFStepper](https://github.com/PerfectFreeze/PFStepper) - May be the most elegant stepper you have ever had! :large_orange_diamond: :star:24
* [ValueStepper](https://github.com/BalestraPatrick/ValueStepper) - A Stepper object that displays its value. :large_orange_diamond: :star:219
* [GMStepper](https://github.com/gmertk/GMStepper) - A stepper with a sliding label in the middle. :large_orange_diamond: :star:571
* [barceloneta](https://github.com/arn00s/barceloneta) - The right way to increment/decrement values with a simple gesture on iOS. :large_orange_diamond: :star:38
* [SnappingStepper](https://github.com/yannickl/SnappingStepper) - An elegant alternative to the UIStepper written in Swift :large_orange_diamond: :star:328
* [SMNumberWheel](https://github.com/SinaMoetakef/SMNumberWheel) - A custom control written in Swift, which is ideal for picking numbers very fast but yet very accurate using a rotating wheel :large_orange_diamond: :star:16

#### Switch
* [AnimatedSwitch](https://github.com/alsedi/AnimatedSwitch) - UISwitch which paints over the parent view with the color in Swift. :large_orange_diamond: :star:162
* [ViralSwitch](https://github.com/andreamazz/ViralSwitch) - A UISwitch that infects its superview with its tint color. :star:319
* [JTMaterialSwitch](https://github.com/JunichiT/JTMaterialSwitch) - A customizable switch UI with ripple effect and bounce animations, inspired from Google's Material Design. :star:235
* [TKSwitcherCollection](https://github.com/TBXark/TKSwitcherCollection) - An animate switch collection :large_orange_diamond: :star:515
* [SevenSwitch](https://github.com/bvogelzang/SevenSwitch) - iOS7 style drop in replacement for UISwitch. :large_orange_diamond: :star:751
* [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch) - Runkeeper design switch control (two part segment control) :large_orange_diamond: :star:1823
* [PMZSwitch](https://github.com/kovpas/PMZSwitch) - Yet another animated toggle :large_orange_diamond: :star:57
* [Switcher](https://github.com/knn90/Switcher) - Swift - Custom UISwitcher with animation when change status :large_orange_diamond: :star:168
* [RAMPaperSwitch](https://github.com/Ramotion/paper-switch) - RAMPaperSwitch is a Swift module which paints over the parent view when the switch is turned on. :large_orange_diamond: :star:2356
* [AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch) - A flat component alternative to UISwitch on iOS :large_orange_diamond: :star:647
* [Switch](https://github.com/T-Pham/Switch) - An iOS switch control implemented in Swift with full Interface Builder support.🔶 :star:74

#### Tab Bar
* [ESTabBarController](https://github.com/ezescaruli/ESTabBarController) - A tab bar controller for iOS that allows highlighting buttons and setting custom actions to them. :star:98
* [GooeyTabbar](https://github.com/KittenYang/GooeyTabbar) -A gooey effect tabbar :large_orange_diamond:
* [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift module for adding animation to tabbar items. :large_orange_diamond: :star:8324
* [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) - Folding Tab Bar and Tab Bar Controller :star:3413
* [GGTabBar](https://github.com/Goles/GGTabBar) - Another UITabBar & UITabBarController (iOS Tab Bar) replacement, but uses Auto Layout for arranging it's views hierarchy. :star:153
* [adaptive-tab-bar](https://github.com/Ramotion/adaptive-tab-bar) - AdaptiveController is a 'Progressive Reduction' Swift module for adding custom states to Native or Custom iOS UI elements :large_orange_diamond: :star:1790
* [Pager](https://github.com/lucoceano/Pager) - Easily create sliding tabs with Pager :large_orange_diamond: :star:201
* [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS. :large_orange_diamond: :star:4607
* [TabPageViewController](https://github.com/EndouMari/TabPageViewController) - Paging view controller and scroll tab view. 🔶 :star:742
* [TabDrawer](https://github.com/winslowdibona/TabDrawer) - Customizable TabBar UI element that allows you to run a block of code upon TabBarItem selection, written in Swift 🔶 :star:500
* [SwipeViewController](https://github.com/fortmarek/SwipeViewController) - SwipeViewController is a Swift modification of RKSwipeBetweenViewControllers - navigate between pages / ViewControllers :large_orange_diamond: :star:460
* [ColorMatchTabs](https://github.com/Yalantis/ColorMatchTabs) - Interesting way to display tabs :large_orange_diamond: :star:991
* [BATabBarController](https://github.com/antiguab/BATabBarController) - A TabBarController with a unique animation for selection :star:654
* [ScrollPager](https://github.com/aryaxt/ScrollPager) - A scroll pager that displays a list of tabs (segments) and manages paging between given views :large_orange_diamond: :star:433
* [Segmentio](https://github.com/Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift. :large_orange_diamond: :star:1499
* [KYWheelTabController](https://github.com/ykyouhei/KYWheelTabController) - KYWheelTabController is a subclass of UITabBarController.It displays the circular menu instead of UITabBar. :large_orange_diamond: :star:87
* [SuperBadges](https://github.com/odedharth/SuperBadges) - Add emojis and colored dots as badges for your Tab Bar buttons 🔶 :star:22
* [AZTabBarController](https://github.com/Minitour/AZTabBarController) - A custom tab bar controller for iOS written in Swift 3.0 🔶 :star:118
* [MiniTabBar](https://github.com/D-32/MiniTabBar) - A clean simple alternative to the UITabBar 🔶 :star:59
* [SwipeableTabBarController](https://github.com/marcosgriselli/SwipeableTabBarController) - UITabBarController with swipe interaction between its tabs. 🔶 :star:153
* [SMSwipeableTabView](https://github.com/smahajan28/SMSwipeableTabView) - Swipeable Views with Tabs (Like Android SwipeView With Tabs Layout) 🔶 :star:28
* [Tabman](https://github.com/uias/Tabman) - A powerful paging view controller with indicator bar for iOS. 🔶 :star:662

#### Table View / Collection View
* [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions. :star:5945
* [ParallaxTableViewHeader](https://github.com/Vinodh-G/ParallaxTableViewHeader) - Parallax scrolling effect on UITableView header view when a tableView is scrolled. :star:1265
* [YXTPageView](https://github.com/hanton/YXTPageView) - A PageView, which supporting scrolling to transition between a UIView and a UITableView. :star:61
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display. :star:9535
* [ConfigurableTableViewController](https://github.com/fastred/ConfigurableTableViewController) - Typed, yet Flexible Table View Controller http://holko.pl/2016/01/05/typed-table-view-controller/ :large_orange_diamond: :star:244
* [CSStickyHeaderFlowLayout](https://github.com/CSStickyHeaderFlowLayout/CSStickyHeaderFlowLayout) - UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. :large_orange_diamond: :star:4831
* [folding-cell](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell inspired by folding paper material :large_orange_diamond: :star:6732
* [Lightning-Table](https://github.com/electrickangaroo/Lightning-Table) - A declarative api for working with UITableView. :star:22
* [Static](https://github.com/venmo/Static) - Simple static table views for iOS in Swift. :large_orange_diamond: :star:996
* [GSKStretchyHeaderView](https://github.com/gskbyte/GSKStretchyHeaderView) - Configurable yet easy to use stretchy header view for UITableView and UICollectionView. :star:1067
* [MEVFloatingButton](https://github.com/manuelescrig/MEVFloatingButton) - An iOS drop-in UITableView, UICollectionView and UIScrollView superclass category for showing a customizable floating button on top of it. :star:282
* [AMWaveTransition](https://github.com/andreamazz/AMWaveTransition) - Custom transition between viewcontrollers holding tableviews. :star:2344
* [Dwifft](https://github.com/jflinter/Dwifft) - Swift Diff :large_orange_diamond: :star:1429
* [AEAccordion](https://github.com/tadija/AEAccordion) - UITableViewController with accordion effect (expand / collapse cells). :large_orange_diamond: :star:164
* [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) - An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)
* [ZYThumbnailTableView](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - a TableView have thumbnail cell only, and you can use gesture let it expands other expansionView, all diy :large_orange_diamond: :star:896
* [BWSwipeRevealCell](https://github.com/bitwit/BWSwipeRevealCell) - A Swift library for swipeable table cells :large_orange_diamond: :star:46
* [preview-transition](https://github.com/Ramotion/preview-transition) - PreviewTransition is a simple preview gallery controller :large_orange_diamond: :star:1620
* [QuickTableViewController](https://github.com/bcylin/QuickTableViewController) - A simple way to create a UITableView for settings in Swift. :large_orange_diamond: :star:112
* [TableKit](https://github.com/maxsokolov/TableKit) - Type-safe declarative table views with Swift :large_orange_diamond: :star:282
* [Preheat](https://github.com/kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView :large_orange_diamond: :star:589
* [VBPiledView](https://github.com/v-braun/VBPiledView) - Simple and beautiful stacked UIView to use as a replacement for an UITableView, UIImageView or as a menu :large_orange_diamond: :star:126
* [DisplaySwitcher](https://github.com/Yalantis/DisplaySwitcher) - Custom transition between two collection view layouts :large_orange_diamond: :star:1622
* [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView. :star:3492
* [FMMosaicLayout](https://github.com/fmitech/FMMosaicLayout) - A drop-in mosaic collection view layout with a focus on simple customizations. :star:569
* [mosaic-layout](https://github.com/vinnyoodles/mosaic-layout) - A mosaic collection view layout inspired by Lightbox's Algorithm, written in Swift :large_orange_diamond: :star:167
* [Reusable](https://github.com/AliSoftware/Reusable) - A Swift mixin for UITableViewCells and UICollectionViewCells :large_orange_diamond: :star:1321
* [VTMagic](https://github.com/tianzhuo112/VTMagic) - VTMagic is a page container library for iOS. :star:1497
* [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - :point_up_2: Convenient UITableViewCell subclass that implements a swippable content to trigger actions (similar to the Mailbox app). :star:3018
* [Sapporo](https://github.com/nghialv/Sapporo) - Cellmodel-driven collectionview manager :large_orange_diamond: :star:232
* [MYTableViewIndex](https://github.com/mindz-eye/MYTableViewIndex) - A pixel perfect replacement for UITableView section index, written in Swift :large_orange_diamond: :star:324
* [RAReorderableLayout](https://github.com/ra1028/RAReorderableLayout) - A UICollectionView layout which can move item with drag and drop. :star:794
* [StickyCollectionView-Swift](https://github.com/matbeich/StickyCollectionView-Swift) - UICollectionView layout for presenting of the overlapping cells. :large_orange_diamond: :star:208
* [ios-dragable-table-cells](https://github.com/palmin/ios-dragable-table-cells) - Support for drag-n-drop of UITableViewCells in a navigation hierarchy of view controllers. You drag cells by tapping and holding them. :star:38
* [TLLayoutTransitioning](https://github.com/SwiftKickMobile/TLLayoutTransitioning) - Enhanced transitioning between UICollectionView layouts in iOS. :star:332
* [Bohr](https://github.com/DavdRoman/Bohr) - Bohr allows you to set up a settings screen for your app with three principles in mind: ease, customization and extensibility. :star:1237
* [SwiftReorder](https://github.com/adamshin/SwiftReorder) - Add drag-and-drop reordering to any table view with just a few lines of code. Robust, lightweight, and completely customizable. :large_orange_diamond:[e] :star:67
* [TLIndexPathTools](https://github.com/SwiftKickMobile/TLIndexPathTools) - TLIndexPathTools is a small set of classes that can greatly simplify your table and collection views. :star:337
* [HoverConversion](https://github.com/marty-suzuki/HoverConversion) - HoverConversion realized vertical paging with UITableView. UIViewController will be paging when reaching top or bottom of UITableView contentOffset. :large_orange_diamond: :star:166
* [TableViewDragger](https://github.com/KyoheiG3/TableViewDragger) - A cells of UITableView can be rearranged by drag and drop. :large_orange_diamond: :star:312
* [IGListKit](https://github.com/Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists. :star:7233
* [MMCardView](https://github.com/MillmanY/MMCardView) - Custom CollectionView like Wallet App :large_orange_diamond: :star:432
* [FlexibleTableViewController](https://github.com/dimpiax/FlexibleTableViewController) - Swift library of generic table view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler :star:9
* [FlexibleCollectionViewController](https://github.com/dimpiax/FlexibleCollectionViewController) - Swift library of generic collection view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler etc :star:1
* [CascadingTableDelegate](https://github.com/edopelawi/CascadingTableDelegate) - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.:large_orange_diamond: :star:790
* [TimelineTableViewCell](https://github.com/kf99916/TimelineTableViewCell) - Simple timeline view implemented by UITableViewCell written in Swift 3.0.:large_orange_diamond: :star:812
* [RHPreviewCell](https://github.com/robertherdzik/RHPreviewCell) - I envied so much Spotify iOS app this great playlist preview cell. Now you can give your users ability to quick check "what content is hidden under your UITableViewCell". :large_orange_diamond: :star:331
* [ThreeLevelAccordian](https://github.com/amratab/ThreeLevelAccordian) - This is a customisable three level accordian with options for adding images and accessories images. :large_orange_diamond: :star:29
* [TORoundedTableView](https://github.com/TimOliver/TORoundedTableView) - A subclass of UITableView that styles it like Settings.app on iPad :star:60
* [ASCollectionView](https://github.com/abdullahselek/ASCollectionView) - A Swift collection view inspired by Airbnb. :large_orange_diamond: :star:131
* [TableFlip](https://github.com/mergesort/TableFlip) - A simpler way to do cool UITableView animations! (╯°□°）╯︵ ┻━┻ :large_orange_diamond: :star:351
* [DTTableViewManager](https://github.com/DenHeadless/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types. :large_orange_diamond: :star:318
* [GLTableCollectionView](https://github.com/giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView :large_orange_diamond: :star:461
* [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app, implemented in Swift. :large_orange_diamond: :star:2604
* [EditDistance](https://github.com/kazuhiro4949/EditDistance) - Incremental update tool for UITableView and UICollectionView :large_orange_diamond: :star:49
* [CenteredCollectionView](https://github.com/BenEmdon/CenteredCollectionView) - A lightweight UICollectionViewLayout that _'pages'_ and centers it's cells 🎡 written in Swift. :large_orange_diamond: :star:166
* [YBSlantedCollectionViewLayout](https://github.com/yacir/YBSlantedCollectionViewLayout) - UICollectionViewLayout with slanted content. :star:134
* [ReverseExtension](https://github.com/marty-suzuki/ReverseExtension) - A UITableView extension that enables cell insertion from the bottom of a table view. :star:1168
* [YNExpandableCell](https://github.com/younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶 :star:336
* [SquareMosaicLayout](https://github.com/iwheelbuy/SquareMosaicLayout) - An extandable mosaic UICollectionViewLayout with a focus on extremely flexible customizations 🔶 :star:69
* [SwiftSpreadSheet](https://github.com/stuffrabbit/SwiftSpreadsheet) - Spreadsheet CollectionViewLayout in Swift. Fully customizable. 🔶 :star:411
* [GenericDataSource](https://github.com/GenericDataSource/GenericDataSource) - A generic small reusable components for data source implementation for UITableView/UICollectionView in Swift. 🔶 :star:44
* [BouncyLayout](https://github.com/roberthein/BouncyLayout) - BouncyLayout is a collection view layout that makes your cells bounce. 🔶 :star:2738
* [Savory](https://github.com/Nandiin/Savory) - A swift accordion view implementation. :large_orange_diamond:
* [PagingView](https://github.com/KyoheiG3/PagingView) - Infinite paging, Smart auto layout, Interface of similar to UIKit. :large_orange_diamond:🔶 :star:247
* [ExpyTableView](https://github.com/okhanokbay/ExpyTableView) - Make your table view expandable just by implementing one method. 🔶 :star:154
* [FTFoldingPaper](https://github.com/monofire/FTFoldingPaper) - Emulates paper folding effect. Can be integrated with UITableView or used with other UI components. :star:23
* [PJFDataSource](https://github.com/square/PJFDataSource) - PJFDataSource is a small library that provides a simple, clean architecture for your app to manage its data sources while providing a consistent user interface for common content states (i.e. loading, loaded, empty, and error). :star:82
* [HGPlaceholders](https://github.com/HamzaGhazouani/HGPlaceholders) - Nice library to show and create placeholders and Empty States for any UITableView/UICollectionView in your project 🔶 :star:968
* [CollapsibleTableSectionViewController](https://github.com/jeantimex/CollapsibleTableSectionViewController) - A swift library to support collapsible sections in a table view. :large_orange_diamond: :star:60
* [ExpandableCell](https://github.com/younatics/ExpandableCell) - Fully refactored YNExapnadableCell with more concise, bug free. Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶 :star:190
* [DataSources](https://github.com/muukii/DataSources) - Type-safe data-driven List-UI Framework. (We can also use ASCollectionNode) 🔶 :star:336
* [KDDragAndDropCollectionView](https://github.com/mmick66/KDDragAndDropCollectionView) - Dragging & Dropping data across multiple UICollectionViews. 🔶 :star:254
* [ListPlaceholder](https://github.com/malkouz/ListPlaceholder) - ListPlaceholder is a swift library allows you to easily add facebook style animated loading placeholder to your tableviews or collection views :large_orange_diamond: :star:270
* [SectionScrubber](https://github.com/bakkenbaeck/SectionScrubber) - A component to quickly scroll between collection view sections :large_orange_diamond: :star:143
* [CardsLayout](https://github.com/filletofish/CardsLayout) - Nice card-designed custom collection view layout. 🔶 :star:281

#### Tag
* [PARTagPicker](https://github.com/paulrolfe/PARTagPicker) - This pod provides a view controller for choosing and creating tags in the style of wordpress or tumblr. :star:271
* [AMTagListView](https://github.com/andreamazz/AMTagListView) - UIScrollView subclass that allows to add a list of highly customizable tags. :star:706
* [TagCellLayout](https://github.com/riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments. :large_orange_diamond: :star:121
* [TTGTagCollectionView](https://github.com/zekunyan/TTGTagCollectionView) - Show simple text tags or custom tag views in a vertical scrollable view. :star:702
* [TagListView](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift. :large_orange_diamond: :star:1188
* [RKTagsView](https://github.com/kuler90/RKTagsView) - Highly customizable iOS tags view (like NSTokenField). Supports editing, multiple selection, Auto Layout and much more. :star:367
* [WSTagsField](https://github.com/whitesmith/WSTagsField) - An iOS text field that represents different Tags :large_orange_diamond: :star:644
* [AKMaskField](https://github.com/artemkrachulov/AKMaskField) - AKMaskField is UITextField subclass which allows enter data in the fixed quantity and in the certain format. :large_orange_diamond: :star:238
* [YNSearch](https://github.com/younatics/YNSearch) - Awesome fully customizable search view like Pinterest written in Swift 3 🔶 :star:715

#### TextField & TextView
* [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels. :star:6555
* [ARAutocompleteTextView](https://github.com/alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews. :star:258
* [IQDropDownTextField](https://github.com/hackiftekhar/IQDropDownTextField) - TextField with DropDown support using UIPickerView :star:238
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake) - UITextField category that adds shake animation. [Also with Swift version](https://github.com/King-Wizard/UITextField-Shake-Swift) :large_orange_diamond: :star:702
* [HTYTextField](https://github.com/hanton/HTYTextField) - A UITextField with bouncy placeholder. :large_orange_diamond: :star:225
* [MVAutocompletePlaceSearchTextField](https://github.com/TheMrugraj/MVAutocompletePlaceSearchTextField) - A drop-in Autocompletion control for Place Search like Google Places, Uber, etc. :star:67
* [AutocompleteField](https://github.com/filipstefansson/AutocompleteField) - Add word completion to your UITextFields. :large_orange_diamond: :star:653
* [RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks. :large_orange_diamond: :star:514
* [RSKPlaceholderTextView](https://github.com/ruslanskorb/RSKPlaceholderTextView) - A light-weight UITextView subclass that adds support for placeholder. :large_orange_diamond: :star:58
* [StatefulViewController](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states :large_orange_diamond: :star:1830
* [MBAutoGrowingTextView](https://github.com/MatejBalantic/MBAutoGrowingTextView) - An auto-layout base UITextView subclass which automatically grows with user input and can be constrained by maximal and minimal height - all without a single line of code :star:118
* [TextFieldEffects](https://github.com/raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift :large_orange_diamond: :star:4332
* [Reel Search](https://github.com/Ramotion/reel-search) - RAMReel is a controller that allows you to choose options from a list. :large_orange_diamond: :star:1927
* [MLPAutoCompleteTextField](https://github.com/EddyBorja/MLPAutoCompleteTextField) - a subclass of UITextField that behaves like a typical UITextField with one notable exception: it manages a drop down table of autocomplete suggestions that update as the user types. :star:1150
* [SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.:large_orange_diamond: :star:2315
* [VMaskTextField](https://github.com/viniciusmo/VMaskTextField) - VMaskTextField is a library which create an input mask for iOS. :star:356
* [TJTextField](https://github.com/tejas-ardeshna/TJTextField) - UITextField with underline and left image :large_orange_diamond: :star:35
* [NextGrowingTextView](https://github.com/muukii/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above. :star:882
* [RPFloatingPlaceholders](https://github.com/iwasrobbed/RPFloatingPlaceholders) - UITextField and UITextView subclasses with placeholders that change into floating labels when the fields are populated with text. :star:1106
* [CurrencyTextField](https://github.com/richa008/CurrencyTextField) - UITextField that automatically formats text to display in the currency format. :large_orange_diamond: :star:21
* [UITextField-Navigation](https://github.com/T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields.🔶[e] :star:345
* [AutoCompleteTextField](https://github.com/nferocious76/AutoCompleteTextField) - Auto complete with suggestion textfield :large_orange_diamond: :star:23
* [EmojiTextView](https://github.com/fastred/EmojiTextView) - Tap to swap out words with emojis. Inspired by Messages.app on iOS 10. :large_orange_diamond: :star:348
* [PLCurrencyTextField](https://github.com/nonameplum/PLCurrencyTextField) - UITextField that support currency in the right way. :large_orange_diamond: :star:82
* [PasswordTextField](https://github.com/PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforce good password policies :large_orange_diamond: :star:139
* [AnimatedTextInput](https://github.com/jobandtalent/AnimatedTextInput) - Animated UITextField and UITextView replacement for iOS :large_orange_diamond: :star:517
* [KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder written in Swift. :large_orange_diamond: :star:484
* [NxEnabled](https://github.com/Otbivnoe/NxEnabled) - Library which allows you binding `enabled` property of button with textable elements (TextView, TextField) :large_orange_diamond: :star:26
* [AwesomeTextField](https://github.com/aleksandrshoshiashvili/AwesomeTextFieldSwift) - Awesome TextField is a nice and simple library for iOS. It's highly customisable and easy-to-use tool. Works perfectly for any registration or login forms in your app. :large_orange_diamond: :star:111
* [ModernSearchBar](https://github.com/PhilippeBoisney/ModernSearchBar) - The famous iOS search bar with auto completion feature implemented. :large_orange_diamond: :star:82
* [SelectableTextView](https://github.com/jhurray/SelectableTextView) - A text view that supports selection and expansion :large_orange_diamond: :star:557
* [CBPinEntryView](https://github.com/Fawxy/CBPinEntryView) - A customisable view written in Swift 3.0 for any numerical pin or code entry. :large_orange_diamond: :star:32
* [GrowingTextView](https://github.com/KennethTsang/GrowingTextView) - An UITextView in Swift3 and Swift2.3. Support auto growing, placeholder and length limit. :large_orange_diamond: :star:199
* [DTTextField](https://github.com/iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label in Swift3.0.🔶 :star:79
* [TextFieldCounter](https://github.com/serralvo/TextFieldCounter) - UITextField character counter with lovable UX. 🔶 :star:310
* [RSFloatInputView](https://github.com/roytornado/RSFloatInputView) - A Float Input View with smooth animation and supporting icon and seperator written with Swift. 🔶 :star:61
* [TaniwhaTextField](https://github.com/iceman201/TaniwhaTextField) - TaniwhaTextField is a lightweight and beautiful swift textfield framework. It has float label pattern, and also you can highly customise it. it's written with Swift. 🔶 :star:20
* [InstantSearch iOS](https://github.com/algolia/instantsearch-ios) - A library of widgets and helpers to build instant-search applications on iOS. 🔶 :star:394
* [SearchTextField](https://github.com/apasccon/SearchTextField) - UITextField subclass with autocompletion suggestions list  :large_orange_diamond: :star:266
* [PYSearch](https://github.com/ko1o/PYSearch) - An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad). :star:2594
* [styled-text](https://github.com/blueapron/styled-text) - Declarative text styles and streamlined Dynamic Type support for iOS. 🔶 :star:211

#### Web View
* [Otafuku](https://github.com/tasanobu/Otafuku) - Otafuku provides utility classes to use WKWebView in Swift. :large_orange_diamond: :star:51
* [SwiftWebVC](https://github.com/meismyles/SwiftWebVC) - A drop-in inline browser for your Swift iOS app. :large_orange_diamond: :star:175
* [SVWebViewController](https://github.com/TransitApp/SVWebViewController) - A drop-in inline browser for your iOS app. :star:2561
* [PTPopupWebView](https://github.com/pjocprac/PTPopupWebView) - PTPopupWebView is a simple and useful WebView for iOS, which can be popup and has many of the customized item. :large_orange_diamond: :star:71

## Utility
 * [Underscore.m](https://github.com/robb/Underscore.m) - A DSL for Data Manipulation. :star:1518
 * [XExtensionItem](https://github.com/tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions. :star:82
 * [ReflectableEnum](https://github.com/fastred/ReflectableEnum) - Reflection for enumerations in Objective-C. :star:330
 * [ObjectiveSugar](https://github.com/supermarin/ObjectiveSugar) - ObjectiveC additions for humans. Ruby style. :star:2215
 * [OpinionatedC](https://github.com/leoschweizer/OpinionatedC) - Because Objective-C should have inherited more from Smalltalk. :star:44
 * [SwiftRandom](https://github.com/thellimist/SwiftRandom) - Generator for random data. :large_orange_diamond: :star:469
 * [RandomKit](https://github.com/nvzqz/RandomKit/) - Random data generation in Swift. :large_orange_diamond:
 * [YOLOKit](https://github.com/mxcl/YOLOKit) - Getting square objects down round holes. :star:628
 * [EZSwiftExtensions](https://github.com/goktugyil/EZSwiftExtensions) - :smirk: How Swift standard types and classes were supposed to work. :large_orange_diamond:[e] :star:2300
 * [Pantry](https://github.com/nickoneill/Pantry) - The missing light persistence layer for Swift :large_orange_diamond: :star:853
 * [SwiftParsec](https://github.com/davedufresne/SwiftParsec) - A parser combinator library written in the Swift programming language. :large_orange_diamond: :star:125
 * [OrderedSet](https://github.com/Weebly/OrderedSet) - A Swift collection of unique, ordered objects :large_orange_diamond: :star:111
 * [Datez](https://github.com/SwiftKitz/Datez) - Swift library for dealing with `NSDate`, `NSCalendar`, and `NSDateComponents`. :large_orange_diamond: :star:208
 * [BFKit](https://github.com/FabrizioBrancati/BFKit) - An Objective-C collection of useful classes to develop Apps faster. :star:762
 * [BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift) - A Swift collection of useful classes to develop Apps faster. :large_orange_diamond: :star:675
 * [Scale](https://github.com/onmyway133/scale) - Unit converter in Swift (available via CocoaPods) :large_orange_diamond: :star:300
 * [Standard Template Protocols](https://github.com/cconeil/Standard-Template-Protocols) - Protocols for your every day iOS needs :large_orange_diamond: :star:381
 * [TimeLord](https://github.com/JonFir/TimeLord) - Easy DateTime (NSDate) management in Swift :large_orange_diamond: :star:6
 * [AppVersionMonitor](https://github.com/eure/AppVersionMonitor) - Monitor iOS app version easily. :star:224
 * [Sugar](https://github.com/hyperoslo/Sugar) - Something sweet that goes great with your Cocoa. :large_orange_diamond:[e] :star:893
 * [Then](https://github.com/devxoul/Then) - ✨ Super sweet syntactic sugar for Swift initializers. :large_orange_diamond:[e] :star:1984
 * [Kvitto](https://github.com/Cocoanetics/Kvitto) - App Store Receipt Validation :large_orange_diamond: :star:197
 * [Notificationz](https://github.com/SwiftKitz/Notificationz) - Helping you own NSNotificationCenter in Swift :large_orange_diamond: :star:57
 * [SwiftFoundation](https://github.com/PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library. (Pure Swift, Supports Linux) :large_orange_diamond:[e] :star:603
 * [libextobjc](https://github.com/jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language. :star:3746
 * [VersionTrackerSwift](https://github.com/tbaranes/VersionTrackerSwift) - Track which versions of your app a user has previously installed. :large_orange_diamond: :star:57
 * [DeviceGuru](https://github.com/InderKumarRathore/DeviceGuru/) - DeviceGuru is a simple lib (Swift) to know the exact type of the device, e.g. iPhone 6 or iPhone 6s. :large_orange_diamond:
 * [AEAppVersion](https://github.com/tadija/AEAppVersion) - Simple and Lightweight App Version Tracking for iOS written in Swift :large_orange_diamond: :star:8
 * [BlocksKit](https://github.com/BlocksKit/BlocksKit) - The Objective-C block utilities you always wish you had. :star:6450
 * [SwiftyUtils](https://github.com/tbaranes/swiftyutils) - All the reusable code that we need in each project. :large_orange_diamond:[e] :star:182
 * [RateLimit](https://github.com/soffes/RateLimit) - Simple utility for only executing code every so often. :large_orange_diamond: :star:868
 * [Outlets](https://github.com/phatblat/Outlets) - Utility functions for validating IBOutlet and IBAction connections :large_orange_diamond: :star:128
 * [EasyAbout](https://github.com/JARMourato/EasyAbout) - A way to easily add CocoaPods licenses and App Version to your iOS App using the Settings Bundle :star:43
 * [Validated](https://github.com/Ben-G/Validated) - A Swift μ-Library for Somewhat Dependent Types :large_orange_diamond: :star:593
 * [Cent](https://github.com/ankurp/Cent) - Extensions for Swift Standard Types and Classes :large_orange_diamond: :star:165
 * [AssistantKit](https://github.com/anatoliyv/AssistantKit) - Easy way to detect iOS device properties, OS versions and work with screen sizes. Powered by Swift. :large_orange_diamond: :star:423
 * [SwiftLinkPreview](https://github.com/LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. 🔶 :star:751
 * [BundleInfos](https://github.com/rollmind/BundleInfos) - Simple getter for Bundle informations. like short version from bundle. 🔶 :star:1
 * [YAML.framework](https://github.com/mirek/YAML.framework) - Proper YAML support for Objective-C based on `LibYAML`. :star:185
 * [ReadabilityKit](https://github.com/exyte/ReadabilityKit) - Metadata extractor for news, articles and full-texts in Swift. 🔶 :star:629
 * [MissionControl-iOS](https://github.com/appculture/MissionControl-iOS) - Super powerful remote config utility written in Swift (iOS, watchOS, tvOS, macOS) :large_orange_diamond: :star:99
 * [SwiftTweaks](https://github.com/Khan/SwiftTweaks) - Tweak your iOS app without recompiling! :large_orange_diamond: :star:1029
 * [UnsupportedOSVersionAlert](https://github.com/caloon/UnsupportedOSVersionAlert) - Alerts users with a popup if they use an app with an unsupported version of iOS (e.g. iOS betas) :large_orange_diamond: :star:9
 * [SwiftSortUtils](https://github.com/dsmatter/SwiftSortUtils) - This library takes a shot at making sorting in Swift more pleasant. It also allows you to reuse your old NSSortDescriptor instances in Swift. :large_orange_diamond: :star:57
 * [Retry](https://github.com/icanzilb/Retry) - Haven't you wished for `try` to sometimes try a little harder? Meet `retry` . :large_orange_diamond: :star:433
 * [ObjectiveKit](https://github.com/marmelroy/ObjectiveKit) - Swift-friendly API for Objective C runtime functions. :large_orange_diamond: :star:706
 * [MoyaSugar](https://github.com/devxoul/MoyaSugar) -  Syntactic sugar for Moya. :large_orange_diamond: :star:75
 * [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) -  A handy collection of more than 400 native Swift 3 extensions to boost your productivity. :large_orange_diamond: :star:4166
 * [Eject](https://github.com/Raizlabs/Eject) - An eject button for Interface Builder to generate swift code. :large_orange_diamond: :star:511
 * [ContactsWrapper](https://github.com/abdullahselek/ContactsWrapper) - Easy to use wrapper for both contacts and contacts group with Objective-C. :star:17
 * [XestiMonitors](https://github.com/eBardX/XestiMonitors) - An extensible monitoring framework written in Swift :large_orange_diamond: :star:240
 * [OpenSourceController](https://github.com/floriangbh/OpenSourceController) - The simplest way to display the libraries licences used in your application. :large_orange_diamond: :star:27
 * [App-Update-Tracker](https://github.com/Stunner/App-Update-Tracker) - Easily detect and run code upon app installation or update. :star:24
 * [ExtensionalSwift](https://github.com/4taras4/SwiftExtension) - Useful swift extensions in one place 🔶[e] :star:3
 * [InAppSettingsKit](https://github.com/futuretap/InAppSettingsKit) - This iOS framework allows settings to be in-app in addition to or instead of being in the Settings app. :star:2822
 * [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions. :star:3342
 * [DefaultStringConvertible](https://github.com/jessesquires/DefaultStringConvertible) - A default CustomStringConvertible implementation for Swift types 🔶[e] :star:129
 * [FluxCapacitor](https://github.com/marty-suzuki/FluxCapacitor) - FluxCapacitor makes implementing Flux design pattern easily with protocols and typealias. 🔶 :star:96
 * [VTAcknowledgementsViewController](https://github.com/vtourraine/VTAcknowledgementsViewController) - Ready to use “Acknowledgements”/“Licenses”/“Credits” view controller for CocoaPods. :star:813
 * [Closures](https://github.com/vhesener/Closures) - Swifty closures for UIKit and Foundation. 🔶 :star:1251
 * [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) - Showcase new features after an app update similar to Pages, Numbers and Keynote :large_orange_diamond: :star:1205

## VR
* [VR Toolkit iOS](https://github.com/Aralekk/VR_Toolkit_iOS) - A sample project that provides the basics to create an interactive VR experience on iOS :large_orange_diamond: :star:76
* [360 VR Player](https://github.com/hanton/HTY360Player) - A open source, ad-free, native and universal 360 degree panorama video player for iOS. :star:1707
* [simple360player](https://github.com/Aralekk/simple360player_iOS) - Free & ad-free 360 VR Video Player. Flat or Stereoscopic. In Swift 2. :large_orange_diamond: :star:133
* [Swifty360Player](https://github.com/abdullahselek/Swifty360Player) - iOS 360-degree video player streaming from an AVPlayer with Swift. :large_orange_diamond: :star:34

## Walkthrough / Intro / Tutorial
* [Onboard](https://github.com/mamaral/Onboard) - Easily create a beautiful and engaging onboarding experience with only a few lines of code. :star:5924
* [EAIntroView](https://github.com/ealeksandrov/EAIntroView) - Highly customizable drop-in solution for introduction views. :star:3534
* [MYBlurIntroductionView](https://github.com/MatthewYork/MYBlurIntroductionView) - A super-charged version of MYIntroductionView for building custom app introductions and tutorials. :star:1543
* [BWWalkthrough](https://github.com/ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App. :large_orange_diamond: :star:2513
* [GHWalkThrough](https://github.com/GnosisHub/GHWalkThrough) - A UICollectionView backed drop-in component for introduction views. :star:739
* [ICETutorial](https://github.com/icepat/ICETutorial) - A nice tutorial like the one introduced in the Path 3.X App. :star:827
* [JazzHands](https://github.com/IFTTT/JazzHands) - Jazz Hands is a simple keyframe-based animation framework for UIKit. Animations can be controlled via gestures, scroll views, KVO, or ReactiveCocoa. :star:6347
* [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle) - A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros. :large_orange_diamond: :star:2862
* [Instructions](https://github.com/ephread/Instructions) - Easily add customizable coach marks into you iOS project. :large_orange_diamond: :star:3034
* [SwiftyWalkthrough](https://github.com/ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps, powered by Swift. :large_orange_diamond: :star:212
* [Gecco](https://github.com/yukiasai/Gecco) - Spotlight view for iOS. :large_orange_diamond: :star:1585
* [VideoSplashKit](https://github.com/svtek/VideoSplashKit) - VideoSplashKit - UIViewController library for creating easy intro pages with background videos :large_orange_diamond: :star:1128
* [Presentation](https://github.com/hyperoslo/Presentation) - Presentation helps you to make tutorials, release notes and animated pages. :large_orange_diamond: :star:2332
* [AMPopTip](https://github.com/andreamazz/AMPopTip) - An animated popover that pops out a given frame, great for subtle UI tips and onboarding. :star:1983
* [AlertOnboarding](https://github.com/PhilippeBoisney/AlertOnboarding) - A simple and handsome AlertView for onboard your users in your amazing world. :large_orange_diamond: :star:370
* [EasyTipView](https://github.com/teodorpatras/EasyTipView) - Fully customisable tooltip view in Swift. :large_orange_diamond: :star:1766
* [paper-onboarding](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design slider :large_orange_diamond: :star:2105
* [InfoView](https://github.com/anatoliyv/InfoView) - Swift based simple information view with pointed arrow. :large_orange_diamond: :star:35
* [Intro](https://github.com/nbolatov/Intro) - An iOS framework to easily create simple animated walkthrough, written in Swift. :large_orange_diamond: :star:25
* [AwesomeSpotlightView](https://github.com/aleksandrshoshiashvili/AwesomeSpotlightView) - Tool to create awesome tutorials or educate user to use application. Or just highlight something on screen. Written in Swift. :large_orange_diamond: :star:49
* [SwiftyOnboard](https://github.com/juanpablofernandez/SwiftyOnboard) - A simple way to add onboarding to your project. :large_orange_diamond: :star:602
* [WVWalkthroughView](https://github.com/praagyajoshi/WVWalkthroughView) - Utility to easily create walkthroughs to help with user onboarding. :star:21
* [SwiftyGuideOverlay](https://github.com/saeid/SwiftyGuideOverlay) - Easy and quick way to show intro / instructions over app UI without any additional images in real-time!. 🔶 :star:10
* [SwiftyOnboardVC](https://github.com/chaser79/SwiftyOnboardVC) - Lightweight walkthrough controller thats uses view controllers as its subviews making the customization endless. 🔶 :star:9
* [PVOnboardKit](https://github.com/vpeschenkov/PVOnboardKit) - Framework that allows you to add your own walkthrough/intro/tutorial into your app. :star:42

## WebSocket
* [SocketRocket](https://github.com/facebook/SocketRocket) - A conforming Objective-C WebSocket client library. :star:7337
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - Socket.IO-client for iOS/macOS. :large_orange_diamond: :star:2771
* [SwiftWebSocket](https://github.com/tidwall/SwiftWebSocket) - High performance WebSocket client library for Swift, iOS and macOS. :large_orange_diamond: :star:909
* [Starscream](https://github.com/daltoniam/Starscream) - Websockets in swift for iOS and macOS :large_orange_diamond: :star:3353
* [SwiftSocket](https://github.com/swiftsocket/SwiftSocket) - simple socket library for apple swift lang. :large_orange_diamond: :star:725
* [Socks](https://github.com/vapor/sockets) - Pure-Swift Sockets: TCP, UDP; Client, Server; Linux, macOS :large_orange_diamond: :star:483
* [SwifterSockets](https://github.com/Balancingrock/SwifterSockets) - A collection of socket utilities in Swift for OS-X and iOS :large_orange_diamond: :star:55
* [Swift-ActionCableClient](https://github.com/danielrhodes/Swift-ActionCableClient) - ActionCable is a new WebSocket server being released with Rails 5 which makes it easy to add real-time features to your app. :large_orange_diamond: :star:108

#### GCD
 * [GCDKit](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :large_orange_diamond: :star:283
 * [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :large_orange_diamond: :star:4164
 * [SwiftSafe](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy :large_orange_diamond: :star:159
 * [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue. :star:292
 * [AlecrimAsyncKit](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :large_orange_diamond: :star:66
 * [GrandSugarDispatch](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD) :large_orange_diamond: :star:31
 * [Threader](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution. :star:39
 * [Dispatch](https://github.com/JARMourato/Dispatch) - Just a tiny library to make using GCD easier and intuitive :large_orange_diamond: :star:173
 * [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :large_orange_diamond: :star:166
 * [Chronos-Swift](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :large_orange_diamond: :star:249
 * [Me](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations. :large_orange_diamond: :star:193
 * [SwiftyTask](https://github.com/CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :large_orange_diamond: :star:10

# Project setup
* [crafter](https://github.com/krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful. :star:542
* [liftoff](https://github.com/liftoffcli/liftoff) - Another CLI for creating iOS projects. :star:1562
* [amaro](https://github.com/crushlovely/Amaro) - iOS Boilerplate full of delights. :star:385
* [chairs](https://github.com/orta/chairs) - Swap around your iOS Simulator Documents :star:233
* [SwiftPlate](https://github.com/JohnSundell/SwiftPlate) - Easily generate cross platform Swift framework projects from the command line. :large_orange_diamond: :star:1423
* [xclint](https://github.com/xcodeswift/xclint) - Validate the state of your Xcode projects. :star:64
* [xcproj](https://github.com/xcodeswift/xcproj) - Read and update Xcode projects. :star:491

# Dependency / Package Manager
* [CocoaPods](https://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
* [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
* [Carthage](https://github.com/Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa. :large_orange_diamond: :star:10546
* [SWM (Swift Modules)](https://github.com/jankuca/swm) - A package/dependency manager for Swift projects similar to npm (node.js package manager) or bower (browser package manager from Twitter). Does not require the use of Xcode. :large_orange_diamond: :star:54
* [Alcatraz](http://alcatraz.io/) - The package manager for Xcode.
* [CocoaSeeds](https://github.com/devxoul/CocoaSeeds) - Git Submodule Alternative for Cocoa. :star:340
* [swift-package-manager](https://github.com/apple/swift-package-manager) - The Package Manager for the Swift Programming Language :large_orange_diamond: :star:5932
* [punic](https://github.com/schwa/punic) - Clean room reimplementation of Carthage tool :star:242

# Tools
* [Shark](https://github.com/kaandedeoglu/Shark) - Swift Script that transforms the .xcassets folder into a type safe enum. :large_orange_diamond: :star:288
* [SBConstants](https://github.com/paulsamuels/SBConstants) - Generate a constants file by grabbing identifiers from storyboards in a project. :star:309
* [R.swift](https://github.com/mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues in your Swift project. :large_orange_diamond: :star:4387
* [SwiftGen](https://github.com/SwiftGen/SwiftGen) - A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings and UIColors). :large_orange_diamond: :star:4073
* [Blade](https://github.com/jondot/blade) - Generate Xcode image catalogs for iOS / macOS app icons, universal images, and more. :star:779
* [Retini](https://github.com/terwanerik/Retini) - A super simple retina (2x, 3x) image converter. :star:105
* [Jazzy](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C. :large_orange_diamond: :star:4889
* [appledoc](https://github.com/tomaz/appledoc) - ObjectiveC code Apple style documentation set generator. :star:3755
* [Laurine](https://github.com/JiriTrecak/Laurine) - Laurine - Localization code generator written in Swift. Sweet! :large_orange_diamond: :star:1050
* [StoryboardMerge](https://github.com/marcinolawski/StoryboardMerge) - Xcode storyboards diff and merge tool. :star:205
* [ai2app](https://github.com/metasmile/ai2appiconset) - Creating AppIcon sets from Adobe Illustrator (all supported formats). :star:76
* [ViewMonitor](https://github.com/daisuke0131/ViewMonitor) - ViewMonitor can measure view positions with accuracy. :large_orange_diamond: :star:713
* [abandoned-strings](https://github.com/ijoshsmith/abandoned-strings) - Command line program that detects unused resource strings in an iOS or macOS application. :large_orange_diamond: :star:93
* [swiftenv](https://github.com/kylef/swiftenv) - swiftenv allows you to easily install, and switch between multiple versions of Swift. :large_orange_diamond: :star:1408
* [Misen](https://github.com/tasanobu/Misen) - Script to support easily using Xcode Asset Catalog in Swift. :large_orange_diamond:[e] :star:120
* [git-xcp](https://github.com/metasmile/git-xcp) - A Git plugin for versioning workflow of real-world Xcode project. fastlane's best friend. :star:11
* [WatchdogInspector](https://github.com/tapwork/WatchdogInspector) - Shows your current framerate (fps) in the status bar of your iOS app :star:440
* [Cichlid](https://github.com/dealforest/Cichlid) - automatically delete the current project's DerivedData directories :large_orange_diamond: :star:253
* [Delta](https://github.com/thoughtbot/Delta) - Managing state is hard. Delta aims to make it simple. :large_orange_diamond: :star:249
* [SwiftLintXcode](https://github.com/ypresto/SwiftLintXcode) - An Xcode plug-in to format your code using SwiftLint. :large_orange_diamond: :star:253
* [XCSwiftr](https://github.com/dzenbot/XCSwiftr) - An Xcode Plugin to convert Objective-C to Swift :large_orange_diamond: :star:322
* [SwiftKitten](https://github.com/johncsnyder/SwiftKitten) - Swift autocompleter for Sublime Text, via the adorable SourceKitten framework :large_orange_diamond: :star:129
* [Kin](https://github.com/Karumi/Kin) - Have you ever found yourself undoing a merge due to a broken Xcode build? Then Kin is your tool. It will parse your project configuration file and detect errors. :large_orange_diamond: :star:187
* [AVXCAssets-Generator](https://github.com/angelvasa/AVXCAssets-Generator) - AVXCAssets Generator takes path for your assets images and creates appiconset and imageset for you in just one click :large_orange_diamond: :star:285
* [Peek](https://github.com/shaps80/Peek) - Take a Peek at your application. :large_orange_diamond: :star:1155
* [SourceKitten](https://github.com/jpsim/SourceKitten) - An adorable little framework and command line tool for interacting with SourceKit. :large_orange_diamond: :star:1162
* [Localizations](https://github.com/athiercelin/localizations) - macOS app that manages localizations of Xcode projects. :large_orange_diamond: :star:96
* [xcbuild](https://github.com/facebook/xcbuild) - Xcode-compatible build tool. :star:1390
* [XcodeIssueGenerator](https://github.com/doubleencore/XcodeIssueGenerator) - An executable that can be placed in a Run Script Build Phase that marks comments like // TODO: or // SERIOUS: as warnings or errors so they display in the Xcode Issue Navigator. :large_orange_diamond: :star:142
* [SwiftCompilationPerformanceReporter](https://github.com/tumblr/SwiftCompilationPerformanceReporter) - Generate automated reports for slow Swift compilation paths in specific targets :large_orange_diamond: :star:148
* [BuildTimeAnalyzer](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) - Build Time Analyzer for Swift :large_orange_diamond: :star:2170
* [Duration](https://github.com/SwiftStudies/Duration) - A simple Swift package for measuring and reporting the time taken for operations :large_orange_diamond: :star:300
* [Benchmark](https://github.com/WorldDownTown/Benchmark) - The Benchmark⏲ module provides methods to measure and report the time used to execute Swift code. :large_orange_diamond: :star:62
* [MBAssetsImporter](https://github.com/MatiBot/MBAssetsImporter) - Import assets from Panoramio or from your macOS file system with their metadata to your iOS simulator (Swift 2.0) :large_orange_diamond: :star:68
* [Realm Browser](https://github.com/realm/realm-browser-osx) - Realm Browser is a macOS utility to open and modify realm database files. :star:460
* [SuperDelegate](https://github.com/square/SuperDelegate) – SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle.
* [fastlane-plugin-appicon](https://github.com/KrauseFx/fastlane-plugin-appicon) - Generate required icon sizes and iconset from a master application icon. :star:178
* [infer](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C. :star:7697
* [PlayNow](https://github.com/marcboquet/PlayNow) - Small app that creates empty Swift playground files and opens them with Xcode. :large_orange_diamond: :star:91
* [Xtrace](https://github.com/johnno1962/Xtrace) - Trace Objective-C method calls by class or instance :star:1682
* [xcenv](https://github.com/xcenv/xcenv) - Groom your Xcode environment. :star:208
* [playgroundbook](https://github.com/playgroundbooks/playgroundbook) - Tool for Swift Playground books :star:212
* [Ecno](https://github.com/xmartlabs/Ecno) - Ecno is a task state manager built on top of UserDefaults in pure Swift 3. :large_orange_diamond: :star:65
* [ipanema](https://github.com/toshi0383/ipanema) - ipanema analyzes and prints useful information from *.ipa file. :star:5
* [pxctest](https://github.com/plu/pxctest) - Parallel XCTest - Execute XCTest suites in parallel on multiple iOS Simulators. :star:777
* [IBM Swift Sandbox](https://swift.sandbox.bluemix.net) - The IBM Swift Sandbox is an interactive website that lets you write Swift code and execute it in a server environment – on top of Linux! :large_orange_diamond:
* [FBSimulatorControl](https://github.com/facebook/FBSimulatorControl) - A macOS library for managing and manipulating iOS Simulators :star:2116
* [Nomad](http://nomad-cli.com) - Suite of command line utilities & libraries for sending APNs, create & distribute *.ipa*, verify In-App-Purchase receipt and more.
* [Cookiecutter](https://github.com/JetpackSwift/FrameworkTemplate) - A template for new Swift iOS / tvOS / watchOS / macOS Framework project ready with travis-ci, cocoapods, Carthage, SwiftPM and a Readme file :large_orange_diamond: :star:434
* [Sourcery](https://github.com/krzysztofzablocki/Sourcery) - A tool that brings meta-programming to Swift, allowing you to code generate Swift code. :large_orange_diamond: :star:2916
* [AssetChecker 👮](https://github.com/freshOS/AssetChecker) - Keeps your Assets.xcassets files clean and emits warnings when something is suspicious. :large_orange_diamond: :star:52
* [PlayAlways](https://github.com/insidegui/PlayAlways) - Create Xcode playgrounds from your menu bar :large_orange_diamond: :star:402
* [GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift) - Shows FPS, CPU usage, app and iOS versions above the status bar and report FPS and CPU usage via delegate. :large_orange_diamond: :star:1589
* [Traits](https://github.com/krzysztofzablocki/Traits) - Library for a real-time design and behavior modification of native iOS apps without recompiling (code and interface builder changes are supported). :large_orange_diamond: :star:865
* [Struct](https://www.get-struct.tools) - A tool for iOS and Mac developers to automate the creation and management of Xcode projects.
* [Nori](https://github.com/yukiasai/Nori) - Easier to apply code based style guide to storyboard. :large_orange_diamond: :star:290
* [Attabench](https://github.com/attaswift/Attabench) - Microbenchmarking app for Swift with nice log-log plots :large_orange_diamond: :star:589
* [Gluten](https://github.com/wilbertliu/Gluten) - Nano library to unify XIB and it's code. :large_orange_diamond: :star:9
* [LicensePlist](https://github.com/mono0926/LicensePlist) - A license list generator of all your dependencies for iOS applications. :large_orange_diamond: :star:1026
* [Swizzlean](https://github.com/rbaumbach/Swizzlean) - An Objective-C Swizzle Helper Class :star:80
* [AppDevKit](https://github.com/yahoo/AppDevKit) - AppDevKit is an iOS development library that provides developers with useful features to fulfill their everyday iOS app development needs. :star:1354
* [Tweaks](https://github.com/facebook/Tweaks) - An easy way to fine-tune, and adjust parameters for iOS apps in development. :star:4638
* [FengNiao](https://github.com/onevcat/FengNiao) - A command line tool for cleaning unused resources in Xcode. :large_orange_diamond: :star:1343
* [LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker) - Find retain cycles / memory leaks sooner. :large_orange_diamond: :star:1410
* [Plank](https://github.com/pinterest/plank) - A tool for generating immutable model objects. :star:365
* [Lona](https://github.com/airbnb/Lona) - A tool for defining design systems and using them to generate cross-platform UI code, Sketch files, images, and other artifacts. :star:3536

# Rapid Development
* [Playgrounds](https://github.com/krzysztofzablocki/Playgrounds) - Playgrounds for Objective-C for extremely fast prototyping / learning. :star:2365
* [MMBarricade](https://github.com/mutualmobile/MMBarricade) - Runtime configurable local server for iOS apps. :star:355
* [STV Framework](http://www.sensiblecocoa.com) - Native visual iOS development.
* [swiftmon](https://github.com/dimpiax/swiftmon) - swiftmon restarts your swift application in case of any file change. :star:2

# Injection
* [dyci](https://github.com/DyCI/dyci-main) - Code injection tool. :star:1069
* [injectionforxcode](https://github.com/johnno1962/injectionforxcode) - Code injection including Swift. :star:5000
* [Swinject](https://github.com/Swinject/Swinject) - Dependency injection framework for Swift :star:2022
* [Reliant](https://github.com/appfoundry/Reliant) - Nonintrusive Objective-C dependency injection. :star:53
* [Kraken](https://github.com/sabirvirtuoso/Kraken) - A Dependency Injection Container for Swift with easy-to-use syntax. :star:1
* [Cleanse](https://github.com/square/Cleanse) - Lightweight Swift Dependency Injection Framework by Square. :large_orange_diamond: :star:985
* [Typhoon](https://github.com/appsquickly/Typhoon) - Powerful dependency injection (Objective-C & Swift). :star:2304
* [Perform](https://github.com/thoughtbot/Perform) - Easy dependency injection for storyboard segues. :large_orange_diamond: :star:252
* [Alchemic](https://github.com/drekka/Alchemic) - Advanced, yet simple to use DI framework for Objective-C. :star:11
* [Guise](https://github.com/prosumma/Guise) - An elegant, flexible, type-safe dependency resolution framework for Swift :large_orange_diamond: :star:25

# Deployment / Distribution
* [fastlane](https://github.com/fastlane/fastlane) - Connect all iOS deployment tools into one streamlined workflow. :star:19651
* [deliver](https://github.com/fastlane/fastlane/tree/master/deliver) - Upload screenshots, metadata and your app to the App Store using a single command.
* [snapshot](https://github.com/fastlane/fastlane/tree/master/snapshot) Automate taking localized screenshots of your iOS app on every device.
* [buddybuild](https://www.buddybuild.com/) - A mobile iteration platform - build, deploy, and collaborate.
* [Bitrise](https://www.bitrise.io) Mobile Continuous Integration & Delivery with dozens of integrations to build, test, deploy and collaborate.
* [watchbuild](https://github.com/fastlane/watchbuild) - Get a notification once your iTunes Connect build is finished processing. :star:68
* [Crashlytics](https://try.crashlytics.com/) - A crash reporting and beta testing service.
* [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
* [HockeyApp](https://www.hockeyapp.net) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.
* [boarding](https://github.com/fastlane/boarding) - Instantly create a simple signup page for TestFlight beta testers. :star:617
* [HockeyKit](https://github.com/bitstadium/HockeyKit) - A software update kit. :star:2196
* [Boombox.io](https://boombox.io/) - Sign up TestFlight beta testers on your website. Embeddable and hosted TestFlight beta sign-up forms
* [Rollout.io](https://rollout.io/) - SDK to patch, fix bugs, modify and manipulate native apps (Obj-c & Swift) in real-time.
* [AppLaunchpad](https://theapplaunchpad.com/) - Free App Store screenshot builder.
* [LaunchKit](https://github.com/LaunchKit/LaunchKit) - A set of web-based tools for mobile app developers, now open source! :star:1835
* [Instabug](https://instabug.com) - In-app feedback, Bug and Crash reporting, Fix Bugs Faster through user-steps, video recordings, screen annotation, network requests logging.

# App Store
* [Average App Store Review Times](http://appreviewtimes.com) This site tracks the average App Store review times for both the iOS and the Mac App Store using data crowdsourced from iOS and Mac developers.
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/)  Highlighted some of the most common issues that cause apps to get rejected.
* [Free App Store Optimization Tool](https://www.mobileaction.co) Lets you track your App Store visibility in terms of keywords and competitors.
* [App Release Checklist](https://github.com/oisin/app-release-checklist/blob/master/checklist.md) - A checklist to pore over before you ship that amazing app that has taken ages to complete, but you don't want to rush out in case you commit a schoolboy error that will end up making you look dumber than you are.
* [Harpy](https://github.com/ArtSabintsev/Harpy) - Notify users when a new version of your iOS app is available, and prompt them with the App Store link. :star:2424
* [iRate](https://github.com/nicklockwood/iRate) - A handy class that prompts users of your iPhone or Mac App Store app to rate your application after using it for a while. Similar to Appirater, but with a simpler, cleaner interface and automatic support for iOS fast application switching. :star:4326
* [appirater](https://github.com/arashpayan/appirater) - A utility that reminds your iPhone app's users to review the app. :star:4526
* [Siren](https://github.com/ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade. :large_orange_diamond: :star:2267
* [Appstore Review Guidelines](https://github.com/aashishtamsya/Appstore-Review-Guidelines) - A curated list of points which a developer has to keep in mind before submitting his/her application on appstore for review. :star:5

# Xcode

#### Extensions (Xcode 8+)
* [CleanClosureXcode](https://github.com/BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond: :star:149
* [xTextHandler](https://github.com/cyanzhong/xTextHandler) - Xcode Source Editor Extension Toolset (Plugins for Xcode 8) :large_orange_diamond: :star:1380
* [SwiftInitializerGenerator](https://github.com/Bouke/SwiftInitializerGenerator) - Xcode 8 Source Code Extension to Generate Swift Initializers. :large_orange_diamond: :star:528
* [XcodeEquatableGenerator](https://github.com/sergdort/XcodeEquatableGenerator) - Xcode 8 Source Code Extension will generate conformance to Swift Equatable protocol based on type and fields selection. :large_orange_diamond: :star:167
* [Import](https://github.com/markohlebar/Import) - Xcode extension for adding imports from anywhere in the code. :large_orange_diamond: :star:705
* [Mark](https://github.com/velyan/Mark) - Xcode extension for generating MARK comments. :large_orange_diamond: :star:113
* [XShared](https://github.com/Otbivnoe/XShared) - Xcode extension which allows you copying the code with special formatting quotes for social (Slack, Telegram). :large_orange_diamond: :star:72
* [XGist](https://github.com/Bunn/Xgist) - Xcode extension which allows you to send your text selection or entire file to Github's Gist and automatically copy the Gist URL into your Clipboard. :large_orange_diamond: :star:54
* [Swiftify](https://objectivec2swift.com/) - Objective-C to Swift online code converter and Xcode extension. :large_orange_diamond:

#### Plugins
* [FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - A Xcode 5+ plugin that adds more flexible autocompletion rather than just prefix-matching. :star:3388
* [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode. :star:1043
* [Show in Github](https://github.com/larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window. :star:242
* [BBUFullIssueNavigator](https://github.com/neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator. :star:247
* [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor. :star:701
* [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases. :star:670
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier. :star:8462
* [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns. :star:2740
* [CocoaPods Xcode Plugin](https://github.com/kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode. :star:2387
* [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls. :star:4298
* [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual. :star:2909
* [Backlight-for-XCode](https://github.com/limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode :star:436
* [KPRunEverywhereXcodePlugin](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) - An Xcode plugin to build and run an app across multiple iOS devices with one click. :star:324
* [RevealPlugin](https://github.com/shjborage/Reveal-Plugin-for-Xcode) - Plugin for Xcode to integrate the Reveal App to your project automatic. :star:235
* [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin)- Xcode plugin to generate new Realm models.
* [AdjustFontSize](https://github.com/zats/AdjustFontSize-Xcode-Plugin) - Instant font size adjustment with `⌘ +` / `⌘ -`. :star:285
* [Rephrase](https://www.rephrase.io) - Localise from Xcode.
* [XCActionBar](https://github.com/pdcgomes/XCActionBar) - "Alfred for Xcode" plugin. :star:1229
* [QuickJump](https://github.com/wiruzx/QuickJump) - Quick code navigation for Xcode. :star:30
* [CATweaker](https://github.com/keefo/CATweaker) - Plugin for creating beautiful CAMediaTimingFunction curve. :star:705
* [XcodeWay](https://github.com/onmyway133/XcodeWay) - An Xcode plugin that makes navigating to many places easier (available via Alcatraz). :star:339
* [GitDiff](https://github.com/johnno1962/GitDiff) - Highlights deltas against git repo in Xcode. :star:881
* [MCLog](https://github.com/yuhua-chen/MCLog) - Xcode plugin for filtering the console area. :star:608
* [XToDo](https://github.com/trawor/XToDo) - Dialog with list of all TODO, FIXME, ??? and !!! in the project. :star:1590
* [CopyIssue](https://github.com/hanton/CopyIssue-Xcode-Plugin) - Makes Copy Xcode Issue Description Easy. :star:179
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) - A Xcode plugin to automatically generate all the App icons needed. :star:2411
* [BBUncrustifyPlugin-Xcode](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) - Xcode plugin to format source code using ClangFormat or Uncrustify. :star:1210
* [Aviator](https://github.com/marksands/Aviator) - Xcode plugin that brings ⇧⌘T (source/test toggle) from AppCode over to Xcode. :star:31
* [JumpMarks](https://github.com/merrickp/JumpMarks) - Navigate your code files with numbered bookmarks. :star:55
* [XCSnippetr](https://github.com/dzenbot/XCSnippetr) - An Xcode Plugin to upload code snippets directly into Slack and Gist. :star:95
* [Peckham](https://github.com/markohlebar/Peckham) - Add #import-s from anywhere in the code. :star:731
* [MLAutoReplace](https://github.com/molon/MLAutoReplace) - Xcode plugin, Re-Intent, make you write code more quickly. :star:244
* [AutoHighlightSymbol](https://github.com/chiahsien/AutoHighlightSymbol) - A Xcode plugin to add highlight to the instances of selected symbol. :star:76
* [Reveal-In-GitHub](https://github.com/lzwjava/Reveal-In-Github) - Xcode plugin to let you jump to GitHub History, Blame, PRs, Issues, Notifications of any GitHub repo with one shortcut. :star:270
* [CleanHeaders-Xcode](https://github.com/insanoid/CleanHeaders-Xcode) - A simple iSort like header sorting and duplicate removal plugin for Xcode, makes your headers look more organized. :star:78
* [Luft](https://github.com/k0nserv/luft) - The Xcode Plugin that helps you write lighter view controllers :star:183
* [You-Can-Do-It](https://github.com/orta/You-Can-Do-It) - Is learning a new language getting you down? Worry not, this Xcode plugin will keep you motivated. :star:232
* [PreciseCoverage](https://github.com/zats/PreciseCoverage) - Make Xcode code coverage more informative :star:172
* [AutoIndentWithSave](https://github.com/ThilinaHewagama/AutoIndentWithSave) Xcode plugin which indent the source code when save
* [Refactorator](https://github.com/johnno1962/Refactorator) - Xcode Plugin that Refactors Swift & Objective-C :large_orange_diamond: :star:985
* [VWInstantRun](https://github.com/wangshengjia/VWInstantRun) - An Xcode plugin let you build & run your selected lines of code in Xcode without running the whole project, you'll have the output instantly in your Xcode console. :large_orange_diamond: :star:1062
* [TTPasteHistory](https://github.com/tutumagi/TTPasteHistory) - A Xcode plugin. Recording you copy-and-paste history easily to write the code :star:31
* [xSendIssue](https://github.com/hungri-yeti/xSendIssue) - Plugin for Xcode to submit GitHub issues directly from within Xcode. :star:4
* [Swimat](https://github.com/Jintin/Swimat) - An Xcode formatter plug-in to format your swift code. :star:786
* [Fastlane-Plugin](https://github.com/RishabhTayal/Fastlane-Plugin) - The awesome Fastlane tools brought into your Xcode. :star:35
* [Gradle Xcode plugin](https://openbakery.org/gxp/) - Build iOS or macOS Projects using Gradle.
* [SYXcodeIconVersion](https://github.com/dvkch/SYXcodeIconVersion) - This Xcode plugin shows Xcode app version in the Dock and App Switcher icon. :star:95
* [Gradle](https://github.com/openbakery/gradle-xcodePlugin) - gradle xcodePlugin to build iOS and Mac projects. :star:367
* [HOStringSense-for-Xcode](https://github.com/holtwick/HOStringSense-for-Xcode) - Plugin for Xcode to make perfect editing regular expressions, multi line texts, inline HTML and many more use cases. Also provides quick feedback on string length. :star:723
* [FastStub-Xcode](https://github.com/music4kid/FastStub-Xcode) - Xcode Plugin helps you find missing methods in your class header, protocols, and super class, also makes fast inserting. :star:496
* [JSPatchX](https://github.com/bang590/JSPatchX) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:744
* [Dash](https://kapeli.com/dash) - Dash is a great documentation browser which integrates closely into Xcode with its plugin.
* [SFJumpToLine](https://github.com/sferrini/SFJumpToLine) - Xcode plugin that moves the instruction pointer to the selected line :star:10
* [ClangFormat-Xcode](https://github.com/travisjeffery/ClangFormat-Xcode) - An Xcode plug-in to format your code using Clang's format tools. :star:2578
* [update_xcode_plugins](https://github.com/inket/update_xcode_plugins) - No more messing with plugin UUIDs; Plugins on Xcode 8! :star:992
* [MakeXcodeGr8Again](https://github.com/fpg1503/MakeXcodeGr8Again) - Xcode + Plugins = :blue_heart: :large_orange_diamond: :star:757

#### Themes
* [Dracula Theme](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode. :star:13
* [Xcode themes list](https://github.com/hdoria/xcode-themes) - Color themes for Xcode. :star:1810
* [Solarized-Dark-for-Xcode](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) - Solarized Dark Theme for Xcode 5.
* [WWDC2016 Xcode Color Scheme](https://github.com/cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation. :star:368

#### Other Xcode

* [awesome-xcode-scripts](https://github.com/aashishtamsya/awesome-xcode-scripts) - A curated list of useful xcode scripts 📝. :star:32
* [Synx](https://github.com/venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups. :star:5682
* [dsnip](https://github.com/Tintenklecks/IBDelegateCodesippets) - Tool to generate (native) Xcode code snippets from all protocols/delegate methods of UIKit (UITableView, ...)
* [SBShortcutMenuSimulator](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 3D Touch shortcuts in the Simulator :star:1789
* [awesome-gitignore-templates](https://github.com/aashishtamsya/awesome-gitignore-templates) - A collection of swift, objective-c, android and many more langugages .gitignore templates 📝. :star:10
* [swift-project-template](https://github.com/artemnovichkov/swift-project-template) - Template for iOS Swift project generation. :star:27
* [Swift-VIPER-Module](https://github.com/Juanpe/Swift-VIPER-Module) - Xcode template for create modules with VIPER Architecture written in Swift 3 :large_orange_diamond: :star:241
* [ViperC](https://github.com/abdullahselek/ViperC) - Xcode template for VIPER Architecture for both Objective-C and Swift :large_orange_diamond: :star:37
* [Microfeatures](https://github.com/microfeatures) - Architectural approach to structure your Xcode projects. :large_orange_diamond:
* [XcodeCodeSnippets](https://github.com/ismetanin/XcodeCodeSnippets) - A set of code snippets for iOS development, includes code and comments snippets. :star:12

# Reference
* [Swift Cheat Sheet](https://github.com/iwasrobbed/Swift-CheatSheet) - A quick reference cheat sheet for common, high level topics in Swift. :large_orange_diamond: :star:715
* [Objective-C Cheat Sheet](https://github.com/iwasrobbed/Objective-C-CheatSheet) - A quick reference cheat sheet for common, high level topics in Objective-C. :star:962
* [SwiftSnippets](https://github.com/hyperoslo/SwiftSnippets) - A collection of Swift snippets to be used in Xcode :star:104
* [App Store Checklist](https://github.com/whitef0x0/app-store-checklist) - A checklist of what to look for before submitting your app to the App Store. :star:21
* [whats-new-in-swift-4](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showcasing the new features in Swift 4.0. :large_orange_diamond: :star:1810
* [WWDC17-Recap](https://github.com/erenkabakci/WWDC17-Recap) - Markdown collection repo for the sessions at WWDC17. :star:96

# Style Guides
* [NY Times - Objective C Style Guide](https://github.com/NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times. :star:4623
* [raywenderlich Style Guide](https://github.com/raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com. :star:2707
* [Github Objective-C Style Guide](https://github.com/github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects. :star:1668
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions.
* [Swift Style Guide by @raywenderlich](https://github.com/raywenderlich/swift-style-guide) - The official Swift style guide for raywenderlich.com. :large_orange_diamond: :star:8011
* [Spotify Objective-C Coding Style](https://github.com/spotify/ios-style) - Guidelines for iOS development in use at Spotify. :star:200
* [Github - Style guide & coding conventions for Swift projects](https://github.com/github/swift-style-guide) - A guide to our Swift style and conventions by @github. :large_orange_diamond: :star:4408
* [Futurice iOS Good Practices](https://github.com/futurice/ios-good-practices) - iOS starting guide and good practices suggestions by [@futurice](https://github.com/futurice). :star:6947
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md) - SlideShare Swift Style Guide we are using for our upcoming iOS 8 only app written in Swift :large_orange_diamond:
* [Prolific Interactive Style Guide](https://github.com/prolificinteractive/swift-style-guide) - A style guide for Swift. :star:153

# Good Websites

#### News, Blogs and more
* [BGR](http://bgr.com/ios-7/)
* [iMore](https://www.imore.com/)
* [Lifehacker](https://lifehacker.com/tag/ios)
* [NSHipster](http://nshipster.com)
* [Objc.io](https://www.objc.io/)
* [ASCIIwwdc](http://asciiwwdc.com)
* [Natasha The Robot](https://www.natashatherobot.com/)
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) :large_orange_diamond:
* [iOS Programming Subreddit](https://www.reddit.com/r/iOSProgramming/)
* [iOS8-day-by-day](https://github.com/shinobicontrols/iOS8-day-by-day) :large_orange_diamond:
* [iOScreator](https://www.ioscreator.com/) :large_orange_diamond:
* [Mathew Sanders](http://mathewsanders.com/) :large_orange_diamond:
* [Little Bites of Cocoa](https://littlebitesofcocoa.com/) :large_orange_diamond:
* [iOS Dev Nuggets](http://hboon.com/iosdevnuggets/) :large_orange_diamond:
* [This Week in Swift](https://swiftnews.curated.co/) :large_orange_diamond:
* [iOS Developer and Designer interview](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions) - A small guide to help those looking to hire a developer or designer for iOS work. :star:1384
* [iOS9-day-by-day](https://github.com/shinobicontrols/iOS9-day-by-day) :large_orange_diamond:
* [Code Facebook](https://code.facebook.com/ios/)
* [iOS Cookies](http://www.ioscookies.com/) - A hand curated collection of iOS libraries written in Swift :large_orange_diamond:
* [Feeds for iOS Developer](https://github.com/rgnlax/Feeds-for-iOS-Developer) - The list of RSS feeds for iOS developers. :star:74
* [iOS10 day-by-day](https://www.shinobicontrols.com/blog/ios-10-day-by-day-index) :large_orange_diamond:

#### UIKit references
* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

#### Forums and discuss lists
* [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
* ["iOS" on Stackoverflow](https://stackoverflow.com/questions/tagged/ios)

#### Tutorials and Keynotes
* [AppCoda](https://www.appcoda.com/)
* [Tutorials Point](http://www.tutorialspoint.com/ios/)
* [Code with Chris](https://codewithchris.com/)
* [Cocoa with Love](http://www.cocoawithlove.com/)
* [Code School - Try Objective-C](https://www.codeschool.com/courses/try-objective-c)
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - Swift tutorials Youtube Channel. :large_orange_diamond:
* [RAYWENDERLICH](https://www.raywenderlich.com/tutorials) - Tutorials for developers and gamers
* [Mike Ash](https://www.mikeash.com/pyblog/)
* [Big Nerd Ranch](https://www.bignerdranch.com/blog/categories/ios/) :large_orange_diamond:
* [Tuts+](https://code.tutsplus.com/categories/ios-sdk) :large_orange_diamond:
* [iOS-Blog](http://www.ios-blog.co.uk/) :large_orange_diamond:
* [Thinkster](https://thinkster.io/a-better-way-to-learn-swift) :large_orange_diamond:
* [Swift Education](https://github.com/swifteducation) - A community of educators sharing materials for teaching Swift and app development. :large_orange_diamond:
* [Cocoa Dev Central](http://cocoadevcentral.com)
* [Use Your Loaf](https://useyourloaf.com/)
* [Swift Tutorials by Jameson Quave](http://jamesonquave.com/blog/tutorials/) :large_orange_diamond:
* [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education) - :fire: All of the resources for Learning About Swift :large_orange_diamond: :star:5292
* [Awesome-Swift-Playgrounds](https://github.com/uraimo/Awesome-Swift-Playgrounds) - ⭐ A List of Awesome Swift Playgrounds! :large_orange_diamond: :star:1933
* [learn-swift](https://github.com/nettlep/learn-swift) - Learn Apple's Swift programming language interactively through these playgrounds. :large_orange_diamond: :star:762
* [Treehouse's iOS Courses and Workshops](https://teamtreehouse.com/library/topic:ios) - Topics for beginner and advanced developers in both Objective-C and Swift.
* [The Swift Summary Book](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language written on Playgrounds. :large_orange_diamond: :star:1646
* [Hacking With Swift](https://www.hackingwithswift.com) - Learn to code iPhone and iPad apps with 3 Swift tutorials. :large_orange_diamond:
* [Realm Academy](https://academy.realm.io/)

#### iOS UI Template
* [iOS UI Design Kit](https://www.invisionapp.com/tethr)
* [iOS Design Guidelines](https://ivomynttinen.com/blog/ios-design-guidelines)
* [iOS GUI by Facebook Design Resources](http://facebook.design/)

#### Prototyping
* [FluidUI](https://www.fluidui.com)
* [Proto.io](https://proto.io/)
* [Framer](https://framer.com/)
* [Pixate](http://www.pixate.com/)
* [Principle](http://principleformac.com)

#### Newsletters
* [iOS Goodies](http://ios-goodies.com) - Weekly iOS newsletter
* [This Week in Swift](https://swiftnews.curated.co) - I'm @NatashaTheRobot and I'm programmed to love #Swift! Every week, I put together a list of the best Swift resources for you. Happy Learning!
* [The iOS Times](http://theiostimes.com) - A weekly publication with news and trending projects in the open source iOS ecosystem.
* [raywenderlich.com Weekly](https://www.raywenderlich.com/newsletter) - sign up to receive the latest tutorials from raywenderlich.com each week
* [iOS Dev Tools Weekly](https://iosdev.tools) - The greatest iOS development tools, including websites, desktop and mobile apps, and back-end services.
* [iOS Trivia Weekly](http://wanderbit.us4.list-manage.com/subscribe?u=4e20cd8ea3a0ce09ff4619a52&id=5898a5992b) - Three challenging questions about iOS development every Wednesday
* [Indie iOS Focus Weekly](https://indieiosfocus.curated.co) - Looking for the best iOS dev links, tutorials, & tips beyond the usual news? Curated by Chris Beshore. Published every Thursday.
* [iOS Dev Weekly](https://iosdevweekly.com/) - Subscribe to a hand-picked round up of the best iOS development links every week. Free.
* [Swift Weekly Brief](https://swiftweekly.github.io/) - A community-driven weekly newsletter about Swift.org. Curated by Jesse Squires and published for free every Thursday
* [Server-Side Swift Weekly](https://www.serverswift.tech) - A weekly newsletter with the best links related to server-side Swift and cross-platform developer tools. Curated by [@maxdesiatov](https://twitter.com/maxdesiatov)
* [WeeklyCocoa.News](https://weeklycocoa.news) - Weekly updated newsletter about iOS, Swift, Objective-C, CocoaTouch, and other Apple connected development technologies.
* [iOS Cookies Newsletter](https://us11.campaign-archive.com/home/?u=cd1f3ed33c6527331d82107ba&id=532dc7fb64) - A weekly digest of new iOS libraries written in Swift.
* [Swift Developments](https://andybargh.com/swiftdevelopments) - A weekly curated newsletter containing a hand picked selection of the latest links, videos, tools and tutorials for people interested in designing and developing their own iOS, WatchOS and AppleTV apps using Swift.

#### Medium
* [iOS App Development](https://medium.com/ios-os-x-development) - Stories and technical tips about building apps for iOS, Apple Watch, and iPad/iPhone
* [Swift Programming](https://medium.com/swift-programming) - The Swift Programming Language

# Social Media

#### Twitter
* [@objcio](https://twitter.com/objcio)
* [@CocoaPods](https://twitter.com/CocoaPods)
* [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
* [@RubyMotion](https://twitter.com/RubyMotion)


#### Facebook Groups
* [HH iOS](https://www.facebook.com/groups/hhios/about/)
* [Sketch - Official group](https://www.facebook.com/groups/sketchformac/about/)
* [Design-Code](https://www.facebook.com/groups/designcode/about/)
* [Sketch-Design.io](https://www.facebook.com/groups/sketchdesignio/about/)
* [Origami Community](https://www.facebook.com/groups/origami.community/about/)
* [Framer JS](https://www.facebook.com/groups/framerjs/about/)

# Podcasts
* [The Ray Wenderlich Podcast](https://www.raywenderlich.com/rwpodcast)
* [Debug](https://www.imore.com/debug)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iPhreaks](https://devchat.tv/iphreaks)
* [Under the Radar](https://www.relay.fm/radar)
* [Core Intuition](http://coreint.org/)
* [Swift Playhouse](http://www.swiftplayhouse.com/)
* [Release Notes](https://releasenotes.tv/)
* [More Than Just Code](http://mtjc.fm/)
* [Runtime](https://spec.fm/podcasts/runtime)
* [Consult](http://consultpodcast.com/)
* [Swift Unwrapped](https://spec.fm/podcasts/swift-unwrapped)
* [Fireside Swift](https://itunes.apple.com/us/podcast/fireside-swift/id1269435221?mt=2)

# Books
* [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11) :large_orange_diamond:
* [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11) :large_orange_diamond:
* [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](https://www.bignerdranch.com/books/ios-programming/)
* [Programming in Objective-C by Stephen G. Kochan](https://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
* [The Complete Friday Q & A: Volume 1](https://www.mikeash.com/book.html)
* [Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch](https://www.amazon.com/Core-Data-iOS-Data-Driven-Applications/dp/0321670426)
* [Cocoa Design Patterns](https://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)
* [Hello Swift! by Tanmay Bakshi with Lynn Beighley](https://www.manning.com/books/hello-swift) :large_orange_diamond:
* [iOS Development with Swift by Craig Grummitt](https://www.manning.com/books/ios-development-with-swift) :large_orange_diamond:
* [Anyone Can Create an App by Wendy L. Wise](https://www.manning.com/books/anyone-can-create-an-app) :large_orange_diamond:
* [Advanced Swift by Chris Eidhof, Ole Begemann, and Airspeed Velocity](https://www.objc.io/books/advanced-swift/) :large_orange_diamond:
* [Functional Swift by Chris Eidhof, Florian Kugler, and Wouter Swierstra](https://www.objc.io/books/functional-swift/) :large_orange_diamond:
* [Core Data by Florian Kugler and Daniel Eggert](https://www.objc.io/books/core-data/) :large_orange_diamond:
* [Classic Computer Science Problems in Swift](https://www.manning.com/books/classic-computer-science-problems-in-swift) :large_orange_diamond:
* [Swift in Depth](https://www.manning.com/books/swift-in-depth) :large_orange_diamond:

# Other Awesome Lists
Other amazingly awesome lists can be found in the
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.
* [Open Source apps](https://github.com/dkhamsing/open-source-ios-apps) list of open source iOS apps
* Awesome-swift
  * [@matteocrippa](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources. :star:13466
  * [@Wolg](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software. :star:4382
  * [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education) - All of the resources for Learning About Swift :large_orange_diamond: :star:5292
* [awesome watchkit apps](https://github.com/sanketfirodiya/sample-watchkit-apps) curated list of sample watchkit apps and tutorials. :watch:
* [iOS Learning Resources](https://github.com/sanketfirodiya/iOS-learning-resources) Comprehensive collection of high quality, frequently updated and well maintained iOS tutorial sites.
* [awesome-ios-animation](https://github.com/ameizi/awesome-ios-animation) - A curated list of awesome iOS animation, including Objective-C and Swift libraries. :star:2994
* [awesome-ios-chart](https://github.com/ameizi/awesome-ios-chart) - A curated list of awesome iOS chart libraries, including Objective-C and Swift. :star:1070
* [awesome-gists](https://github.com/vsouza/awesome-gists#ios) - A list of amazing gists (iOS section).
* [awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) - A curated list of awesome iOS UI/UX libraries. :star:9892
* [Awesome-Server-Side-Swift/TheList](https://github.com/Awesome-Server-Side-Swift/TheList) - A list of Awesome Server Side Swift 3 projects :star:633
* [awesome-interview-questions](https://github.com/MaximAbramchuck/awesome-interview-questions#ios) - A curated awesome list of lists of interview questions including iOS.
* [iOS-Playbook](https://github.com/bakkenbaeck/iOS-handbook) - Guidelines and best practices for excellent iOS apps :star:75
* [iOS-Learning-Materials](https://github.com/jVirus/iOS-Learning-Materials) - Curated list of articles, web-resources, tutorials and code repositories that may help you dig a little bit deeper into iOS. :star:68
* [Awesome-iOS-Twitter](https://github.com/carolanitz/Awesome-iOS-Twitter) - A curated list of awesome iOS Twitter accounts :star:159
* [Marketing for Engineers](https://github.com/LisaDziuba/Marketing-for-Engineers) - A curated collection of marketing articles & tools to grow your product. :star:4178
* [Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit) - A curated list of awesome ARKit projects and resources. :star:3464
* [CocoaConferences](https://github.com/Lascorbe/CocoaConferences) - List of cocoa conferences for iOS & macOS developers. :star:744
* [example-ios-apps](https://github.com/imjog/example-ios-apps) - A curated list of Open Source example iOS apps developed in Swift. :star:14

# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.


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
    - [App Routing](#app-routing)
    - [Apple TV](#apple-tv)
    - [Architecture Patterns](#architecture-patterns)
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
    - [GCD](#gcd)
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
* [Stanford - Developing iOS 11 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-11-apps-with-swift/id1309275316) - Stanford's 2017 iTunes U course updated for iOS 11 and Swift. :large_orange_diamond:
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
* [ARAnalytics](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data. :star:1714
* [Segment](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application. :star:261
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions. :star:2
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing
* [WAAppRouting](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically! :star:565
* [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links. :star:3034
* [IntentKit](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps. :star:1810
* [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API. :star:4034
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :large_orange_diamond: :star:93
* [Compass](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :large_orange_diamond: :star:637
* [Appz](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :large_orange_diamond: :star:888
* [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :large_orange_diamond: :star:1429
* [Marshroute](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful. :large_orange_diamond:  :star:144
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 3 :large_orange_diamond: :star:165
* [Router](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS. :large_orange_diamond: :star:105
* [ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain. :star:244
* [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) - Navigation framework for iOS applications based on a Reactive Flow Coordinator pattern. :large_orange_diamond: :star:527

## Apple TV
* [Voucher](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts. :star:491
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2256
* [TVMLKitchen](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :large_orange_diamond: :star:69
* [BrowserTV](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :large_orange_diamond: :star:205
* [Swift-GA-Tracker-for-Apple-tvOS](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :large_orange_diamond: :star:68
* [ParallaxView](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :large_orange_diamond: :star:342
* [TvOSTextViewer](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :large_orange_diamond: :star:27
* [FocusTvButton](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :large_orange_diamond: :star:35
* [TvOSMoreButton](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :large_orange_diamond: :star:24
* [TvOSPinKeyboard](https://github.com/zattoo/TvOSPinKeyboard) - PIN keyboard for tvOS :large_orange_diamond: :star:92
* [TvOSScribble](https://github.com/dcordero/TvOSScribble) - Handwriting numbers recognizer for Siri Remote :large_orange_diamond: :star:158
* [TvOSCustomizableTableViewCell](https://github.com/zattoo/TvOSCustomizableTableViewCell) - Light wrapper of UITableViewCell that allows extra customization for tvOS :large_orange_diamond: :star:17

## Architecture Patterns
* [SwiftyVIPER](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.  :large_orange_diamond: :star:56
* [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :large_orange_diamond: :star:1119
* [Viperit](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :large_orange_diamond: :star:222
* [Reactant](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS :large_orange_diamond: :star:320
* [YARCH](https://github.com/alfa-laboratory/YARCH-Examples) - More clean alternative to VIPER with unidirectional data flow (flux-like). :large_orange_diamond: :star:37


## ARKit
* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data. :large_orange_diamond:
* [Virtual Objects](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality. :star:175
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆. :large_orange_diamond: :star:520

## Authentication
* [Heimdallr.swift](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :large_orange_diamond: :star:461
* [OhMyAuth](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :large_orange_diamond: :star:53
* [AuthenticationViewController](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :large_orange_diamond: :star:234
* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift. :large_orange_diamond: :star:645
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :large_orange_diamond: :star:1936
* [SimpleAuth](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS. :star:1165
* [AlamofireOauth2](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :large_orange_diamond: :star:73
* [SwiftyOAuth](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :large_orange_diamond: :star:458
* [Simplicity](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps. :large_orange_diamond: :star:647
* [InstagramAuthViewController](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :large_orange_diamond: :star:33
* [InstagramSimpleOAuth](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app. :star:83
* [DropboxSimpleOAuth](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app. :star:42
* [BoxSimpleOAuth](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app. :star:15
* [InstagramLogin](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS. :large_orange_diamond: :star:20
* [ReCaptcha](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS. :large_orange_diamond: :star:54
* [LinkedInSignIn](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn. :large_orange_diamond: :star:9

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:10218
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews :star:10068
* [MAIKit](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS :star:138

## Cache
* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift) :large_orange_diamond: :star:1100
* [mattress](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content :large_orange_diamond: :star:452
* [Carlos](https://github.com/WeltN24/Carlos) - A simple but flexible cache :large_orange_diamond: :star:459
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :large_orange_diamond: :star:4605
* [YYCache](https://github.com/ibireme/YYCache) - High performance cache framework for iOS. :star:1634
* [Cache](https://github.com/hyperoslo/Cache) - Nothing but Cache. :large_orange_diamond: :star:1069
* [MGCacheManager](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class. :star:8
* [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify :star:1149
* [Track](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :large_orange_diamond: :star:190
* [UITableView Cache](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating. :star:64
* [RocketData](https://github.com/linkedin/RocketData) - A caching and consistency solution for immutable models. :large_orange_diamond: :star:528
* [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS :star:1847
* [Johnny](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift :large_orange_diamond: :star:27
* [Disk](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data. 🔶 :star:1774
* [Cachyr](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift :large_orange_diamond: :star:98

## Charts
* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart). :large_orange_diamond: :star:16976
* [JTChartView](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart. :star:120
* [PNChart](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS :star:9065
* [XJYChart](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight. :star:516
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library). :star:2687
* [JBChartView](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs. :star:3775
* [XYPieChart](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app. :star:1750
* [TEAChart](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart. :star:1151
* [EChart](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported. :star:644
* [FSLineChart](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS. :star:828
* [chartee](https://github.com/zhiyu/chartee) - a charting library for mobile platforms. :star:880
* [ANDLineChartView](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart. :star:415
* [TWRCharts](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code. :star:367
* [SwiftCharts](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :large_orange_diamond: :star:1564
* [FlowerChart](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :large_orange_diamond: :star:9
* [Scrollable-GraphView](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :large_orange_diamond: :star:4280
* [Dr-Charts](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C. :star:69
* [Graphs](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS. :large_orange_diamond: :star:875
* [FSInteractiveMap](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS! :star:467
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation. :star:394
* [TKRadarChart](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift :large_orange_diamond: :star:133
* [MagicPie](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1 :large_orange_diamond: 🎉 ✨✨✨✨✨ :star:530
* [PieCharts](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :large_orange_diamond: :star:342
* [CSPieChart](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :large_orange_diamond: :star:28
* [DDSpiderChart](https://github.com/dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift. :large_orange_diamond: :star:32
* [core-plot](https://github.com/core-plot/core-plot) - a 2D plotting lib which is highly customizable and capable of drawing many types of plots. :star:2524
* [ChartProgressBar](https://github.com/hadiidbouk/ChartProgressBar-iOS) - Draw a chart with progress bar style. :star:26
* [SMDiagramViewSwift](https://github.com/VRGsoftUA/SMDiagramView) - Meet cute and very flexibility library for iOS application for different data view in one circle diagram.  :star:17

## Code Quality
* [Bootstrap](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding. :star:1901
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL. :star:106
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle](https://github.com/Cue/ocstyle) - Objective-C style checker. :star:255
* [spacecommander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying. :star:795
* [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling. :star:566
* [Tailor](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs. :star:1152
* [SwiftCop](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :large_orange_diamond: :star:503
* [Trackable](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :large_orange_diamond: :star:134
* [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time. :star:2989
* [HeapInspector-for-iOS](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments :star:1651
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage. :star:2847
* [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime. :star:2767
* [Buglife](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps :star:371
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets. :star:430
* [Aardvark](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports. :star:202
* [Stats](https://github.com/shu223/Stats) - In-app memory usage monitoring. :star:149
* [GlueKit](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift. :large_orange_diamond: :star:352
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :large_orange_diamond: :star:1712
* [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods. :star:213
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :large_orange_diamond: :star:34
* [ODUIThreadGuard](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :large_orange_diamond: :star:700
* [IBAnalyzer](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :large_orange_diamond: :star:853
* [DecouplingKit](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project. :star:112
* [Clue](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure. :star:239

#### Linter
* [OCLint](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects. :star:2320
* [Taylor](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :large_orange_diamond: :star:195
* [Swiftlint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions. :large_orange_diamond: :star:8434

## Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :large_orange_diamond: :star:10579
* [ColorArt](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11. :star:131
* [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. :large_orange_diamond:[e] :star:1759
* [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. :large_orange_diamond:[e] :star:518
* [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier. :star:2957
* [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :large_orange_diamond: :star:840
* [Hue](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need. :star:2328
* [FlatUIColors](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :large_orange_diamond: :star:146
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :large_orange_diamond: :star:451
* [PFColorHash](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string. :large_orange_diamond: :star:17
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift) :large_orange_diamond: :star:428
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes :star:2941
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm). :large_orange_diamond: :star:146
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :large_orange_diamond: :star:16
* [CostumeKit](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app. :large_orange_diamond: :star:294
* [CSS3ColorsSwift](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :large_orange_diamond: :star:55
* [Colorify](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017. :large_orange_diamond: :star:78
* [ChromaColorPicker](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift. :large_orange_diamond: :star:102
* [Lorikeet](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation. :large_orange_diamond: :star:16

## Command Line
* [Swiftline](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications. :large_orange_diamond: :star:994
* [CommandLine](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :large_orange_diamond: :star:1003
* [Commander](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift :large_orange_diamond: :star:1025
* [ColorizeSwift](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift. :large_orange_diamond: :star:169
* [Guaka](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :large_orange_diamond: :star:1063
* [Marathon](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :large_orange_diamond: :star:1351
* [CommandCougar](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications. :large_orange_diamond: :star:19

## Concurrency
* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :large_orange_diamond: :star:1341
* [Concurrent](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives :large_orange_diamond: :star:145
* [Flow](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift :large_orange_diamond: :star:195
* [Brisk](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :large_orange_diamond: :star:22
* [Aojet](https://github.com/aojet/Aojet) - An actor model library for swift. :star:22
* [Overdrive](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :large_orange_diamond: :star:823
* [NSLock+Synchronized](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via CocoaPods and Carthage Framework. :large_orange_diamond:[e] :star:3
* [AsyncNinja](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :large_orange_diamond: :star:66
* [Kommander](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand. :large_orange_diamond: :star:116
* [Threadly](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift :large_orange_diamond: :star:44
* [Flow-iOS](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable :large_orange_diamond: :star:10
* [Queuer](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD). :large_orange_diamond: :star:706
* [SwiftQueue](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more. :large_orange_diamond: :star:28
* [GroupWork](https://github.com/quanvo87/GroupWork) - Easy concurrent, asynchronous tasks in Swift. :large_orange_diamond: :star:30

## Core Data
* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework. :star:71
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C. :star:1337
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code. :star:467
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data. :star:237
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data. :star:1563
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping. :star:185
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation. :star:2956
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread. :star:207
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher. :star:659
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data. :star:10598
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond: :star:1289
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond: :star:1766
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond: :star:752
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond: :star:32
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond: :star:2102
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond: :star:731
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond: :star:284
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond: :star:529
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond: :star:447
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond: :star:185
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond: :star:95
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond: :star:6
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond: :star:166
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box. :star:100
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :large_orange_diamond: :star:479
* [Records](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift. :large_orange_diamond: :star:13

## Database
* [Realm](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast. :star:11709
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac. :star:2986
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite. :star:12192
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access. :star:1647
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond: :star:430
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond: :star:449
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond: :star:51
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :large_orange_diamond: :star:2989
* [SugarRecord](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0 :large_orange_diamond: :star:1979
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond: :star:4909
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond: :star:1184
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond: :star:767
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers. :star:2609
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond: :star:111
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond: :star:148
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond: :star:80
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e] :star:101
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond: :star:270
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage. :star:37
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API. :star:36
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond: :star:64
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond: :star:21
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:43
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:19
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:67
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:17
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:31
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:23
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond: :star:211
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond: :star:163
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS. :star:5172
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠 :star:170
* [UserDefaults](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS :large_orange_diamond: :star:831
* [Default](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support :large_orange_diamond: :star:337
* [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit :large_orange_diamond: :star:716

## Data Structures / Algorithms
* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond: :star:4
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond: :star:714
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond: :star:976
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond: :star:1808
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift :large_orange_diamond: :star:86
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond: :star:52
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond: :star:614
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond: :star:57
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond: :star:3791
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :large_orange_diamond: :star:1937
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C. :star:2293
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData. :star:22
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond: :star:335
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond: :star:344
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond: :star:233
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond: :star:72
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond: :star:50
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond: :star:21
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :large_orange_diamond: :star:15720
* [Impeller](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift :large_orange_diamond: :star:93
* [Dispatch](https://github.com/alexdrone/Dispatch) - Multi-store Flux implementation in Swift :large_orange_diamond: :star:245
* [DeepDiff](https://github.com/onmyway133/DeepDiff) - Diff in Swift :large_orange_diamond: :star:415

## Date & Time

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift :large_orange_diamond: :star:2428
* [SwiftDate](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0 :large_orange_diamond: :star:3532
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2 :large_orange_diamond: :star:1511
* [DateTools](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C :star:5969
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer :large_orange_diamond: :star:937
* [DateHelper](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift :large_orange_diamond: :star:898
* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats. :star:601
* [EmojiTimeFormatter](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :large_orange_diamond: :star:73
* [Kronos](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift :large_orange_diamond: :star:234
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :large_orange_diamond: :star:230
* [10Clock](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :large_orange_diamond: :star:443
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad. :star:1717
* [AnyDate](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API. :large_orange_diamond: :star:147
* [TimeZonePicker](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app. :large_orange_diamond: :star:93
* [Time](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. :large_orange_diamond:[e] :star:652
* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library :large_orange_diamond: :star:803

## Debugging
* [Xniffer](https://github.com/vsouza/awesome-ios/issues/1841) - A swift network profiler built on top of URLSession. 🔶
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library! :large_orange_diamond: :star:2031
* [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools. :star:5523
* [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers. :star:585
* [Flex](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS. :star:8750
* [chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps. :star:6461
* [Alpha](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS. :star:671
* [AEConsole](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :large_orange_diamond: :star:78
* [GodEye](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :large_orange_diamond: :star:2875
* [NetworkEye](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request. :star:1042
* [Dotzu](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network. :star:1263
* [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations. :star:1255
* [Httper-iOS](https://github.com/MuShare/Httper-iOS) - App for developers to test REST API. :large_orange_diamond: :star:280

## EventBus
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8. :large_orange_diamond: :star:605
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS. :star:8726
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links). :star:5244
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.  :large_orange_diamond: :star:1761
* [When](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift. :large_orange_diamond: :star:129
* [then🎬](https://github.com/freshOS/then) - Elegant Async code in Swift. :large_orange_diamond: :star:606
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :large_orange_diamond: :star:1059
* [RWPromiseKit](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C :star:100
* [FutureLib](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :large_orange_diamond: :star:37
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :large_orange_diamond: :star:473
* [FutureKit](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS. :large_orange_diamond: :star:684
* [signals-ios](https://github.com/uber/signals-ios) - Typeful eventing :star:500
* [BrightFutures](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :large_orange_diamond: :star:1585
* [NoticeObserveKit](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :large_orange_diamond: :star:110
* [Hydra](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift :large_orange_diamond: :star:1320
* [Promis](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate. :large_orange_diamond: :star:70
* [Bluebird.swift](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4. :large_orange_diamond: :star:23

## Files
* [FileKit](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift. :large_orange_diamond: :star:1713
* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files. :large_orange_diamond: :star:1169
* [FileBrowser](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :large_orange_diamond: :star:1148
* [Ares](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :large_orange_diamond: :star:115
* [FileProvider](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :large_orange_diamond: :star:234
* [KZFileWatchers](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :large_orange_diamond: :star:802
* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac. :star:3290
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :large_orange_diamond: :star:525
* [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift :large_orange_diamond: :star:847

## Functional Programming
* [Forbind](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift. :large_orange_diamond: :star:44
* [Funky](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift. :large_orange_diamond: :star:12
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :large_orange_diamond: :star:634
* [Oriole](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. :large_orange_diamond:[e] :star:11
* [Prelude](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools. :large_orange_diamond: :star:322
* [Swiftx](https://github.com/typelift/Swiftx) - Functional data types and functions for any project. :large_orange_diamond: :star:185
* [Swiftz](https://github.com/typelift/Swiftz) -  Functional programming in Swift. :large_orange_diamond: :star:3053
* [OptionalExtensions](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. :large_orange_diamond:[e] :star:173
* [Hookah](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project. :large_orange_diamond: :star:56
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift :large_orange_diamond: :star:3265
* [Runes](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift. :large_orange_diamond: :star:673
* [ifAction](https://github.com/trilliwon/ifAction) - Custom if for Optional and Boolean :large_orange_diamond: [e] :star:2

## Games
* [Sage](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift. :large_orange_diamond: :star:333
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :large_orange_diamond: :star:49
* [SKTiled](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :large_orange_diamond: :star:105
* [CollectionNode](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit :large_orange_diamond: :star:45

## GCD
 * [GCDKit](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :large_orange_diamond: :star:284
 * [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :large_orange_diamond: :star:4190
 * [SwiftSafe](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy :large_orange_diamond: :star:157
 * [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue. :star:300
 * [AlecrimAsyncKit](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :large_orange_diamond: :star:66
 * [GrandSugarDispatch](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD) :large_orange_diamond: :star:31
 * [Threader](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution. :star:39
 * [Dispatch](https://github.com/JARMourato/Dispatch) - Just a tiny library to make using GCD easier and intuitive :large_orange_diamond: :star:173
 * [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :large_orange_diamond: :star:169
 * [Chronos-Swift](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :large_orange_diamond: :star:248
 * [Me](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations. :large_orange_diamond: :star:193
 * [SwiftyTask](https://github.com/CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :large_orange_diamond: :star:10

## Gesture
* [Tactile](https://github.com/delba/Tactile) - A better way to handle gestures on iOS :large_orange_diamond: :star:635
* [SwiftyGestureRecognition](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :large_orange_diamond: :star:142
* [DBPathRecognizer](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :large_orange_diamond: :star:1092
* [Sensitive](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :large_orange_diamond: :star:466
* [SplitViewDragAndDrop](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode. :large_orange_diamond: :star:290

## Graphics
* [Graphicz](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :large_orange_diamond: :star:32
* [PKCoreTechniques](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich. :star:145
* [MPWDrawingContext](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext :star:90
* [DePict](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :large_orange_diamond: :star:29
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :large_orange_diamond: :star:886
* [InkKit](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift! :large_orange_diamond: :star:353
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display. :star:374
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :large_orange_diamond: :star:1033
* [jot](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images. :star:1674
* [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating). :star:2964
* [Snowflake](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift. :large_orange_diamond: :star:817
* [HxSTLParser](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit :star:13
* [ProcessingKit](https://github.com/natmark/ProcessingKit) - Visual designing library for iOS & OSX :large_orange_diamond: :star:151

## Hardware
#### Bluetooth
* [Discovery](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background). :star:378
* [LGBluetooth](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code. :star:148
* [PeerKit](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. :large_orange_diamond:
* [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE. :large_orange_diamond: :star:1604
* [Bluetonium](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift :large_orange_diamond: :star:128
* [BlueCap](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework :large_orange_diamond: :star:442
* [Apple Family](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.  :large_orange_diamond: :star:35
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U  :large_orange_diamond: :star:445
* [Bluejay](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps. :large_orange_diamond: :star:623
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS. :star:3386
* [ExtendaBLE](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates. :star:73
* [PeerConnectivity](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :large_orange_diamond: :star:30

#### Camera
* [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects. :star:1424
* [PBJVision](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture. :star:1777
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation. :star:1186
* [SCRecorder](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing. :star:2740
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :large_orange_diamond: :star:1543
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :large_orange_diamond: :star:3418
* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :large_orange_diamond: :star:668
* [RSBarcodes_Swift](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :large_orange_diamond: :star:561
* [LLSimpleCamera](https://github.com/omergul/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS. :star:1118
* [Fusuma](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :large_orange_diamond: :star:1954
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :large_orange_diamond: :star:827
* [JVTImageFilePicker](https://github.com/mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C. :star:53
* [HorizonSDK-iOS](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library. :star:164
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters :star:1746
* [DKCamera](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. 🔶 :star:38
* [NextLevel](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :large_orange_diamond: :star:1042
* [CameraEngine](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :large_orange_diamond: :star:442
* [SwiftyCam](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :large_orange_diamond: :star:1101
* [CameraBackground](https://github.com/yonat/CameraBackground) -  Show camera layer as a background to any UIView. :large_orange_diamond: :star:17
* [Lumina](https://github.com/dokun1/Lumina) - Full service camera that takes photos, videos, streams frames, detects metadata, and streams CoreML predictions :largeorangediamond: :star:96
* [RAImagePicker](https://github.com/rallahaseh/RAImagePicker) - RAImagePicker is a protocol-oriented framework that provides custom features from the built-in Image Picker Edit. :star:7

#### Force Touch
* [QuickActions](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts) :large_orange_diamond: :star:206
* [JustPeek](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :large_orange_diamond: :star:64
* [PeekView](https://github.com/itsmeichigo/PeekView) - PeekView supports peek, pop and preview actions for iOS devices without 3D Touch capibility. 🔶 :star:111

#### iBeacon
* [Proxitee](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences. :star:15
* [OWUProximityManager](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth. :star:357
* [Vicinity](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background. :star:362
* [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon. :star:815
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. 🔶 :star:134

#### Location
* [IngeoSDK](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS. :star:92
* [LocationManager](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously. :star:2187
* [SwiftLocation](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :large_orange_diamond: :star:1572
* [SOMotionDetector](https://github.com/arturdev/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration. :star:1002
* [LocationPicker](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :large_orange_diamond: :star:296
* [BBLocationManager](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS. :star:78
* [set-simulator-location](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :large_orange_diamond: :star:197

#### Other Hardware
* [MotionKit](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple. :star:963
* [DarkLightning](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and macOS. :star:181
* [Deviice](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties) 🔶 :star:21
* [DeviceKit](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :large_orange_diamond: :star:1757
* [Luminous](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :large_orange_diamond: :star:191
* [Device](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :large_orange_diamond: :star:1039
* [WatchShaker](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :large_orange_diamond: :star:151
* [WatchCon](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️ :star:25
* [TapticEngine](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :large_orange_diamond: :star:167
* [UIDeviceComplete](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces. :large_orange_diamond: :star:225
* [NFCNDEFParse](https://github.com/jvk75/NFCNDEFParse) - NFC Forum Well Known Type Data Parser for iOS11 and Core NFC. :large_orange_diamond: :star:3

## Layout
* [FlexboxLayout](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :large_orange_diamond: :star:316
* [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax. :star:15959
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code. :star:1510
* [Façade](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative. :star:710
* [PureLayout](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & macOS Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible. :star:6820
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & macOS. :large_orange_diamond: :star:11806
* [Cartography](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :large_orange_diamond: :star:6123
* [AutoLayoutPlus](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :large_orange_diamond: :star:28
* [Neon](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework. :large_orange_diamond: :star:4180
* [MisterFusion](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :large_orange_diamond: :star:266
* [SwiftBox](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :large_orange_diamond: :star:806
* [ManualLayout](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. :large_orange_diamond:[e] :star:274
* [Stevia](https://github.com/freshOS/Stevia) - Elegant view layout for iOS. :large_orange_diamond: :star:2182
* [Manuscript](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :large_orange_diamond: :star:78
* [FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating :star:8493
* [SwiftAutoLayout](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :large_orange_diamond: :star:648
* [FormationLayout](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily. :large_orange_diamond: :star:52
* [SwiftyLayout](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :large_orange_diamond: :star:15
* [Swiftstraints](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :large_orange_diamond: :star:97
* [SwiftBond](https://github.com/ReactiveKit/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :large_orange_diamond: :star:3370
* [Restraint](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift :large_orange_diamond: :star:74
* [EasyPeasy](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy  :large_orange_diamond: :star:1583
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! :large_orange_diamond:
* [Anchorman](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :large_orange_diamond: :star:62
* [LayoutKit](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :large_orange_diamond: :star:2360
* [MarkupKit](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications :star:448
* [Relayout](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :large_orange_diamond: :star:577
* [Anchorage](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :large_orange_diamond: :star:315
* [Compose](https://github.com/VivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :large_orange_diamond: :star:127
* [BrickKit](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :large_orange_diamond: :star:581
* [Framezilla](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :large_orange_diamond: :star:84
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :large_orange_diamond: :star:2224
* [MyLinearLayout](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. :star:2661
* [SugarAnchor](https://github.com/ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable. :large_orange_diamond: :star:20
* [Anchors](https://github.com/onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+ :large_orange_diamond: :star:113
* [PinLayout](https://github.com/mirego/PinLayout) - Extremely Fast views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable. 🔶 :star:783
* [SnapLayout](https://github.com/sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. 🔶[e] :star:9
* [Cupcake](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS. :large_orange_diamond: :star:176
* [MiniLayout](https://github.com/yonat/MiniLayout) - Minimal AutoLayout convenience layer. Program constraints succinctly. :large_orange_diamond: :star:4
* [Bamboo](https://github.com/wordlessj/Bamboo) - Bamboo makes Auto Layout (and manual layout) elegant and concise. :large_orange_diamond: :star:46
* [FlexLayout](https://github.com/layoutBox/FlexLayout) - FlexLayout gently wraps the highly optimized [facebook/yoga](https://github.com/facebook/yoga) flexbox implementation in a concise, intuitive & chainable syntax. 🔶 :star:204
* [Layout](https://github.com/schibsted/layout) - A declarative UI framework for iOS :large_orange_diamond: :star:1229
* [CGLayout](https://github.com/k-o-d-e-n/CGLayout) - Powerful autolayout framework based on constraints, that can manage UIView(NSView), CALayer and not rendered views. Not Apple Autolayout wrapper. 🔶 :star:21
* [YogaKit](https://github.com/facebook/yoga/tree/master/YogaKit) - Powerful layout engine which implements Flexbox. Developed and maintained by Facebook.
* [FlightLayout](https://github.com/AntonTheDev/FlightLayout) -  Balanced medium between manual layout and auto-layout. Great for calculating frames for complex animations. :star:21
* [QLayout](https://github.com/josejuanqm/QLayout) - AutoLayout Utility for iOS. 🔶 :star:1

## Localization
* [Hodor](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App. :star:496
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :large_orange_diamond: :star:542
* [Rubustrings](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files :star:53
* [BartyCrouch](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :large_orange_diamond: :star:330
* [LocalizationKit](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission. :star:938
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :large_orange_diamond: :star:1619
* [LocalizedView](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file. :star:8
* [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:48
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language. :star:103
* [IBLocalizable](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :large_orange_diamond: :star:399
* [nslocalizer](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings :star:125
* [L10n-swift](https://github.com/Decybel07/L10n-swift) - Localization of an application with ability to change language "on the fly" and support for plural forms in any language. :large_orange_diamond: :star:47

## Logging
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :large_orange_diamond: :star:1119
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS. :star:9873
* [NSLogger](https://github.com/fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on macOS, iOS and Android. :star:4159
* [QorumLogs](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. :large_orange_diamond:
* [Log](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :large_orange_diamond: :star:697
* [Rainbow](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers. :large_orange_diamond: :star:963
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :large_orange_diamond: :star:3317
* [SwiftyTextTable](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :large_orange_diamond: :star:117
* [Watchdog](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :large_orange_diamond: :star:1469
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :large_orange_diamond: :star:2791
* [puree](https://github.com/cookpad/puree-ios) - A log collector for iOS :star:152
* [Colors](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! :large_orange_diamond:[e] :star:25
* [Loggerithm](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :large_orange_diamond: :star:266
* [AELog](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :large_orange_diamond: :star:14
* [ReflectedStringConvertible](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :large_orange_diamond: :star:49
* [Evergreen](https://github.com/nilsleiffischer/Evergreen) - Most natural Swift logging :large_orange_diamond: :star:69
* [SwiftTrace](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :large_orange_diamond: :star:126
* [Willow](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :large_orange_diamond: :star:1008
* [Bugfender](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps. :star:37
* [LxDBAnything](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly! :star:420
* [XLTestLog](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console :star:60
* [XLFacility](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for macOS & iOS (includes database, Telnet and HTTP servers)
* [Atlantis](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :large_orange_diamond: :star:201
* [StoryTeller](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important. :star:8
* [LumberMill](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0 :star:2
* [TinyConsole](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :large_orange_diamond: :star:1737
* [Lighty](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :large_orange_diamond: :star:37
* [JustLog](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :large_orange_diamond: :star:203
* [Twitter Logging Service](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients. :star:167
* [Reqres](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :large_orange_diamond: :star:24

## Machine Learning
* [Swift-Brain](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :large_orange_diamond: :star:303
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :large_orange_diamond: :star:649
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/ios) - The official Google-built powerful neural network library port for iOS.
* [Bender](https://github.com/xmartlabs/Bender) - Easily craft fast Neural Networks. Use TensorFlow models. Metal under the hood. :star:1339
* [Caffe2](https://github.com/caffe2/caffe2) - Lightweight, modular, and scalable deep learning framework. :star:6834
* [CoreML-samples](https://github.com/ytakzk/CoreML-samples) - Sample code for Core ML using ResNet50 provided by Apple and a custom model generated by coremltools. :large_orange_diamond: :star:19
* [Revolver](https://github.com/petrmanek/Revolver) - A framework for building fast genetic algorithms in Swift. Comes with modular architecture, pre-implemented operators and loads of examples. :large_orange_diamond: :star:15
* [CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models. :star:2156
* [Serrano](https://github.com/pcpLiu/Serrano) - A deep learning library for iOS and macOS. :large_orange_diamond: :star:30

## Maps
* [Route-me](https://github.com/route-me/route-me) - Open source map library for iOS. :star:1310
* [NAMapKit](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework. :star:255
* [Mapbox GL](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS. :star:2367
* [CMMapLauncher](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications. :star:193
* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine. :large_orange_diamond: :star:892
* [PXGoogleDirections](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :large_orange_diamond: :star:210
* [Cluster](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering. :large_orange_diamond: :star:789
* [JDSwiftHeatMap](https://github.com/jamesdouble/JDSwiftHeatMap) - JDSwiftMap is an IOS Native MapKit Library. You can easily make a highly customized HeatMap. :large_orange_diamond: :star:49
* [ClusterKit](https://github.com/hulab/ClusterKit) - An iOS map clustering framework targeting MapKit, Google Maps and Mapbox. :star:244

## Math
* [Euler](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation :large_orange_diamond: :star:871
* [SwiftMath](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :large_orange_diamond: :star:144
* [Arithmosophi](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :large_orange_diamond: :star:56
* [Surge](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :large_orange_diamond: :star:3882
* [Upsurge](https://github.com/aleph7/Upsurge) - Swift math :large_orange_diamond: :star:128
* [Swift-MathEagle](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :large_orange_diamond: :star:31
* [iosMath](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS. :star:704
* [swift-pons](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :large_orange_diamond: :star:211
* [BigInt](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic in pure Swift :large_orange_diamond: :star:358
* [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :large_orange_diamond: :star:487
* [VectorMath](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :large_orange_diamond: :star:166
* [Expression](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :large_orange_diamond: :star:335
* [Metron](https://github.com/toineheuvelmans/Metron) - Metron is a comprehensive collection of geometric functions and types that extend the 2D geometric primitives provided by CoreGraphics. :large_orange_diamond: :star:927
* [NumericAnnex](https://github.com/xwu/NumericAnnex) - NumericAnnex supplements the numeric facilities provided in the Swift standard library with generic integer algorithms, complex numbers, rational numbers, and pseudorandom number generators (written in, and for, Swift 4) :large_orange_diamond: :star:30

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :large_orange_diamond: :star:4738
* [EZAudio](https://github.com/syedhali/EZAudio) - An iOS/macOS audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations. :star:4188
* [novocaine](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and macOS. :star:2096
* [QHSpeechSynthesizerQueue](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech). :star:27
* [Cephalopod](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :large_orange_diamond: :star:79
* [Chirp](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :large_orange_diamond: :star:304
* [Beethoven](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :large_orange_diamond: :star:311
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. :large_orange_diamond:
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :large_orange_diamond: :star:325
* [TuningFork](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :large_orange_diamond: :star:352
* [MusicKit](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift :large_orange_diamond: :star:468
* [SubtleVolume](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :large_orange_diamond: :star:610
* [NVDSP](https://github.com/bartolsthoorn/NVDSP) - iOS/macOS DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:70
* [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface. :star:447
* [TheAmazingAudioEngine2](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to. :star:361
* [InteractivePlayerView](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :large_orange_diamond: :star:234
* [ESTMusicIndicator](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :large_orange_diamond: :star:358
* [QuietModemKit](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. CocoaPods and Carthage compatible. :large_orange_diamond: :star:548
* [BPMAnalyser](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond: :star:13
* [PandoraPlayer](https://github.com/AppliKeySolutions/PandoraPlayer) - A lightweight music player for iOS, based on AudioKit and completely written in Swift :large_orange_diamond: :star:628
* [SonogramView](https://github.com/Luccifer/SonogramView) - Audio visualisation of song :star:8

#### GIF
* [YLGIFImage](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory. :star:1701
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS :star:6339
* [gifu](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond: :star:1909
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling :star:1038
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond: :star:577
* [SwiftGif](https://github.com/bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond: :star:765
* [APNGKit](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond: :star:1316
* [YYImage](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more. :star:1106
* [AImage](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond: :star:934
* [NSGIF2](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url. :star:61
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond: :star:727

#### Image
* [GPU Image](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. :star:16864
* [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - iOS UIImage processing functions using the vDSP/Accelerate framework for speed. :star:377
* [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI. :star:944
* [SDWebImage](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category. :star:19222
* [DFImageManager](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession. :star:1220
* [MapleBacon](https://github.com/JanGorman/MapleBacon) - An image download and caching library for iOS written in Swift. :large_orange_diamond: :star:201
* [NYTPhotoViewer](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer. :star:2302
* [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer. :star:2495
* [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController) - Interactive iOS image viewer. :star:2288
* [Concorde](https://github.com/contentful-labs/Concorde/) - Download and decode progressive JPEGs.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects. :star:1932
* [YXTMotionView](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling. :star:79
* [PINRemoteImage](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher. :star:3248
* [SABlurImageView](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :large_orange_diamond: :star:481
* [FastImageCache](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling. :star:7717
* [BKAsciiImage](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art :star:406
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire. :large_orange_diamond: :star:2805
* [Nuke](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating :large_orange_diamond: :star:2552
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :large_orange_diamond: :star:1963
* [YYWebImage](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF). :star:3027
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation. :star:1932
* [Silo](https://github.com/josejuanqm/Silo) - Image loading framework with loaders. :large_orange_diamond: :star:12
* [Ody](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :large_orange_diamond: :star:43
* [Banana](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface. :large_orange_diamond: :star:16
* [JDSwiftAvatarProgress](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :large_orange_diamond: :star:83
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :large_orange_diamond: :star:10743
* [EBPhotoPages](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser. :star:1633
* [UIImageView-BetterFace-Swift](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :large_orange_diamond: :star:446
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :large_orange_diamond: :star:340
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift :large_orange_diamond: :star:2086
* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :large_orange_diamond: :star:265
* [ImageScout](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :large_orange_diamond: :star:856
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :large_orange_diamond: :star:356
* [Agrume](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :large_orange_diamond: :star:230
* [PASImageView](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :large_orange_diamond: :star:166
* [Navi](https://github.com/nixzhu/Navi) - Focus on avatar caching. :large_orange_diamond: :star:116
* [SwiftPhotoGallery](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :large_orange_diamond: :star:89
* [MetalAcc](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift.:large_orange_diamond: :star:198
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections. :star:7963
* [UIImageColors](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. :large_orange_diamond:[e] :star:1757
* [CDFlipView](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects. :star:94
* [GPUImage2](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :large_orange_diamond: :star:3498
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :large_orange_diamond: :star:404
* [ImageButter](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth :star:382
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift :large_orange_diamond: :star:1443
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework :star:782
* [CLImageViewPopup](https://github.com/vinbhai4u/CLImageViewPopup/) - A simple Image full screen pop up :large_orange_diamond:
* [APKenBurnsView](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :large_orange_diamond: :star:53
* [Moa](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. :large_orange_diamond:[e] :star:273
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :large_orange_diamond: :star:125
* [ImageViewer](https://github.com/MailOnline/ImageViewer) - An image viewer à la Twitter :large_orange_diamond: :star:1675
* [FaceAware](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :large_orange_diamond: :star:2202
* [SwiftyAvatar](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard :star:170
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond: :star:64
* [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :large_orange_diamond: :star:1371
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :large_orange_diamond: :star:555
* [ImageSlideshow](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :large_orange_diamond: :star:747
* [Imaginary](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :large_orange_diamond: :star:397
* [PPAssetsActionController](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :large_orange_diamond: :star:53
* [Vulcan](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :large_orange_diamond: :star:275
* [FacebookImagePicker](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker written in Swift. :large_orange_diamond: :star:106
* [Lightbox](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :large_orange_diamond: :star:580
* [AvatarImageView](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :large_orange_diamond: :star:221
* [Ebblink](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time. :star:3
* [Sharaku](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController. :large_orange_diamond: :star:1301
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :large_orange_diamond: :star:770
* [Twitter Image Pipline](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application. :star:1466
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :large_orange_diamond: :star:1487
* [FlexibleImage](https://github.com/kawoou/FlexibleImage) - A simple way to play with image! :large_orange_diamond: :star:645
* [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook. :large_orange_diamond: :star:1125
* [YapImageManager](https://github.com/yapstudios/YapImageManager) - A high-performance image downloader written in Swift, powered by YapDatabase. :large_orange_diamond: :star:52
* [PhotoEditorSDK](https://www.photoeditorsdk.com) - A fully customizable photo editor for your app. :large_orange_diamond:
* [SimpleImageViewer](https://github.com/aFrogleap/SimpleImageViewer) - A snappy image viewer with zoom and interactive dismissal transition. :large_orange_diamond: :star:224
* [AZImagePreview](https://github.com/Minitour/AZImagePreview) - A framework that makes image viewing easy. :large_orange_diamond: :star:13
* [FaceCropper](https://github.com/KimDarren/FaceCropper) - Crop faces, inside of your image, with iOS 11 Vision api :large_orange_diamond: :star:403
* [Paparazzo](https://github.com/avito-tech/Paparazzo) - Custom iOS camera and photo picker with editing capabilities :large_orange_diamond: :star:519
* [ZImageCropper](https://github.com/ZaidPathan/ZImageCropper) - A Swift  project to crop image in any shape. :large_orange_diamond: :star:35
* [InitialsImageView](https://github.com/bachonk/InitialsImageView) - An UIImageView extension that generates letter initials as a placeholder for user profile images, with a randomized background color. :large_orange_diamond: :star:93
* [DTPhotoViewerController](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController, inspired by Facebook photo viewer. :large_orange_diamond: :star:72
* [LetterAvatarKit](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars written in Swift. :large_orange_diamond: :star:53
* [AXPhotoViewer](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos :large_orange_diamond: :star:263
* [TJProfileImage](https://github.com/tejas-ardeshna/TJProfileImage) - Live rendering of componet’s properties in Interface Builder. :large_orange_diamond: :star:30
* [Viewer](https://github.com/bakkenbaeck/Viewer) - Image viewer (or Lightbox) with support for local and remote videos and images :large_orange_diamond: :star:315
* [OverlayComposite](https://github.com/aaronjsutton/OverlayComposite) - An asynchronous, multithreaded, image compositing framework written in Swift. :large_orange_diamond: :star:9
* [MCScratchImageView](https://github.com/Minecodecraft/MCScratchImageView) - A custom ImageView that is used to cover the surface of other view like a scratch card, user can swipe the mulch to see the view below :large_orange_diamond: :star:270

#### Media Processing
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :large_orange_diamond: :star:3032
* [QR Code Scanner](https://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift. :large_orange_diamond: :star:501
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :large_orange_diamond: :star:2467

#### PDF
* [Reader](https://github.com/vfr/Reader) - PDF Reader Core for iOS. :star:3988
* [UIView 2 PDF](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB :star:28
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond: :star:1560
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond: :star:316
* [SimplePDF](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond: :star:107
* [SwiftPDFGenerator](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond: :star:12
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond: :star:161

#### Streaming
* [HaishinKit.swift](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :large_orange_diamond: :star:891
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for macOS and iOS. :star:1718
* [Jukebox](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :large_orange_diamond: :star:427
* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate :star:2894
* [Airstream](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay. :star:324
* [OTAcceleratorCore](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox. :star:20

#### Video
* [VIMVideoPlayer](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes. :star:268
* [MobilePlayer](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS. :star:2334
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2256
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :large_orange_diamond: :star:475
* [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery :star:1944
* [PlayerView](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :large_orange_diamond: :star:97
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:70
* [AVPlayerViewController-Subtitles](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e] :star:90
* [MPMoviePlayerController-Subtitles](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e] :star:173
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress. :star:3946
* [Player](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :large_orange_diamond: :star:1001
* [BMPlayer](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :large_orange_diamond: :star:883
* [VideoPager](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available. :large_orange_diamond: :star:33
* [ios-360-videos](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer. :star:198
* [swift-360-videos](https://github.com/team-pie/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360. :star:56
* [ABMediaView](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner. :star:45
* [PryntTrimmerView](https://github.com/prynt/PryntTrimmerView) - A set of UI elements to trim, crop and select frames inside a video. :large_orange_diamond: :star:123
* [VGPlayer](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player in Swift,Support play local and network,Background playback mode. :large_orange_diamond: :star:209
* [YoutubeKit](https://github.com/rinov/YoutubeKit) - A video player that fully supports Youtube IFrame API and YoutubeDataAPI for easily create a Youtube app. :large_orange_diamond: :star:162

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application. :star:139
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS. :star:5362
* [Chatto](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :large_orange_diamond: :star:3126
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. :star:8234
* [MessageKit](https://github.com/MessageKit/MessageKit) - Eventually, a Swift re-write of JSQMessagesViewController :large_orange_diamond: :star:1491
* [NoChat](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS. :large_orange_diamond: :star:504
* [NMessenger](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :large_orange_diamond: :star:2151
* [Atlas](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer. :star:3741
* [Messenger](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support. :star:2932
* [OTTextChatAccelerator](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices. :star:10
* [chat-sdk-ios](https://github.com/chat-sdk/chat-sdk-ios) - Chat SDK iOS - Open Source Mobile Messenger. :star:406

## Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and macOS networking framework. :star:30568
* [RestKit](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun. :star:10203
* [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library. :star:400
* [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone. :star:5794
* [Overcoat](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun. :star:1139
* [ROADFramework](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible. :star:50
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :large_orange_diamond: :star:26589
* [Transporter](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond: :star:437
* [CDZPinger](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping. :star:48
* [NSRails](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails. :star:528
* [NKMultipeer](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :large_orange_diamond: :star:14
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS. :star:9596
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :large_orange_diamond: :star:4610
* [OctopusKit](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs. :star:1
* [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. :large_orange_diamond: :star:7896
* [TWRDownloadManager](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files. :star:339
* [HappyDns](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record. :star:325
* [Bridge](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond: :star:93
* [TRON](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond: :star:424
* [EVCloudKitDao](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond: :star:520
* [EVURLCache](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond: :star:258
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond: :star:1707
* [Pitaya](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond: :star:851
* [Just](https://github.com/JustHTTP/Just) - Swift HTTP for Humans :large_orange_diamond: :star:1086
* [agent](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS :large_orange_diamond: :star:611
* [Reach](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond: :star:427
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond: :star:1734
* [Netdiag](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS. :star:69
* [AFNetworkingHelper](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively :star:18
* [NetKit](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond: :star:4
* [RealReachability](https://github.com/dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do. :star:2505
* [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond: :star:1941
* [NetworkKit](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond: :star:26
* [APIKit](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond: :star:1330
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond: :star:257
* [SPTDataLoader](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client. :star:581
* [SWNetworking](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, macOS and tvOS networking library. :star:21
* [Networking](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :large_orange_diamond: :star:1077
* [SOAPEngine](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, macOS app and AppleTV app. :star:435
* [Swish](https://github.com/thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond: :star:356
* [Malibu](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond: :star:319
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking. :star:5002
* [UnboxedAlamofire](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond: :star:59
* [MMLanScan](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library :star:232
* [Domainer](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table :star:6
* [Restofire](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond: :star:151
* [AFNetworking+RetryPolicy](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking. :star:157
* [SwiftyZeroMQ](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚ :star:27
* [Nikka](https://github.com/JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚ :star:12
* [XMNetworking](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking. :star:719
* [Merhaba](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices. :star:34
* [DBNetworkStack](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond: :star:20
* [EFInternetIndicator](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond: :star:112
* [AFNetworking-Synchronous](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x. :star:144
* [QwikHttp](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶 :star:1
* [NetClient](https://github.com/intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :large_orange_diamond: :star:75
* [WANetworkRouting](https://github.com/Wasappli/WANetworkRouting) - An iOS library to route API paths to objects on client side with request, mapping, routing and auth layers :star:10
* [Reactor](https://github.com/MailOnline/Reactor) - Powering your RAC architecture :large_orange_diamond: :star:178
* [SWNetworking](https://github.com/isamankumara/skywite) - Powerful high-level iOS, macOS and tvOS networking library. from the creator of SWNetworking 🔶 :star:5
* [Digger](https://github.com/cornerAnt/Digger) - Digger is a lightweight download framework that requires only one line of code to complete the file download task :star:378
. :large_orange_diamond:
* [Ciao](https://github.com/AlTavares/Ciao) - Publish and discover services using mDNS(Bonjour, Zeroconf). :large_orange_diamond: :star:21
* [PerfectAPIClient](https://github.com/SvenTiigi/PerfectAPIClient) - An API Client based on a network abstraction layer for the Perfect Server-Side Swift Framework 🔶 :star:18
* [Bamboots](https://github.com/mmoaay/Bamboots) - Bamboots is a network request framework based on Alamofire, aiming at making network request easier for business development :large_orange_diamond: :star:349

#### Email

* [Mail Core 2](https://github.com/MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP. :star:1716
* [Postal](https://github.com/snipsco/Postal) - A swift framework providing simple access to common email providers. :large_orange_diamond: :star:474

#### Representations

 * [apollo-ios](https://github.com/apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :large_orange_diamond: :star:948
 * [JSONRPCKit](https://github.com/bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :large_orange_diamond: :star:99
 * [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift :large_orange_diamond: :star:831

## Notifications

#### Push Notifications
* [Orbiter](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS. :star:699
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS). :star:3986
* [FBNotifications](https://github.com/facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework. :star:462
* [NWPusher](https://github.com/noodlewerk/NWPusher) - macOS and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications](https://github.com/acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator :star:1241

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
* [Pushkin](https://github.com/Nordeus/pushkin) - Free and open-source. :star:168
* [Pusher](https://pusher.com/push-notifications) - Free and unlimited.
* [Swrve](https://www.swrve.com)

#### Local Notifications
* [DLLocalNotifications](https://github.com/d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :large_orange_diamond: :star:70

## Optimization
* [Unreachable](https://github.com/nvzqz/Unreachable) - Unreachable code path optimization hint for Swift. :large_orange_diamond: :star:87

## Parsing

#### CSV
* [CSwiftV](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond: :star:127

#### JSON
* [JSON-Framework](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C. :star:3804
* [Mantle](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch. :star:10864
* [Groot](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects. :star:487
* [PropertyMapper](https://github.com/krzysztofzablocki/PropertyMapper) - Data mapping and validation with minimal amount of code. :star:1128
* [JSONModel](https://github.com/JSONModel/JSONModel) - Magical Data Modeling Framework for JSON. Create rapidly powerful, atomic and smart data model classes. :star:6416
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond: :star:16196
* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast. :star:528
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :large_orange_diamond: :star:6745
* [JASON](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators. :large_orange_diamond: :star:1012
* [Gloss](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift. :large_orange_diamond: :star:1598
* [Cereal](https://github.com/Weebly/Cereal) - Swift object serialization :large_orange_diamond: :star:378
* [SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :large_orange_diamond: :star:678
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :large_orange_diamond: :star:613
* [Tailor](https://github.com/zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :large_orange_diamond: :star:245
* [alexander](https://github.com/hodinkee/alexander) - An extremely simple JSON helper written in Swift. :large_orange_diamond: :star:36
* [Freddy](https://github.com/bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :large_orange_diamond: :star:1115
* [mapper](https://github.com/lyft/mapper) - A JSON deserialization library for Swift :large_orange_diamond: :star:1043
* [AlamofireJsonToObjects](https://github.com/evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :large_orange_diamond: :star:152
* [Jay](https://github.com/DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & macOS ready. :large_orange_diamond: :star:128
* [YYModel](https://github.com/ibireme/YYModel) - High performance model framework for iOS/macOS. :star:3300
* [Alembic](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond: :star:103
* [Wrap](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond: :star:591
* [Arrow 🏹](https://github.com/freshOS/Arrow) - Elegant JSON Parsing in Swift. :large_orange_diamond: :star:262
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :large_orange_diamond: :star:1076
* [Genome](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux) :large_orange_diamond: :star:790
* [Unbox](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond: :star:1802
* [JSONJoy-Swift](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond: :star:352
* [LazyObject](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond: :star:10
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - JSONExport is a desktop application for macOS which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :large_orange_diamond: :star:3051
* [Elevate](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond: :star:611
* [MJExtension](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file. :star:7427
* [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond: :star:2112
* [GuardedSwiftyJSON](https://github.com/wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initalizers for data models. :large_orange_diamond: :star:4
* [JAYSON](https://github.com/muukii/JAYSON) - Strict and Scalable JSON library. :large_orange_diamond: :star:224
* [HandyJSON](https://github.com/alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :large_orange_diamond: :star:1699
* [Marshal](https://github.com/utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based). :star:612
* [Motis](https://github.com/mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC). :star:247
* [NSTEasyJSON](https://github.com/bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON). :star:6
* [Serpent](https://github.com/nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :large_orange_diamond: :star:274
* [MagicMapper](https://github.com/adrianitech/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :large_orange_diamond: :star:25
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - This project brings FlatBuffers (an efficient cross platform serialization library) to Swift. :large_orange_diamond: :star:477
* [CodableAlamofire](https://github.com/Otbivnoe/CodableAlamofire) - An extension for Alamofire that converts JSON data into Decodable objects (Swift 4). :large_orange_diamond: :star:533
* [WAMapping](https://github.com/Wasappli/WAMapping) - A library to turn dictionary into object and vice versa for iOS. Designed for speed! :star:9

#### XML & HTML
* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond: :star:722
* [Ji](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond: :star:742
* [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS :star:2211
* [AlamofireXmlToObjects](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond: :star:62
* [Fuzi](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond: :star:640
* [Kanna](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for macOS/iOS. :large_orange_diamond:
* [SwiftyXMLParser](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :large_orange_diamond: :star:154
* [HTMLKit](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs. :star:114
* [SWXMLHash](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond: :star:912
* [SwiftyXML](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 3 :large_orange_diamond: :star:24

#### Other Parsing
* [WKZombie](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/macOS to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond: :star:898
* [URLPreview](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond: :star:182
* [FeedKit](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond: :star:408
* [Erik](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond: :star:271
* [URLEmbeddedView](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :large_orange_diamond: :star:436
* [SwiftyConfiguration](https://github.com/ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :large_orange_diamond: :star:104
* [JSONFeed](https://github.com/totocaster/JSONFeed) - Swift parser for JSON Feed, a format similar to RSS and Atom but in JSON. :large_orange_diamond: :star:27
* [SwiftCssParser](https://github.com/100mango/SwiftCssParser) - A Powerful , Extensible CSS Parser written in pure Swift. :large_orange_diamond: :star:233

## Passbook
* [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+. :star:212
* [Dubai](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes. :star:317
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :large_orange_diamond: :star:671
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://moltin.com/ios-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit](https://github.com/MosheBerman/PatronKit) - A framework to add patronage to your apps. :large_orange_diamond: :star:360
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and macOS 9.0+ :large_orange_diamond: :star:2705
* [InAppFramework](https://github.com/sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :large_orange_diamond: :star:38
* [SwiftInAppPurchase](https://github.com/rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :large_orange_diamond: :star:17
* [monza](https://github.com/gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions :star:93
* [EasyIAPs](https://github.com/aaalveee/EasyIAPs) - An easy way to manage In App Purchases :star:5
* [PayPal](https://github.com/paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal. :star:895
* [card.io-iOS-SDK](https://github.com/card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps :star:1963
* [SwiftLuhn](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :large_orange_diamond: :star:108
* [ObjectiveLuhn](https://github.com/MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm :star:119
* [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases :star:2082
* [MFCard](https://github.com/mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI :star:278
* [TPInAppReceipt](https://github.com/tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :large_orange_diamond: :star:36
* [iCard](https://github.com/eliakorkmaz/iCard) - Bank Card Generator with Swift using SnapKit DSL :large_orange_diamond: :star:255

## Permissions
* [Proposer](https://github.com/nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :large_orange_diamond: :star:756
* [ICanHas](https://github.com/wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :large_orange_diamond: :star:82
* [VWWPermissionKit](https://github.com/zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS. :star:133
* [ISHPermissionKit](https://github.com/iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions. :star:582
* [JLPermissions](https://github.com/jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request. :star:403
* [ClusterPrePermissions](https://github.com/rsattar/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request. :star:1214
* [Permission](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS :large_orange_diamond: :star:2327
* [STLocationRequest](https://github.com/SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :large_orange_diamond: :star:560
* [PAPermissions](https://github.com/pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :large_orange_diamond: :star:666
* [AREK](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :large_orange_diamond: :star:808
* [RequestPermission](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI :large_orange_diamond: :star:1717

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io](https://github.com/openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google. :star:309

## Reactive Programming
* [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift :large_orange_diamond: :star:12070
* [RxOptional](https://github.com/thanegill/RxOptional) - RxSwift extentions for Swift optionals and "Occupiable" types :large_orange_diamond: :star:7
* [ReactiveTask](https://github.com/Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :large_orange_diamond: :star:123
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Streams of values over time. :star:18270
* [RxMediaPicker](https://github.com/RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :large_orange_diamond: :star:95
* [ReactiveCoreData](https://github.com/apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world. :star:274
* [ReSwift](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :large_orange_diamond: :star:4658
* [ReactiveKit](https://github.com/ReactiveKit/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :large_orange_diamond: :star:927
* [RxPermission](https://github.com/sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :large_orange_diamond: :star:200
* [RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :large_orange_diamond: :star:846
* [RxRealm](https://github.com/RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :large_orange_diamond: :star:583
* [RxMultipeer](https://github.com/RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :large_orange_diamond: :star:49
* [RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit) - iOS & macOS Bluetooth library for RxSwift :large_orange_diamond: :star:687
* [RxGesture](https://github.com/RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :large_orange_diamond: :star:511
* [NSObject-Rx](https://github.com/RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :large_orange_diamond: :star:273
* [RxCoreData](https://github.com/RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :large_orange_diamond: :star:84
* [RxAutomaton](https://github.com/inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :large_orange_diamond: :star:606
* [ReactiveArray](https://github.com/Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :large_orange_diamond: :star:55
* [Interstellar](https://github.com/JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :large_orange_diamond: :star:971
* [ReduxSwift](https://github.com/lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :large_orange_diamond: :star:33
* [Aftermath](https://github.com/hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :large_orange_diamond: :star:59
* [RxKeyboard](https://github.com/RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :large_orange_diamond: :star:661
* [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON. :star:4886
* [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group :star:1710
* [Listenable](https://github.com/msaps/Listenable) - Swift object that provides an observable platform. :large_orange_diamond: :star:4
* [Reactor](https://github.com/ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :large_orange_diamond: :star:138
* [Snail](https://github.com/UrbanCompass/Snail) - An observables framework for Swift :large_orange_diamond: :star:74
* [RxWebSocket](https://github.com/fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :large_orange_diamond: :star:36
* [ACKReactiveExtensions](https://github.com/AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :large_orange_diamond: :star:11
* [ReactiveLocation](https://github.com/AckeeCZ/ReactiveLocation) - CoreLocation made reactive :large_orange_diamond: :star:15
* [Hanson](https://github.com/blendle/Hanson) - Lightweight observations and bindings in Swift, with support for KVO and NotificationCenter. :large_orange_diamond: :star:465
* [Observable](https://github.com/roberthein/Observable) - The easiest way to observe values in Swift. 🔶 :star:162
* [SimpleApiClient](https://github.com/jaychang0917/SimpleApiClient-ios) - A configurable api client based on Alamofire4 and RxSwift4 for iOS. 🔶 :star:65
* [VueFlux](https://github.com/ra1028/VueFlux) - Unidirectional Data Flow State Management Architecture for Swift - Inspired by Vuex and Flux 🔶 :star:129
* [RxAnimated](https://github.com/RxSwiftCommunity/RxAnimated) - Animated RxCocoa bindings :star:339

#### React-Like
* [Render](https://github.com/alexdrone/Render) - Swift and UIKit a la React. :large_orange_diamond: :star:1693
* [Katana](https://github.com/BendingSpoons/katana-swift) - Swift apps a la React and Redux. :large_orange_diamond: :star:1644
* [TemplateKit](https://github.com/mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :large_orange_diamond: :star:134
* [Komponents 📦](https://github.com/freshOS/Komponents) - React-inspired UIKit Components. :large_orange_diamond: :star:157

## Reflection
* [Reflection](https://github.com/Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :large_orange_diamond: :star:378
* [Reflect](https://github.com/CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :large_orange_diamond: :star:307
* [EVReflection](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :large_orange_diamond: :star:775
* [JSONNeverDie](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :large_orange_diamond: :star:476
* [SwiftKVC](https://github.com/bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :large_orange_diamond: :star:107

## Regex
* [Regex](https://github.com/sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :large_orange_diamond: :star:458
* [SwiftRegex](https://github.com/kasei/SwiftRegex) - Perl-like Regex =~ operator for Swift :large_orange_diamond: :star:117
* [PySwiftyRegex](https://github.com/cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :large_orange_diamond: :star:212
* [Regex](https://github.com/crossroadlabs/Regex) - Regular expressions for swift :large_orange_diamond: :star:219
* [Regex](https://github.com/brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :large_orange_diamond: :star:63

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
* [Adobe Creative SDK](https://www.adobe.io/apis/creativecloud/creativesdk.html) Adobe creative tools and Creative Cloud SDK.
* [Dropbox](https://www.dropbox.com/developers) SDKs for Drop-ins and Dropbox Core API.
* [Fabric by Twitter](https://docs.fabric.io/apple/fabric/overview.html) Fabric Twitter Kit for iOS.
* [Liquid Analytics](https://github.com/lqd-io/liquid-sdk-ios) Identify behaviours through Analytics and react with real-time Personalization.
* [ResearchKit](https://github.com/ResearchKit/ResearchKit) ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects.
* [PacketZoom](https://packetzoom.com) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure](https://github.com/Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device :star:56
* [1Password](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps :star:2413
* [CareKit](https://github.com/carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :large_orange_diamond: :star:1393
* [Shopify](https://github.com/Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app. :star:192
* [Pinterest](https://github.com/pinterest/ios-pdk) - Pinterest iOS SDK :star:99
* [playkit-ios](https://github.com/kaltura/playkit-ios) - PlayKit: Kaltura Player SDK for iOS. :star:18
* [algoliasearch-client-swift](https://github.com/algolia/algoliasearch-client-swift) - Algolia Search API Client for Swift :large_orange_diamond: :star:89
* [twitter-kit-ios](https://github.com/twitter/twitter-kit-ios) - Twitter Kit is a native SDK to include Twitter content inside mobile apps. :star:389

#### Unofficial

* [STTwitter](https://github.com/nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine](https://github.com/natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy](https://github.com/heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit](https://github.com/sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API. :star:97
* [InstagramKit](https://github.com/shyambhat/InstagramKit) - Instagram iOS SDK. :star:913
* [DribbbleSDK](https://github.com/agilie/dribbble-ios-sdk) - Dribbble iOS SDK. :star:78
* [objectiveflickr](https://github.com/lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C. :star:726
* [Easy Social](https://github.com/pjebs/EasySocial) - Twitter & Facebook Integration. :star:130
* [das-quadrat](https://github.com/Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and macOS. :large_orange_diamond: :star:169
* [SocialLib](https://github.com/darkcl/SocialLib) - SocialLib handles sharing message to multiple social media. :star:10
* [PokemonKit](https://github.com/ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :large_orange_diamond: :star:77
* [TJDropbox](https://github.com/timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C :star:48
* [Lyft](https://github.com/genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :large_orange_diamond: :star:60
* [Github.swift](https://github.com/onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :large_orange_diamond: :star:159
* [CloudRail SI](https://github.com/CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more. :star:203
* [Medium SDK - Swift](https://github.com/96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project :large_orange_diamond: :star:8
* [Swifter](https://github.com/mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & macOS written in Swift :large_orange_diamond: :star:1870
* [SlackKit](https://github.com/SlackKit/SlackKit) - a Slack client library for iOS and macOS written in Swift :large_orange_diamond: :star:644
* [RandomUserSwift](https://github.com/dingwilson/RandomUserSwift) - Swift 3 Framework to Generate Random Users - An Unofficial SDK for randomuser.me :large_orange_diamond: :star:80
* [PPEventRegistryAPI](https://github.com/pantuspavel/PPEventRegistryAPI/) - Swift 3 Framework for Event Registry API (eventregistry.org). :large_orange_diamond:
* [UnsplashKit](https://github.com/carambalabs/UnsplashKit) - Swift client for Unsplash. :large_orange_diamond: :star:156
* [Swiftly Salesforce](https://github.com/mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :large_orange_diamond: :star:67
* [Spartan](https://github.com/Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :large_orange_diamond: :star:30
* [BigBoard](https://github.com/Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :large_orange_diamond: :star:45
* [SwiftyVK](https://github.com/SwiftyVK/SwiftyVK) Library for easy interact with VK social network API written in Swift 🔶
* [ARKKit](https://github.com/sleepdefic1t/ARKKit) - ARK Ecosystem Cryptocurrency API Framework for iOS & macOS, written purely in Swift 4.0. :large_orange_diamond: :star:12
* [SwiftInstagram](https://github.com/AnderGoig/SwiftInstagram) - Swift Client for Instagram API. :large_orange_diamond: :star:373
* [SwiftyArk](https://github.com/Awalz/SwiftyArk) - A simple, lightweight, fully-asynchronous cryptocurrency framework for the ARK Ecosystem. :large_orange_diamond: :star:9
* [PerfectSlackAPIClient](https://github.com/SvenTiigi/PerfectSlackAPIClient) - A Slack API Client for the Perfect Server-Side Swift Framework 🔶 :star:5

## Security
* [cocoapods-keys](https://github.com/orta/cocoapods-keys) - A key value store for storing environment and application keys. :star:928
* [simple-touch](https://github.com/simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS. :star:98
* [SwiftPasscodeLock](https://github.com/yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :large_orange_diamond: :star:577
* [Smile-Lock](https://github.com/recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View. :star:486
* [zxcvbn-ios](https://github.com/dropbox/zxcvbn-ios) - A realistic password strength estimator. :star:154
* [TPObfuscatedString](https://github.com/Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :large_orange_diamond: :star:11
* [LTHPasscodeViewController](https://github.com/rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support. :star:605
* [iOS-App-Security-Class](https://github.com/karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment. :star:37
* [BiometricAuth](https://github.com/vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application 🔶 :star:18
* [SAPinViewController](https://github.com/siavashalipour/SAPinViewController) - Simple and easy to use default iOS PIN screen. This simple library allows you to draw a fully customisable PIN screen same as the iOS default PIN view. My inspiration to create this library was form THPinViewController, however SAPinViewController is completely implemented in Swift. Also the main purpose of creating this library was to have simple, easy to use and fully customisable PIN screen. 🔶 :star:15
* [VoiceItAPI1IosSDK](https://github.com/voiceittech/VoiceItAPI1IosSDK) - A super easy way to add Voice Authentication(Biometrics) to your iOS apps, conveniently usable via cocoapods :large_orange_diamond: :star:4
* [TOPasscodeViewController](https://github.com/timoliver/TOPasscodeViewController) - A modal passcode input and validation view controller for iOS :star:234
* [BiometricAuthentication](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication :large_orange_diamond: :star:393

#### Encryption
* [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works. :star:715
* [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :large_orange_diamond: :star:360
* [Arcane](https://github.com/onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :large_orange_diamond: :star:201
* [SwiftMD5](https://github.com/mpurland/SwiftMD5) - A pure Swift implementation of MD5 :large_orange_diamond: :star:12
* [SwiftHash](https://github.com/onmyway133/SwiftHash) - 🍕 Hash in Swift :large_orange_diamond: :star:60
* [SweetHMAC](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :large_orange_diamond: :star:32
* [SwCrypt](https://github.com/soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and macOS :large_orange_diamond: :star:441
* [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :large_orange_diamond: :star:186
* [SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :large_orange_diamond: :star:415
* [EnigmaKit](https://github.com/mikaoj/EnigmaKit) - Enigma encryption in Swift :large_orange_diamond: :star:101
* [Themis](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/macOS, Android and different server side platforms. :star:469
* [Obfuscator-iOS](https://github.com/pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings. :star:432
* [swift-sodium](https://github.com/jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :large_orange_diamond: :star:207
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :large_orange_diamond: :star:4953
* [SCrypto](https://github.com/sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :large_orange_diamond: :star:17
* [SipHash](https://github.com/attaswift/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :large_orange_diamond: :star:199
* [RNCryptor](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift. -- For ObjC, see RNCryptor/RNCryptor-objc. :large_orange_diamond: :star:2766
* [CatCrypto](https://github.com/ImKcat/CatCrypto) - An easy way for hashing and encryption. :large_orange_diamond: :star:14

#### Keychain
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS. :star:2538
* [Valet](https://github.com/square/Valet) - Securely store data in the iOS or macOS Keychain without knowing a thing about how the Keychain works. :star:2826
* [Locksmith](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :large_orange_diamond: :star:2449
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and macOS :large_orange_diamond: :star:3549
* [Keychains](https://github.com/hyperoslo/Keychains) - Because you should care... about the security... of your shit. :large_orange_diamond: :star:62
* [Lockbox](https://github.com/granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain. :star:842
* [SAMKeychain](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS. :star:4681
* [SwiftKeychainWrapper](https://github.com/jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. Written in Swift. :large_orange_diamond: :star:653

## Server
* [Perfect](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :large_orange_diamond: :star:12575
* [Swifter](https://github.com/httpswift/swifter) - Tiny http server engine written in Swift programming language. :large_orange_diamond: :star:2188
* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for macOS or iOS applications. :star:4456
* [Curassow](https://github.com/kylef/Curassow) - Swift HTTP server using the pre-fork worker model. :large_orange_diamond: :star:392
* [Zewo](https://github.com/Zewo/Zewo) - Venice based HTTP server for Swift 2.2 on Linux :large_orange_diamond: :star:1749
* [Vapor](https://github.com/vapor/vapor) - Elegant web framework for Swift that works on iOS, macOS, and Ubuntu. :large_orange_diamond: :star:12308
* [swiftra](https://github.com/takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :large_orange_diamond: :star:272
* [blackfire](https://github.com/elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :large_orange_diamond: :star:947
* [swift-http](https://github.com/huytd/swift-http) - HTTP Implementation for Swift on Linux and macOS :large_orange_diamond: :star:460
* [Trevi](https://github.com/Yoseob/Trevi) - libuv base Swift web HTTP server framework :large_orange_diamond: :star:47
* [Express](https://github.com/crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :large_orange_diamond: :star:853
* [Taylor](https://github.com/izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :large_orange_diamond: :star:926
* [Frank](https://github.com/kylef/Frank) - Frank is a DSL for quickly writing web applications in Swift :large_orange_diamond: :star:382
* [Kitura](https://github.com/IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :large_orange_diamond: :star:6243
* [Swifton](https://github.com/necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and macOS :large_orange_diamond: :star:2049
* [Dynamo](https://github.com/johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :large_orange_diamond: :star:63
* [Redis](https://github.com/vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. macOS + Linux compatible. :large_orange_diamond: :star:346
* [NetworkObjects](https://github.com/colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux) :large_orange_diamond: :star:268
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift. :large_orange_diamond:
* [Lightning](https://github.com/skylab-inc/Lightning) - A Swift Multiplatform Web and Networking Framework. :large_orange_diamond: :star:297
* [SwiftGD](https://github.com/twostraws/swiftgd) - A simple Swift wrapper for libgd. :large_orange_diamond: :star:182
* [Jobs](https://github.com/BrettRToomey/Jobs) - A job system for Swift backends. :large_orange_diamond: :star:165
* [ApacheExpress](https://github.com/ApacheExpress/ApacheExpress) - Write Apache Modules in Swift! :large_orange_diamond: :star:168
* [GCDWebServer](https://github.com/swisspol/GCDWebServer) - Lightweight GCD based HTTP server for macOS & iOS (includes web based uploader & WebDAV server)

## Text
* [Twitter Text Obj](https://github.com/twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library. :star:1848
* [Nimbus](https://github.com/jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers. :star:6381
* [NSStringEmojize](https://github.com/diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters. :star:615
* [MMMarkdown](https://github.com/mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML. :star:1117
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText. :star:5267
* [DTRichTextEditor](https://github.com/Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS. :star:294
* [NBEmojiSearchView](https://github.com/neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view. :star:81
* [Pluralize.swift](https://github.com/joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :large_orange_diamond: :star:137
* [RichEditorView](https://github.com/cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :large_orange_diamond: :star:1004
* [Money](https://github.com/danthorpe/Money) - Swift value types for working with money & currency :large_orange_diamond: :star:826
* [PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :large_orange_diamond: :star:2217
* [YYText](https://github.com/ibireme/YYText) - Powerful text framework for iOS to display and edit rich text. :star:6986
* [Format](https://github.com/marmelroy/Format) - A Swift Formatter Kit. :large_orange_diamond: :star:1152
* [Tribute](https://github.com/zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :large_orange_diamond: :star:58
* [EmojiKit](https://github.com/dasmer/EmojiKit) - Effortless emoji-querying in Swift :large_orange_diamond: :star:85
* [Roman](https://github.com/nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :large_orange_diamond: :star:33
* [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view. :star:2701
* [pangu.Objective-C](https://github.com/Cee/pangu.objective-c) - Paranoid text spacing in Objective-C. :star:107
* [SwiftString](https://github.com/amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :large_orange_diamond: :star:1432
* [Marklight](https://github.com/macteo/Marklight) - Markdown syntax highlighter for iOS :large_orange_diamond: :star:376
* [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :large_orange_diamond: :star:560
* [TextAttributes](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings. :large_orange_diamond:[e] :star:1945
* [Reductio](https://github.com/fdzsergio/Reductio) - Automatic summarizer text in Swift :large_orange_diamond: :star:348
* [SmarkDown](https://github.com/SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :large_orange_diamond: :star:60
* [SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :large_orange_diamond: :star:832
* [SZMentions](https://github.com/szweier/SZMentions) - Library to help handle mentions :star:8
* [SZMentionsSwift](https://github.com/szweier/SZMentionsSwift) - Library to help handle mentions. :star:32
* [Heimdall](https://github.com/henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :large_orange_diamond: :star:299
* [NoOptionalInterpolation](https://github.com/T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.🔶[e] :star:41
* [Smile](https://github.com/onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601](https://github.com/onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift 🔶[e]
* [Translucid](https://github.com/Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :large_orange_diamond: :star:523
* [FormatterKit](https://github.com/mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set :star:4056
* [BonMot](https://github.com/Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :large_orange_diamond: :star:1918
* [SwiftValidators](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator). :star:130
* [StringStylizer](https://github.com/kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :large_orange_diamond: :star:34
* [SwiftyAttributes](https://github.com/eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :large_orange_diamond: :star:910
* [MarkdownKit](https://github.com/ivanbruel/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :large_orange_diamond: :star:125
* [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and macOS. :large_orange_diamond: :star:950
* [Apodimark](https://github.com/loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :large_orange_diamond: :star:439
* [Notepad](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :large_orange_diamond: :star:328
* [KKStringValidator](https://github.com/krizhanovskii/KKStringValidator) - Fast and simple string validation for iOS. With UITextField extension. :large_orange_diamond: :star:15
* [ISO8859](https://github.com/Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :large_orange_diamond: :star:11
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne](https://github.com/emojione/emojione). :large_orange_diamond: :star:42
* [SwiftRichString](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :large_orange_diamond: :star:1297
* [libPhoneNumber-iOS](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library). :star:1769
* [AttributedTextView](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions). :star:229
* [StyleDecorator](https://github.com/dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts :star:9
* [Mustard](https://github.com/mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :large_orange_diamond: :star:673
* [Input Mask](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :large_orange_diamond: :star:133
* [Attributed](https://github.com/Nirma/Attributed) - Modern Swift µframework for attributed strings. :large_orange_diamond: :star:610
* [Atributika](https://github.com/psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :large_orange_diamond: :star:186
* [Guitar](https://github.com/ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :large_orange_diamond: :star:546
* [RealTimeCurrencyFormatter](https://github.com/kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility. :star:11
* [Down](https://github.com/iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. 🔶 :star:605
* [Marky Mark](https://github.com/m2mobi/Marky-Mark) - Highly customizable Markdown parsing and native rendering in Swift. 🔶 :star:71
* [MarkdownView](https://github.com/keitaoouchi/MarkdownView) - Markdown View for iOS. 🔶 :star:1059
* [Highlighter](https://github.com/younatics/Highlighter) - Highlight whatever you want! Highlighter will magically find UI objects such as UILabel, UITextView, UITexTfield, UIButton in your UITableViewCell or other Class. :large_orange_diamond: :star:678
* [Sprinter](https://github.com/nicklockwood/Sprinter) - A library for formatting strings on iOS and macOS :large_orange_diamond: :star:154

#### Font
* [FontBlaster](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :large_orange_diamond: :star:873
* [GoogleMaterialIconFont](https://github.com/kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :large_orange_diamond: :star:140
* [ios-fontawesome](https://github.com/alexdrone/ios-fontawesome) - NSString+FontAwesome. :star:1752
* [FontAwesome.swift](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :large_orange_diamond: :star:941
* [SwiftFontName](https://github.com/morizotter/SwiftFontName) - OS font complements library. Localized font supported :large_orange_diamond: :star:98
* [SwiftIconFont](https://github.com/0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon) :large_orange_diamond: :star:821
* [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons. :star:2623
* [Iconic](https://github.com/dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS  :large_orange_diamond: :star:1410
* [GoogleMaterialDesignIcons](https://github.com/dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :large_orange_diamond: :star:366
* [OcticonsKit](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond: :star:34
* [IoniconsKit](https://github.com/keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond: :star:295
* [FontAwesomeKit.Swift](https://github.com/qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :large_orange_diamond: :star:157
* [UIFontComplete](https://github.com/Nirma/UIFontComplete) - Font management (System & Custom) for iOS and tvOS :large_orange_diamond: :star:944
* [Swicon](https://github.com/UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :large_orange_diamond: :star:36
* [SwiftIcons](https://github.com/ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :large_orange_diamond: :star:380

## Testing

#### TDD / BDD
* [Kiwi](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development. :star:3745
* [Specta](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa. :star:2110
* [Quick](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C. :star:7176
* [XcodeCoverage](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects. :star:705
* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers! :star:3538
* [Dixie](https://github.com/Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours. :star:202
* [gh-unit](https://github.com/gh-unit/gh-unit) - Test Framework for Objective-C. :star:1923
* [Nimble](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C :large_orange_diamond: :star:2596
* [Sleipnir](https://github.com/railsware/Sleipnir) - BDD-style framework for Swift :large_orange_diamond: :star:857
* [SwiftCheck](https://github.com/typelift/SwiftCheck) - QuickCheck for Swift :large_orange_diamond: :star:884
* [Spry](https://github.com/Quick/Spry) - A Mac and iOS Playgrounds Unit Testing library based on Nimble. 🔶 :star:285

#### A/B Testing
* [Switchboard](https://github.com/KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users. :star:267
* [SkyLab](https://github.com/mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac :star:688
* [MSActiveConfig](https://github.com/mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS :star:80
* [ABKit](https://github.com/recruit-mp/ABKit) - AB testing framework for iOS :large_orange_diamond: :star:101

#### UI Testing
* [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS. :star:187
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary](https://github.com/serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework. :star:153
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework. :star:5187
* [Subliminal](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing. :star:787
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any iOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Zucchini](https://github.com/zucchini-src/zucchini) - A visual iOS testing framework that loves your apps. :star:163
* [Remote](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing. :star:656
* [LayoutTest-iOS](https://github.com/linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations. :star:499
* [EarlGrey](https://github.com/google/EarlGrey) - :tea: iOS UI Automation Test Framework. :star:4031
* [UI Testing Cheat Sheet](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :large_orange_diamond: :star:1248
* [Floater_](https://github.com/Buglife/Floater_) - Add a floating fingertip to your app demo :large_orange_diamond: :star:233
* [Bluepill](https://github.com/linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine :star:2524
* [Flawless App](https://flawlessapp.io/) - tool for visual quality check of mobile app in a real-time. It compares initial design with the actual implementation right inside iOS simulator.

#### Other Testing
* [NaughtyKeyboard](https://github.com/Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device. :star:585
* [Fakery](https://github.com/vadymmarkov/Fakery) - Swift fake data generator. :large_orange_diamond: :star:811
* [DVR](https://github.com/venmo/DVR) - Network testing for Swift :large_orange_diamond: :star:522
* [Cuckoo](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :large_orange_diamond: :star:663
* [Parallel iOS Tests](https://github.com/plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :large_orange_diamond:
* [Vinyl](https://github.com/Velhotes/Vinyl) - Network testing à la VCR in Swift :large_orange_diamond: :star:207
* [Mockit](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :large_orange_diamond: :star:63
* [Cribble](https://github.com/maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :large_orange_diamond: :star:272
* [second_curtain](https://github.com/ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3 :star:115
* [trainer](https://github.com/KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports :star:99
* [Buildasaur](https://github.com/buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :large_orange_diamond: :star:730
* [Kakapo](https://github.com/devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :large_orange_diamond: :star:734
* [AcceptanceMark](https://github.com/bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit](https://github.com/metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :large_orange_diamond: :star:19
* [MirrorDiffKit](https://github.com/Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :large_orange_diamond: :star:101
* [SnappyTestCase](https://github.com/tooploox/SnappyTestCase) - iOS Simulator type agnostic snapshot testing, built on top of the FBSnapshotTestCase. :large_orange_diamond: :star:8

## UI
* [FlatUIKit](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS. :star:7699
* [BetweenKit](https://github.com/ice3-software/between-kit) - A robust drag-and-drop framework for iOS. :star:262
* [MDCSwipeToChoose](https://github.com/modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours! :star:2490
* [Motif](https://github.com/erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS. :star:830
* [Texture](https://github.com/TextureGroup/Texture) - Smooth asynchronous user interfaces for iOS apps. :star:2712
* [GaugeKit](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :large_orange_diamond: :star:901
* [MVMaterialView](https://github.com/TheMrugraj/MVMaterialView) - Subclass of UIControls and UIButton to mimic Ripple effect of Material Design concept. :star:66
* [TisprCardStack](https://github.com/tispr/tispr-card-stack) - Library that allows to have cards UI. :large_orange_diamond: :star:663
* [SAHistoryNavigationViewController](https://github.com/marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :large_orange_diamond: :star:1500
* [SAInboxViewController](https://github.com/marty-suzuki/SAInboxViewController) - UIViewController subclass inspired by "Inbox by google" animated transitioning. :large_orange_diamond: :star:283
* [iCarousel](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS. :star:10164
* [Cocoa Controls](https://www.cocoacontrols.com/) - Open source UI components for iOS and macOS.
* [tapkulibrary](https://github.com/devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework. :star:4010
* [HorizontalDial](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :large_orange_diamond: :star:106
* [ComponentKit](http://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [PMTween](https://github.com/poetmountain/PMTween) - An elegant and flexible tweening library for iOS. :star:340
* [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center. :star:2840
* [EatFit](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :large_orange_diamond: :star:620
* [phone-number-picker](https://github.com/hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :large_orange_diamond: :star:115
* [EXTView](https://github.com/recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable. :star:154
* [SFFocusViewLayout](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout with focused content. :star:1604
* [CardAnimation](https://github.com/seedante/CardAnimation) - Card flip animation by pan gesture. :large_orange_diamond: :star:1018
* [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [HorizontalProgress](https://github.com/AliThink/HorizontalProgress) - Simple horizontal progress bar with animation :star:160
* [JRSplitVC](https://github.com/tommypeps/JRSplitVC) - UISplitViewController with adaptative layouts :star:30
* [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :large_orange_diamond: :star:1513
* [Splitflap](https://github.com/yannickl/Splitflap) - A simple split-flap display for your Swift applications :large_orange_diamond: :star:772
* [EZSwipeController](https://github.com/goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :large_orange_diamond: :star:720
* [Koloda](https://github.com/Yalantis/Koloda) - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. :large_orange_diamond: :star:3620
* [XLActionController](https://github.com/xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller written in Swift. :large_orange_diamond: :star:2352
* [StackPageView](https://github.com/noppefoxwolf/StackPageView) - Vertical page view with UIViewControllers stacked on the top of each other :large_orange_diamond: :star:34
* [PageControl](https://github.com/kasper-lahti/PageControl) - ● ○ ○ ○ A nice, animated UIPageControl alternative. :large_orange_diamond: :star:95
* [Curry](https://github.com/devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit. :star:33
* [Pages](https://github.com/hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :large_orange_diamond: :star:376
* [BothamUI](https://github.com/Karumi/BothamUI) - Model View Presenter Framework written in Swift. :large_orange_diamond: :star:341
* [RainbowNavigation](https://github.com/DanisFabric/RainbowNavigation) - An easy way to change backgroundColor of UINavigationBar when Push & Pop :large_orange_diamond: :star:672
* [ALTextInputBar](https://github.com/AlexLittlejohn/ALTextInputBar) - An auto growing text input bar for messaging apps. :large_orange_diamond: :star:189
* [APCustomBlurView](https://github.com/collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :large_orange_diamond: :star:157
* [BAFluidView](https://github.com/antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion :star:1278
* [WZDraggableSwitchHeaderView](https://github.com/wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers :star:519
* [MICountryPicker](https://github.com/mustafaibrahim989/MICountryPicker) - Swift country picker with search option. :large_orange_diamond: :star:78
* [SCNavigationControlCenter](https://github.com/SergioChan/SCNavigationControlCenter) - This is an advanced navigation control center on iOS that can allow you to navigate to whichever view controller you want :star:399
* [SCTrelloNavigation](https://github.com/SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation. :star:784
* [FXBlurView](https://github.com/nicklockwood/FXBlurView) - UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above. :star:5027
* [NGAParallaxMotion](https://github.com/michaeljbishop/NGAParallaxMotion) - A tiny category on UIView that allows you to set one property: "parallaxIntensity" to achieve a parallax effect with UIMotionEffect :star:679
* [EPShapes](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder. :large_orange_diamond: :star:374
* [CRParticleEffect](https://github.com/Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects. :star:353
* [Spots](https://github.com/hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :large_orange_diamond: :star:1223
* [APAddressBook](https://github.com/Alterplay/APAddressBook) - Easy access to iOS address book :star:1405
* [AZExpandableIconListView](https://github.com/Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :large_orange_diamond: :star:194
* [greedo-layout-for-ios](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS :star:809
* [FlourishUI](https://github.com/thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :large_orange_diamond: :star:209
* [GranadaLayout](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater. :star:42
* [Navigation Stack](https://github.com/Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :large_orange_diamond: :star:1949
* [UIView-draggable](https://github.com/andreamazz/UIView-draggable) - UIView category that adds dragging capabilities. :star:384
* [PeekPop](https://github.com/marmelroy/PeekPop) - Backwards-compatible Peek and Pop. :star:1887
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. 🔶 :star:81
* [EPSignature](https://github.com/ipraba/EPSignature) - Signature component for iOS in Swift :large_orange_diamond: :star:650
* [CoreDragon](https://github.com/nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :large_orange_diamond: :star:43
* [EVFaceTracker](https://github.com/evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face. :star:222
* [Fashion](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :large_orange_diamond: :star:74
* [LeeGo](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :large_orange_diamond: :star:908
* [MEVHorizontalContacts](https://github.com/manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items. :star:310
* [Ripple](https://github.com/RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :large_orange_diamond: :star:57
* [ScalePicker](https://github.com/kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app. :star:142
* [VisualEffectView](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :large_orange_diamond: :star:467
* [NumPad](https://github.com/efremidze/NumPad) - Number Pad (inspired by Square's design). :large_orange_diamond: :star:50
* [expanding-collection](https://github.com/Ramotion/expanding-collection) - ExpandingCollection is a card peek/pop controller :large_orange_diamond: :star:4143
* [Cacao](https://github.com/PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux) :large_orange_diamond: :star:823
* [LFTimePicker](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :large_orange_diamond: :star:45
* [StateView](https://github.com/sahandnayebaziz/StateView) - Views that automatically update themselves. :large_orange_diamond: :star:494
* [JDFlipNumberView](https://github.com/calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays. :star:723
* [JQSwiftIcon](https://github.com/josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :large_orange_diamond: :star:5
* [FlickToDismiss](https://github.com/jakelawson1/FlickToDismiss) - A basic UIViewController class that presents a UIView which can be dismissed by flicking it off the screen. :large_orange_diamond: :star:206
* [ISTimeline](https://github.com/instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :large_orange_diamond: :star:894
* [JFCardSelectionViewController](https://github.com/atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :large_orange_diamond: :star:393
* [DCKit](https://github.com/agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :large_orange_diamond: :star:90
* [BackgroundVideoiOS](https://github.com/Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views. :star:512
* [NightNight](https://github.com/Draveness/NightNight) - Elegant way to integrate night mode to swift projects :large_orange_diamond: :star:609
* [SwiftTheme](https://github.com/jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :large_orange_diamond: :star:1033
* [PinpointKit](https://github.com/Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :large_orange_diamond: :star:990
* [FDStackView](https://github.com/forkingdog/FDStackView) - Use UIStackView directly in iOS6+ :star:2380
* [Popover](https://github.com/corin8823/Popover) - Popover is a balloon library like Facebook app. It is written in pure swift. :large_orange_diamond: :star:1367
* [YangMingShan](https://github.com/yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps. :star:616
* [TOActionSheet](https://github.com/TimOliver/TOActionSheet) - A custom-designed reimplementation of the UIActionSheet control for iOS :star:158
* [nui](https://github.com/tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS :star:3765
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material](https://github.com/CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :large_orange_diamond: :star:9234
* [Blurable](https://github.com/FlexMonkey/Blurable) - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions :large_orange_diamond: :star:826
* [EZYGradientView](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :large_orange_diamond: :star:309
* [DistancePicker](https://github.com/qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :large_orange_diamond: :star:95
* [OAStackView](https://github.com/nsomar/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView. :star:2181
* [StyleKit](https://github.com/146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. Behind the scenes, StyleKit uses UIAppearance and some selector magic to apply the styles. You can also customize the parser for greater flexibility. :large_orange_diamond: :star:1133
* [planet](https://github.com/kwallet/planet) - A country picker :large_orange_diamond: :star:54
* [PageController](https://github.com/hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :large_orange_diamond: :star:209
* [StatusProvider](https://github.com/mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :large_orange_diamond: :star:808
* [ASBubbleDrag](https://github.com/scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :large_orange_diamond: :star:38
* [StackLayout](https://github.com/bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns. :star:77
* [NightView](https://github.com/Boris-Em/NightView) - Dazzling Nights on iOS. :large_orange_diamond: :star:158
* [VENTokenField](https://github.com/venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app. :star:749
* [SwiftVideoBackground](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementing a video background :large_orange_diamond: :star:96
* [MRArticleViewController](https://github.com/mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :large_orange_diamond: :star:104
* [Macaw](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :large_orange_diamond: :star:3311
* [HubFramework](https://github.com/spotify/HubFramework) - Spotify’s component-driven UI framework for iOS. :star:1818
* [ConfettiView](https://github.com/OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :large_orange_diamond: :star:216
* [BouncyPageViewController](https://github.com/BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :large_orange_diamond: :star:630
* [LTHRadioButton](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :large_orange_diamond: :star:197
* [CRRulerControl](https://github.com/Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument. :star:94
* [Macaw-Examples](https://github.com/exyte/Macaw-Examples) - Various usages of the Macaw library. :large_orange_diamond: :star:162
* [KVCardSelectionVC](https://github.com/kunalverma25/KVCardSelectionVC) - Awesome looking Dial like card selection ViewController. :large_orange_diamond: :star:15
* [Reactions](https://github.com/yannickl/Reactions) - Fully customizable Facebook reactions control :large_orange_diamond: :star:456
* [Newly](https://github.com/dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :large_orange_diamond: :star:175
* [CardStackController](https://github.com/jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :large_orange_diamond: :star:345
* [Material Components](https://github.com/material-components/material-components-ios) - Google developed UI components that help developers execute Material Design. :star:1890
* [DMSwipeCards](https://github.com/D-32/DMSwipeCards) - Tinder like card stack that supports lazy loading and generics :large_orange_diamond: :star:203
* [RKMultiUnitRuler](https://github.com/farshidce/RKMultiUnitRuler/) - Simple customizable ruler control that supports multiple units. 🔶
* [FAQView](https://github.com/mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :large_orange_diamond: :star:369
* [CRPageViewController](https://github.com/Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further. :star:374
* [OXPatternLock](https://github.com/oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :large_orange_diamond: :star:18
* [LMArticleViewController](https://github.com/lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts :star:5
* [FSPagerView](https://github.com/WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :large_orange_diamond: :star:2607
* [PanelKit](https://github.com/louisdh/panelkit) - A UI framework that enables panels on iOS. :large_orange_diamond: :star:3081
* [ElongationPreview](https://github.com/Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond: :star:657
* [Pageboy](https://github.com/uias/Pageboy) - A simple, highly informative page view controller. :large_orange_diamond: :star:917
* [IGColorPicker](https://github.com/iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift 🔶 :star:79
* [KPActionSheet](https://github.com/khuong291/KPActionSheet) - 🔶 A replacement of default action sheet, but has very simple usage. 🔶 :star:4
* [SegmentedProgressBar](https://github.com/D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :large_orange_diamond: :star:189
* [CHIPageControl](https://github.com/ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl. :large_orange_diamond: :star:1682
* [Magnetic](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). 🔶 :star:747
* [AmazingBubbles](https://github.com/GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. 🔶 :star:41
* [Haptica](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator. :large_orange_diamond: :star:210
* [GDCheckbox](https://github.com/saeid/GDCheckbox) - An easy to use custom checkbox/radio button component for iOS, with support of IBDesign Inspector. 🔶 :star:4
* [HamsterUIKit](https://github.com/Howardw3/HamsterUIKit) - A simple and elegant UIKit(Chart) for iOS.  🔶 :star:15
* [AZEmptyState](https://github.com/Minitour/AZEmptyState) - A UIControl subclass that makes it easy to create empty states. 🔶 :star:67
* [URWeatherView](https://github.com/jegumhon/URWeatherView) - Show the weather effects onto view written in Swift3. 🔶 :star:341
* [LCUIComponents](https://github.com/linhcn/LCUIComponents) - A framework supports creating transient views on top of other content onscreen such as popover with a data list. 🔶 :star:5
* [ViewComposer](https://github.com/Sajjon/ViewComposer) - `let lbl: UILabel = [.text("Hello"), .textColor(.red)]` - Create views using array literal of enum expressing view attributes. :star:14
* [BatteryView](https://github.com/yonat/BatteryView) - Simple battery shaped UIView. 🔶 :star:10
* [ShadowView](https://github.com/PierrePerrin/ShadowView) - Make shadows management easy on UIView :large_orange_diamond: :star:233
* [Pulley](https://github.com/52inc/Pulley) - A library to imitate the iOS 10 Maps UI :large_orange_diamond: :star:899
* [N8iveKit](https://github.com/n8iveapps/N8iveKit) - A set of frameworks making iOS development more fun. :large_orange_diamond: :star:18
* [Panda](https://github.com/wordlessj/Panda) - Create view hierarchies declaratively. :large_orange_diamond: :star:17
* [NotchKit](https://github.com/HarshilShah/NotchKit) - A simple way to hide the notch on the iPhone X :large_orange_diamond: :star:1797
* [Overlay](https://github.com/TintPoint/Overlay) - Overlay is a flexible UI framework designed for Swift. It allows you to write CSS like Swift code. :large_orange_diamond: :star:39
* [SwiftyUI](https://github.com/haoking/SwiftyUI) - High performance and lightweight(one class each UI) UIView, UIImage, UIImageView, UIlabel, UIButton, Promise and more. 🔶 :star:110
* [NotchToolkit](https://github.com/AFathi/NotchToolkit) - A framework for iOS that allow developers use the iPhone X notch in creative ways. 🔶 :star:35
* [PullUpController](https://github.com/MarioIannotta/PullUpController) - Pull up controller with multiple sticky points like in iOS Maps. 🔶 :star:459
* [DrawerKit](https://github.com/Babylonpartners/DrawerKit) - DrawerKit lets an UIViewController modally present another UIViewController in a manner similar to the way Apple's Maps app works. :large_orange_diamond: :star:444
* [TimelineCards](https://github.com/vladaverin24/TimelineCards) - Presenting timelines as cards, single or bundled in scrollable feed!. :star:280
* [Shades](https://github.com/aaronjsutton/Shades) - Easily add drop shadows, borders, and round corners to a UIView. :large_orange_diamond: :star:5
* [ISPageControl](https://github.com/Interactive-Studio/ISPageControl) - A page control similar to that used in Instagram. 🔶 :star:132
* [Mixin](https://github.com/oney/Mixin) - React.js like Mixin. More powerful Protocol-Oriented Programming. 🔶 :star:33
* [Shiny](https://github.com/efremidze/Shiny) - Iridescent Effect View (inspired by Apple Pay Cash). 🔶 :star:466

#### Activity Indicator

* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :large_orange_diamond: :star:6407
* [TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator) - Rubber Indicator in Swift :large_orange_diamond: :star:1060
* [RPLoadingAnimation](https://github.com/naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :large_orange_diamond: :star:180
* [LiquidLoader](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation :large_orange_diamond: :star:1028
* [iOS-CircleProgressView](https://github.com/CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :large_orange_diamond: :star:402
* [iOS Circle Progress Bar](https://github.com/Eclair/CircleProgressBar) - iOS Circle Progress Bar :star:350
* [LinearProgressBar](https://github.com/PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :large_orange_diamond: :star:92
* [STLoadingGroup](https://github.com/saitjr/STLoadingGroup) - loading views :large_orange_diamond: :star:328
* [ALThreeCircleSpinner](https://github.com/AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :large_orange_diamond: :star:37
* [MHRadialProgressView](https://github.com/mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view. :star:81
* [Loader](https://github.com/Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :large_orange_diamond: :star:90
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. :star:14201
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app. :star:10597
* [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD. :star:1011
* [M13ProgressSuite](https://github.com/Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS. :star:3653
* [PKHUD](https://github.com/pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :large_orange_diamond: :star:2675
* [EZLoadingActivity](https://github.com/goktugyil/EZLoadingActivity) - Lightweight loading activity HUD.  :large_orange_diamond: :star:530
* [FFCircularProgressView](https://github.com/elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view :star:1008
* [MRProgress](https://github.com/mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress :star:2588
* [BigBrother](https://github.com/marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :large_orange_diamond: :star:455
* [AlamofireNetworkActivityIndicator](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :large_orange_diamond: :star:441
* [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :large_orange_diamond: :star:690
* [DACircularProgress](https://github.com/danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties. :star:2254
* [KYNavigationProgress](https://github.com/ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. :large_orange_diamond:[e] :star:197
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :large_orange_diamond: :star:574
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module. :star:3824
* [MKRingProgressView](https://github.com/maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. 🔶 :star:674
* [Hexacon](https://github.com/gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. 🔶 :star:256
* [StackViewController](https://github.com/seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :large_orange_diamond: :star:635
* [ParticlesLoadingView](https://github.com/BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :large_orange_diamond: :star:798
* [RPCircularProgress](https://github.com/iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :large_orange_diamond: :star:120
* [MBCircularProgressBar](https://github.com/MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable. :star:731
* [WSProgressHUD](https://github.com/devSC/WSProgressHUD) - This is a beautiful hud view for iPhone & iPad :star:541
* [DBMetaballLoading](https://github.com/dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :large_orange_diamond: :star:56
* [FillableLoaders](https://github.com/polqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond: :star:1798
* [PageControls](https://github.com/popwarsweet/PageControls) - This is a selection of custom page controls to replace UIPageControl, inspired by a dribbble found here :large_orange_diamond: :star:647
* [VHUD](https://github.com/xxxAIRINxxx/VHUD) Simple HUD. :large_orange_diamond:
* [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :large_orange_diamond: :star:1681
* [SnapTimer](https://github.com/andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :large_orange_diamond: :star:255
* [AudioIndicatorBars](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :large_orange_diamond: :star:172
* [LLSpinner](https://github.com/alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :large_orange_diamond: :star:11
* [SVUploader](https://github.com/kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy.  :large_orange_diamond: :star:39
* [YLProgressBar](https://github.com/yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics. :star:1076
* [FlexibleSteppedProgressBar](https://github.com/amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar.  :large_orange_diamond: :star:130
* [GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar. :large_orange_diamond: :star:73
* [DSGradientProgressView](https://github.com/DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :large_orange_diamond: :star:253
* [GradientProgressBar](https://github.com/fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :large_orange_diamond: :star:27
* [BPCircleActivityIndicator](https://github.com/ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :large_orange_diamond: :star:36
* [DottedProgressBar](https://github.com/nikola9core/DottedProgressBar) - Simple and customizable animated progress bar with dots for iOS. :large_orange_diamond: :star:20
* [RSLoadingView](https://github.com/roytornado/RSLoadingView) - Awesome loading animations using 3D engine written with Swift. :large_orange_diamond: :star:255
* [SendIndicator](https://github.com/LeonardoCardoso/SendIndicator) - Yet another task indicator :large_orange_diamond: :star:37
* [StepProgressView](https://github.com/yonat/StepProgressView) - Step-by-step progress view with labels and shapes. A good replacement for UIActivityIndicatorView and UIProgressView. :large_orange_diamond: :star:60
* [BPBlockActivityIndicator](https://github.com/ppth0608/BPBlockActivityIndicator) - A simple and awesome Loading Activity Indicator(with funny block animation) for your iOS app. :large_orange_diamond: :star:28
* [JustHUD](https://github.com/shubh10/JustHUD) - JustHUD is an iOS drop-in class written in Swift that displays a translucent HUD. :large_orange_diamond: :star:15
* [JDBreaksLoading](https://github.com/jamesdouble/JDBreaksLoading) - You can easily start up a little breaking game indicator by one line. :large_orange_diamond: :star:127
* [SkeletonView](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting. :large_orange_diamond: :star:3244
* [Windless](https://github.com/Interactive-Studio/Windless) - Windless makes it easy to implement invisible layout loading view. :large_orange_diamond: :star:571
* [Skeleton](https://github.com/gonzalonunez/Skeleton) - An easy way to create sliding CAGradientLayer animations! Works great for creating skeleton screens for loading content. 🔶 :star:329
+* [StatusBarOverlay](https://github.com/IdleHandsApps/StatusBarOverlay) - Automatically show/hide a "No Internet Connection" bar when your app loses/gains connection. It supports apps which hide the status bar and "The Notch" 🔶

#### Animation
* [Pop](https://github.com/facebook/pop) - An extensible iOS and macOS animation library, useful for physics-based interactions. :star:18554
* [AnimationEngine](https://github.com/intuit/AnimationEngine) - Easily build advanced custom animations on iOS. :star:1036
* [Awesome-iOS-Animation](https://github.com/jackymelb/awesome-ios-animation) - Collection of Animation projects :star:851
* [RZTransitions](https://github.com/Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions. :star:1768
* [DCAnimationKit](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations. :star:738
* [Spring](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift. :large_orange_diamond: :star:11782
* [Canvas](https://github.com/CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io :star:5291
* [Fluent](https://github.com/matthewcheok/Fluent) - Swift animation made easy :large_orange_diamond: :star:306
* [Cheetah](https://github.com/suguru/Cheetah) - Easy animation library on iOS with Swift2. :large_orange_diamond: :star:570
* [RadialLayer](https://github.com/soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :large_orange_diamond: :star:52
* [Pop By Example](https://github.com/hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example. :star:179
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation](https://github.com/icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :large_orange_diamond: :star:2523
* [Animo](https://github.com/eure/Animo) - SpriteKit-like animation builders for CALayers. :large_orange_diamond: :star:193
* [CurryFire](https://github.com/devinross/curry-fire) - A framework for creating unique animations. :star:86
* [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :large_orange_diamond: :star:7037
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :large_orange_diamond: :star:1618
* [DaisyChain](https://github.com/alikaragoz/DaisyChain) - :link: Easy animation chaining :large_orange_diamond: :star:27
* [SYBlinkAnimationKit](https://github.com/shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :large_orange_diamond: :star:106
* [PulsingHalo](https://github.com/shu223/PulsingHalo) - iOS Component for creating a pulsing animation. :star:1625
* [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit) - Chainable animations in Swift :large_orange_diamond: :star:1814
* [JDAnimationKit](https://github.com/JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :large_orange_diamond: :star:565
* [Advance](https://github.com/timdonnelly/Advance) - A powerful animation framework for iOS. :large_orange_diamond: :star:4079
* [UIView-Shake](https://github.com/andreamazz/UIView-Shake) - UIView category that adds shake animation :star:480
* [Walker](https://github.com/RamonGilabert/Walker) - A new animation engine for your app. :large_orange_diamond: :star:141
* [Morgan](https://github.com/RamonGilabert/Morgan) - An animation set for your app. :large_orange_diamond: :star:95
* [MagicMove](https://github.com/patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :large_orange_diamond: :star:11
* [Shimmer](https://github.com/facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app. :star:8321
* [SAConfettiView](https://github.com/sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :large_orange_diamond: :star:1064
* [CCMRadarView](https://github.com/cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :large_orange_diamond: :star:183
* [Pulsator](https://github.com/shu223/Pulsator) - Pulse animation for iOS :large_orange_diamond: :star:826
* [Interpolate](https://github.com/marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :large_orange_diamond: :star:1545
* [ADPuzzleAnimation](https://github.com/Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :large_orange_diamond: :star:113
* [Wave](https://github.com/onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :large_orange_diamond: :star:71
* [Stellar](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift :large_orange_diamond: :star:2499
* [MotionMachine](https://github.com/poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :large_orange_diamond: :star:336
* [JRMFloatingAnimation](https://github.com/carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views. :star:174
* [AHKBendableView](https://github.com/fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :large_orange_diamond: :star:596
* [FlightAnimator](https://github.com/AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :large_orange_diamond: :star:560
* [ZoomTransitioning](https://github.com/WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :large_orange_diamond: :star:554
* [Ubergang](https://github.com/RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :large_orange_diamond: :star:46
* [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C :star:3059
* [Popsicle](https://github.com/DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :large_orange_diamond: :star:1129
* [WXWaveView](https://github.com/WelkinXie/WXWaveView) - Add a pretty water wave to your view. :star:302
* [Twinkle](https://github.com/piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :large_orange_diamond: :star:456
* [MotionBlur](https://github.com/fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations. :star:1499
* [RippleEffectView](https://github.com/alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :large_orange_diamond: :star:302
* [Keyframes](https://github.com/facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices. :star:4793
* [SwiftyAnimate](https://github.com/rchatham/SwiftyAnimate) - Composable animations in Swift. :large_orange_diamond: :star:157
* [SamuraiTransition](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat “cutting” animations. :large_orange_diamond: :star:207
* [Lottie](https://github.com/airbnb/lottie-ios) - An iOS library for a real time rendering of native vector animations from Adobe After Effects. :star:12208
* [Overlap](https://github.com/ML-Works/Overlap) - Tiny iOS library to achieve overlap visual effect. :large_orange_diamond: :star:118
* [anim](https://github.com/onurersel/anim) - An animation library for iOS with custom easings and easy to follow API. :large_orange_diamond: :star:52
* [AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout) - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView. :large_orange_diamond: :star:2895
* [Dance](https://github.com/saoudrizwan/Dance) - A radical & elegant animation library built for iOS. :large_orange_diamond: :star:611
* [AKVideoImageView](https://github.com/numen31337/AKVideoImageView) - UIImageView subclass which allows you to display a looped video as a background. :star:113
* [Spruce iOS Animation Library](https://github.com/willowtreeapps/spruce-ios) - Swift library for choreographing animations on the screen.:large_orange_diamond: :star:2266
* [CircularRevealKit](https://github.com/T-Pro/CircularRevealKit) - UI framework that implements the material design's reveal effect. 🔶 :star:10
* [TweenKit](https://github.com/SteveBarnegren/TweenKit) - Animation library for iOS in Swift. 🔶 :star:638
* [Water](https://github.com/KrisYu/Water) - Simple calculation to render cheap water effects. 🔶 :star:327
* [Pastel](https://github.com/cruisediary/Pastel) - Gradient animation effect like Instagram. 🔶 :star:2376
* [YapAnimator](https://github.com/yapstudios/YapAnimator) - Your fast and friendly physics-based animation system. :large_orange_diamond: :star:1762
* [Bubble](https://github.com/goldmoment/Bubble) - Fruit Animation :large_orange_diamond: :star:185
* [Gemini](https://github.com/shoheiyokoyama/Gemini) - Gemini is rich scroll based animation framework for iOS, written in Swift :large_orange_diamond: :star:2118
* [WaterDrops](https://github.com/LeFal/WaterDrops) - Simple water drops animation for iOS in Swift :large_orange_diamond: :star:219
* [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) - ViewAnimator brings your UI to life with just one line. 🔶 :star:2946
* [Ease](https://github.com/roberthein/Ease) - Animate everything with Ease. 🔶 :star:835

##### Transition
* [BlurryModalSegue](https://github.com/Citrrus/BlurryModalSegue) - A custom modal segue for providing a blurred overlay effect. :star:926
* [DAExpandAnimation](https://github.com/ifitdoesntwork/DAExpandAnimation) - A custom modal transition that presents a controller with an expanding effect while sliding out the presenter remnants. :large_orange_diamond: :star:535
* [BubbleTransition](https://github.com/andreamazz/BubbleTransition) - A custom modal transition that presents and dismiss a controller with an expanding bubble effect. :large_orange_diamond: :star:2638
* [RPModalGestureTransition](https://github.com/naoyashiga/RPModalGestureTransition) - You can dismiss modal by using gesture :point_up_2: :iphone: :large_orange_diamond: :star:87
* [RMPZoomTransitionAnimator](https://github.com/recruit-mp/RMPZoomTransitionAnimator) - A custom zooming transition animation for UIViewController :star:1595
* [ElasticTransition](https://github.com/lkzhao/ElasticTransition) - A UIKit custom transition that simulates an elastic drag. Written in Swift. :large_orange_diamond: :star:1838
* [ElasticTransition-ObjC](https://github.com/taglia3/ElasticTransition-ObjC) - A UIKit custom transition that simulates an elastic drag.This is the Objective-C Version of Elastic Transition written in Swift by lkzhao :star:361
* [ZFDragableModalTransition](https://github.com/zoonooz/ZFDragableModalTransition) - Custom animation transition for present modal view controller :star:2328
* [ImageOpenTransition](https://github.com/mcmatan/ImageOpenTransition) - Beautiful and precise transitions between ViewControllers images written in Swift. :large_orange_diamond: :star:797
* [ZOZolaZoomTransition](https://github.com/NewAmsterdamLabs/ZOZolaZoomTransition) - Zoom transition that animates the entire view heirarchy. Used extensively in the Zola iOS application. :star:881
* [JTMaterialTransition](https://github.com/jonathantribouharet/JTMaterialTransition) - An iOS transition for controllers based on material design. :star:898
* [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery) - Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol. :star:2277
* [TransitionTreasury](https://github.com/DianQK/TransitionTreasury) - Easier way to push your viewController. :large_orange_diamond: :star:1947
* [Presenter](https://github.com/muukii/Presenter) - Screen transition with safe and clean code.  :large_orange_diamond: :star:10
* [Kaeru](https://github.com/bannzai/Kaeru) - Switch viewcontroller like iOS task manager :large_orange_diamond: :star:420
* [View2ViewTransition](https://github.com/naru-jpn/View2ViewTransition) - Custom interactive view controller transition from one view to another view. :large_orange_diamond: :star:782
* [AZTransitions](https://github.com/azimin/AZTransitions) - API to make great custom transitions in one method. :large_orange_diamond: :star:371
* [Hero](https://github.com/lkzhao/Hero) - Supercharged transition engine for iOS. Build your custom view transitions with no code at all. Inspired by Keynote's Magic Move. :large_orange_diamond: :star:11996
* [Motion](https://github.com/CosmicMind/Motion) - Seamless animations and transitions in Swift. :large_orange_diamond: :star:867
* [PresenterKit](https://github.com/jessesquires/PresenterKit) - Swifty view controller presentation for iOS :large_orange_diamond: :star:408
* [Transition](https://github.com/Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions. :large_orange_diamond: :star:1839
* [Gagat](https://github.com/Boerworz/Gagat) - A delightful way to transition between visual styles in your iOS applications. :large_orange_diamond: :star:740
* [DeckTransition](https://github.com/HarshilShah/DeckTransition) - A library to recreate the iOS Apple Music now playing transition :large_orange_diamond: :star:1650
* [TransitionableTab](https://github.com/Interactive-Studio/TransitionableTab) - TransitionableTab makes it easy to animate when switching between tab :large_orange_diamond: :star:453

#### Alert & Action Sheet

* [SweetAlert](https://github.com/codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift. :large_orange_diamond: :star:1787
* [NYAlertViewController](https://github.com/nealyoung/NYAlertViewController) - Highly configurable iOS Alert Views with custom content views. :star:523
* [SCLAlertView-Swift](https://github.com/vikmeup/SCLAlertView-Swift) - Beautiful animated Alert View, written in Swift. :large_orange_diamond: :star:4181
* [TTGSnackbar](https://github.com/zekunyan/TTGSnackbar) - Show simple message and action button on the bottom of the screen with multi kinds of animation. :large_orange_diamond: :star:364
* [Swift-Prompts](https://github.com/GabrielAlva/Swift-Prompts) - A Swift library to design custom prompts with a great scope of options to choose from. :large_orange_diamond: :star:714
* [BRYXBanner](https://github.com/bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift. :large_orange_diamond: :star:866
* [LNRSimpleNotifications](https://github.com/LISNR/LNRSimpleNotifications) - Simple Swift in-app notifications. LNRSimpleNotifications is a simplified Swift port of TSMessages :large_orange_diamond: :star:172
* [HDNotificationView](https://github.com/nhdang103/HDNotificationView) - Emulates the native Notification Banner UI for any alert. :star:248
* [JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification) - Easy, customizable notifications displayed on top of the statusbar. :star:3406
* [Notie](https://github.com/thii/Notie) - In-app notification in Swift, with customizable buttons and input text field. :large_orange_diamond: :star:79
* [EZAlertController](https://github.com/thellimist/EZAlertController) - Easy Swift UIAlertController :large_orange_diamond: :star:284
* [GSMessages](https://github.com/wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+. :large_orange_diamond: :star:275
* [OEANotification](https://github.com/OEA/OEANotification) - In-app customizable notification views on top of screen for iOS which is written in Swift 2.1. :large_orange_diamond: :star:18
* [RKDropdownAlert](https://github.com/cwRichardKim/RKDropdownAlert) - Extremely simple UIAlertView alternative. :star:1456
* [TKSwarmAlert](https://github.com/entotsu/TKSwarmAlert) - Animated alert library like Swarm app. :large_orange_diamond: :star:463
* [Whisper](https://github.com/hyperoslo/Whisper) - Whisper is a component that will make the task of display messages and in-app notifications simple. It has three different views inside :large_orange_diamond: :star:3222
* [SimpleAlert](https://github.com/KyoheiG3/SimpleAlert) - Customizable simple Alert and simple ActionSheet for Swift :large_orange_diamond: :star:297
* [Hokusai](https://github.com/ytakzk/Hokusai) - A Swift library to provide a bouncy action sheet :large_orange_diamond: :star:382
* [SwiftNotice](https://github.com/johnlui/SwiftNotice) - SwiftNotice is a GUI library for displaying various popups (HUD) written in pure Swift, fits any scrollview. :large_orange_diamond: :star:635
* [SwiftOverlays](https://github.com/peterprokop/SwiftOverlays) - SwiftOverlays is a Swift GUI library for displaying various popups and notifications :large_orange_diamond: :star:503
* [SwiftyDrop](https://github.com/morizotter/SwiftyDrop) - SwiftyDrop is a lightweight pure Swift simple and beautiful dropdown message. :large_orange_diamond: :star:570
* [LKAlertController](https://github.com/Lightningkite/LKAlertController) - An easy to use UIAlertController builder for swift. :large_orange_diamond: :star:62
* [DOAlertController](https://github.com/okmr-d/DOAlertController) - Simple Alert View written in Swift, which can be used as a UIAlertController. (AlertController/AlertView/ActionSheet) :large_orange_diamond: :star:337
* [CustomizableActionSheet](https://github.com/beryu/CustomizableActionSheet) - Action sheet allows including your custom views and buttons. :large_orange_diamond: :star:131
* [Toast-Swift](https://github.com/scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class. :large_orange_diamond: :star:1014
* [PMAlertController](https://github.com/Codeido/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController. 🔶 :star:1719
* [PopupViewController](https://github.com/dimillian/PopupViewController) - UIAlertController drop in replacement with much more customization. 🔶 :star:16
* [AlertViewLoveNotification](https://github.com/PhilippeBoisney/AlertViewLoveNotification) - A simple and attractive AlertView to ask permission to your users for Push Notification. 🔶 :star:27
* [CRToast](https://github.com/cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs :star:4003
* [JLToast](https://github.com/devxoul/Toaster) - Toast for iOS with very simple interface. :large_orange_diamond: :star:917
* [CuckooAlert](https://github.com/rollmind/CuckooAlert) - Multiple use of presentViewController for UIAlertController. 🔶 :star:5
* [KRAlertController](https://github.com/krimpedance/KRAlertController) - A colored alert view for your iOS. :large_orange_diamond: :star:36
* [Dodo](https://github.com/evgenyneu/Dodo) - A message bar for iOS written in Swift. :large_orange_diamond: :star:786
* [MaterialActionSheetController](https://github.com/ntnhon/MaterialActionSheetController) - A Google like action sheet for iOS written in Swift. :large_orange_diamond: :star:85
* [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift. :large_orange_diamond: :star:2803
* [FCAlertView](https://github.com/krispenney/FCAlertView) - A Flat Customizable AlertView for iOS. (Swift) :large_orange_diamond: :star:81
* [FCAlertView](https://github.com/nimati/FCAlertView) - A Flat Customizable AlertView for iOS. (Objective-C)
* [CDAlertView](https://github.com/candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup 🔶 :star:767
* [RMActionController](https://github.com/CooperRS/RMActionController) - Present any UIView in an UIAlertController like manner. :star:378
* [RMDateSelectionViewController](https://github.com/CooperRS/RMDateSelectionViewController) - Select a date using UIDatePicker in a UIAlertController like fashion. :star:1050
* [RMPickerViewController](https://github.com/CooperRS/RMPickerViewController) - Select something using UIPickerView in a UIAlertController like fashion. :star:339
* [Hedwig](https://github.com/dereklimbus/hedwig) - Interactive notification :large_orange_diamond: :star:17
* [Jelly](https://github.com/SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code. :large_orange_diamond: :star:1453
* [Malert](https://github.com/vitormesquita/Malert) - Malert is a simple, easy and custom iOS UIAlertView written in Swift 🔶 :star:162
* [RAlertView](https://github.com/roycms/AlertView) - AlertView, iOS popup window, A pop-up framework, Can be simple and convenient to join your project. :star:44
* [NoticeBar](https://github.com/qiuncheng/NoticeBar) - 😍A simple NoticeBar written by Swift 3, similar with QQ notice view. :large_orange_diamond: :star:229
* [LIHAlert](https://github.com/Lasithih/LIHAlert) - Advance animated banner alerts for iOS :large_orange_diamond: :star:24
* [BPStatusBarAlert](https://github.com/ppth0608/BPStatusBarAlert) - A simple alerts that appear on the status bar and below navigation bar(like Facebook).🔶 :star:75
* [CFAlertViewController](https://github.com/Codigami/CFAlertViewController) -  A library that helps you display and customise alerts and action sheets on iPad and iPhone.🔶 :star:835
* [NotificationBanner](https://github.com/Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS. 🔶 :star:1634
* [Alertift](https://github.com/sgr-ksmt/Alertift) - Swifty, modern UIAlertController wrapper. :large_orange_diamond: :star:83
* [PCLBlurEffectAlert](https://github.com/hryk224/PCLBlurEffectAlert) - Swift AlertController with UIVisualEffectView. :large_orange_diamond: :star:132
* [JDropDownAlert](https://github.com/trilliwon/JDropDownAlert) - Multi dirction dropdown alert view. 🔶 :star:38
* [BulletinBoard](https://github.com/alexaubry/BulletinBoard) - Generate and Display Bottom Card Interfaces on iOS :large_orange_diamond: :star:2270
* [Cards](https://github.com/PaoloCuscela/Cards) - Awesome iOS 11 AppStore's Card Views. :large_orange_diamond: :star:2224
* [CFNotify](https://github.com/hallelujahbaby/CFNotify) - A customizable framework to create draggable views. :large_orange_diamond: :star:385
* [StatusAlert](https://github.com/LowKostKustomz/StatusAlert) - Display Apple system-like self-hiding status alerts without interrupting user flow. :large_orange_diamond: :star:338
* [Alerts & Pickers](https://github.com/dillidon/Alerts-Pickers) - Advanced usage of native UIAlertController with TextField, DatePicker, PickerView, TableView and CollectionView. :large_orange_diamond: :star:666

#### Badge
* [MIBadgeButton](https://github.com/mustafaibrahim989/MIBadgeButton-Swift) - Notification badge for UIButtons. :large_orange_diamond: :star:294
* [EasyNotificationBadge](https://github.com/Minitour/EasyNotificationBadge) - UIView extension that adds a notification badge. :large_orange_diamond:[e] :star:40
* [Sheriff](https://github.com/gemr/Sheriff) - Add badges to anything. :star:243
* [swift-badge](https://github.com/evgenyneu/swift-badge) - Badge view for iOS written in swift :large_orange_diamond: :star:252

#### Button
* [SSBouncyButton](https://github.com/StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component. :star:300
* [DOFavoriteButton](https://github.com/okmr-d/DOFavoriteButton) - Cute Animated Button written in Swift. :large_orange_diamond: :star:2967
* [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) - Flat button with 9 different states animated using Facebook POP. :star:2906
* [HTPressableButton](https://github.com/Famolus/HTPressableButton) - Flat design pressable button. :star:825
* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state :large_orange_diamond: :star:3217
* [JTFadingInfoView](https://github.com/JunichiT/JTFadingInfoView) - An UIButton-based view with fade in/out animation features. :star:125
* [Floaty](https://github.com/kciter/Floaty) - :heart: Floating Action Button for iOS :large_orange_diamond: :star:630
* [TVButton](https://github.com/marmelroy/TVButton) - Recreating the cool parallax icons from Apple TV as iOS UIButtons (in Swift). :large_orange_diamond: :star:956
* [SwiftyButton](https://github.com/TakeScoop/SwiftyButton) - Simple and customizable button in Swift :large_orange_diamond: :star:268
* [AnimatablePlayButton](https://github.com/suzuki-0000/AnimatablePlayButton) - Animated Play and Pause Button using CALayer, CAKeyframeAnimation. :large_orange_diamond: :star:71
* [gbkui-button-progress-view](https://github.com/Guidebook/gbkui-button-progress-view) - Inspired by Apple’s download progress buttons in the App Store. :star:519
* [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) - Custom UIButton effect inspired by Google Material Design :large_orange_diamond: :star:1312
* [JOEmojiableBtn](https://github.com/lojals/JOEmojiableBtn) - Emoji selector like Facebook Reactions. :star:230
* [EMEmojiableBtn](https://github.com/Eke/EMEmojiableBtn) - Option selector that works similar to Reactions by fb. Objective-c version. :star:71
* [WYMaterialButton](https://github.com/Yu-w/WYMaterialButton) - Interactive and fully animated Material Design button for iOS developers. :star:63
* [DynamicButton](https://github.com/yannickl/DynamicButton) - Yet another animated flat buttons in Swift :large_orange_diamond: :star:883
* [OnOffButton](https://github.com/rakaramos/OnOffButton) - Custom On/Off Animated UIButton, written in Swift. By Creativedash :large_orange_diamond: :star:420
* [CRNetworkButton](https://github.com/Cleveroad/CRNetworkButton) - Send Button for iOS :large_orange_diamond: :star:622
* [WCLShineButton](https://github.com/imwcl/WCLShineButton) - This is a UI lib for iOS. Effects like shining. :large_orange_diamond: :star:1009
* [EasySocialButton](https://github.com/Minitour/EasySocialButton) - An easy way to create beautiful social authentication buttons. :large_orange_diamond: :star:134
* [NFDownloadButton](https://github.com/LeonardoCardoso/NFDownloadButton) - Revamped Download Button. 🔶 :star:285
* [LGButton](https://github.com/loregr/LGButton) - A fully customisable subclass of the native UIControl which allows you to create beautiful buttons without writing any line of code. :large_orange_diamond: :star:1544
* [MultiToggleButton](https://github.com/yonat/MultiToggleButton) - A UIButton subclass that implements tap-to-toggle button text (Like the camera flash and timer buttons). :large_orange_diamond: :star:30
* [PMSuperButton](https://github.com/Codeido/PMSuperButton) - A powerful UIButton with super powers, customizable from Storyboard! 🔶 :star:394
* [JSButton](https://github.com/imjog/JSButton) - A fully customisable swift subclass on UIButton which allows you to create beautiful buttons without writing any line of code. 🔶
* [TransitionButton](https://github.com/AladinWay/TransitionButton) - UIButton sublass for loading and transition animation :large_orange_diamond: :star:406
* [ButtonProgressBar-iOS](https://github.com/thePsguy/ButtonProgressBar-iOS) - A small and flexible UIButton subclass with animated loading progress, and completion animation. :large_orange_diamond: :star:244
* [SpicyButton](https://github.com/lukecrum/SpicyButton) - Full-featured IBDesignable UIButton class 🔶 :star:1
* [DesignableButton](https://github.com/IdleHandsApps/DesignableButton) - UIButton subclass with centralised and reusable styles. View styles and customise in InterfaceBuilder in real time! 🔶 :star:57

#### Calendar
* [CVCalendar](https://github.com/CVCalendar/CVCalendar) - A custom visual calendar for iOS 8+ written in Swift (2.0). :large_orange_diamond: :star:2845
* [RSDayFlow](https://github.com/ruslanskorb/RSDayFlow) - iOS 7+ Calendar with Infinite Scrolling. :star:772
* [NWCalendarView](https://github.com/nbwar/NWCalendarView) - An availability calendar implementation for iOS :large_orange_diamond: :star:56
* [FSCalendar](https://github.com/WenchaoD/FSCalendar) - A superiorly awesome iOS7+ calendar control, compatible with both Objective-C and Swift2. :star:5918
* [GLCalendarView](https://github.com/Glow-Inc/GLCalendarView) - A fully customizable calendar view acting as a date range picker :star:817
* [JTCalendar](https://github.com/jonathantribouharet/JTCalendar) - A customizable calendar view for iOS. :star:2483
* [JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar) - The Unofficial Swift Apple Calendar Library. View. Control. for iOS & tvOS :large_orange_diamond: :star:4230
* [Daysquare](https://github.com/unixzii/Daysquare) - An elegant calendar control for iOS. :star:629
* [ASCalendar](https://github.com/scamps88/ASCalendar) - A calendar control for iOS written in swift with mvvm pattern :large_orange_diamond: :star:189
* [Calendar](https://github.com/jumartin/Calendar) - A set of views and controllers for displaying and scheduling events on iOS :star:551
* [Koyomi](https://github.com/shoheiyokoyama/Koyomi) - Simple customizable calendar component in Swift :large_orange_diamond: :star:516
* [DateTimePicker](https://github.com/itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time :large_orange_diamond: :star:1329
* [RCalendarPicker](https://github.com/roycms/RCalendarPicker) - RCalendarPicker A date picker control. :star:63
* [CalendarKit](https://github.com/richardtop/CalendarKit) - Fully customizable calendar day view. :large_orange_diamond: :star:811
* [GDPersianCalendar](https://github.com/saeid/GDPersianCalendar) - Customizable and easy to use Persian Calendar component. 🔶 :star:4
* [MBCalendarKit](https://github.com/MosheBerman/MBCalendarKit) - A calendar framework for iOS built with customization, and localization in mind. :star:544
* [PTEventView](https://github.com/amantaneja/PTEventView) - An Event View based on Apple's Event Detail View within Calender.Supports ARC, Autolayout and editing via StoryBoard. 🔶 :star:23
* [KDCalendarView](https://github.com/mmick66/CalendarView) - A calendar component for iOS written in Swift 4.0. It features both vertical and horizontal layout (and scrolling) and the display of native calendar events. :star:112

#### Form & Settings
* [Form](https://github.com/hyperoslo/Form) - The most flexible and powerful way to build a form on iOS :star:1607
* [XLForm](https://github.com/xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms. Fully compatible with Swift & Obj-C. :star:4917
* [Eureka](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder in pure Swift. :large_orange_diamond: :star:7581
* [YALField](https://github.com/Yalantis/YALField) - Custom Field component with validation for creating easier form-like UI from interface builder. :star:456
* [Former](https://github.com/ra1028/Former) - Former is a fully customizable Swift2 library for easy creating UITableView based form. :large_orange_diamond: :star:966
* [SwiftForms](https://github.com/ortuman/SwiftForms) - A small and lightweight library written in Swift that allows you to easily create forms. :large_orange_diamond: :star:1141
* [APValidators](https://github.com/Alterplay/APValidators) - Codeless solution for form validation in iOS! :star:116
* [Formalist](https://github.com/seedco/Formalist) - Declarative form building framework for iOS :large_orange_diamond: :star:126
* [SwiftyFORM](https://github.com/neoneye/SwiftyFORM) - SwiftyFORM is a form framework for iOS written in Swift :large_orange_diamond: :star:730
* [FXForms](https://github.com/nicklockwood/FXForms) - FXForms is an Objective-C library for easily creating table-based forms on iOS. It is ideal for settings pages, or user data entry tasks. :star:3029
* [SwiftValidator](https://github.com/SwiftValidatorCommunity/SwiftValidator) - A rule-based validation library for Swift :large_orange_diamond: :star:989
* [MZFormSheetPresentationController](https://github.com/m1entus/MZFormSheetPresentationController) - MZFormSheetPresentationController provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet. :star:889
* [GenericPasswordRow](https://github.com/EurekaCommunity/GenericPasswordRow) - A row for Eureka to implement password validations. :large_orange_diamond: :star:141
* [SuggestionsBox](https://github.com/manuelescrig/SuggestionsBox) - SuggestionsBox helps you build better a product trough your user suggestions. :large_orange_diamond: :star:99
* [formvalidator-swift](https://github.com/ustwo/formvalidator-swift) - A framework to validate inputs of text fields and text views in a convenient way. :large_orange_diamond: :star:460
* [LightForm](https://github.com/farshidce/LightForm) - A Simple interactive and customizable library to handle form input and validations :star:6
* [ValidationToolkit](https://github.com/nsagora/validation-toolkit) - Lightweight framework for input validation written in Swift. :large_orange_diamond: :star:7

#### Keyboard
* [RSKKeyboardAnimationObserver](https://github.com/ruslanskorb/RSKKeyboardAnimationObserver) - Showing / dismissing keyboard animation in simple UIViewController category. :star:37
* [RFKeyboardToolbar](https://github.com/ruddfawcett/RFKeyboardToolbar) - This is a flexible UIView and UIButton subclass to add customized buttons and toolbars to your UITextFields/UITextViews. :star:406
* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView. :star:10783
* [NgKeyboardTracker](https://github.com/meiwin/NgKeyboardTracker) - Objective-C library for tracking keyboard in iOS apps. :star:775
* [MMNumberKeyboard](https://github.com/matmartinez/MMNumberKeyboard) - A simple keyboard to use with numbers and, optionally, a decimal point. :star:888
* [KeyboardObserver](https://github.com/morizotter/KeyboardObserver) - For less complicated keyboard event handling. :large_orange_diamond: :star:109
* [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS :star:5477
* [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) - iOS utility class allows you to access keyboard view and track keyboard animation. :star:395
* [KeyboardMan](https://github.com/nixzhu/KeyboardMan) - KeyboardMan helps you make keyboard animation. :large_orange_diamond: :star:334
* [MakemojiSDK](https://github.com/makemoji/MakemojiSDK) - Emoji Keyboard SDK (iOS)
* [Typist](https://github.com/totocaster/Typist) - Small, drop-in Swift UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center. :large_orange_diamond: :star:837
* [KeyboardHideManager](https://github.com/bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS written in Swift :large_orange_diamond: :star:49
* [Toolbar](https://github.com/1amageek/Toolbar) - Awesome autolayout Toolbar. :large_orange_diamond: :star:370
* [IHKeyboardAvoiding](https://github.com/IdleHandsApps/IHKeyboardAvoiding) - A drop-in universal solution for keeping any UIView visible when the keyboard is being shown - no more UIScrollViews! 🔶 :star:1088

#### Label
* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel written in Swift. :large_orange_diamond: :star:6128
* [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift :large_orange_diamond: :star:2122
* [MZTimerLabel](https://github.com/mineschan/MZTimerLabel) - A handy class for iOS to use UILabel as a countdown timer or stopwatch just like in Apple Clock App. :star:1379
* [CountdownLabel](https://github.com/suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function. :large_orange_diamond: :star:377
* [IncrementableLabel](https://github.com/tbaranes/IncrementableLabel) - Incrementable label for iOS, macOS, and tvOS. :large_orange_diamond: :star:36
* [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more :star:7944
* [NumberMorphView](https://github.com/me-abhinav/NumberMorphView) - A label view for displaying numbers which can transition or animate using a technique called number tweening or number morphing. :large_orange_diamond: :star:1337
* [GlitchLabel](https://github.com/kciter/GlitchLabel) - Glitching UILabel for iOS. :large_orange_diamond: :star:697
* [TOMSMorphingLabel](https://github.com/tomknig/TOMSMorphingLabel) - Configurable morphing transitions between text values of a label. :star:1847
* [THLabel](https://github.com/tobihagemann/THLabel) - UILabel subclass, which additionally allows shadow blur, inner shadow, stroke text and fill gradient. :star:555
* [RQShineLabel](https://github.com/zipme/RQShineLabel) - Secret app like text animation :star:1724
* [ZCAnimatedLabel](https://github.com/overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation :star:1854
* [TriLabelView](https://github.com/mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS written in Swift. :large_orange_diamond: :star:114
* [Preloader.Ophiuchus](https://github.com/Yalantis/Preloader.Ophiuchus) - Custom Label to apply animations on whole text or letters. :star:826
* [MTLLinkLabel](https://github.com/recruit-mtl/MTLLinkLabel) - MTLLinkLabel is linkable UILabel. Written in Swift. :large_orange_diamond: :star:71
* [UICountingLabel](https://github.com/dataxpress/UICountingLabel/) - Adds animated counting support to UILabel.
* [SlidingText](https://github.com/dnKaratzas/SlidingText) -  Swift UIView for sliding text with page indicator. :large_orange_diamond: :star:37
* [NumericAnimatedLabel](https://github.com/javalnanda/NumericAnimatedLabel/) -  Swift UIView for showing numeric label with incremental and decremental step animation while changing value. Useful for scenarios like displaying currency. :large_orange_diamond:
* [JSLabel](https://github.com/imjog/JSLabel/) -  A simple designable subclass on UILabel with extra IBDesignable and Blinking features. :large_orange_diamond:

#### Login
* [LFLoginController](https://github.com/awesome-labs/LFLoginController) - Customizable login screen, written in Swift. :large_orange_diamond: :star:95
* [LoginKit](https://github.com/IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.  🔶 :star:445
* [Cely](https://github.com/chaione/Cely) - Plug-n-Play login framework written in Swift. :large_orange_diamond: :star:92

#### Menu
* [ENSwiftSideMenu](https://github.com/evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift. :large_orange_diamond: :star:1718
* [RESideMenu](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect inspired by Dribbble shots. :star:7107
* [SSASideMenu](https://github.com/SSA111/SSASideMenu) - A Swift implementation of RESideMenu. A iOS 7/8 style side menu with parallax effect. :large_orange_diamond: :star:590
* [PagingMenuController](https://github.com/kitasuke/PagingMenuController) - Paging view controller with customizable menu in Swift. :large_orange_diamond: :star:2117
* [RadialMenu](https://github.com/bradjasper/radialmenu) - RadialMenu is a custom control for providing a touch context menu (like iMessage recording in iOS 8) built with Swift & POP :large_orange_diamond: :star:285
* [cariocamenu](https://github.com/arn00s/cariocamenu) - The fastest zero-tap iOS menu. :large_orange_diamond: :star:602
* [VLDContextSheet](https://github.com/vangelov/VLDContextSheet) - Context menu similar to the one in the Pinterest iOS app :star:168
* [GuillotineMenu](https://github.com/Yalantis/GuillotineMenu) - Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine. :large_orange_diamond: :star:2594
* [MediumMenu](https://github.com/pixyzehn/MediumMenu) - A menu based on Medium iOS app. :large_orange_diamond: :star:300
* [SwiftySideMenu](https://github.com/hossamghareeb/SwiftySideMenu) - SwiftySideMenu is a lightweight and easy to use side menu controller to add left menu and center view controllers with scale animation based on Pop framework. :star:80
* [LLSlideMenu](https://github.com/lilei644/LLSlideMenu) - This is a spring slide menu for iOS apps :star:562
* [Swift-Slide-Menu](https://github.com/PhilippeBoisney/Swift-Slide-Menu) - A Slide Menu, written in Swift, inspired by Slide Menu Material Design. :large_orange_diamond: :star:67
* [MenuItemKit](https://github.com/cxa/MenuItemKit) - UIMenuItem with image and block(closure) :large_orange_diamond: :star:341
* [BTNavigationDropdownMenu](https://github.com/PhamBaTho/BTNavigationDropdownMenu) - The elegant dropdown menu, written in Swift, appears underneath navigation bar to display a list of related items when a user click on the navigation title. :large_orange_diamond: :star:2195
* [ALRadialMenu](https://github.com/AlexLittlejohn/ALRadialMenu) - A radial/circular menu featuring spring animations. Written in swift :large_orange_diamond: :star:36
* [AZDropdownMenu](https://github.com/Azuritul/AZDropdownMenu) - An easy to use dropdown menu that supports images. :large_orange_diamond: :star:168
* [CircleMenu](https://github.com/Ramotion/circle-menu) - An animated, multi-option menu button. :large_orange_diamond: :star:2513
* [SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure Swift. :large_orange_diamond: :star:2885
* [SideMenu](https://github.com/jonkykong/SideMenu) - Simple side menu control in Swift inspired by Facebook. Right and Left sides. Lots of customization and animation options. Can be implemented in Storyboard with no code. :large_orange_diamond: :star:2143
* [CategorySliderView](https://github.com/cemolcay/CategorySliderView) - slider view for choosing categories. add any UIView type as category item view. Fully customisable :star:359
* [MKDropdownMenu](https://github.com/maxkonovalov/MKDropdownMenu) - A Dropdown Menu for iOS with many customizable parameters to suit any needs. :star:354
* [ExpandingMenu](https://github.com/monoqlo/ExpandingMenu) - ExpandingMenu is menu button for iOS written in Swift. :large_orange_diamond: :star:281
* [PageMenu](https://github.com/PageMenu/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) :large_orange_diamond: :star:4504
* [XXXRoundMenuButton](https://github.com/zsy78191/XXXRoundMenuButton) - A simple circle style menu. :star:297
* [IGCMenu](https://github.com/sunilsharma08/IGCMenu) - Grid and Circular menu with animation.Easy to customise. :star:92
* [EEJSelectMenu](https://github.com/eejahromi/EEJSelectMenu) - Single selection menu with cool animations, responsive with all screen sizes. :star:17
* [IGLDropDownMenu](https://github.com/bestwnh/IGLDropDownMenu) - An iOS drop down menu with pretty animation and easy to customize. :star:1127
* [Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS) - Animated side menu with customizable UI :large_orange_diamond: :star:2520
* [PopMenu](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app. :star:829
* [FlowingMenu](https://github.com/yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects in Swift :large_orange_diamond: :star:768
* [Persei](https://github.com/Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift :large_orange_diamond: :star:2906
* [DropDown](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS :large_orange_diamond: :star:1040
* [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) - A not bad gooey effects menu. :star:1755
* [SideMenuController](https://github.com/teodorpatras/SideMenuController) - A side menu controller written in Swift :large_orange_diamond: :star:943
* [Context-Menu.iOS](https://github.com/Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app. :star:1816
* [ViewDeck](https://github.com/ViewDeck/ViewDeck) - An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps. :star:5258
* [FrostedSidebar](https://github.com/edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's :large_orange_diamond: :star:435
* [VHBoomMenuButton](https://github.com/Nightonke/VHBoomMenuButton) - A menu which can ... BOOM! :star:442
* [DropDownMenuKit](https://github.com/qmathe/DropDownMenuKit) - A simple, modular and highly customizable UIKit menu, that can be attached to the navigation bar or toolbar, written in Swift. :large_orange_diamond: :star:146
* [RevealMenuController](https://github.com/anatoliyv/RevealMenuController) - Expandable item groups, custom position and appearance animation. Similar to ActionSheet style. :large_orange_diamond: :star:16
* [RHSideButtons](https://github.com/robertherdzik/RHSideButtons) - Library provides easy to implement variation of Android (Material Design) Floating Action Button for iOS. You can use it as your app small side menu. :large_orange_diamond: :star:57
* [Swift-CircleMenu](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) - Rotating circle menu written in Swift 3. :large_orange_diamond: :star:108
* [AKSideMenu](https://github.com/dogo/AKSideMenu) - Beautiful iOS side menu library with parallax effect. :large_orange_diamond: :star:107
* [InteractiveSideMenu](https://github.com/handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu written in Swift 3. :large_orange_diamond: :star:362
* [YNDropDownMenu](https://github.com/younatics/YNDropDownMenu) - Adorable iOS drop down menu with Swift3. :large_orange_diamond: :star:833
* [KWDrawerController](https://github.com/Kawoou/KWDrawerController) - Drawer view controller that easy to use! :large_orange_diamond: :star:58
* [JNDropDownMenu](https://github.com/javalnanda/JNDropDownMenu) - Easy to use tableview style drop down menu with multi-column support written in Swift3. :large_orange_diamond: :star:49
* [FanMenu](https://github.com/exyte/fan-menu) - Menu with a circular layout based on Macaw. :large_orange_diamond: :star:236
* [AirBar](https://github.com/uptechteam/AirBar) - UIScrollView driven expandable menu written in Swift 3. :large_orange_diamond: :star:161
* [FAPanels](https://github.com/fahidattique55/FAPanels) - FAPanels for transition :large_orange_diamond: :star:575
* [SwipeMenuViewController](https://github.com/yysskk/SwipeMenuViewController) - Swipable tab and menu View and ViewController. :large_orange_diamond: :star:401
* [DTPagerController](https://github.com/tungvoduc/DTPagerController) - A fully customizable container view controller to display set of ViewControllers in horizontal scroller 🔶 :star:59
* [PagingKit](https://github.com/kazuhiro4949/PagingKit) - PagingKit provides customizable menu UI It has more flexible layout and design than the other libraries.  🔶 :star:571
* [Dropdowns](https://github.com/hyperoslo/Dropdowns) - 💧 Dropdown in Swift :star:94

#### Navigation Bar
* [HidingNavigationBar](https://github.com/tristanhimmelman/HidingNavigationBar) - Easily hide and show a view controller's navigation bar (and tab bar) as a user scrolls :large_orange_diamond: :star:679
* [TLYShyNavBar](https://github.com/telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars! :star:3480
* [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations. :star:2345
* [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) - UINavigationBar Category which allows you to change its appearance dynamically :star:4301
* [BusyNavigationBar](https://github.com/gmertk/BusyNavigationBar) - A UINavigationBar extension to show loading effects :large_orange_diamond: :star:886
* [KDInteractiveNavigationController](https://github.com/kingiol/KDInteractiveNavigationController) - A UINavigationController subclass that support pop interactive UINavigationbar with hidden or show. :large_orange_diamond: :star:124
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView :large_orange_diamond: :star:5130
* [NavKit](https://github.com/wilbertliu/NavKit) - Simple and integrated way to customize navigation bar experience on iOS app. :large_orange_diamond: :star:27

#### PickerView
* [ActionSheetPicker-3.0](https://github.com/skywinder/ActionSheetPicker-3.0/) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
* [PickerView](https://github.com/filipealva/PickerView) - A customizable alternative to UIPickerView in Swift. :large_orange_diamond: :star:306
* [DatePickerDialog](https://github.com/squimer/DatePickerDialog-iOS-Swift) - Date picker dialog for iOS :large_orange_diamond: :star:332
* [CZPicker](https://github.com/chenzeyu/CZPicker) - A picker view shown as a popup for iOS. :star:489
* [AIDatePickerController](https://github.com/alikaragoz/AIDatePickerController) - :date: UIDatePicker modally presented with iOS 7 custom transitions. :star:88
* [CountryPicker](https://github.com/4taras4/CountryCode) - :date: UIPickerView with Country names flags and phoneCodes 🔶 :star:75
* [McPicker](https://github.com/kmcgill88/McPicker-iOS) - A customizable, closure driven UIPickerView drop-in solution with animations that is rotation ready. :large_orange_diamond: :star:54
* [Mandoline](https://github.com/blueapron/Mandoline) - An iOS picker view to serve all your "picking" needs :large_orange_diamond: :star:617
* [D2PDatePicker](https://github.com/di2pra/D2PDatePicker) - Elegant and Easy-to-Use iOS Swift Date Picker :large_orange_diamond: :star:191
* [CountryPickerView](https://github.com/kizitonwose/CountryPickerView)- A simple, customizable view for efficiently collecting country information in iOS apps :large_orange_diamond: 

#### Popup
* [PopupKit](https://github.com/rynecheow/PopupKit) - A simple and flexible class for presenting custom views as a popup in iOS and tvOS, maintained from [KLCPopup](https://github.com/jmascia/KLCPopup). :star:28
* [MMPopupView](https://github.com/adad184/MMPopupView) - Pop-up based view(e.g. alert sheet), can easily customize. :star:1827
* [STPopup](https://github.com/kevin0571/STPopup) - STPopup provides a UINavigationController in popup style, for both iPhone and iPad. :star:2079
* [NMPopUpView](https://github.com/psy2k/NMPopUpView) - Simple iOS class for showing nice popup windows. Swift and Objective-C versions available. :large_orange_diamond: :star:170
* [CNPPopupController](https://github.com/carsonperrotti/CNPPopupController) - Simple and versatile class for presenting a custom popup in a variety of fashions. It includes a many options for controlling how your popup appears and behaves. :star:1600
* [PopupController](https://github.com/daisuke310vvv/PopupController) - A customizable controller for showing temporary popup view. :star:229
* [SubscriptionPrompt](https://github.com/binchik/SubscriptionPrompt) - Subscription View Controller like the Tinder uses :large_orange_diamond: :star:206
* [Presentr](https://github.com/IcaliaLabs/Presentr) - Wrapper for custom ViewController presentations in iOS 8+ :large_orange_diamond: :star:1714
* [PopupDialog](https://github.com/Orderella/PopupDialog) - A simple, customizable popup dialog for iOS written in Swift. Replaces UIAlertControllers alert style. :large_orange_diamond: :star:2329
* [SelectionDialog](https://github.com/kciter/SelectionDialog) - Simple selection dialog. :large_orange_diamond: :star:78
* [AZDialogViewController](https://github.com/Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog. :large_orange_diamond: :star:533
* [MIBlurPopup](https://github.com/MarioIannotta/MIBlurPopup) - MIBlurPopup let you create amazing popups with a blurred background. :star:378
* [LNPopupController](https://github.com/LeoNatan/LNPopupController) - a framework for presenting view controllers as popups of other view controllers, much like the Apple Music and Podcasts apps. :star:2045
* [PopupWindow](https://github.com/shin8484/PopupWindow) - PopupWindow is a simple Popup using another UIWindow in Swift. :large_orange_diamond: :star:161
* [SHPopup](https://github.com/iamshezad/SHPopup) - SHPopup is a simple lightweight library for popup view. :large_orange_diamond: :star:15


#### ProgressView
* [ProgressMeter](https://github.com/khawajafarooq/ProgressMeter) - Display the progress on a meter with customized annotations for iOS developed in Swift :large_orange_diamond: :star:61

#### Pull to Refresh
* [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift :large_orange_diamond: :star:3027
* [PullToBounce](https://github.com/entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView. :large_orange_diamond: :star:1680
* [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) - Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code. http://samvermette.com/314 :star:4853
* [UzysAnimatedGifPullToRefresh](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh) - Add PullToRefresh using animated GIF to any scrollView with just simple code :star:1412
* [PullToRefreshCoreText](https://github.com/cemolcay/PullToRefreshCoreText) - PullToRefresh extension for all UIScrollView type classes with animated text drawing style :star:315
* [BOZPongRefreshControl](https://github.com/boztalay/BOZPongRefreshControl) - A pull-down-to-refresh control for iOS that plays pong, originally created for the MHacks III iOS app :star:901
* [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - Fully customizable pull-to-refresh control inspired by Storehouse iOS app :star:3979
* [SurfingRefreshControl](https://github.com/peiweichen/SurfingRefreshControl) - Inspired by CBStoreHouseRefreshControl.Customizable pull-to-refresh control,written in pure Swift :large_orange_diamond: :star:52
* [mntpulltoreact](https://github.com/mentionapp/mntpulltoreact) - One gesture, many actions. An evolution of Pull to Refresh. :star:782
* [ADChromePullToRefresh](https://github.com/Antondomashnev/ADChromePullToRefresh) - Chrome iOS app style pull to refresh with multiple actions. :star:236
* [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit. :large_orange_diamond: :star:2198
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) An easy way to use pull-to-refresh.
* [HTPullToRefresh](https://github.com/hoang-tran/HTPullToRefresh) - Easily add vertical and horizontal pull to refresh to any UIScrollView. Can also add multiple pull-to-refesh views at once. :star:29
* [PullToRefreshSwift](https://github.com/dekatotoro/PullToRefreshSwift) - iOS Simple Cool PullToRefresh Library. It is written in pure swift. :large_orange_diamond: :star:498
* [GIFRefreshControl](https://github.com/delannoyk/GIFRefreshControl) - GIFRefreshControl is a pull to refresh that supports GIF images as track animations. :large_orange_diamond: :star:133
* [ReplaceAnimation](https://github.com/fruitcoder/ReplaceAnimation) - Pull-to-refresh animation in UICollectionView with a sticky header flow layout, written in Swift :large_orange_diamond: :large_orange_diamond: :star:821
* [PullToMakeSoup](https://github.com/Yalantis/PullToMakeSoup) - Custom animated pull-to-refresh that can be easily added to UIScrollView :large_orange_diamond: :star:1734
* [RainyRefreshControl](https://github.com/Onix-Systems/RainyRefreshControl) - Simple refresh control for iOS inspired by [concept](https://dribbble.com/shots/2242263--1-Pull-to-refresh-Freebie-Weather-Concept). :large_orange_diamond: :star:613
* [ESPullToRefresh](https://github.com/eggswift/pull-to-refresh) - Customisable pull-to-refresh, including nice animation on the top :large_orange_diamond: :star:796
* [CRRefresh](https://github.com/CRAnimation/CRRefresh) - An easy way to use pull-to-refresh. :large_orange_diamond: :star:415

#### Rating Stars
* [FloatRatingView](https://github.com/glenyi/FloatRatingView) - Whole, half or floating point ratings control written in Swift :large_orange_diamond: :star:409
* [TTGEmojiRate](https://github.com/zekunyan/TTGEmojiRate) - An emoji-liked rating view for iOS, implemented in Swift. :large_orange_diamond: :star:233
* [StarryStars](https://github.com/peterprokop/StarryStars) - StarryStars is iOS GUI library for displaying and editing ratings :large_orange_diamond: :star:139
* [Cosmos](https://github.com/evgenyneu/Cosmos) - A star rating control for iOS / Swift :large_orange_diamond: :star:884
* [HCSStarRatingView](https://github.com/hsousa/HCSStarRatingView) - Simple star rating view for iOS written in Objective-C :star:1062
* [MBRateApp](https://github.com/MatiBot/MBRateApp) - A groovy app rate stars screen for iOS written in Swift :large_orange_diamond: :star:53

#### ScrollView
* [ScrollingFollowView](https://github.com/ktanaka117/ScrollingFollowView) - ScrollingFollowView is a simple view which follows UIScrollView scrolling. :star:142
* [UIScrollView-InfiniteScroll](https://github.com/pronebird/UIScrollView-InfiniteScroll) - UIScrollView infinite scroll category. :star:790
* [GoAutoSlideView](https://github.com/zjmdp/GoAutoSlideView) - GoAutoSlideView extends UIScrollView by featuring infinitely and automatically slide. :star:48
* [AppStoreStyleHorizontalScrollView](https://github.com/terenceLuffy/AppStoreStyleHorizontalScrollView) - App store style horizontal scroll view. :large_orange_diamond: :star:590
* [PullToDismiss](https://github.com/sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar in Swift. :large_orange_diamond: :star:202
* [SpreadsheetView](https://github.com/kishikawakatsumi/SpreadsheetView) - Full configurable spreadsheet view user interfaces for iOS applications. With this framework, you can easily create complex layouts like schedule, gantt chart or timetable as if you are using Excel. :large_orange_diamond: :star:2185
*  [VegaScroll](https://github.com/AppliKeySolutions/VegaScroll) - VegaScroll is a lightweight animation flowlayout for UICollectionView completely written in Swift 4, compatible with iOS 11 and Xcode 9 :large_orange_diamond:
*  [ShelfView-iOS](https://github.com/tdscientist/ShelfView-iOS) - iOS custom view to display books on shelf :large_orange_diamond:

#### Segmented Control
* [BetterSegmentedControl](https://github.com/gmarm/BetterSegmentedControl) - An easy to use, customizable replacement for UISegmentedControl & UISwitch. :large_orange_diamond: :star:925
* [LUNSegmentedControl](https://github.com/Stormotion-Mobile/LUNSegmentedControl) - Customizable segmented control with interactive animation. :star:220
* [AKASegmentedControl](https://github.com/alikaragoz/AKASegmentedControl) - :chocolate_bar: Fully customizable Segmented Control for iOS. :star:403
* [TwicketSegmentedControl](https://github.com/twicketapp/TwicketSegmentedControl) - Custom UISegmentedControl replacement for iOS, written in Swift. :large_orange_diamond: :star:1232
* [SJFluidSegmentedControl](https://github.com/sasojadrovski/SJFluidSegmentedControl) - A segmented control with custom appearance and interactive animations. Written in Swift 3.0. :large_orange_diamond: :star:713
* [HMSegmentedControl](https://github.com/HeshamMegid/HMSegmentedControl) - A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products. :star:3250
* [YUSegment](https://github.com/afishhhhh/YUSegment) - A customizable segmented control for iOS. Supports both text and image. :star:94
* [MultiSelectSegmentedControl](https://github.com/yonat/MultiSelectSegmentedControl) - adds Multiple-Selection to the standard `UISegmentedControl`. :star:78
* [DynamicMaskSegmentSwitch](https://github.com/KittenYang/DynamicMaskSegmentSwitch) - A segment switcher with dynamic text mask effect :large_orange_diamond: :star:289
* [PinterestSegment](https://github.com/TBXark/PinterestSegment) - A Pinterest-like segment control with masking animation. :large_orange_diamond: :star:298
* [Rotary](https://github.com/rob-nash/Rotary) - A customisable rotary wheel composed of selectable segments. :large_orange_diamond: :star:6

#### Slider
* [VolumeControl](https://github.com/12Rockets/VolumeControl) - Custom volume control for iPhone featuring a well-designed round slider. :star:61
* [WESlider](https://github.com/Ekhoo/WESlider) - Simple and light weight slider with chapter management :star:81
* [IntervalSlider](https://github.com/shushutochako/IntervalSlider) - IntervalSlider is a slider library like ReutersTV app. written in pure swift. :large_orange_diamond: :star:50
* [RangeSlider](https://github.com/warchimede/RangeSlider) - A simple range slider made in Swift :large_orange_diamond: :star:169
* [CircleSlider](https://github.com/shushutochako/CircleSlider) - CircleSlider is a Circular slider library. written in pure Swift. :large_orange_diamond: :star:107
* [MARKRangeSlider](https://github.com/vadymmarkov/MARKRangeSlider) - A custom reusable slider control with 2 thumbs (range slider). :star:141
* [ASValueTrackingSlider](https://github.com/alskipp/ASValueTrackingSlider) - A UISlider subclass that displays the slider value in a popup view :star:1737
* [TTRangeSlider](https://github.com/TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range. :star:667
* [MMSegmentSlider](https://github.com/MedvedevMax/MMSegmentSlider) - Customizable animated slider for iOS. :star:29
* [StepSlider](https://github.com/spromicky/StepSlider) - StepSlider its custom implementation of slider such as UISlider for preset integer values. :star:157
* [JDSlider](https://github.com/JellyDevelopment/JDSlider) - An iOS Slider written in Swift. :large_orange_diamond: :star:76
* [SnappingSlider](https://github.com/rehatkathuria/SnappingSlider) - A beautiful slider control for iOS built purely upon Swift :large_orange_diamond: :star:532
* [MTCircularSlider](https://github.com/EranBoudjnah/MTCircularSlider) - A feature-rich circular slider control. :large_orange_diamond: :star:23
* [VerticalSlider](https://github.com/jonkykong/VerticalSlider) - VerticalSlider is a vertical implementation of the UISlider slider control. :large_orange_diamond: :star:33
* [CircularSlider](https://github.com/taglia3/CircularSlider) - A powerful Circular Slider. It's written in Swift, it's 100% IBDesignable and all parameters are IBInspectable. :large_orange_diamond: :star:168
* [HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application. :large_orange_diamond: :star:1284
* [PivotSlider](https://github.com/dereklimbus/pivot-slider) - Slider that pivots :large_orange_diamond: :star:25
* [RangeSeekSlider](https://github.com/WorldDownTown/RangeSeekSlider) - A customizable range slider for iOS. :large_orange_diamond: :star:178
* [SectionedSlider](https://github.com/LeonardoCardoso/SectionedSlider) - Control Center Slider. :large_orange_diamond: :star:155
* [MultiSlider](https://github.com/yonat/MultiSlider) - UISlider clone with multiple thumbs and values, optional snap intervals, optional value labels. :large_orange_diamond: :star:7
* [AGCircularPicker](https://github.com/agilie/AGCircularPicker) - AGCircularPicker is helpful component for creating a controller aimed to manage any calculated parameter. :large_orange_diamond: :star:433
* [VSVerticalSlider](https://github.com/vsmithers1087/VSVerticalSlider) - An animatable and customizable vertical slider written in Swift4.🔶 :star:12
* [Fluid Slider](https://github.com/Ramotion/fluid-slider) - A slider widget with a popup bubble displaying the precise value selected. :large_orange_diamond: :star:814

#### Splash View
* [CBZSplashView](https://github.com/callumboddy/CBZSplashView) - Twitter style Splash Screen View. Grows to reveal the Initial view behind. :star:1442
* [SKSplashView](https://github.com/sachinkesiraju/SKSplashView) - Create custom animated splash views similar to the ones in the Twitter, Uber and Ping iOS app. :star:455
* [RevealingSplashView](https://github.com/PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by Twitter splash :large_orange_diamond: :star:817

#### Stepper
* [PFStepper](https://github.com/PerfectFreeze/PFStepper) - May be the most elegant stepper you have ever had! :large_orange_diamond: :star:24
* [ValueStepper](https://github.com/BalestraPatrick/ValueStepper) - A Stepper object that displays its value. :large_orange_diamond: :star:223
* [GMStepper](https://github.com/gmertk/GMStepper) - A stepper with a sliding label in the middle. :large_orange_diamond: :star:581
* [barceloneta](https://github.com/arn00s/barceloneta) - The right way to increment/decrement values with a simple gesture on iOS. :large_orange_diamond: :star:39
* [SnappingStepper](https://github.com/yannickl/SnappingStepper) - An elegant alternative to the UIStepper written in Swift :large_orange_diamond: :star:331
* [SMNumberWheel](https://github.com/SinaMoetakef/SMNumberWheel) - A custom control written in Swift, which is ideal for picking numbers very fast but yet very accurate using a rotating wheel :large_orange_diamond: :star:16

#### Switch
* [AnimatedSwitch](https://github.com/alsedi/AnimatedSwitch) - UISwitch which paints over the parent view with the color in Swift. :large_orange_diamond: :star:166
* [ViralSwitch](https://github.com/andreamazz/ViralSwitch) - A UISwitch that infects its superview with its tint color. :star:319
* [JTMaterialSwitch](https://github.com/JunichiT/JTMaterialSwitch) - A customizable switch UI with ripple effect and bounce animations, inspired from Google's Material Design. :star:241
* [TKSwitcherCollection](https://github.com/TBXark/TKSwitcherCollection) - An animate switch collection :large_orange_diamond: :star:523
* [SevenSwitch](https://github.com/bvogelzang/SevenSwitch) - iOS7 style drop in replacement for UISwitch. :large_orange_diamond: :star:752
* [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch) - Runkeeper design switch control (two part segment control) :large_orange_diamond: :star:1826
* [PMZSwitch](https://github.com/kovpas/PMZSwitch) - Yet another animated toggle :large_orange_diamond: :star:58
* [Switcher](https://github.com/knn90/Switcher) - Swift - Custom UISwitcher with animation when change status :large_orange_diamond: :star:174
* [RAMPaperSwitch](https://github.com/Ramotion/paper-switch) - RAMPaperSwitch is a Swift module which paints over the parent view when the switch is turned on. :large_orange_diamond: :star:2394
* [AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch) - A flat component alternative to UISwitch on iOS :large_orange_diamond: :star:658
* [Switch](https://github.com/T-Pham/Switch) - An iOS switch control implemented in Swift with full Interface Builder support.🔶 :star:77

#### Tab Bar
* [ESTabBarController](https://github.com/ezescaruli/ESTabBarController) - A tab bar controller for iOS that allows highlighting buttons and setting custom actions to them. :star:98
* [GooeyTabbar](https://github.com/KittenYang/GooeyTabbar) -A gooey effect tabbar :large_orange_diamond:
* [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift module for adding animation to tabbar items. :large_orange_diamond: :star:8491
* [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) - Folding Tab Bar and Tab Bar Controller :star:3456
* [GGTabBar](https://github.com/Goles/GGTabBar) - Another UITabBar & UITabBarController (iOS Tab Bar) replacement, but uses Auto Layout for arranging it's views hierarchy. :star:153
* [adaptive-tab-bar](https://github.com/Ramotion/adaptive-tab-bar) - AdaptiveController is a 'Progressive Reduction' Swift module for adding custom states to Native or Custom iOS UI elements :large_orange_diamond: :star:1805
* [Pager](https://github.com/lucoceano/Pager) - Easily create sliding tabs with Pager :large_orange_diamond: :star:202
* [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS. :large_orange_diamond: :star:4723
* [TabPageViewController](https://github.com/EndouMari/TabPageViewController) - Paging view controller and scroll tab view. 🔶 :star:766
* [TabDrawer](https://github.com/winslowdibona/TabDrawer) - Customizable TabBar UI element that allows you to run a block of code upon TabBarItem selection, written in Swift 🔶 :star:497
* [SwipeViewController](https://github.com/fortmarek/SwipeViewController) - SwipeViewController is a Swift modification of RKSwipeBetweenViewControllers - navigate between pages / ViewControllers :large_orange_diamond: :star:465
* [ColorMatchTabs](https://github.com/Yalantis/ColorMatchTabs) - Interesting way to display tabs :large_orange_diamond: :star:1001
* [BATabBarController](https://github.com/antiguab/BATabBarController) - A TabBarController with a unique animation for selection :star:658
* [ScrollPager](https://github.com/aryaxt/ScrollPager) - A scroll pager that displays a list of tabs (segments) and manages paging between given views :large_orange_diamond: :star:439
* [Segmentio](https://github.com/Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift. :large_orange_diamond: :star:1536
* [KYWheelTabController](https://github.com/ykyouhei/KYWheelTabController) - KYWheelTabController is a subclass of UITabBarController.It displays the circular menu instead of UITabBar. :large_orange_diamond: :star:91
* [SuperBadges](https://github.com/odedharth/SuperBadges) - Add emojis and colored dots as badges for your Tab Bar buttons 🔶 :star:22
* [AZTabBarController](https://github.com/Minitour/AZTabBarController) - A custom tab bar controller for iOS written in Swift 3.0 🔶 :star:122
* [MiniTabBar](https://github.com/D-32/MiniTabBar) - A clean simple alternative to the UITabBar 🔶 :star:66
* [SwipeableTabBarController](https://github.com/marcosgriselli/SwipeableTabBarController) - UITabBarController with swipe interaction between its tabs. 🔶 :star:170
* [SMSwipeableTabView](https://github.com/smahajan28/SMSwipeableTabView) - Swipeable Views with Tabs (Like Android SwipeView With Tabs Layout) 🔶 :star:29
* [Tabman](https://github.com/uias/Tabman) - A powerful paging view controller with indicator bar for iOS. 🔶 :star:808
* [WormTabStrip](https://github.com/EzimetYusup/WormTabStrip) Beatiful ViewPager For iOS written in Swift 🔶 (inspired by Android [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout))

#### Table View / Collection View
* [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions. :star:6032
* [ParallaxTableViewHeader](https://github.com/Vinodh-G/ParallaxTableViewHeader) - Parallax scrolling effect on UITableView header view when a tableView is scrolled. :star:1275
* [YXTPageView](https://github.com/hanton/YXTPageView) - A PageView, which supporting scrolling to transition between a UIView and a UITableView. :star:61
* [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display. :star:9712
* [ConfigurableTableViewController](https://github.com/fastred/ConfigurableTableViewController) - Typed, yet Flexible Table View Controller http://holko.pl/2016/01/05/typed-table-view-controller/ :large_orange_diamond: :star:243
* [CSStickyHeaderFlowLayout](https://github.com/CSStickyHeaderFlowLayout/CSStickyHeaderFlowLayout) - UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. :large_orange_diamond: :star:4858
* [folding-cell](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell inspired by folding paper material :large_orange_diamond: :star:6872
* [Lightning-Table](https://github.com/electrickangaroo/Lightning-Table) - A declarative api for working with UITableView. :star:22
* [Static](https://github.com/venmo/Static) - Simple static table views for iOS in Swift. :large_orange_diamond: :star:1016
* [GSKStretchyHeaderView](https://github.com/gskbyte/GSKStretchyHeaderView) - Configurable yet easy to use stretchy header view for UITableView and UICollectionView. :star:1089
* [MEVFloatingButton](https://github.com/manuelescrig/MEVFloatingButton) - An iOS drop-in UITableView, UICollectionView and UIScrollView superclass category for showing a customizable floating button on top of it. :star:283
* [AMWaveTransition](https://github.com/andreamazz/AMWaveTransition) - Custom transition between viewcontrollers holding tableviews. :star:2356
* [Dwifft](https://github.com/jflinter/Dwifft) - Swift Diff :large_orange_diamond: :star:1469
* [AEAccordion](https://github.com/tadija/AEAccordion) - UITableViewController with accordion effect (expand / collapse cells). :large_orange_diamond: :star:168
* [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) - An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)
* [ZYThumbnailTableView](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - a TableView have thumbnail cell only, and you can use gesture let it expands other expansionView, all diy :large_orange_diamond: :star:897
* [BWSwipeRevealCell](https://github.com/bitwit/BWSwipeRevealCell) - A Swift library for swipeable table cells :large_orange_diamond: :star:48
* [preview-transition](https://github.com/Ramotion/preview-transition) - PreviewTransition is a simple preview gallery controller :large_orange_diamond: :star:1652
* [QuickTableViewController](https://github.com/bcylin/QuickTableViewController) - A simple way to create a UITableView for settings in Swift. :large_orange_diamond: :star:124
* [TableKit](https://github.com/maxsokolov/TableKit) - Type-safe declarative table views with Swift :large_orange_diamond: :star:302
* [Preheat](https://github.com/kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView :large_orange_diamond: :star:594
* [VBPiledView](https://github.com/v-braun/VBPiledView) - Simple and beautiful stacked UIView to use as a replacement for an UITableView, UIImageView or as a menu :large_orange_diamond: :star:127
* [DisplaySwitcher](https://github.com/Yalantis/DisplaySwitcher) - Custom transition between two collection view layouts :large_orange_diamond: :star:1647
* [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView. :star:3523
* [FMMosaicLayout](https://github.com/fmitech/FMMosaicLayout) - A drop-in mosaic collection view layout with a focus on simple customizations. :star:571
* [mosaic-layout](https://github.com/vinnyoodles/mosaic-layout) - A mosaic collection view layout inspired by Lightbox's Algorithm, written in Swift :large_orange_diamond: :star:174
* [Reusable](https://github.com/AliSoftware/Reusable) - A Swift mixin for UITableViewCells and UICollectionViewCells :large_orange_diamond: :star:1401
* [VTMagic](https://github.com/tianzhuo112/VTMagic) - VTMagic is a page container library for iOS. :star:1525
* [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - :point_up_2: Convenient UITableViewCell subclass that implements a swippable content to trigger actions (similar to the Mailbox app). :star:3024
* [Sapporo](https://github.com/nghialv/Sapporo) - Cellmodel-driven collectionview manager :large_orange_diamond: :star:232
* [MYTableViewIndex](https://github.com/mindz-eye/MYTableViewIndex) - A pixel perfect replacement for UITableView section index, written in Swift :large_orange_diamond: :star:329
* [RAReorderableLayout](https://github.com/ra1028/RAReorderableLayout) - A UICollectionView layout which can move item with drag and drop. :star:798
* [StickyCollectionView-Swift](https://github.com/matbeich/StickyCollectionView-Swift) - UICollectionView layout for presenting of the overlapping cells. :large_orange_diamond: :star:218
* [ios-dragable-table-cells](https://github.com/palmin/ios-dragable-table-cells) - Support for drag-n-drop of UITableViewCells in a navigation hierarchy of view controllers. You drag cells by tapping and holding them. :star:39
* [TLLayoutTransitioning](https://github.com/SwiftKickMobile/TLLayoutTransitioning) - Enhanced transitioning between UICollectionView layouts in iOS. :star:338
* [Bohr](https://github.com/DavdRoman/Bohr) - Bohr allows you to set up a settings screen for your app with three principles in mind: ease, customization and extensibility. :star:1249
* [SwiftReorder](https://github.com/adamshin/SwiftReorder) - Add drag-and-drop reordering to any table view with just a few lines of code. Robust, lightweight, and completely customizable. :large_orange_diamond:[e] :star:81
* [TLIndexPathTools](https://github.com/SwiftKickMobile/TLIndexPathTools) - TLIndexPathTools is a small set of classes that can greatly simplify your table and collection views. :star:336
* [HoverConversion](https://github.com/marty-suzuki/HoverConversion) - HoverConversion realized vertical paging with UITableView. UIViewController will be paging when reaching top or bottom of UITableView contentOffset. :large_orange_diamond: :star:166
* [TableViewDragger](https://github.com/KyoheiG3/TableViewDragger) - A cells of UITableView can be rearranged by drag and drop. :large_orange_diamond: :star:314
* [IGListKit](https://github.com/Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists. :star:7438
* [MMCardView](https://github.com/MillmanY/MMCardView) - Custom CollectionView like Wallet App :large_orange_diamond: :star:438
* [FlexibleTableViewController](https://github.com/dimpiax/FlexibleTableViewController) - Swift library of generic table view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler :star:10
* [FlexibleCollectionViewController](https://github.com/dimpiax/FlexibleCollectionViewController) - Swift library of generic collection view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler etc :star:1
* [CascadingTableDelegate](https://github.com/edopelawi/CascadingTableDelegate) - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.:large_orange_diamond: :star:801
* [TimelineTableViewCell](https://github.com/kf99916/TimelineTableViewCell) - Simple timeline view implemented by UITableViewCell written in Swift 3.0.:large_orange_diamond: :star:828
* [RHPreviewCell](https://github.com/robertherdzik/RHPreviewCell) - I envied so much Spotify iOS app this great playlist preview cell. Now you can give your users ability to quick check "what content is hidden under your UITableViewCell". :large_orange_diamond: :star:333
* [ThreeLevelAccordian](https://github.com/amratab/ThreeLevelAccordian) - This is a customisable three level accordian with options for adding images and accessories images. :large_orange_diamond: :star:32
* [TORoundedTableView](https://github.com/TimOliver/TORoundedTableView) - A subclass of UITableView that styles it like Settings.app on iPad :star:64
* [ASCollectionView](https://github.com/abdullahselek/ASCollectionView) - A Swift collection view inspired by Airbnb. :large_orange_diamond: :star:140
* [TableFlip](https://github.com/mergesort/TableFlip) - A simpler way to do cool UITableView animations! (╯°□°）╯︵ ┻━┻ :large_orange_diamond: :star:363
* [DTTableViewManager](https://github.com/DenHeadless/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types. :large_orange_diamond: :star:324
* [GLTableCollectionView](https://github.com/giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView :large_orange_diamond: :star:471
* [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app, implemented in Swift. :large_orange_diamond: :star:2775
* [EditDistance](https://github.com/kazuhiro4949/EditDistance) - Incremental update tool for UITableView and UICollectionView :large_orange_diamond: :star:56
* [CenteredCollectionView](https://github.com/BenEmdon/CenteredCollectionView) - A lightweight UICollectionViewLayout that _'pages'_ and centers it's cells 🎡 written in Swift. :large_orange_diamond: :star:182
* [CollectionViewSlantedLayout](https://github.com/yacir/CollectionViewSlantedLayout) - UICollectionViewLayout with slanted content :large_orange_diamond: :star:726
* [ReverseExtension](https://github.com/marty-suzuki/ReverseExtension) - A UITableView extension that enables cell insertion from the bottom of a table view. :star:1180
* [YNExpandableCell](https://github.com/younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶 :star:345
* [SquareMosaicLayout](https://github.com/iwheelbuy/SquareMosaicLayout) - An extandable mosaic UICollectionViewLayout with a focus on extremely flexible customizations 🔶 :star:79
* [SwiftSpreadSheet](https://github.com/stuffrabbit/SwiftSpreadsheet) - Spreadsheet CollectionViewLayout in Swift. Fully customizable. 🔶 :star:412
* [GenericDataSource](https://github.com/GenericDataSource/GenericDataSource) - A generic small reusable components for data source implementation for UITableView/UICollectionView in Swift. 🔶 :star:48
* [BouncyLayout](https://github.com/roberthein/BouncyLayout) - BouncyLayout is a collection view layout that makes your cells bounce. 🔶 :star:2792
* [Savory](https://github.com/Nandiin/Savory) - A swift accordion view implementation. :large_orange_diamond:
* [PagingView](https://github.com/KyoheiG3/PagingView) - Infinite paging, Smart auto layout, Interface of similar to UIKit. :large_orange_diamond:🔶 :star:248
* [ExpyTableView](https://github.com/okhanokbay/ExpyTableView) - Make your table view expandable just by implementing one method. 🔶 :star:162
* [FTFoldingPaper](https://github.com/monofire/FTFoldingPaper) - Emulates paper folding effect. Can be integrated with UITableView or used with other UI components. :star:24
* [PJFDataSource](https://github.com/square/PJFDataSource) - PJFDataSource is a small library that provides a simple, clean architecture for your app to manage its data sources while providing a consistent user interface for common content states (i.e. loading, loaded, empty, and error). :star:82
* [HGPlaceholders](https://github.com/HamzaGhazouani/HGPlaceholders) - Nice library to show and create placeholders and Empty States for any UITableView/UICollectionView in your project 🔶 :star:1039
* [CollapsibleTableSectionViewController](https://github.com/jeantimex/CollapsibleTableSectionViewController) - A swift library to support collapsible sections in a table view. :large_orange_diamond: :star:67
* [ExpandableCell](https://github.com/younatics/ExpandableCell) - Fully refactored YNExapnadableCell with more concise, bug free. Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶 :star:206
* [DataSources](https://github.com/muukii/DataSources) - Type-safe data-driven List-UI Framework. (We can also use ASCollectionNode) 🔶 :star:341
* [KDDragAndDropCollectionView](https://github.com/mmick66/KDDragAndDropCollectionView) - Dragging & Dropping data across multiple UICollectionViews. 🔶 :star:260
* [ListPlaceholder](https://github.com/malkouz/ListPlaceholder) - ListPlaceholder is a swift library allows you to easily add facebook style animated loading placeholder to your tableviews or collection views :large_orange_diamond: :star:284
* [SectionScrubber](https://github.com/bakkenbaeck/SectionScrubber) - A component to quickly scroll between collection view sections :large_orange_diamond: :star:146
* [CardsLayout](https://github.com/filletofish/CardsLayout) - Nice card-designed custom collection view layout. 🔶 :star:319
* [CollectionKit](https://github.com/SoySauceLab/CollectionKit) - A modern Swift framework for building reusable data-driven collection components. 🔶 :star:1990

#### Tag
* [PARTagPicker](https://github.com/paulrolfe/PARTagPicker) - This pod provides a view controller for choosing and creating tags in the style of wordpress or tumblr. :star:280
* [AMTagListView](https://github.com/andreamazz/AMTagListView) - UIScrollView subclass that allows to add a list of highly customizable tags. :star:710
* [TagCellLayout](https://github.com/riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments. :large_orange_diamond: :star:124
* [TTGTagCollectionView](https://github.com/zekunyan/TTGTagCollectionView) - Show simple text tags or custom tag views in a vertical scrollable view. :star:738
* [TagListView](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift. :large_orange_diamond: :star:1230
* [RKTagsView](https://github.com/kuler90/RKTagsView) - Highly customizable iOS tags view (like NSTokenField). Supports editing, multiple selection, Auto Layout and much more. :star:368
* [WSTagsField](https://github.com/whitesmith/WSTagsField) - An iOS text field that represents different Tags :large_orange_diamond: :star:661
* [AKMaskField](https://github.com/artemkrachulov/AKMaskField) - AKMaskField is UITextField subclass which allows enter data in the fixed quantity and in the certain format. :large_orange_diamond: :star:244
* [YNSearch](https://github.com/younatics/YNSearch) - Awesome fully customizable search view like Pinterest written in Swift 3 🔶 :star:748

#### TextField & TextView
* [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels. :star:6601
* [ARAutocompleteTextView](https://github.com/alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews. :star:257
* [IQDropDownTextField](https://github.com/hackiftekhar/IQDropDownTextField) - TextField with DropDown support using UIPickerView :star:239
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake) - UITextField category that adds shake animation. [Also with Swift version](https://github.com/King-Wizard/UITextField-Shake-Swift) :large_orange_diamond: :star:707
* [HTYTextField](https://github.com/hanton/HTYTextField) - A UITextField with bouncy placeholder. :large_orange_diamond: :star:230
* [MVAutocompletePlaceSearchTextField](https://github.com/TheMrugraj/MVAutocompletePlaceSearchTextField) - A drop-in Autocompletion control for Place Search like Google Places, Uber, etc. :star:67
* [AutocompleteField](https://github.com/filipstefansson/AutocompleteField) - Add word completion to your UITextFields. :large_orange_diamond: :star:650
* [RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks. :large_orange_diamond: :star:524
* [RSKPlaceholderTextView](https://github.com/ruslanskorb/RSKPlaceholderTextView) - A light-weight UITextView subclass that adds support for placeholder. :large_orange_diamond: :star:63
* [StatefulViewController](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states :large_orange_diamond: :star:1858
* [MBAutoGrowingTextView](https://github.com/MatejBalantic/MBAutoGrowingTextView) - An auto-layout base UITextView subclass which automatically grows with user input and can be constrained by maximal and minimal height - all without a single line of code :star:118
* [TextFieldEffects](https://github.com/raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift :large_orange_diamond: :star:4397
* [Reel Search](https://github.com/Ramotion/reel-search) - RAMReel is a controller that allows you to choose options from a list. :large_orange_diamond: :star:1960
* [MLPAutoCompleteTextField](https://github.com/EddyBorja/MLPAutoCompleteTextField) - a subclass of UITextField that behaves like a typical UITextField with one notable exception: it manages a drop down table of autocomplete suggestions that update as the user types. :star:1161
* [SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.:large_orange_diamond: :star:2382
* [VMaskTextField](https://github.com/viniciusmo/VMaskTextField) - VMaskTextField is a library which create an input mask for iOS. :star:359
* [TJTextField](https://github.com/tejas-ardeshna/TJTextField) - UITextField with underline and left image :large_orange_diamond: :star:38
* [NextGrowingTextView](https://github.com/muukii/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above. :star:894
* [RPFloatingPlaceholders](https://github.com/iwasrobbed/RPFloatingPlaceholders) - UITextField and UITextView subclasses with placeholders that change into floating labels when the fields are populated with text. :star:1109
* [CurrencyTextField](https://github.com/richa008/CurrencyTextField) - UITextField that automatically formats text to display in the currency format. :large_orange_diamond: :star:23
* [UITextField-Navigation](https://github.com/T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields.🔶[e] :star:351
* [AutoCompleteTextField](https://github.com/nferocious76/AutoCompleteTextField) - Auto complete with suggestion textfield :large_orange_diamond: :star:27
* [EmojiTextView](https://github.com/fastred/EmojiTextView) - Tap to swap out words with emojis. Inspired by Messages.app on iOS 10. :large_orange_diamond: :star:348
* [PLCurrencyTextField](https://github.com/nonameplum/PLCurrencyTextField) - UITextField that support currency in the right way. :large_orange_diamond: :star:83
* [PasswordTextField](https://github.com/PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforce good password policies :large_orange_diamond: :star:156
* [AnimatedTextInput](https://github.com/jobandtalent/AnimatedTextInput) - Animated UITextField and UITextView replacement for iOS :large_orange_diamond: :star:530
* [KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder written in Swift. :large_orange_diamond: :star:492
* [NxEnabled](https://github.com/Otbivnoe/NxEnabled) - Library which allows you binding `enabled` property of button with textable elements (TextView, TextField) :large_orange_diamond: :star:26
* [AwesomeTextField](https://github.com/aleksandrshoshiashvili/AwesomeTextFieldSwift) - Awesome TextField is a nice and simple library for iOS. It's highly customisable and easy-to-use tool. Works perfectly for any registration or login forms in your app. :large_orange_diamond: :star:116
* [ModernSearchBar](https://github.com/PhilippeBoisney/ModernSearchBar) - The famous iOS search bar with auto completion feature implemented. :large_orange_diamond: :star:85
* [SelectableTextView](https://github.com/jhurray/SelectableTextView) - A text view that supports selection and expansion :large_orange_diamond: :star:560
* [CBPinEntryView](https://github.com/Fawxy/CBPinEntryView) - A customisable view written in Swift 3.0 for any numerical pin or code entry. :large_orange_diamond: :star:34
* [GrowingTextView](https://github.com/KennethTsang/GrowingTextView) - An UITextView in Swift3 and Swift2.3. Support auto growing, placeholder and length limit. :large_orange_diamond: :star:244
* [DTTextField](https://github.com/iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label in Swift3.0.🔶 :star:88
* [TextFieldCounter](https://github.com/serralvo/TextFieldCounter) - UITextField character counter with lovable UX. 🔶 :star:319
* [RSFloatInputView](https://github.com/roytornado/RSFloatInputView) - A Float Input View with smooth animation and supporting icon and seperator written with Swift. 🔶 :star:61
* [TaniwhaTextField](https://github.com/iceman201/TaniwhaTextField) - TaniwhaTextField is a lightweight and beautiful swift textfield framework. It has float label pattern, and also you can highly customise it. it's written with Swift. 🔶 :star:30
* [InstantSearch iOS](https://github.com/algolia/instantsearch-ios) - A library of widgets and helpers to build instant-search applications on iOS. 🔶 :star:396
* [SearchTextField](https://github.com/apasccon/SearchTextField) - UITextField subclass with autocompletion suggestions list  :large_orange_diamond: :star:295
* [PYSearch](https://github.com/ko1o/PYSearch) - An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad). :star:2680
* [styled-text](https://github.com/blueapron/styled-text) - Declarative text styles and streamlined Dynamic Type support for iOS. 🔶 :star:212
* [TweeTextField](https://github.com/oleghnidets/TweeTextField) - Lightweight set of text fields with nice animation and functionality. 🔶 :star:92

#### Web View
* [Otafuku](https://github.com/tasanobu/Otafuku) - Otafuku provides utility classes to use WKWebView in Swift. :large_orange_diamond: :star:50
* [SwiftWebVC](https://github.com/meismyles/SwiftWebVC) - A drop-in inline browser for your Swift iOS app. :large_orange_diamond: :star:185
* [SVWebViewController](https://github.com/TransitApp/SVWebViewController) - A drop-in inline browser for your iOS app. :star:2566
* [PTPopupWebView](https://github.com/pjocprac/PTPopupWebView) - PTPopupWebView is a simple and useful WebView for iOS, which can be popup and has many of the customized item. :large_orange_diamond: :star:73

## Utility
 * [Underscore.m](https://github.com/robb/Underscore.m) - A DSL for Data Manipulation. :star:1518
 * [XExtensionItem](https://github.com/tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions. :star:81
 * [ReflectableEnum](https://github.com/fastred/ReflectableEnum) - Reflection for enumerations in Objective-C. :star:331
 * [ObjectiveSugar](https://github.com/supermarin/ObjectiveSugar) - ObjectiveC additions for humans. Ruby style. :star:2218
 * [OpinionatedC](https://github.com/leoschweizer/OpinionatedC) - Because Objective-C should have inherited more from Smalltalk. :star:44
 * [SwiftRandom](https://github.com/thellimist/SwiftRandom) - Generator for random data. :large_orange_diamond: :star:483
 * [RandomKit](https://github.com/nvzqz/RandomKit/) - Random data generation in Swift. :large_orange_diamond:
 * [YOLOKit](https://github.com/mxcl/YOLOKit) - Getting square objects down round holes. :star:632
 * [EZSwiftExtensions](https://github.com/goktugyil/EZSwiftExtensions) - :smirk: How Swift standard types and classes were supposed to work. :large_orange_diamond:[e] :star:2341
 * [Pantry](https://github.com/nickoneill/Pantry) - The missing light persistence layer for Swift :large_orange_diamond: :star:851
 * [SwiftParsec](https://github.com/davedufresne/SwiftParsec) - A parser combinator library written in the Swift programming language. :large_orange_diamond: :star:124
 * [OrderedSet](https://github.com/Weebly/OrderedSet) - A Swift collection of unique, ordered objects :large_orange_diamond: :star:118
 * [Datez](https://github.com/SwiftKitz/Datez) - Swift library for dealing with `NSDate`, `NSCalendar`, and `NSDateComponents`. :large_orange_diamond: :star:212
 * [BFKit](https://github.com/FabrizioBrancati/BFKit) - An Objective-C collection of useful classes to develop Apps faster. :star:767
 * [BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift) - A Swift collection of useful classes to develop Apps faster. :large_orange_diamond: :star:691
 * [Scale](https://github.com/onmyway133/scale) - Unit converter in Swift (available via CocoaPods) :large_orange_diamond: :star:305
 * [Standard Template Protocols](https://github.com/cconeil/Standard-Template-Protocols) - Protocols for your every day iOS needs :large_orange_diamond: :star:379
 * [TimeLord](https://github.com/JonFir/TimeLord) - Easy DateTime (NSDate) management in Swift :large_orange_diamond: :star:6
 * [AppVersionMonitor](https://github.com/eure/AppVersionMonitor) - Monitor iOS app version easily. :star:224
 * [Sugar](https://github.com/hyperoslo/Sugar) - Something sweet that goes great with your Cocoa. :large_orange_diamond:[e] :star:897
 * [Then](https://github.com/devxoul/Then) - ✨ Super sweet syntactic sugar for Swift initializers. :large_orange_diamond:[e] :star:2055
 * [Kvitto](https://github.com/Cocoanetics/Kvitto) - App Store Receipt Validation :large_orange_diamond: :star:200
 * [Notificationz](https://github.com/SwiftKitz/Notificationz) - Helping you own NSNotificationCenter in Swift :large_orange_diamond: :star:60
 * [SwiftFoundation](https://github.com/PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library. (Pure Swift, Supports Linux) :large_orange_diamond:[e] :star:607
 * [libextobjc](https://github.com/jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language. :star:3796
 * [VersionTrackerSwift](https://github.com/tbaranes/VersionTrackerSwift) - Track which versions of your app a user has previously installed. :large_orange_diamond: :star:57
 * [DeviceGuru](https://github.com/InderKumarRathore/DeviceGuru/) - DeviceGuru is a simple lib (Swift) to know the exact type of the device, e.g. iPhone 6 or iPhone 6s. :large_orange_diamond:
 * [AEAppVersion](https://github.com/tadija/AEAppVersion) - Simple and Lightweight App Version Tracking for iOS written in Swift :large_orange_diamond: :star:9
 * [BlocksKit](https://github.com/BlocksKit/BlocksKit) - The Objective-C block utilities you always wish you had. :star:6491
 * [SwiftyUtils](https://github.com/tbaranes/swiftyutils) - All the reusable code that we need in each project. :large_orange_diamond:[e] :star:203
 * [RateLimit](https://github.com/soffes/RateLimit) - Simple utility for only executing code every so often. :large_orange_diamond: :star:870
 * [Outlets](https://github.com/phatblat/Outlets) - Utility functions for validating IBOutlet and IBAction connections :large_orange_diamond: :star:127
 * [EasyAbout](https://github.com/JARMourato/EasyAbout) - A way to easily add CocoaPods licenses and App Version to your iOS App using the Settings Bundle :star:43
 * [Validated](https://github.com/Ben-G/Validated) - A Swift μ-Library for Somewhat Dependent Types :large_orange_diamond: :star:594
 * [Cent](https://github.com/ankurp/Cent) - Extensions for Swift Standard Types and Classes :large_orange_diamond: :star:166
 * [AssistantKit](https://github.com/anatoliyv/AssistantKit) - Easy way to detect iOS device properties, OS versions and work with screen sizes. Powered by Swift. :large_orange_diamond: :star:434
 * [SwiftLinkPreview](https://github.com/LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. 🔶 :star:759
 * [BundleInfos](https://github.com/rollmind/BundleInfos) - Simple getter for Bundle informations. like short version from bundle. 🔶 :star:1
 * [YAML.framework](https://github.com/mirek/YAML.framework) - Proper YAML support for Objective-C based on `LibYAML`. :star:189
 * [ReadabilityKit](https://github.com/exyte/ReadabilityKit) - Metadata extractor for news, articles and full-texts in Swift. 🔶 :star:633
 * [MissionControl-iOS](https://github.com/appculture/MissionControl-iOS) - Super powerful remote config utility written in Swift (iOS, watchOS, tvOS, macOS) :large_orange_diamond: :star:99
 * [SwiftTweaks](https://github.com/Khan/SwiftTweaks) - Tweak your iOS app without recompiling! :large_orange_diamond: :star:1048
 * [UnsupportedOSVersionAlert](https://github.com/caloon/UnsupportedOSVersionAlert) - Alerts users with a popup if they use an app with an unsupported version of iOS (e.g. iOS betas) :large_orange_diamond: :star:9
 * [SwiftSortUtils](https://github.com/dsmatter/SwiftSortUtils) - This library takes a shot at making sorting in Swift more pleasant. It also allows you to reuse your old NSSortDescriptor instances in Swift. :large_orange_diamond: :star:58
 * [Retry](https://github.com/icanzilb/Retry) - Haven't you wished for `try` to sometimes try a little harder? Meet `retry` . :large_orange_diamond: :star:435
 * [ObjectiveKit](https://github.com/marmelroy/ObjectiveKit) - Swift-friendly API for Objective C runtime functions. :large_orange_diamond: :star:723
 * [MoyaSugar](https://github.com/devxoul/MoyaSugar) -  Syntactic sugar for Moya. :large_orange_diamond: :star:80
 * [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) -  A handy collection of more than 400 native Swift 3 extensions to boost your productivity. :large_orange_diamond: :star:4289
 * [Eject](https://github.com/Raizlabs/Eject) - An eject button for Interface Builder to generate swift code. :large_orange_diamond: :star:513
 * [ContactsWrapper](https://github.com/abdullahselek/ContactsWrapper) - Easy to use wrapper for both contacts and contacts group with Objective-C. :star:17
 * [XestiMonitors](https://github.com/eBardX/XestiMonitors) - An extensible monitoring framework written in Swift :large_orange_diamond: :star:240
 * [OpenSourceController](https://github.com/floriangbh/OpenSourceController) - The simplest way to display the libraries licences used in your application. :large_orange_diamond: :star:28
 * [App-Update-Tracker](https://github.com/Stunner/App-Update-Tracker) - Easily detect and run code upon app installation or update. :star:24
 * [ExtensionalSwift](https://github.com/4taras4/SwiftExtension) - Useful swift extensions in one place 🔶[e] :star:3
 * [InAppSettingsKit](https://github.com/futuretap/InAppSettingsKit) - This iOS framework allows settings to be in-app in addition to or instead of being in the Settings app. :star:2833
 * [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions. :star:3361
 * [DefaultStringConvertible](https://github.com/jessesquires/DefaultStringConvertible) - A default CustomStringConvertible implementation for Swift types 🔶[e] :star:128
 * [FluxCapacitor](https://github.com/marty-suzuki/FluxCapacitor) - FluxCapacitor makes implementing Flux design pattern easily with protocols and typealias. 🔶 :star:96
 * [VTAcknowledgementsViewController](https://github.com/vtourraine/VTAcknowledgementsViewController) - Ready to use “Acknowledgements”/“Licenses”/“Credits” view controller for CocoaPods. :star:815
 * [Closures](https://github.com/vhesener/Closures) - Swifty closures for UIKit and Foundation. 🔶 :star:1290
 * [WhatsNew](https://github.com/BalestraPatrick/WhatsNew) - Showcase new features after an app update similar to Pages, Numbers and Keynote :large_orange_diamond: :star:1240

## VR
* [VR Toolkit iOS](https://github.com/Aralekk/VR_Toolkit_iOS) - A sample project that provides the basics to create an interactive VR experience on iOS :large_orange_diamond: :star:76
* [360 VR Player](https://github.com/hanton/HTY360Player) - A open source, ad-free, native and universal 360 degree panorama video player for iOS. :star:1716
* [simple360player](https://github.com/Aralekk/simple360player_iOS) - Free & ad-free 360 VR Video Player. Flat or Stereoscopic. In Swift 2. :large_orange_diamond: :star:133
* [Swifty360Player](https://github.com/abdullahselek/Swifty360Player) - iOS 360-degree video player streaming from an AVPlayer with Swift. :large_orange_diamond: :star:35

## Walkthrough / Intro / Tutorial
* [Onboard](https://github.com/mamaral/Onboard) - Easily create a beautiful and engaging onboarding experience with only a few lines of code. :star:5975
* [EAIntroView](https://github.com/ealeksandrov/EAIntroView) - Highly customizable drop-in solution for introduction views. :star:3556
* [MYBlurIntroductionView](https://github.com/MatthewYork/MYBlurIntroductionView) - A super-charged version of MYIntroductionView for building custom app introductions and tutorials. :star:1548
* [BWWalkthrough](https://github.com/ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App. :large_orange_diamond: :star:2541
* [GHWalkThrough](https://github.com/GnosisHub/GHWalkThrough) - A UICollectionView backed drop-in component for introduction views. :star:739
* [ICETutorial](https://github.com/icepat/ICETutorial) - A nice tutorial like the one introduced in the Path 3.X App. :star:826
* [JazzHands](https://github.com/IFTTT/JazzHands) - Jazz Hands is a simple keyframe-based animation framework for UIKit. Animations can be controlled via gestures, scroll views, KVO, or ReactiveCocoa. :star:6373
* [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle) - A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros. :large_orange_diamond: :star:2888
* [Instructions](https://github.com/ephread/Instructions) - Easily add customizable coach marks into you iOS project. :large_orange_diamond: :star:3086
* [SwiftyWalkthrough](https://github.com/ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps, powered by Swift. :large_orange_diamond: :star:218
* [Gecco](https://github.com/yukiasai/Gecco) - Spotlight view for iOS. :large_orange_diamond: :star:1601
* [VideoSplashKit](https://github.com/svtek/VideoSplashKit) - VideoSplashKit - UIViewController library for creating easy intro pages with background videos :large_orange_diamond: :star:1138
* [Presentation](https://github.com/hyperoslo/Presentation) - Presentation helps you to make tutorials, release notes and animated pages. :large_orange_diamond: :star:2367
* [AMPopTip](https://github.com/andreamazz/AMPopTip) - An animated popover that pops out a given frame, great for subtle UI tips and onboarding. :star:2030
* [AlertOnboarding](https://github.com/PhilippeBoisney/AlertOnboarding) - A simple and handsome AlertView for onboard your users in your amazing world. :large_orange_diamond: :star:401
* [EasyTipView](https://github.com/teodorpatras/EasyTipView) - Fully customisable tooltip view in Swift. :large_orange_diamond: :star:1791
* [paper-onboarding](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design slider :large_orange_diamond: :star:2152
* [InfoView](https://github.com/anatoliyv/InfoView) - Swift based simple information view with pointed arrow. :large_orange_diamond: :star:36
* [Intro](https://github.com/nbolatov/Intro) - An iOS framework to easily create simple animated walkthrough, written in Swift. :large_orange_diamond: :star:25
* [AwesomeSpotlightView](https://github.com/aleksandrshoshiashvili/AwesomeSpotlightView) - Tool to create awesome tutorials or educate user to use application. Or just highlight something on screen. Written in Swift. :large_orange_diamond: :star:57
* [SwiftyOnboard](https://github.com/juanpablofernandez/SwiftyOnboard) - A simple way to add onboarding to your project. :large_orange_diamond: :star:617
* [WVWalkthroughView](https://github.com/praagyajoshi/WVWalkthroughView) - Utility to easily create walkthroughs to help with user onboarding. :star:23
* [SwiftyGuideOverlay](https://github.com/saeid/SwiftyGuideOverlay) - Easy and quick way to show intro / instructions over app UI without any additional images in real-time!. 🔶 :star:10
* [SwiftyOnboardVC](https://github.com/chaser79/SwiftyOnboardVC) - Lightweight walkthrough controller thats uses view controllers as its subviews making the customization endless. 🔶 :star:10
* [PVOnboardKit](https://github.com/vpeschenkov/PVOnboardKit) - Framework that allows you to add your own walkthrough/intro/tutorial into your app. :star:42

## WebSocket
* [SocketRocket](https://github.com/facebook/SocketRocket) - A conforming Objective-C WebSocket client library. :star:7444
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - Socket.IO-client for iOS/macOS. :large_orange_diamond: :star:2846
* [SwiftWebSocket](https://github.com/tidwall/SwiftWebSocket) - High performance WebSocket client library for Swift, iOS and macOS. :large_orange_diamond: :star:950
* [Starscream](https://github.com/daltoniam/Starscream) - Websockets in swift for iOS and macOS :large_orange_diamond: :star:3480
* [SwiftSocket](https://github.com/swiftsocket/SwiftSocket) - simple socket library for apple swift lang. :large_orange_diamond: :star:753
* [Socks](https://github.com/vapor/sockets) - Pure-Swift Sockets: TCP, UDP; Client, Server; Linux, macOS :large_orange_diamond: :star:489
* [SwifterSockets](https://github.com/Balancingrock/SwifterSockets) - A collection of socket utilities in Swift for OS-X and iOS :large_orange_diamond: :star:55
* [Swift-ActionCableClient](https://github.com/danielrhodes/Swift-ActionCableClient) - ActionCable is a new WebSocket server being released with Rails 5 which makes it easy to add real-time features to your app. :large_orange_diamond: :star:109

# Project setup
* [crafter](https://github.com/krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful. :star:544
* [liftoff](https://github.com/liftoffcli/liftoff) - Another CLI for creating iOS projects. :star:1570
* [amaro](https://github.com/crushlovely/Amaro) - iOS Boilerplate full of delights. :star:388
* [chairs](https://github.com/orta/chairs) - Swap around your iOS Simulator Documents :star:233
* [SwiftPlate](https://github.com/JohnSundell/SwiftPlate) - Easily generate cross platform Swift framework projects from the command line. :large_orange_diamond: :star:1444
* [xclint](https://github.com/xcodeswift/xclint) - Validate the state of your Xcode projects. :star:76
* [xcproj](https://github.com/xcodeswift/xcproj) - Read and update Xcode projects. :star:531

# Dependency / Package Manager
* [CocoaPods](https://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
* [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
* [Carthage](https://github.com/Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa. :large_orange_diamond: :star:10921
* [SWM (Swift Modules)](https://github.com/jankuca/swm) - A package/dependency manager for Swift projects similar to npm (node.js package manager) or bower (browser package manager from Twitter). Does not require the use of Xcode. :large_orange_diamond: :star:54
* [CocoaSeeds](https://github.com/devxoul/CocoaSeeds) - Git Submodule Alternative for Cocoa. :star:342
* [swift-package-manager](https://github.com/apple/swift-package-manager) - The Package Manager for the Swift Programming Language :large_orange_diamond: :star:6031
* [punic](https://github.com/schwa/punic) - Clean room reimplementation of Carthage tool :star:242

# Tools
* [Shark](https://github.com/kaandedeoglu/Shark) - Swift Script that transforms the .xcassets folder into a type safe enum. :large_orange_diamond: :star:295
* [SBConstants](https://github.com/paulsamuels/SBConstants) - Generate a constants file by grabbing identifiers from storyboards in a project. :star:310
* [R.swift](https://github.com/mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues in your Swift project. :large_orange_diamond: :star:4516
* [SwiftGen](https://github.com/SwiftGen/SwiftGen) - A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings and UIColors). :large_orange_diamond: :star:4161
* [Blade](https://github.com/jondot/blade) - Generate Xcode image catalogs for iOS / macOS app icons, universal images, and more. :star:788
* [Retini](https://github.com/terwanerik/Retini) - A super simple retina (2x, 3x) image converter. :star:108
* [Jazzy](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C. :large_orange_diamond: :star:4941
* [appledoc](https://github.com/tomaz/appledoc) - ObjectiveC code Apple style documentation set generator. :star:3768
* [Laurine](https://github.com/JiriTrecak/Laurine) - Laurine - Localization code generator written in Swift. Sweet! :large_orange_diamond: :star:1057
* [StoryboardMerge](https://github.com/marcinolawski/StoryboardMerge) - Xcode storyboards diff and merge tool. :star:210
* [ai2app](https://github.com/metasmile/ai2appiconset) - Creating AppIcon sets from Adobe Illustrator (all supported formats). :star:76
* [ViewMonitor](https://github.com/daisuke0131/ViewMonitor) - ViewMonitor can measure view positions with accuracy. :large_orange_diamond: :star:716
* [abandoned-strings](https://github.com/ijoshsmith/abandoned-strings) - Command line program that detects unused resource strings in an iOS or macOS application. :large_orange_diamond: :star:94
* [swiftenv](https://github.com/kylef/swiftenv) - swiftenv allows you to easily install, and switch between multiple versions of Swift. :large_orange_diamond: :star:1425
* [Misen](https://github.com/tasanobu/Misen) - Script to support easily using Xcode Asset Catalog in Swift. :large_orange_diamond:[e] :star:119
* [git-xcp](https://github.com/metasmile/git-xcp) - A Git plugin for versioning workflow of real-world Xcode project. fastlane's best friend. :star:11
* [WatchdogInspector](https://github.com/tapwork/WatchdogInspector) - Shows your current framerate (fps) in the status bar of your iOS app :star:440
* [Cichlid](https://github.com/dealforest/Cichlid) - automatically delete the current project's DerivedData directories :large_orange_diamond: :star:252
* [Delta](https://github.com/thoughtbot/Delta) - Managing state is hard. Delta aims to make it simple. :large_orange_diamond: :star:247
* [SwiftLintXcode](https://github.com/ypresto/SwiftLintXcode) - An Xcode plug-in to format your code using SwiftLint. :large_orange_diamond: :star:255
* [XCSwiftr](https://github.com/dzenbot/XCSwiftr) - An Xcode Plugin to convert Objective-C to Swift :large_orange_diamond: :star:324
* [SwiftKitten](https://github.com/johncsnyder/SwiftKitten) - Swift autocompleter for Sublime Text, via the adorable SourceKitten framework :large_orange_diamond: :star:130
* [Kin](https://github.com/Karumi/Kin) - Have you ever found yourself undoing a merge due to a broken Xcode build? Then Kin is your tool. It will parse your project configuration file and detect errors. :large_orange_diamond: :star:203
* [AVXCAssets-Generator](https://github.com/angelvasa/AVXCAssets-Generator) - AVXCAssets Generator takes path for your assets images and creates appiconset and imageset for you in just one click :large_orange_diamond: :star:285
* [Peek](https://github.com/shaps80/Peek) - Take a Peek at your application. :large_orange_diamond: :star:1157
* [SourceKitten](https://github.com/jpsim/SourceKitten) - An adorable little framework and command line tool for interacting with SourceKit. :large_orange_diamond: :star:1193
* [Localizations](https://github.com/athiercelin/localizations) - macOS app that manages localizations of Xcode projects. :large_orange_diamond: :star:97
* [xcbuild](https://github.com/facebook/xcbuild) - Xcode-compatible build tool. :star:1406
* [XcodeIssueGenerator](https://github.com/doubleencore/XcodeIssueGenerator) - An executable that can be placed in a Run Script Build Phase that marks comments like // TODO: or // SERIOUS: as warnings or errors so they display in the Xcode Issue Navigator. :large_orange_diamond: :star:143
* [SwiftCompilationPerformanceReporter](https://github.com/tumblr/SwiftCompilationPerformanceReporter) - Generate automated reports for slow Swift compilation paths in specific targets :large_orange_diamond: :star:147
* [BuildTimeAnalyzer](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) - Build Time Analyzer for Swift :large_orange_diamond: :star:2227
* [Duration](https://github.com/SwiftStudies/Duration) - A simple Swift package for measuring and reporting the time taken for operations :large_orange_diamond: :star:300
* [Benchmark](https://github.com/WorldDownTown/Benchmark) - The Benchmark⏲ module provides methods to measure and report the time used to execute Swift code. :large_orange_diamond: :star:68
* [MBAssetsImporter](https://github.com/MatiBot/MBAssetsImporter) - Import assets from Panoramio or from your macOS file system with their metadata to your iOS simulator (Swift 2.0) :large_orange_diamond: :star:68
* [Realm Browser](https://github.com/realm/realm-browser-osx) - Realm Browser is a macOS utility to open and modify realm database files. :star:470
* [SuperDelegate](https://github.com/square/SuperDelegate) – SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle.
* [fastlane-plugin-appicon](https://github.com/KrauseFx/fastlane-plugin-appicon) - Generate required icon sizes and iconset from a master application icon. :star:185
* [infer](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C. :star:7967
* [PlayNow](https://github.com/marcboquet/PlayNow) - Small app that creates empty Swift playground files and opens them with Xcode. :large_orange_diamond: :star:91
* [Xtrace](https://github.com/johnno1962/Xtrace) - Trace Objective-C method calls by class or instance :star:1690
* [xcenv](https://github.com/xcenv/xcenv) - Groom your Xcode environment. :star:211
* [playgroundbook](https://github.com/playgroundbooks/playgroundbook) - Tool for Swift Playground books :star:219
* [Ecno](https://github.com/xmartlabs/Ecno) - Ecno is a task state manager built on top of UserDefaults in pure Swift 3. :large_orange_diamond: :star:68
* [ipanema](https://github.com/toshi0383/ipanema) - ipanema analyzes and prints useful information from *.ipa file. :star:5
* [pxctest](https://github.com/plu/pxctest) - Parallel XCTest - Execute XCTest suites in parallel on multiple iOS Simulators. :star:779
* [IBM Swift Sandbox](https://swift.sandbox.bluemix.net) - The IBM Swift Sandbox is an interactive website that lets you write Swift code and execute it in a server environment – on top of Linux! :large_orange_diamond:
* [FBSimulatorControl](https://github.com/facebook/FBSimulatorControl) - A macOS library for managing and manipulating iOS Simulators :star:2137
* [Nomad](http://nomad-cli.com) - Suite of command line utilities & libraries for sending APNs, create & distribute *.ipa*, verify In-App-Purchase receipt and more.
* [Cookiecutter](https://github.com/JetpackSwift/FrameworkTemplate) - A template for new Swift iOS / tvOS / watchOS / macOS Framework project ready with travis-ci, cocoapods, Carthage, SwiftPM and a Readme file :large_orange_diamond: :star:436
* [Sourcery](https://github.com/krzysztofzablocki/Sourcery) - A tool that brings meta-programming to Swift, allowing you to code generate Swift code. :large_orange_diamond: :star:3091
* [AssetChecker 👮](https://github.com/freshOS/AssetChecker) - Keeps your Assets.xcassets files clean and emits warnings when something is suspicious. :large_orange_diamond: :star:59
* [PlayAlways](https://github.com/insidegui/PlayAlways) - Create Xcode playgrounds from your menu bar :large_orange_diamond: :star:411
* [GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift) - Shows FPS, CPU usage, app and iOS versions above the status bar and report FPS and CPU usage via delegate. :large_orange_diamond: :star:1614
* [Traits](https://github.com/krzysztofzablocki/Traits) - Library for a real-time design and behavior modification of native iOS apps without recompiling (code and interface builder changes are supported). :large_orange_diamond: :star:878
* [Struct](https://www.get-struct.tools) - A tool for iOS and Mac developers to automate the creation and management of Xcode projects.
* [Nori](https://github.com/yukiasai/Nori) - Easier to apply code based style guide to storyboard. :large_orange_diamond: :star:290
* [Attabench](https://github.com/attaswift/Attabench) - Microbenchmarking app for Swift with nice log-log plots :large_orange_diamond: :star:601
* [Gluten](https://github.com/wilbertliu/Gluten) - Nano library to unify XIB and it's code. :large_orange_diamond: :star:9
* [LicensePlist](https://github.com/mono0926/LicensePlist) - A license list generator of all your dependencies for iOS applications. :large_orange_diamond: :star:1058
* [Swizzlean](https://github.com/rbaumbach/Swizzlean) - An Objective-C Swizzle Helper Class :star:80
* [AppDevKit](https://github.com/yahoo/AppDevKit) - AppDevKit is an iOS development library that provides developers with useful features to fulfill their everyday iOS app development needs. :star:1353
* [Tweaks](https://github.com/facebook/Tweaks) - An easy way to fine-tune, and adjust parameters for iOS apps in development. :star:4643
* [FengNiao](https://github.com/onevcat/FengNiao) - A command line tool for cleaning unused resources in Xcode. :large_orange_diamond: :star:1379
* [LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker) - Find retain cycles / memory leaks sooner. :large_orange_diamond: :star:1431
* [Plank](https://github.com/pinterest/plank) - A tool for generating immutable model objects. :star:365
* [Lona](https://github.com/airbnb/Lona) - A tool for defining design systems and using them to generate cross-platform UI code, Sketch files, images, and other artifacts. :star:4005
* [XcodeGen](https://github.com/yonaskolb/XcodeGen) - Command line tool that generates your Xcode project from a spec file and your folder structure. :large_orange_diamond: :star:754
* [iSimulator](https://github.com/wigl/iSimulator) - iSimulator is a GUI utility to control the Simulator, and manage the app installed on the simulator. :star:14

# Rapid Development
* [Playgrounds](https://github.com/krzysztofzablocki/Playgrounds) - Playgrounds for Objective-C for extremely fast prototyping / learning. :star:2380
* [MMBarricade](https://github.com/mutualmobile/MMBarricade) - Runtime configurable local server for iOS apps. :star:354
* [STV Framework](http://www.sensiblecocoa.com) - Native visual iOS development.
* [swiftmon](https://github.com/dimpiax/swiftmon) - swiftmon restarts your swift application in case of any file change. :star:2

# Injection
* [dyci](https://github.com/DyCI/dyci-main) - Code injection tool. :star:1076
* [injectionforxcode](https://github.com/johnno1962/injectionforxcode) - Code injection including Swift. :star:5078
* [Swinject](https://github.com/Swinject/Swinject) - Dependency injection framework for Swift :star:2094
* [Reliant](https://github.com/appfoundry/Reliant) - Nonintrusive Objective-C dependency injection. :star:53
* [Kraken](https://github.com/sabirvirtuoso/Kraken) - A Dependency Injection Container for Swift with easy-to-use syntax. :star:1
* [Cleanse](https://github.com/square/Cleanse) - Lightweight Swift Dependency Injection Framework by Square. :large_orange_diamond: :star:1003
* [Typhoon](https://github.com/appsquickly/Typhoon) - Powerful dependency injection (Objective-C & Swift). :star:2331
* [Perform](https://github.com/thoughtbot/Perform) - Easy dependency injection for storyboard segues. :large_orange_diamond: :star:253
* [Alchemic](https://github.com/drekka/Alchemic) - Advanced, yet simple to use DI framework for Objective-C. :star:11
* [Guise](https://github.com/prosumma/Guise) - An elegant, flexible, type-safe dependency resolution framework for Swift :large_orange_diamond: :star:27

# Deployment / Distribution
* [fastlane](https://github.com/fastlane/fastlane) - Connect all iOS deployment tools into one streamlined workflow. :star:20237
* [deliver](https://github.com/fastlane/fastlane/tree/master/deliver) - Upload screenshots, metadata and your app to the App Store using a single command.
* [snapshot](https://github.com/fastlane/fastlane/tree/master/snapshot) Automate taking localized screenshots of your iOS app on every device.
* [buddybuild](https://www.buddybuild.com/) - A mobile iteration platform - build, deploy, and collaborate.
* [Bitrise](https://www.bitrise.io) Mobile Continuous Integration & Delivery with dozens of integrations to build, test, deploy and collaborate.
* [watchbuild](https://github.com/fastlane/watchbuild) - Get a notification once your iTunes Connect build is finished processing. :star:71
* [Crashlytics](https://try.crashlytics.com/) - A crash reporting and beta testing service.
* [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
* [HockeyApp](https://www.hockeyapp.net) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.
* [boarding](https://github.com/fastlane/boarding) - Instantly create a simple signup page for TestFlight beta testers. :star:629
* [HockeyKit](https://github.com/bitstadium/HockeyKit) - A software update kit. :star:2198
* [Boombox.io](https://boombox.io/) - Sign up TestFlight beta testers on your website. Embeddable and hosted TestFlight beta sign-up forms
* [Rollout.io](https://rollout.io/) - SDK to patch, fix bugs, modify and manipulate native apps (Obj-c & Swift) in real-time.
* [AppLaunchpad](https://theapplaunchpad.com/) - Free App Store screenshot builder.
* [LaunchKit](https://github.com/LaunchKit/LaunchKit) - A set of web-based tools for mobile app developers, now open source! :star:1855
* [Instabug](https://instabug.com) - In-app feedback, Bug and Crash reporting, Fix Bugs Faster through user-steps, video recordings, screen annotation, network requests logging.

# App Store
* [Average App Store Review Times](http://appreviewtimes.com) This site tracks the average App Store review times for both the iOS and the Mac App Store using data crowdsourced from iOS and Mac developers.
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/)  Highlighted some of the most common issues that cause apps to get rejected.
* [Free App Store Optimization Tool](https://www.mobileaction.co) Lets you track your App Store visibility in terms of keywords and competitors.
* [App Release Checklist](https://github.com/oisin/app-release-checklist/blob/master/checklist.md) - A checklist to pore over before you ship that amazing app that has taken ages to complete, but you don't want to rush out in case you commit a schoolboy error that will end up making you look dumber than you are.
* [Harpy](https://github.com/ArtSabintsev/Harpy) - Notify users when a new version of your iOS app is available, and prompt them with the App Store link. :star:2446
* [iRate](https://github.com/nicklockwood/iRate) - A handy class that prompts users of your iPhone or Mac App Store app to rate your application after using it for a while. Similar to Appirater, but with a simpler, cleaner interface and automatic support for iOS fast application switching. :star:4322
* [appirater](https://github.com/arashpayan/appirater) - A utility that reminds your iPhone app's users to review the app. :star:4549
* [Siren](https://github.com/ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade. :large_orange_diamond: :star:2318
* [Appstore Review Guidelines](https://github.com/aashishtamsya/Appstore-Review-Guidelines) - A curated list of points which a developer has to keep in mind before submitting his/her application on appstore for review. :star:5

# Xcode

#### Extensions (Xcode 8+)
* [CleanClosureXcode](https://github.com/BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond: :star:150
* [xTextHandler](https://github.com/cyanzhong/xTextHandler) - Xcode Source Editor Extension Toolset (Plugins for Xcode 8) :large_orange_diamond: :star:1386
* [SwiftInitializerGenerator](https://github.com/Bouke/SwiftInitializerGenerator) - Xcode 8 Source Code Extension to Generate Swift Initializers. :large_orange_diamond: :star:529
* [XcodeEquatableGenerator](https://github.com/sergdort/XcodeEquatableGenerator) - Xcode 8 Source Code Extension will generate conformance to Swift Equatable protocol based on type and fields selection. :large_orange_diamond: :star:168
* [Import](https://github.com/markohlebar/Import) - Xcode extension for adding imports from anywhere in the code. :large_orange_diamond: :star:716
* [Mark](https://github.com/velyan/Mark) - Xcode extension for generating MARK comments. :large_orange_diamond: :star:115
* [XShared](https://github.com/Otbivnoe/XShared) - Xcode extension which allows you copying the code with special formatting quotes for social (Slack, Telegram). :large_orange_diamond: :star:75
* [XGist](https://github.com/Bunn/Xgist) - Xcode extension which allows you to send your text selection or entire file to Github's Gist and automatically copy the Gist URL into your Clipboard. :large_orange_diamond: :star:54
* [Swiftify](https://objectivec2swift.com/) - Objective-C to Swift online code converter and Xcode extension. :large_orange_diamond:
* [DocumenterXcode](https://github.com/serhii-londar/DocumenterXcode) - Attempt to give a new life for VVDocumenter-Xcode as source editor extension.  :star:5

#### Themes
* [Dracula Theme](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode. :star:13
* [Xcode themes list](https://github.com/hdoria/xcode-themes) - Color themes for Xcode. :star:1848
* [Solarized-Dark-for-Xcode](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) - Solarized Dark Theme for Xcode 5.
* [WWDC2016 Xcode Color Scheme](https://github.com/cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation. :star:373

#### Other Xcode

* [awesome-xcode-scripts](https://github.com/aashishtamsya/awesome-xcode-scripts) - A curated list of useful xcode scripts 📝. :star:33
* [Synx](https://github.com/venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups. :star:5690
* [dsnip](https://github.com/Tintenklecks/IBDelegateCodesippets) - Tool to generate (native) Xcode code snippets from all protocols/delegate methods of UIKit (UITableView, ...)
* [SBShortcutMenuSimulator](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 3D Touch shortcuts in the Simulator :star:1790
* [awesome-gitignore-templates](https://github.com/aashishtamsya/awesome-gitignore-templates) - A collection of swift, objective-c, android and many more langugages .gitignore templates 📝. :star:11
* [swift-project-template](https://github.com/artemnovichkov/swift-project-template) - Template for iOS Swift project generation. :star:30
* [Swift-VIPER-Module](https://github.com/Juanpe/Swift-VIPER-Module) - Xcode template for create modules with VIPER Architecture written in Swift 3 :large_orange_diamond: :star:260
* [ViperC](https://github.com/abdullahselek/ViperC) - Xcode template for VIPER Architecture for both Objective-C and Swift :large_orange_diamond: :star:39
* [XcodeCodeSnippets](https://github.com/ismetanin/XcodeCodeSnippets) - A set of code snippets for iOS development, includes code and comments snippets. :star:12

# Reference
* [Swift Cheat Sheet](https://github.com/iwasrobbed/Swift-CheatSheet) - A quick reference cheat sheet for common, high level topics in Swift. :large_orange_diamond: :star:726
* [Objective-C Cheat Sheet](https://github.com/iwasrobbed/Objective-C-CheatSheet) - A quick reference cheat sheet for common, high level topics in Objective-C. :star:975
* [SwiftSnippets](https://github.com/hyperoslo/SwiftSnippets) - A collection of Swift snippets to be used in Xcode :star:106
* [App Store Checklist](https://github.com/whitef0x0/app-store-checklist) - A checklist of what to look for before submitting your app to the App Store. :star:22
* [whats-new-in-swift-4](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showcasing the new features in Swift 4.0. :large_orange_diamond: :star:1841
* [WWDC17-Recap](https://github.com/erenkabakci/WWDC17-Recap) - Markdown collection repo for the sessions at WWDC17. :star:98

# Style Guides
* [NY Times - Objective C Style Guide](https://github.com/NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times. :star:4640
* [raywenderlich Style Guide](https://github.com/raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com. :star:2726
* [Github Objective-C Style Guide](https://github.com/github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects. :star:1668
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions.
* [Swift Style Guide by @raywenderlich](https://github.com/raywenderlich/swift-style-guide) - The official Swift style guide for raywenderlich.com. :large_orange_diamond: :star:8170
* [Spotify Objective-C Coding Style](https://github.com/spotify/ios-style) - Guidelines for iOS development in use at Spotify. :star:198
* [Github - Style guide & coding conventions for Swift projects](https://github.com/github/swift-style-guide) - A guide to our Swift style and conventions by @github. :large_orange_diamond: :star:4432
* [Futurice iOS Good Practices](https://github.com/futurice/ios-good-practices) - iOS starting guide and good practices suggestions by [@futurice](https://github.com/futurice). :star:7144
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md) - SlideShare Swift Style Guide we are using for our upcoming iOS 8 only app written in Swift :large_orange_diamond:
* [Prolific Interactive Style Guide](https://github.com/prolificinteractive/swift-style-guide) - A style guide for Swift. :star:154

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
* [iOS Developer and Designer interview](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions) - A small guide to help those looking to hire a developer or designer for iOS work. :star:1393
* [iOS9-day-by-day](https://github.com/shinobicontrols/iOS9-day-by-day) :large_orange_diamond:
* [Code Facebook](https://code.facebook.com/ios/)
* [iOS Cookies](http://www.ioscookies.com/) - A hand curated collection of iOS libraries written in Swift :large_orange_diamond:
* [Feeds for iOS Developer](https://github.com/rgnlax/Feeds-for-iOS-Developer) - The list of RSS feeds for iOS developers. :star:73
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
* [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education) - :fire: All of the resources for Learning About Swift :large_orange_diamond: :star:5299
* [Awesome-Swift-Playgrounds](https://github.com/uraimo/Awesome-Swift-Playgrounds) - ⭐ A List of Awesome Swift Playgrounds! :large_orange_diamond: :star:1978
* [learn-swift](https://github.com/nettlep/learn-swift) - Learn Apple's Swift programming language interactively through these playgrounds. :large_orange_diamond: :star:764
* [Treehouse's iOS Courses and Workshops](https://teamtreehouse.com/library/topic:ios) - Topics for beginner and advanced developers in both Objective-C and Swift.
* [The Swift Summary Book](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language written on Playgrounds. :large_orange_diamond: :star:1648
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
* [Swift Developments](https://andybargh.com/swiftdevelopments/) - A weekly curated newsletter containing a hand picked selection of the latest links, videos, tools and tutorials for people interested in designing and developing their own iOS, WatchOS and AppleTV apps using Swift.

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
  * [@matteocrippa](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources. :star:13696
  * [@Wolg](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software. :star:4444
  * [Awesome-Swift-Education](https://github.com/hsavit1/Awesome-Swift-Education) - All of the resources for Learning About Swift :large_orange_diamond: :star:5299
* [awesome watchkit apps](https://github.com/sanketfirodiya/sample-watchkit-apps) curated list of sample watchkit apps and tutorials. :watch:
* [iOS Learning Resources](https://github.com/sanketfirodiya/iOS-learning-resources) Comprehensive collection of high quality, frequently updated and well maintained iOS tutorial sites.
* [awesome-ios-animation](https://github.com/ameizi/awesome-ios-animation) - A curated list of awesome iOS animation, including Objective-C and Swift libraries. :star:3101
* [awesome-ios-chart](https://github.com/ameizi/awesome-ios-chart) - A curated list of awesome iOS chart libraries, including Objective-C and Swift. :star:1106
* [awesome-gists](https://github.com/vsouza/awesome-gists#ios) - A list of amazing gists (iOS section).
* [awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) - A curated list of awesome iOS UI/UX libraries. :star:9956
* [Awesome-Server-Side-Swift/TheList](https://github.com/Awesome-Server-Side-Swift/TheList) - A list of Awesome Server Side Swift 3 projects :star:652
* [awesome-interview-questions](https://github.com/MaximAbramchuck/awesome-interview-questions#ios) - A curated awesome list of lists of interview questions including iOS.
* [iOS-Playbook](https://github.com/bakkenbaeck/iOS-handbook) - Guidelines and best practices for excellent iOS apps :star:80
* [iOS-Learning-Materials](https://github.com/jVirus/iOS-Learning-Materials) - Curated list of articles, web-resources, tutorials and code repositories that may help you dig a little bit deeper into iOS. :star:78
* [Awesome-iOS-Twitter](https://github.com/carolanitz/Awesome-iOS-Twitter) - A curated list of awesome iOS Twitter accounts :star:167
* [Marketing for Engineers](https://github.com/LisaDziuba/Marketing-for-Engineers) - A curated collection of marketing articles & tools to grow your product. :star:4258
* [Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit) - A curated list of awesome ARKit projects and resources. :star:3711
* [CocoaConferences](https://github.com/Lascorbe/CocoaConferences) - List of cocoa conferences for iOS & macOS developers. :star:757
* [example-ios-apps](https://github.com/imjog/example-ios-apps) - A curated list of Open Source example iOS apps developed in Swift. :star:18

# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.


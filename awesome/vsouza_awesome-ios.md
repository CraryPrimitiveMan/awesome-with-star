# Information comes from [vsouza/awesome-ios](https://github.com/vsouza/awesome-ios)
<img src="https://raw.githubusercontent.com/vsouza/awesome-ios/master/awesome_logo.png">

<p align="center">
    <img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  <a href="https://gitter.im/vsouza/awesome-ios"><img alt="Join the chat at gitter" src="https://badges.gitter.im/Join%20Chat.svg" /></a>
  <a href="https://travis-ci.org/vsouza/awesome-ios"><img alt="Build Status" src="https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master" /></a>
  <img alt="Language" src="https://awesomelinkcounter.herokuapp.com/swift" />
  <img alt="Language" src="https://awesomelinkcounter.herokuapp.com/objc" />
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

[Subscribe on Awesome-iOS Weekly!! 🗞](https://goo.gl/UtS5qk)

# About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode extensions and plugins, components and much more.
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).

## Recommended SDK for bug and crash reporting [Instabug](https://goo.gl/hNadrZ)
[![ios](https://user-images.githubusercontent.com/9888943/35385975-e6829fc0-01d2-11e8-963f-2166c4a67763.gif)](https://try.instabug.com/awesomeios/?utm_source=awesomeios&utm_medium=spon&utm_content=banner)
> We highly recommend integrating Instabug’s framework as they compiled a lot of great features in their SDK that provides useful and rich data with each bug/crash report. 
They removed the hassle of debugging as the SDK automatically attach screenshots, screen recordings, device details, network logs and repro-steps with each bug report which speeds up development process. Instabug is offering awesome-ios community an exclusive **15% discount** on all paid plans. [**Go to 5-minute installation guide.**](https://goo.gl/q93Qtd)🚀
[![](https://goo.gl/A74z8Q)](https://instabug.com)

# How to Use
Awesome-iOS is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/awesome_ios) or [Gitter Channel](https://gitter.im/vsouza/awesome-ios)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

## Content
- [About](#about)
- [How to Use](#how-to-use)
- [Courses](#courses)
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
        - [UIPageControl](#uipagecontrol)
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

# Courses

### Getting Started
* [Apple- Start Developing with iOS](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/) - Apple Guide. 
* [Apple - Object-Oriented Programming with Objective-C](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html)
* [Apple - Programming with Objective-C](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [CodeProject](https://www.codeproject.com/articles/88929/getting-started-with-iphone-and-ios-development) - Getting Started with iPhone and iOS Development.
* [Lifehacker](https://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
* [Ray Wenderlich](https://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - Learn to code iOS Apps.
* [Stanford - Developing iOS 7 Apps for iPhone and iPad](https://itunes.apple.com/us/course/developing-ios-7-apps-for-iphone-and-ipad/id733644550)
* [Stanford - Developing iOS 10 Apps with Swift](https://itunes.apple.com/in/course/developing-ios-10-apps-swift/id1198467120) - Stanford's 2017 iTunes U course. 
* [Stanford - Developing iOS 11 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-11-apps-with-swift/id1309275316) - Stanford's 2017 iTunes U course updated for iOS 11 and Swift. 
* [Swifteducation - Teaching App Development with Swift](https://swifteducation.github.io/teaching_app_development_with_swift/)
* [Udacity - Intro to iOS App Development with Swift](https://br.udacity.com/course/intro-to-ios-app-development-with-swift--ud585)

### Other free courses

 * [Codeschool - Exploring Google Maps for iOS](https://www.codeschool.com/courses/exploring-google-maps-for-ios) 
 * [Udemy - ARKit - Beginner to Professional in Swift 4 and iOS 11](https://www.udemy.com/arkit-beginner-to-professional/?couponCode=CREATORS)

 
# Libraries And Frameworks

## Analytics
* [Instabug](https://instabug.com) - In-app feedback, Bug and Crash reporting, Fix Bugs Faster through user-steps, video recordings, screen annotation, network requests logging.
* [Mixpanel](https://mixpanel.com/) - Advanced analytics platform.
* [Localytics](https://www.localytics.com/) - Brings app marketing and analytics together.
* [Answers by Fabric](https://answers.io/) - Answers gives you real-time insight into people’s experience in your app.
* [Liquid Analytics](https://onliquid.com) - Identify behaviours through Analytics and react with real-time Personalization.
* [GTrack](https://github.com/gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies. :star:85
* [ARAnalytics](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data. :star:1723
* [Segment](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application. :star:265
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions. :star:2
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing
* [WAAppRouting](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically! :star:572
* [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links. :star:3056
* [IntentKit](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps. :star:1821
* [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API. :star:4184
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks  :star:95
* [Compass](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application  :star:670
* [Appz](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed.  :star:895
* [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift  :star:1501
* [Marshroute](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful.   :star:150
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 3  :star:178
* [Router](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS.  :star:138
* [ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain. :star:281
* [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) - Navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.  :star:688

## Apple TV
* [Voucher](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts. :star:496
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2283
* [TVMLKitchen](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server  :star:69
* [BrowserTV](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage!  :star:208
* [Swift-GA-Tracker-for-Apple-tvOS](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV.  :star:71
* [ParallaxView](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application.  :star:350
* [TvOSTextViewer](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text  :star:28
* [FocusTvButton](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS  :star:38
* [TvOSMoreButton](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'.  :star:29
* [TvOSPinKeyboard](https://github.com/zattoo/TvOSPinKeyboard) - PIN keyboard for tvOS  :star:95
* [TvOSScribble](https://github.com/dcordero/TvOSScribble) - Handwriting numbers recognizer for Siri Remote  :star:160
* [TvOSCustomizableTableViewCell](https://github.com/zattoo/TvOSCustomizableTableViewCell) - Light wrapper of UITableViewCell that allows extra customization for tvOS  :star:20

## Architecture Patterns
* [SwiftyVIPER](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.   :star:62
* [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift.  :star:1274
* [Viperit](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift.  :star:241
* [Reactant](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS  :star:329
* [YARCH](https://github.com/alfa-laboratory/YARCH) - More clean alternative to VIPER with unidirectional data flow (flux-like).  :star:50
* [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) - This repository contains a detailed sample app that implements VIPER architecture in iOS using libraries and frameworks like Alamofire, AlamofireImage, PKHUD, CoreData etc. :star:259
* [Tempura](https://github.com/BendingSpoons/tempura-swift) - A holistic approach to iOS development, inspired by Redux and MVVM. :star:276


## ARKit
* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data. 
* [Virtual Objects](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality. :star:187
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆.  :star:600
* [ARKitEnvironmentMapper](https://github.com/svtek/ARKitEnvironmentMapper) - A library that allows you to generate and update environment maps in real-time using the camera feed and ARKit's tracking capabilities.  :star:30
* [SmileToUnlock](https://github.com/rsrbk/SmileToUnlock) - This library uses ARKit Face Tracking in order to catch a user's smile. :star:491

## Authentication
* [Heimdallr.swift](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift.  :star:470
* [OhMyAuth](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services.  :star:55
* [AuthenticationViewController](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController.  :star:237
* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift.  :star:667
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS  :star:1990
* [SimpleAuth](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS. :star:1167
* [AlamofireOauth2](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2  :star:74
* [SwiftyOAuth](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers  :star:465
* [Simplicity](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps.  :star:650
* [InstagramAuthViewController](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication.  :star:33
* [InstagramSimpleOAuth](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app. :star:83
* [DropboxSimpleOAuth](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app. :star:42
* [BoxSimpleOAuth](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app. :star:15
* [InstagramLogin](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS.  :star:22
* [ReCaptcha](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS.  :star:67
* [LinkedInSignIn](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn.  :star:10

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:10299
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews :star:10381
* [MAIKit](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS :star:141

## Cache

*Thread safe, offline and high performance cache libs and frameworks.*

* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift)  :star:1104
* [mattress](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content  :star:455
* [Carlos](https://github.com/WeltN24/Carlos) - A simple but flexible cache  :star:470
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images.  :star:4635
* [YYCache](https://github.com/ibireme/YYCache) - High performance cache framework for iOS. :star:1695
* [Cache](https://github.com/hyperoslo/Cache) - Nothing but Cache.  :star:1149
* [MGCacheManager](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class. :star:8
* [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify :star:1162
* [Track](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU.  :star:194
* [UITableView Cache](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating. :star:67
* [RocketData](https://github.com/plivesey/RocketData) - A caching and consistency solution for immutable models.  :star:533
* [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS :star:1890
* [Johnny](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift  :star:27
* [Disk](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data.  :star:1885
* [Cachyr](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift  :star:98
* [Cache](https://github.com/soffes/Cache) - Swift caching library.  :star:182

## Charts

*Beautiful, Easy and Fully customized charts*

* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart).  :star:17566
* [JTChartView](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart. :star:121
* [PNChart](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS :star:9139
* [XJYChart](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight. :star:572
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library). :star:2708
* [JBChartView](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs. :star:3794
* [XYPieChart](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app. :star:1755
* [TEAChart](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart. :star:1157
* [EChart](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported. :star:644
* [FSLineChart](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS. :star:836
* [chartee](https://github.com/zhiyu/chartee) - a charting library for mobile platforms. :star:892
* [ANDLineChartView](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart. :star:417
* [TWRCharts](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code. :star:370
* [SwiftCharts](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS.  :star:1624
* [FlowerChart](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector.  :star:9
* [Scrollable-GraphView](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift.  :star:4386
* [Dr-Charts](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C. :star:70
* [Graphs](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS.  :star:883
* [FSInteractiveMap](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS! :star:478
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation. :star:399
* [TKRadarChart](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift  :star:141
* [MagicPie](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1  🎉 ✨✨✨✨✨ :star:530
* [PieCharts](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS.  :star:357
* [CSPieChart](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable.  :star:30
* [DDSpiderChart](https://github.com/dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift.  :star:33
* [core-plot](https://github.com/core-plot/core-plot) - a 2D plotting lib which is highly customizable and capable of drawing many types of plots. :star:2539
* [ChartProgressBar](https://github.com/hadiidbouk/ChartProgressBar-iOS) - Draw a chart with progress bar style. :star:40
* [SMDiagramViewSwift](https://github.com/VRGsoftUA/SMDiagramView) - Meet cute and very flexibility library for iOS application for different data view in one circle diagram. :star:18
* [Swift LineChart](https://github.com/zemirco/swift-linechart) - Line Chart library for iOS written in Swift.  :star:518
* [SwiftChart](https://github.com/gpbl/SwiftChart) - Line and area chart library for iOS.  :star:618
* [EatFit](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :star:630

## Code Quality

 *Quality always matters. Code checkers, memory vigilants, syntastic sugars and more.*

* [Bootstrap](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding. :star:1934
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL. :star:106
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle](https://github.com/Cue/ocstyle) - Objective-C style checker. :star:257
* [spacecommander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying. :star:860
* [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling. :star:568
* [Tailor](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs. :star:1178
* [SwiftCop](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations.  :star:509
* [Trackable](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects.  :star:137
* [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time. :star:3186
* [HeapInspector-for-iOS](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments :star:1669
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage. :star:2896
* [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime. :star:2862
* [Buglife](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps :star:408
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets. :star:433
* [Aardvark](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports. :star:204
* [Stats](https://github.com/shu223/Stats) - In-app memory usage monitoring. :star:150
* [GlueKit](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift.  :star:353
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code.  :star:1861
* [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods. :star:215
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch.  :star:37
* [ODUIThreadGuard](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread.  :star:700
* [IBAnalyzer](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests.  :star:865
* [DecouplingKit](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project. :star:116
* [Clue](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure. :star:262

#### Linter
* [OCLint](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects. :star:2586
* [Taylor](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms.  :star:209
* [Swiftlint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.  :star:8923
* [IBLinter](https://github.com/kateinoigakukun/IBLinter) - A linter tool for Interface Builder.  :star:587

## Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift).  :star:10884
* [ColorArt](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11. :star:133
* [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. [e] :star:1792
* [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. [e] :star:527
* [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier. :star:2964
* [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string.  :star:861
* [Hue](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need. :star:2415
* [FlatUIColors](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift.  :star:149
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js.  :star:450
* [PFColorHash](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string.  :star:17
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift)  :star:428
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes :star:2993
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm).  :star:148
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift).  :star:16
* [CostumeKit](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app.  :star:297
* [CSS3ColorsSwift](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name.  :star:56
* [Colorify](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017.  :star:81
* [ChromaColorPicker](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift.  :star:120
* [Lorikeet](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation.  :star:17
* [Gestalt](https://github.com/regexident/Gestalt) - An unintrusive & light-weight iOS app-theming library with support for animated theme switching.  :star:117

## Command Line
* [Swiftline](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications.  :star:1009
* [CommandLine](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces  :star:1026
* [Commander](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift  :star:1055
* [ColorizeSwift](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift.  :star:169
* [Guaka](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift  :star:1063
* [Marathon](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts  :star:1430
* [CommandCougar](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications.  :star:20

## Concurrency
* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift  :star:1353
* [Concurrent](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives  :star:149
* [Flow](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift  :star:194
* [Brisk](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation.  :star:22
* [Aojet](https://github.com/aojet/Aojet) - An actor model library for swift. :star:24
* [Overdrive](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading.  :star:828
* [NSLock+Synchronized](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via CocoaPods and Carthage Framework. [e] :star:4
* [AsyncNinja](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives.  :star:72
* [Kommander](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand.  :star:124
* [Threadly](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift  :star:45
* [Flow-iOS](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable  :star:10
* [Queuer](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD).  :star:720
* [SwiftQueue](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more.  :star:41
* [GroupWork](https://github.com/quanvo87/GroupWork) - Easy concurrent, asynchronous tasks in Swift.  :star:35

## Core Data
* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework. :star:71
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C. :star:1334
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code. :star:469
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data. :star:239
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data. :star:1568
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping. :star:185
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation. :star:2966
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread. :star:208
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher. :star:667
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data. :star:10621
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language.  :star:1299
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc.  :star:1834
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. 
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift.  :star:759
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations.  :star:32
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data  :star:2141
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift.  :star:738
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift.  :star:288
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack  :star:536
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack  :star:451
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour.  :star:189
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices.  :star:96
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations.  :star:6
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer.  :star:175
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box. :star:102
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift.  :star:483
* [Records](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift.  :star:13
* [PredicateFlow](https://github.com/andreadelfante/PredicateFlow) - Write amazing, strong-typed and easy-to-read NSPredicate, allowing you to write flowable NSPredicate, without guessing attribution names, predicate operation or writing wrong arguments type. :star:4

## Database
* [Realm](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast. :star:11906
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac. :star:3023
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite. :star:12278
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access. :star:1641
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud.  :star:439
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state.  :star:451
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support).  :star:54
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults.  :star:3126
* [SugarRecord](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0  :star:1993
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3.  :star:5056
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support  :star:1241
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift.  :star:793
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers. :star:2628
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults.  :star:110
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats.  :star:151
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift  :star:80
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  [e] :star:108
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift  :star:272
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage. :star:38
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API. :star:63
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB  :star:67
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API.  :star:22
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:45
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:22
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:72
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:20
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:36
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:24
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage.  :star:221
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk.  :star:163
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS. :star:5462
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠 :star:184
* [UserDefaults](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS  :star:954
* [Default](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support  :star:349
* [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit  :star:768
* [FirebaseHelper](https://github.com/quanvo87/FirebaseHelper) - Safe and easy wrappers for common Firebase Realtime Database functions. :star:6
* [Shallows](https://github.com/dreymonde/Shallows) - Your lightweight persistence toolbox. :star:475

## Data Structures / Algorithms
* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift  :star:4
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another  :star:729
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees  :star:988
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift.  :star:1845
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift  :star:90
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios  :star:54
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset.  :star:640
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily.  :star:61
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/.  :star:3810
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations.  :star:2008
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C. :star:2320
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData. :star:21
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration.  :star:339
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift.  :star:357
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift.  :star:236
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily.  :star:73
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library.  :star:60
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs.  :star:22
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations!  :star:16399
* [Impeller](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift  :star:94
* [Dispatch](https://github.com/alexdrone/Dispatch) - Multi-store Flux implementation in Swift  :star:256
* [DeepDiff](https://github.com/onmyway133/DeepDiff) - Diff in Swift  :star:887
* [BinaryKit](https://github.com/Cosmo/BinaryKit) - Access bits and bytes directly in Swift.  :star:41
* [Differ](https://github.com/tonyarnold/Differ) - Swift library to generate differences and patches between collections. :star:156
* [Probably](https://github.com/harlanhaskins/Probably) - A Swift probability and statistics library.  :star:231
* [RandMyMod](https://github.com/jamesdouble/RandMyMod) - RandMyMod base on your own struct or class create one or a set of randomized instance. :star:1

## Date & Time

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift  :star:2457
* [SwiftDate](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0  :star:3635
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2  :star:1514
* [DateTools](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C :star:6092
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer  :star:954
* [DateHelper](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift  :star:925
* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats. :star:598
* [EmojiTimeFormatter](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis.  :star:73
* [Kronos](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift  :star:248
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) .  :star:241
* [10Clock](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer.  :star:447
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad. :star:1729
* [AnyDate](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API.  :star:153
* [TimeZonePicker](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app.  :star:95
* [Time](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. [e] :star:800
* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library  :star:917
* [Solar](https://github.com/ceeK/Solar) - A Swift micro library for generating Sunrise and Sunset times.  :star:157
* [TimePicker](https://github.com/Endore8/TimePicker) - Configurable time picker component based on a pan gesture and its velocity. :star:9
* [LFTimePicker](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift  :star:47

## Debugging
* [Xniffer](https://github.com/vsouza/awesome-ios/issues/1841) - A swift network profiler built on top of URLSession. 
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library!  :star:2063
* [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools. :star:5549
* [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers. :star:600
* [Flex](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS. :star:8885
* [chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps. :star:6613
* [Alpha](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS. :star:678
* [AEConsole](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App.  :star:95
* [GodEye](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift.  :star:2945
* [NetworkEye](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request. :star:1068
* [Dotzu](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network. :star:1475
* [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations. :star:1369
* [Httper-iOS](https://github.com/MuShare/Httper-iOS) - App for developers to test REST API.  :star:326

## EventBus
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8.  :star:629
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS. :star:9042
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links). :star:5264
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.   :star:1773
* [When](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift.  :star:135
* [then🎬](https://github.com/freshOS/then) - Elegant Async code in Swift.  :star:619
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier.  :star:1075
* [RWPromiseKit](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C :star:100
* [FutureLib](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala.  :star:36
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety  :star:481
* [FutureKit](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS.  :star:691
* [signals-ios](https://github.com/uber/signals-ios) - Typeful eventing :star:502
* [BrightFutures](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises.  :star:1627
* [NoticeObserveKit](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type.  :star:112
* [Hydra](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift  :star:1423
* [Promis](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate.  :star:74
* [Bluebird.swift](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4.  :star:29
* [Promise](https://github.com/khanlou/Promise) - A Promise library for Swift, based partially on Javascript's A+ spec.  :star:437
* [promises](https://github.com/google/promises) - Google provides a synchronization construct for Objective-C and Swift to facilitate writing asynchronous code. :star:1888
* [Continuum](https://github.com/marty-suzuki/Continuum) - NotificationCenter based Lightweight UI / AnyObject binder. :star:79

## Files
* [FileKit](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift.  :star:1763
* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files.  :star:1208
* [FileBrowser](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS.  :star:1170
* [Ares](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices  :star:116
* [FileProvider](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS.  :star:255
* [KZFileWatchers](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools.  :star:831
* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac. :star:3370
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories.  :star:527
* [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift  :star:864
* [AppFolder](https://github.com/dreymonde/AppFolder) - AppFolder is a lightweight framework that lets you design a friendly, strongly-typed representation of a directories inside your app's container.  :star:745
* [ZipZap](https://github.com/pixelglow/ZipZap) - zip file I/O library for iOS, macOS and tvOS. :star:1132

## Functional Programming
* [Forbind](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift.  :star:43
* [Funky](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift.  :star:12
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools.  :star:629
* [Oriole](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. [e] :star:11
* [Prelude](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools.  :star:325
* [Swiftx](https://github.com/typelift/Swiftx) - Functional data types and functions for any project.  :star:193
* [Swiftz](https://github.com/typelift/Swiftz) -  Functional programming in Swift.  :star:3094
* [OptionalExtensions](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. [e] :star:174
* [Hookah](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project.  :star:56
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift  :star:3306
* [Runes](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift.  :star:680

## Games
* [Sage](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift.  :star:341
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI.  :star:50
* [SKTiled](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit  :star:110
* [CollectionNode](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit  :star:48
* [AssetImportKit](https://github.com/eugenebokhan/AssetImportKit) - Swifty cross platform library (macOS, iOS) that converts Assimp supported models to SceneKit scenes. :star:10

## GCD
 * [GCDKit](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift.  :star:285
 * [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch  :star:4210
 * [SwiftSafe](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy  :star:157
 * [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue. :star:314
 * [AlecrimAsyncKit](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring.  :star:66
 * [GrandSugarDispatch](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD)  :star:31
 * [Threader](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution. :star:39
 * [Dispatch](https://github.com/JARMourato/Dispatch) - Just a tiny library to make using GCD easier and intuitive  :star:173
 * [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift.  :star:171
 * [Chronos-Swift](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities  :star:251
 * [Me](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations.  :star:193
 * [SwiftyTask](https://github.com/CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure.  :star:11

## Gesture
* [Tactile](https://github.com/delba/Tactile) - A better way to handle gestures on iOS  :star:640
* [SwiftyGestureRecognition](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds  :star:145
* [DBPathRecognizer](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS]  :star:1098
* [Sensitive](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift.  :star:469
* [SplitViewDragAndDrop](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode.  :star:292
* [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. :star:4736

## Graphics
* [Graphicz](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics!  :star:36
* [PKCoreTechniques](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich. :star:145
* [MPWDrawingContext](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext :star:90
* [DePict](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift!  :star:30
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView).  :star:960
* [InkKit](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift!  :star:356
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display. :star:388
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone  :star:1050
* [jot](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images. :star:1687
* [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating). :star:3024
* [Snowflake](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift.  :star:823
* [HxSTLParser](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit :star:14
* [ProcessingKit](https://github.com/natmark/ProcessingKit) - Visual designing library for iOS & OSX  :star:227
* [EZYGradientView](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code  :star:319
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift.  :star:47
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift.  :star:87
* [EPShapes](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder.  :star:377
* [Macaw](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift.  :star:3472

## Hardware
#### Bluetooth
* [Discovery](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background). :star:384
* [LGBluetooth](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code. :star:149
* [PeerKit](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. 
* [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE.  :star:1630
* [Bluetonium](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift  :star:136
* [BlueCap](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework  :star:464
* [Apple Family](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.   :star:39
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U   :star:447
* [Bluejay](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps.  :star:653
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS. :star:3466
* [ExtendaBLE](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates. :star:74
* [PeerConnectivity](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :star:36
* [AZPeerToPeerConnection](https://github.com/AfrozZaheer/AZPeerToPeerConnection) - AZPeerToPeerConnectivity is a wrapper on top of Apple iOS Multipeer Connectivity framework. It provides an easier way to create and manage sessions. Easy to integrate. :star:40

#### Camera
* [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects. :star:1432
* [PBJVision](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture. :star:1797
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation. :star:1198
* [SCRecorder](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing. :star:2777
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift.  :star:1611
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works.  :star:3534
* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app.  :star:682
* [RSBarcodes_Swift](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift.  :star:574
* [LLSimpleCamera](https://github.com/omergul/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS. :star:1126
* [Fusuma](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift.  :star:2027
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner.  :star:869
* [JVTImageFilePicker](https://github.com/mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C. :star:56
* [HorizonSDK-iOS](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library. :star:164
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters :star:1757
* [DKCamera](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift.  :star:38
* [NextLevel](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS.  :star:1103
* [CameraEngine](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒  :star:459
* [SwiftyCam](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift.  :star:1139
* [CameraBackground](https://github.com/yonat/CameraBackground) -  Show camera layer as a background to any UIView.  :star:19
* [Lumina](https://github.com/dokun1/Lumina) - Full service camera that takes photos, videos, streams frames, detects metadata, and streams CoreML predictions :largeorangediamond: :star:293
* [RAImagePicker](https://github.com/rallahaseh/RAImagePicker) - RAImagePicker is a protocol-oriented framework that provides custom features from the built-in Image Picker Edit. :star:8
* [FDTake](https://github.com/fulldecent/FDTake) - Easily take a photo or video or choose from library.  :star:262
* [YPImagePicker](https://github.com/Yummypets/YPImagePicker) - Instagram-like image picker & filters for iOS :star:577

#### Force Touch
* [QuickActions](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts)  :star:213
* [JustPeek](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction.  :star:66
* [PeekView](https://github.com/itsmeichigo/PeekView) - PeekView supports peek, pop and preview actions for iOS devices without 3D Touch capibility.  :star:114

#### iBeacon
* [Proxitee](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences. :star:15
* [OWUProximityManager](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth. :star:357
* [Vicinity](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background. :star:363
* [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon. :star:819
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby.  :star:135

#### Location
* [IngeoSDK](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS. :star:93
* [LocationManager](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously. :star:2219
* [SwiftLocation](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift  :star:1663
* [SOMotionDetector](https://github.com/arturdev/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration. :star:1006
* [LocationPicker](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app  :star:304
* [BBLocationManager](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS. :star:85
* [set-simulator-location](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator.  :star:206

#### Other Hardware
* [MotionKit](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple. :star:970
* [DarkLightning](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and macOS. :star:190
* [Deviice](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties)  :star:22
* [DeviceKit](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice.  :star:1845
* [Luminous](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system.  :star:197
* [Device](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift.  :star:1069
* [WatchShaker](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift.  :star:151
* [WatchCon](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️ :star:25
* [TapticEngine](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations.  :star:175
* [UIDeviceComplete](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces.  :star:230
* [NFCNDEFParse](https://github.com/jvk75/NFCNDEFParse) - NFC Forum Well Known Type Data Parser for iOS11 and Core NFC.  :star:4
* [Device.swift](https://github.com/schickling/Device.swift) - Super-lightweight library to detect used device. :star:138
* [SDVersion](https://github.com/sebyddd/SDVersion) - :iphone: Lightweight Cocoa library for detecting the running device's model and screen size.  :star:1267

## Layout
* [FlexboxLayout](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift  :star:320
* [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax. :star:16150
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code. :star:1514
* [Façade](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative. :star:708
* [PureLayout](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & macOS Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible. :star:6888
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & macOS.  :star:12222
* [Cartography](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler:  :star:6223
* [AutoLayoutPlus](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift.  :star:27
* [Neon](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework.  :star:4254
* [MisterFusion](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C.  :star:268
* [SwiftBox](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout.  :star:803
* [ManualLayout](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. [e] :star:275
* [Stevia](https://github.com/freshOS/Stevia) - Elegant view layout for iOS.  :star:2215
* [Manuscript](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift.  :star:76
* [FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating :star:8666
* [SwiftAutoLayout](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout  :star:648
* [FormationLayout](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily.  :star:53
* [SwiftyLayout](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift  :star:15
* [Swiftstraints](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy  :star:98
* [SwiftBond](https://github.com/DeclarativeHub/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm.  :star:3437
* [Restraint](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift  :star:74
* [EasyPeasy](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy   :star:1591
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! 
* [Anchorman](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego.  :star:63
* [LayoutKit](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS.  :star:2415
* [MarkupKit](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications :star:460
* [Relayout](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally  :star:578
* [Anchorage](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code.  :star:338
* [Compose](https://github.com/GrupoZapVivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views.  :star:125
* [BrickKit](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors.  :star:596
* [Framezilla](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax.  :star:92
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use.  :star:2447
* [MyLinearLayout](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. :star:2754
* [SugarAnchor](https://github.com/ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable.  :star:20
* [Anchors](https://github.com/onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+  :star:121
* [PinLayout](https://github.com/mirego/PinLayout) - Extremely Fast views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable.  :star:846
* [SnapLayout](https://github.com/sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. [e] :star:9
* [Cupcake](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS.  :star:193
* [MiniLayout](https://github.com/yonat/MiniLayout) - Minimal AutoLayout convenience layer. Program constraints succinctly.  :star:4
* [Bamboo](https://github.com/wordlessj/Bamboo) - Bamboo makes Auto Layout (and manual layout) elegant and concise.  :star:46
* [FlexLayout](https://github.com/layoutBox/FlexLayout) - FlexLayout gently wraps the highly optimized [facebook/yoga](https://github.com/facebook/yoga) flexbox implementation in a concise, intuitive & chainable syntax.  :star:408
* [Layout](https://github.com/schibsted/layout) - A declarative UI framework for iOS  :star:1277
* [CGLayout](https://github.com/k-o-d-e-n/CGLayout) - Powerful autolayout framework based on constraints, that can manage UIView(NSView), CALayer and not rendered views. Not Apple Autolayout wrapper.  :star:24
* [YogaKit](https://github.com/facebook/yoga/tree/master/YogaKit) - Powerful layout engine which implements Flexbox. Developed and maintained by Facebook.
* [FlightLayout](https://github.com/AntonTheDev/FlightLayout) -  Balanced medium between manual layout and auto-layout. Great for calculating frames for complex animations. :star:22
* [QLayout](https://github.com/josejuanqm/QLayout) - AutoLayout Utility for iOS.  :star:1
* [Layoutless](https://github.com/DeclarativeHub/Layoutless) - Minimalistic declarative layout and styling framework built on top of Auto Layout. :star:183
* [Yalta](https://github.com/kean/Yalta) - An intuitive and powerful Auto Layout library. :star:120
* [GranadaLayout](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater. :star:42
* [SuperLayout](https://github.com/lionheart/SuperLayout) - Simplify Auto Layout with super syntactic sugar. :star:40

## Localization
* [Hodor](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App. :star:501
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework.  :star:552
* [Rubustrings](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files :star:57
* [BartyCrouch](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs.  :star:384
* [LocalizationKit](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission. :star:968
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching  :star:1738
* [LocalizedView](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file. :star:8
* [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:50
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language. :star:106
* [IBLocalizable](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable  :star:408
* [nslocalizer](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings :star:122
* [L10n-swift](https://github.com/Decybel07/L10n-swift) - Localization of an application with ability to change language "on the fly" and support for plural forms in any language.  :star:58

## Logging
* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant.  :star:1130
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS. :star:10049
* [NSLogger](https://github.com/fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on macOS, iOS and Android. :star:4199
* [QorumLogs](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. 
* [Log](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns.  :star:704
* [Rainbow](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers.  :star:1002
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3  :star:3441
* [SwiftyTextTable](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables.  :star:124
* [Watchdog](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread  :star:1493
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number.  :star:2861
* [puree](https://github.com/cookpad/puree-ios) - A log collector for iOS :star:153
* [Colors](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! [e] :star:26
* [Loggerithm](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output.  :star:266
* [AELog](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift.  :star:18
* [ReflectedStringConvertible](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct.  :star:50
* [Evergreen](https://github.com/nilsleiffischer/Evergreen) - Most natural Swift logging  :star:70
* [SwiftTrace](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations  :star:127
* [Willow](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift.  :star:1034
* [Bugfender](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps. :star:38
* [LxDBAnything](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly! :star:419
* [XLTestLog](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console :star:60
* [XLFacility](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for macOS & iOS (includes database, Telnet and HTTP servers)
* [Atlantis](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability.  :star:201
* [StoryTeller](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important. :star:8
* [LumberMill](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0 :star:2
* [TinyConsole](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3.  :star:1748
* [Lighty](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3.  :star:37
* [JustLog](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket.  :star:233
* [Twitter Logging Service](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients. :star:168
* [Reqres](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support  :star:26

## Machine Learning
* [Swift-Brain](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI.  :star:305
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians.  :star:666
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/ios) - The official Google-built powerful neural network library port for iOS.
* [Bender](https://github.com/xmartlabs/Bender) - Easily craft fast Neural Networks. Use TensorFlow models. Metal under the hood. :star:1450
* [Caffe2](https://github.com/caffe2/caffe2) - Lightweight, modular, and scalable deep learning framework. :star:7580
* [CoreML-samples](https://github.com/ytakzk/CoreML-samples) - Sample code for Core ML using ResNet50 provided by Apple and a custom model generated by coremltools.  :star:21
* [Revolver](https://github.com/petrmanek/Revolver) - A framework for building fast genetic algorithms in Swift. Comes with modular architecture, pre-implemented operators and loads of examples.  :star:15
* [CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models. :star:2468
* [Serrano](https://github.com/pcpLiu/Serrano) - A deep learning library for iOS and macOS.  :star:30
* [Swift-AI](https://github.com/Swift-AI/Swift-AI) - The Swift machine learning library.  :star:5280
* [TensorSwift](https://github.com/qoncept/TensorSwift) - A lightweight library to calculate tensors in Swift, which has similar APIs to TensorFlow's.  :star:287

## Maps
* [Route-me](https://github.com/route-me/route-me) - Open source map library for iOS. :star:1307
* [NAMapKit](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework. :star:256
* [Mapbox GL](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS. :star:2492
* [CMMapLauncher](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications. :star:193
* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine.  :star:909
* [PXGoogleDirections](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift  :star:215
* [Cluster](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering.  :star:816
* [JDSwiftHeatMap](https://github.com/jamesdouble/JDSwiftHeatMap) - JDSwiftMap is an IOS Native MapKit Library. You can easily make a highly customized HeatMap.  :star:52
* [ClusterKit](https://github.com/hulab/ClusterKit) - An iOS map clustering framework targeting MapKit, Google Maps and Mapbox. :star:267
* [FlyoverKit](https://github.com/SvenTiigi/FlyoverKit) - FlyoverKit enables you to present stunning 360° flyover views on your MKMapView with zero effort while maintaining full configuration possibilities. :star:373

## Math
* [Euler](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation  :star:879
* [SwiftMath](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials.  :star:152
* [Arithmosophi](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations  :star:56
* [Surge](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation.  :star:3947
* [Upsurge](https://github.com/alejandro-isaza/Upsurge) - Swift math  :star:129
* [Swift-MathEagle](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions.  :star:33
* [iosMath](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS. :star:724
* [swift-pons](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift  :star:212
* [BigInt](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic in pure Swift  :star:375
* [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation.  :star:498
* [VectorMath](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics  :star:175
* [Expression](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime  :star:355
* [Metron](https://github.com/toineheuvelmans/Metron) - Metron is a comprehensive collection of geometric functions and types that extend the 2D geometric primitives provided by CoreGraphics.  :star:932
* [NumericAnnex](https://github.com/xwu/NumericAnnex) - NumericAnnex supplements the numeric facilities provided in the Swift standard library with generic integer algorithms, complex numbers, rational numbers, and pseudorandom number generators (written in, and for, Swift 4)  :star:40
* [EasyRoot](https://github.com/aaronjsutton/EasyRoot) - A framework to simplify radical expressions 
* [SwiftSimplify](https://github.com/malcommac/SwiftSimplify) - Tiny high-performance Swift Polyline Simplification Library. :star:152

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds.  :star:5043
* [EZAudio](https://github.com/syedhali/EZAudio) - An iOS/macOS audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations. :star:4246
* [novocaine](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and macOS. :star:2101
* [QHSpeechSynthesizerQueue](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech). :star:28
* [Cephalopod](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift.  :star:80
* [Chirp](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app!  :star:306
* [Beethoven](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals.  :star:333
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. 
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote).  :star:340
* [TuningFork](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS  :star:357
* [MusicKit](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift  :star:485
* [SubtleVolume](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator.  :star:624
* [NVDSP](https://github.com/bartolsthoorn/NVDSP) - iOS/macOS DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:82
* [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface. :star:459
* [TheAmazingAudioEngine2](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to. :star:370
* [InteractivePlayerView](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view  :star:238
* [ESTMusicIndicator](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift  :star:364
* [QuietModemKit](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. CocoaPods and Carthage compatible.  :star:578
* [BPMAnalyser](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files.  :star:17
* [PandoraPlayer](https://github.com/AppliKeySolutions/PandoraPlayer) - A lightweight music player for iOS, based on AudioKit and completely written in Swift  :star:678
* [SonogramView](https://github.com/Luccifer/SonogramView) - Audio visualisation of song :star:14
* [AudioIndicatorBars](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app.  :star:179

#### GIF
* [YLGIFImage](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory. :star:1707
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS :star:6464
* [gifu](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift  :star:1953
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling :star:1038
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage  :star:576
* [SwiftGif](https://github.com/swiftgif/SwiftGif) - :sparkles: A small UIImage extension with gif support  :star:805
* [APNGKit](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS.  :star:1339
* [YYImage](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more. :star:1152
* [AImage](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case. :star:940
* [NSGIF2](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url. :star:62
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - High performance GIF engine  :star:774

#### Image
* [GPU Image](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. :star:17110
* [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - iOS UIImage processing functions using the vDSP/Accelerate framework for speed. :star:377
* [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI. :star:941
* [SDWebImage](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category. :star:19525
* [DFImageManager](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession. :star:1216
* [MapleBacon](https://github.com/JanGorman/MapleBacon) - An image download and caching library for iOS written in Swift.  :star:206
* [NYTPhotoViewer](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer. :star:2343
* [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer. :star:2519
* [JTSImageViewController](https://github.com/jaredsinclair/JTSImageViewController) - Interactive iOS image viewer. :star:2294
* [Concorde](https://github.com/contentful-labs/Concorde/) - Download and decode progressive JPEGs.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects. :star:2065
* [YXTMotionView](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling. :star:79
* [PINRemoteImage](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher. :star:3323
* [SABlurImageView](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image.  :star:488
* [FastImageCache](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling. :star:7742
* [BKAsciiImage](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art :star:407
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire.  :star:2870
* [Nuke](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating  :star:2651
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web.  :star:1994
* [YYWebImage](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF). :star:3098
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation. :star:1975
* [Silo](https://github.com/josejuanqm/Silo) - Image loading framework with loaders.  :star:12
* [Ody](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders.  :star:43
* [Banana](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface.  :star:16
* [JDSwiftAvatarProgress](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated  :star:83
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web.  :star:11190
* [EBPhotoPages](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser. :star:1635
* [UIImageView-BetterFace-Swift](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace  :star:448
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch.  :star:341
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift  :star:2109
* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift.  :star:264
* [ImageScout](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG.  :star:864
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image.  :star:363
* [Agrume](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift.  :star:235
* [PASImageView](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift  :star:167
* [Navi](https://github.com/nixzhu/Navi) - Focus on avatar caching.  :star:117
* [SwiftPhotoGallery](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures.  :star:107
* [MetalAcc](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift. :star:202
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections. :star:8032
* [UIImageColors](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. [e] :star:1794
* [CDFlipView](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects. :star:94
* [GPUImage2](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing.  :star:3574
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect  :star:408
* [ImageButter](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth :star:381
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift  :star:1497
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework :star:797
* [CLImageViewPopup](https://github.com/vinbhai4u/CLImageViewPopup/) - A simple Image full screen pop up 
* [APKenBurnsView](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition!  :star:58
* [Moa](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. [e] :star:273
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images.  :star:125
* [ImageViewer](https://github.com/MailOnline/ImageViewer) - An image viewer à la Twitter  :star:1735
* [FaceAware](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill.  :star:2278
* [SwiftyAvatar](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard :star:172
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters  :star:64
* [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches.  :star:1383
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js.  :star:567
* [ImageSlideshow](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer.  :star:796
* [Imaginary](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three.  :star:417
* [PPAssetsActionController](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview.  :star:53
* [Vulcan](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift.  :star:276
* [FacebookImagePicker](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker written in Swift.  :star:115
* [Lightbox](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app.  :star:655
* [AvatarImageView](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable.  :star:230
* [Ebblink](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time. :star:3
* [Sharaku](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController.  :star:1321
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options.  :star:791
* [Twitter Image Pipline](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application. :star:1528
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps.  :star:1507
* [FlexibleImage](https://github.com/kawoou/FlexibleImage) - A simple way to play with image!  :star:672
* [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook.  :star:1167
* [YapImageManager](https://github.com/yapstudios/YapImageManager) - A high-performance image downloader written in Swift, powered by YapDatabase.  :star:56
* [PhotoEditorSDK](https://www.photoeditorsdk.com) - A fully customizable photo editor for your app. 
* [SimpleImageViewer](https://github.com/aFrogleap/SimpleImageViewer) - A snappy image viewer with zoom and interactive dismissal transition.  :star:249
* [AZImagePreview](https://github.com/Minitour/AZImagePreview) - A framework that makes image viewing easy.  :star:15
* [FaceCropper](https://github.com/KimDarren/FaceCropper) - Crop faces, inside of your image, with iOS 11 Vision api  :star:408
* [Paparazzo](https://github.com/avito-tech/Paparazzo) - Custom iOS camera and photo picker with editing capabilities  :star:536
* [ZImageCropper](https://github.com/ZaidPathan/ZImageCropper) - A Swift  project to crop image in any shape.  :star:41
* [InitialsImageView](https://github.com/bachonk/InitialsImageView) - An UIImageView extension that generates letter initials as a placeholder for user profile images, with a randomized background color.  :star:100
* [DTPhotoViewerController](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController, inspired by Facebook photo viewer.  :star:79
* [LetterAvatarKit](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars written in Swift.  :star:62
* [AXPhotoViewer](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos  :star:285
* [TJProfileImage](https://github.com/tejas-ardeshna/TJProfileImage) - Live rendering of componet’s properties in Interface Builder.  :star:32
* [Viewer](https://github.com/bakkenbaeck/Viewer) - Image viewer (or Lightbox) with support for local and remote videos and images  :star:328
* [OverlayComposite](https://github.com/aaronjsutton/OverlayComposite) - An asynchronous, multithreaded, image compositing framework written in Swift.  :star:10
* [MCScratchImageView](https://github.com/Minecodecraft/MCScratchImageView) - A custom ImageView that is used to cover the surface of other view like a scratch card, user can swipe the mulch to see the view below  :star:337
* [MetalPetal](https://github.com/MetalPetal/MetalPetal) - A GPU-accelerated image/video processing framework based on [Metal](https://developer.apple.com/metal/). :star:102
* [ShadowImageView](https://github.com/olddonkey/ShadowImageView) - ShadowImageView is a iOS 10 Apple Music style image view, help you create elegent image with shadow.  :star:659
* [Avatar](https://github.com/wvabrinskas/Avatar) - Generate random user Avatar images using CoreGraphics and QuartzCore.  :star:19
* [Serrata](https://github.com/horitaku46/Serrata) - Slide image viewer library similar to Twitter and LINE. :star:254
* [StyleArt](https://github.com/ileafsolutions/StyleArt) - Style Art library process images using COREML with a set of pre trained machine learning models and convert them to Art style.  :star:136
* [greedo-layout-for-ios](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS :star:816

#### Media Processing
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift  :star:3138
* [QR Code Scanner](https://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift.  :star:525
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift.  :star:2604

#### PDF
* [Reader](https://github.com/vfr/Reader) - PDF Reader Core for iOS. :star:4017
* [UIView 2 PDF](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB :star:28
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS.  :star:1618
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s).  :star:335
* [SimplePDF](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly.  :star:117
* [SwiftPDFGenerator](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'.  :star:12
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout.  :star:169
* [FastPdfKit](https://github.com/mobfarm/FastPdfKit) - A Static Library to be embedded on iOS applications to display pdf documents derived from Fast PDF. :star:1160

#### Streaming
* [HaishinKit.swift](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS.  :star:944
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for macOS and iOS. :star:1761
* [Jukebox](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift.  :star:436
* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate :star:2983
* [Airstream](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay. :star:325
* [OTAcceleratorCore](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox. :star:21
* [webrtc](https://webrtc.org/native-code/ios/) - Provides browsers and mobile applications with Real-Time Communications (RTC) capabilities via simple APIs. 

#### Video
* [VIMVideoPlayer](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes. :star:269
* [MobilePlayer](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS. :star:2385
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2284
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control  :star:479
* [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery :star:1951
* [PlayerView](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift  :star:100
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:82
* [AVPlayerViewController-Subtitles](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. [e] :star:97
* [MPMoviePlayerController-Subtitles](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. [e] :star:177
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress. :star:4123
* [Player](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app  :star:1043
* [BMPlayer](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide.  :star:945
* [VideoPager](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available.  :star:36
* [ios-360-videos](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer. :star:205
* [swift-360-videos](https://github.com/gsabran/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360. :star:63
* [ABMediaView](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner. :star:52
* [PryntTrimmerView](https://github.com/prynt/PryntTrimmerView) - A set of UI elements to trim, crop and select frames inside a video.  :star:141
* [VGPlayer](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player in Swift,Support play local and network,Background playback mode.  :star:228
* [YoutubeKit](https://github.com/rinov/YoutubeKit) - A video player that fully supports Youtube IFrame API and YoutubeDataAPI for easily create a Youtube app.  :star:180
* [Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player) - Swift library for embedding and controlling YouTube videos in your iOS applications! :star:493
* [JDVideoKit](https://github.com/jamesdouble/JDVideoKit) - You can easily transfer your video into Three common video type via this framework. :star:18

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application. :star:140
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS. :star:5412
* [Chatto](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift  :star:3225
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. :star:8339
* [MessageKit](https://github.com/MessageKit/MessageKit) - Eventually, a Swift re-write of JSQMessagesViewController  :star:1766
* [NoChat](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS.  :star:529
* [NMessenger](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift  :star:2203
* [Atlas](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer. :star:3779
* [Messenger](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support. :star:2972
* [OTTextChatAccelerator](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices. :star:11
* [chat-sdk-ios](https://github.com/chat-sdk/chat-sdk-ios) - Chat SDK iOS - Open Source Mobile Messenger. :star:446
* [AsyncMessagesViewController](https://github.com/nguyenhuy/AsyncMessagesViewController) - A smooth, responsive and flexible messages UI library for iOS. :star:226
* [MessageViewController](https://github.com/GitHawkApp/MessageViewController) - A SlackTextViewController replacement written in Swift for the iPhone X.  :star:1222

## Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and macOS networking framework. :star:30788
* [RestKit](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun. :star:10226
* [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library. :star:398
* [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone. :star:5799
* [Overcoat](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun. :star:1135
* [ROADFramework](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible. :star:50
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking.  :star:27228
* [Transporter](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier.  :star:435
* [CDZPinger](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping. :star:48
* [NSRails](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails. :star:530
* [NKMultipeer](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity.  :star:14
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS. :star:9782
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. 
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures  :star:4786
* [OctopusKit](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs. :star:1
* [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift.  :star:8333
* [TWRDownloadManager](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files. :star:351
* [HappyDns](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record. :star:335
* [Bridge](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily.  :star:93
* [TRON](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire  :star:434
* [EVCloudKitDao](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit  :star:526
* [EVURLCache](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest  :star:265
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer.  :star:1721
* [Pitaya](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines  :star:850
* [Just](https://github.com/JustHTTP/Just) - Swift HTTP for Humans  :star:1098
* [agent](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS  :star:609
* [Reach](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift.  :star:427
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests.  :star:1744
* [Netdiag](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS. :star:77
* [AFNetworkingHelper](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFN :star:18

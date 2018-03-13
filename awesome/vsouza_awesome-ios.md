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
* [ARAnalytics](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data. :star:1721
* [Segment](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application. :star:265
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions. :star:2
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing
* [WAAppRouting](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically! :star:572
* [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links. :star:3057
* [IntentKit](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps. :star:1821
* [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API. :star:4163
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks  :star:93
* [Compass](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application  :star:667
* [Appz](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed.  :star:896
* [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift  :star:1497
* [Marshroute](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful.   :star:149
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 3  :star:175
* [Router](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS.  :star:137
* [ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain. :star:278
* [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) - Navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.  :star:683

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
* [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift.  :star:1261
* [Viperit](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift.  :star:236
* [Reactant](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS  :star:329
* [YARCH](https://github.com/alfa-laboratory/YARCH-Examples) - More clean alternative to VIPER with unidirectional data flow (flux-like).  :star:50
* [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) - This repository contains a detailed sample app that implements VIPER architecture in iOS using libraries and frameworks like Alamofire, AlamofireImage, PKHUD, CoreData etc. :star:257
* [Tempura](https://github.com/BendingSpoons/tempura-swift) - A holistic approach to iOS development, inspired by Redux and MVVM. :star:257


## ARKit
* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data. 
* [Virtual Objects](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality. :star:187
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆.  :star:597
* [ARKitEnvironmentMapper](https://github.com/svtek/ARKitEnvironmentMapper) - A library that allows you to generate and update environment maps in real-time using the camera feed and ARKit's tracking capabilities.  :star:29
* [SmileToUnlock](https://github.com/rsrbk/SmileToUnlock) - This library uses ARKit Face Tracking in order to catch a user's smile. :star:491

## Authentication
* [Heimdallr.swift](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift.  :star:469
* [OhMyAuth](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services.  :star:55
* [AuthenticationViewController](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController.  :star:237
* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift.  :star:665
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS  :star:1988
* [SimpleAuth](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS. :star:1168
* [AlamofireOauth2](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2  :star:74
* [SwiftyOAuth](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers  :star:465
* [Simplicity](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps.  :star:649
* [InstagramAuthViewController](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication.  :star:33
* [InstagramSimpleOAuth](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app. :star:83
* [DropboxSimpleOAuth](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app. :star:42
* [BoxSimpleOAuth](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app. :star:15
* [InstagramLogin](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS.  :star:22
* [ReCaptcha](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS.  :star:66
* [LinkedInSignIn](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn.  :star:10

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:10293
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews :star:10360
* [MAIKit](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS :star:141

## Cache

*Thread safe, offline and high performance cache libs and frameworks.*

* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift)  :star:1105
* [mattress](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content  :star:456
* [Carlos](https://github.com/WeltN24/Carlos) - A simple but flexible cache  :star:471
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images.  :star:4636
* [YYCache](https://github.com/ibireme/YYCache) - High performance cache framework for iOS. :star:1691
* [Cache](https://github.com/hyperoslo/Cache) - Nothing but Cache.  :star:1148
* [MGCacheManager](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class. :star:8
* [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify :star:1163
* [Track](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU.  :star:194
* [UITableView Cache](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating. :star:67
* [RocketData](https://github.com/plivesey/RocketData) - A caching and consistency solution for immutable models.  :star:532
* [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS :star:1888
* [Johnny](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift  :star:27
* [Disk](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data.  :star:1879
* [Cachyr](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift  :star:98
* [Cache](https://github.com/soffes/Cache) - Swift caching library.  :star:182

## Charts

*Beautiful, Easy and Fully customized charts*

* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart).  :star:17536
* [JTChartView](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart. :star:121
* [PNChart](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS :star:9135
* [XJYChart](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight. :star:571
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library). :star:2708
* [JBChartView](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs. :star:3791
* [XYPieChart](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app. :star:1755
* [TEAChart](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart. :star:1156
* [EChart](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported. :star:644
* [FSLineChart](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS. :star:837
* [chartee](https://github.com/zhiyu/chartee) - a charting library for mobile platforms. :star:890
* [ANDLineChartView](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart. :star:417
* [TWRCharts](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code. :star:370
* [SwiftCharts](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS.  :star:1624
* [FlowerChart](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector.  :star:9
* [Scrollable-GraphView](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift.  :star:4378
* [Dr-Charts](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C. :star:69
* [Graphs](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS.  :star:882
* [FSInteractiveMap](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS! :star:478
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation. :star:400
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

* [Bootstrap](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding. :star:1931
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL. :star:106
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle](https://github.com/Cue/ocstyle) - Objective-C style checker. :star:258
* [spacecommander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying. :star:862
* [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling. :star:568
* [Tailor](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs. :star:1175
* [SwiftCop](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations.  :star:507
* [Trackable](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects.  :star:137
* [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time. :star:3170
* [HeapInspector-for-iOS](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments :star:1670
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage. :star:2894
* [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime. :star:2854
* [Buglife](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps :star:408
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets. :star:433
* [Aardvark](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports. :star:205
* [Stats](https://github.com/shu223/Stats) - In-app memory usage monitoring. :star:150
* [GlueKit](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift.  :star:353
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code.  :star:1856
* [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods. :star:215
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch.  :star:37
* [ODUIThreadGuard](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread.  :star:701
* [IBAnalyzer](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests.  :star:865
* [DecouplingKit](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project. :star:116
* [Clue](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure. :star:263

#### Linter
* [OCLint](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects. :star:2585
* [Taylor](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms.  :star:208
* [Swiftlint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.  :star:8896
* [IBLinter](https://github.com/kateinoigakukun/IBLinter) - A linter tool for Interface Builder.  :star:585

## Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift).  :star:10878
* [ColorArt](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11. :star:133
* [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. [e] :star:1789
* [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. [e] :star:526
* [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier. :star:2964
* [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string.  :star:861
* [Hue](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need. :star:2411
* [FlatUIColors](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift.  :star:149
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js.  :star:450
* [PFColorHash](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string.  :star:17
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift)  :star:428
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes :star:2990
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm).  :star:148
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift).  :star:16
* [CostumeKit](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app.  :star:297
* [CSS3ColorsSwift](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name.  :star:56
* [Colorify](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017.  :star:81
* [ChromaColorPicker](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift.  :star:119
* [Lorikeet](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation.  :star:17
* [Gestalt](https://github.com/regexident/Gestalt) - An unintrusive & light-weight iOS app-theming library with support for animated theme switching.  :star:117

## Command Line
* [Swiftline](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications.  :star:1008
* [CommandLine](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces  :star:1026
* [Commander](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift  :star:1053
* [ColorizeSwift](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift.  :star:169
* [Guaka](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift  :star:1063
* [Marathon](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts  :star:1426
* [CommandCougar](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications.  :star:20

## Concurrency
* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift  :star:1354
* [Concurrent](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives  :star:149
* [Flow](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift  :star:194
* [Brisk](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation.  :star:22
* [Aojet](https://github.com/aojet/Aojet) - An actor model library for swift. :star:24
* [Overdrive](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading.  :star:828
* [NSLock+Synchronized](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via CocoaPods and Carthage Framework. [e] :star:4
* [AsyncNinja](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives.  :star:72
* [Kommander](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand.  :star:122
* [Threadly](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift  :star:45
* [Flow-iOS](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable  :star:10
* [Queuer](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD).  :star:718
* [SwiftQueue](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more.  :star:40
* [GroupWork](https://github.com/quanvo87/GroupWork) - Easy concurrent, asynchronous tasks in Swift.  :star:35

## Core Data
* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework. :star:71
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C. :star:1335
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code. :star:469
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data. :star:239
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data. :star:1568
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping. :star:185
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation. :star:2966
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread. :star:208
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher. :star:665
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data. :star:10618
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language.  :star:1299
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc.  :star:1828
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. 
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift.  :star:759
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations.  :star:32
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data  :star:2140
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift.  :star:737
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift.  :star:288
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack  :star:537
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack  :star:451
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour.  :star:188
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices.  :star:96
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations.  :star:6
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer.  :star:175
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box. :star:102
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift.  :star:483
* [Records](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift.  :star:13
* [PredicateFlow](https://github.com/andreadelfante/PredicateFlow) - Write amazing, strong-typed and easy-to-read NSPredicate, allowing you to write flowable NSPredicate, without guessing attribution names, predicate operation or writing wrong arguments type. :star:4

## Database
* [Realm](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast. :star:11903
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac. :star:3018
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite. :star:12273
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access. :star:1641
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud.  :star:440
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state.  :star:451
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support).  :star:54
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults.  :star:3119
* [SugarRecord](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0  :star:1992
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3.  :star:5050
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support  :star:1234
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift.  :star:790
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers. :star:2627
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults.  :star:110
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats.  :star:151
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift  :star:80
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  [e] :star:108
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift  :star:272
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage. :star:38
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API. :star:60
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB  :star:67
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API.  :star:22
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:45
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:22
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:72
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:20
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:36
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support. :star:24
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage.  :star:220
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk.  :star:163
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS. :star:5437
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠 :star:184
* [UserDefaults](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS  :star:952
* [Default](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support  :star:349
* [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit  :star:763
* [FirebaseHelper](https://github.com/quanvo87/FirebaseHelper) - Safe and easy wrappers for common Firebase Realtime Database functions. :star:6
* [Shallows](https://github.com/dreymonde/Shallows) - Your lightweight persistence toolbox. :star:473

## Data Structures / Algorithms
* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift  :star:4
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another  :star:728
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees  :star:987
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift.  :star:1844
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift  :star:90
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios  :star:54
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset.  :star:640
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily.  :star:62
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/.  :star:3810
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations.  :star:2002
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C. :star:2319
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData. :star:21
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration.  :star:340
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift.  :star:357
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift.  :star:236
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily.  :star:73
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library.  :star:60
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs.  :star:22
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations!  :star:16363
* [Impeller](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift  :star:94
* [Dispatch](https://github.com/alexdrone/Dispatch) - Multi-store Flux implementation in Swift  :star:255
* [DeepDiff](https://github.com/onmyway133/DeepDiff) - Diff in Swift  :star:878
* [BinaryKit](https://github.com/Cosmo/BinaryKit) - Access bits and bytes directly in Swift.  :star:41
* [Differ](https://github.com/tonyarnold/Differ) - Swift library to generate differences and patches between collections. :star:156
* [Probably](https://github.com/harlanhaskins/Probably) - A Swift probability and statistics library.  :star:231
* [RandMyMod](https://github.com/jamesdouble/RandMyMod) - RandMyMod base on your own struct or class create one or a set of randomized instance. :star:1

## Date & Time

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift  :star:2457
* [SwiftDate](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0  :star:3627
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2  :star:1514
* [DateTools](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C :star:6080
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer  :star:954
* [DateHelper](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift  :star:923
* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats. :star:598
* [EmojiTimeFormatter](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis.  :star:73
* [Kronos](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift  :star:247
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) .  :star:242
* [10Clock](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer.  :star:447
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad. :star:1728
* [AnyDate](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API.  :star:153
* [TimeZonePicker](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app.  :star:94
* [Time](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. [e] :star:797
* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library  :star:915
* [Solar](https://github.com/ceeK/Solar) - A Swift micro library for generating Sunrise and Sunset times.  :star:156
* [TimePicker](https://github.com/Endore8/TimePicker) - Configurable time picker component based on a pan gesture and its velocity. :star:9
* [LFTimePicker](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift  :star:47

## Debugging
* [Xniffer](https://github.com/vsouza/awesome-ios/issues/1841) - A swift network profiler built on top of URLSession. 
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library!  :star:2065
* [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools. :star:5549
* [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers. :star:599
* [Flex](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS. :star:8876
* [chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps. :star:6575
* [Alpha](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS. :star:677
* [AEConsole](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App.  :star:94
* [GodEye](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift.  :star:2941
* [NetworkEye](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request. :star:1066
* [Dotzu](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network. :star:1458
* [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations. :star:1368
* [Httper-iOS](https://github.com/MuShare/Httper-iOS) - App for developers to test REST API.  :star:323

## EventBus
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8.  :star:629
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS. :star:9033
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links). :star:5267
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.   :star:1777
* [When](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift.  :star:135
* [then🎬](https://github.com/freshOS/then) - Elegant Async code in Swift.  :star:620
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier.  :star:1076
* [RWPromiseKit](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C :star:100
* [FutureLib](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala.  :star:36
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety  :star:482
* [FutureKit](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS.  :star:691
* [signals-ios](https://github.com/uber/signals-ios) - Typeful eventing :star:505
* [BrightFutures](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises.  :star:1626
* [NoticeObserveKit](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type.  :star:112
* [Hydra](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift  :star:1406
* [Promis](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate.  :star:71
* [Bluebird.swift](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4.  :star:29
* [Promise](https://github.com/khanlou/Promise) - A Promise library for Swift, based partially on Javascript's A+ spec.  :star:436
* [promises](https://github.com/google/promises) - Google provides a synchronization construct for Objective-C and Swift to facilitate writing asynchronous code. :star:1877
* [Continuum](https://github.com/marty-suzuki/Continuum) - NotificationCenter based Lightweight UI / AnyObject binder. :star:79

## Files
* [FileKit](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift.  :star:1760
* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files.  :star:1207
* [FileBrowser](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS.  :star:1168
* [Ares](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices  :star:116
* [FileProvider](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS.  :star:255
* [KZFileWatchers](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools.  :star:830
* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac. :star:3369
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories.  :star:527
* [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift  :star:864
* [AppFolder](https://github.com/dreymonde/AppFolder) - AppFolder is a lightweight framework that lets you design a friendly, strongly-typed representation of a directories inside your app's container.  :star:741
* [ZipZap](https://github.com/pixelglow/ZipZap) - zip file I/O library for iOS, macOS and tvOS. :star:1132

## Functional Programming
* [Forbind](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift.  :star:44
* [Funky](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift.  :star:12
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools.  :star:629
* [Oriole](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. [e] :star:11
* [Prelude](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools.  :star:325
* [Swiftx](https://github.com/typelift/Swiftx) - Functional data types and functions for any project.  :star:193
* [Swiftz](https://github.com/typelift/Swiftz) -  Functional programming in Swift.  :star:3094
* [OptionalExtensions](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. [e] :star:174
* [Hookah](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project.  :star:56
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift  :star:3305
* [Runes](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift.  :star:680

## Games
* [Sage](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift.  :star:341
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI.  :star:50
* [SKTiled](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit  :star:110
* [CollectionNode](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit  :star:48
* [AssetImportKit](https://github.com/eugenebokhan/AssetImportKit) - Swifty cross platform library (macOS, iOS) that converts Assimp supported models to SceneKit scenes. :star:10

## GCD
 * [GCDKit](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift.  :star:287
 * [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch  :star:4212
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
* [Tactile](https://github.com/delba/Tactile) - A better way to handle gestures on iOS  :star:641
* [SwiftyGestureRecognition](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds  :star:145
* [DBPathRecognizer](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS]  :star:1100
* [Sensitive](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift.  :star:469
* [SplitViewDragAndDrop](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode.  :star:292
* [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. :star:4729

## Graphics
* [Graphicz](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics!  :star:36
* [PKCoreTechniques](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich. :star:145
* [MPWDrawingContext](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext :star:90
* [DePict](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift!  :star:30
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView).  :star:959
* [InkKit](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift!  :star:356
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display. :star:387
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone  :star:1049
* [jot](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images. :star:1685
* [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating). :star:3022
* [Snowflake](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift.  :star:825
* [HxSTLParser](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit :star:14
* [ProcessingKit](https://github.com/natmark/ProcessingKit) - Visual designing library for iOS & OSX  :star:227
* [EZYGradientView](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code  :star:319
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift.  :star:47
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift.  :star:86
* [EPShapes](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder.  :star:377
* [Macaw](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift.  :star:3466

## Hardware
#### Bluetooth
* [Discovery](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background). :star:384
* [LGBluetooth](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code. :star:149
* [PeerKit](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. 
* [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE.  :star:1630
* [Bluetonium](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift  :star:136
* [BlueCap](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework  :star:462
* [Apple Family](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.   :star:39
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U   :star:447
* [Bluejay](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps.  :star:651
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS. :star:3464
* [ExtendaBLE](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates. :star:74
* [PeerConnectivity](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :star:35
* [AZPeerToPeerConnection](https://github.com/AfrozZaheer/AZPeerToPeerConnection) - AZPeerToPeerConnectivity is a wrapper on top of Apple iOS Multipeer Connectivity framework. It provides an easier way to create and manage sessions. Easy to integrate. :star:38

#### Camera
* [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects. :star:1433
* [PBJVision](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture. :star:1797
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation. :star:1199
* [SCRecorder](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animata :star:2774

# Information comes from [vsouza/awesome-ios](https://github.com/vsouza/awesome-ios)
<img src="https://github.com/vsouza/awesome-ios/blob/master/header.png">

<p align="center">
    <img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  <a href="https://gitter.im/vsouza/awesome-ios"><img alt="Join the chat at gitter" src="https://badges.gitter.im/Join%20Chat.svg" /></a>
  <a href="https://travis-ci.org/vsouza/awesome-ios"><img alt="Build Status" src="https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

<a href="http://weekly.awesomeios.com"><img src="https://github.com/vsouza/awesome-ios/blob/master/newsletter.png"></a>

## About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode extensions and plugins, components and much more.
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).

## Recommended SDK for bug and crash reporting [Instabug](https://goo.gl/hNadrZ)
[![instabug-visual-repro-steps](https://user-images.githubusercontent.com/9888943/40114739-4e0ff416-590e-11e8-9a29-55fb2d4cfebc.png)](https://try.instabug.com/awesomeios/?utm_source=awesomeios&utm_medium=spon&utm_content=banner)
> Instabug has just released their visual repro steps feature to enable you to trace all the views that the user interacted with before a bug or a crash occured. This will help you reproduce bugs and fix them 10x faster. We highly recommend integrating Instabug’s framework as they compiled a lot of other great features like network logs and screen annotations, providing you with useful and rich data attached to each bug or crash report.
Instabug is offering awesome-ios community an exclusive **15% discount** on all paid plans. [**Go to 1 minute integration guide.**](https://goo.gl/q93Qtd)
[![](https://goo.gl/A74z8Q)](https://instabug.com)

## How to Use
Awesome-iOS is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/awesome_ios) or [Gitter Channel](https://gitter.im/vsouza/awesome-ios)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

### Content
- [About](#about)
- [How to Use](#how-to-use)
- [Courses](#courses)
- [Analytics](#analytics)
- [App Routing](#app-routing)
- [Apple TV](#apple-tv)
- [Architecture Patterns](#architecture-patterns)
- [ARKit](#arkit)
- [Authentication](#authentication)
- [Blockchain](#blockchain)
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
    - [Cards](#cards)
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
      - [Expandable Cell](#expandable-cell)
      - [Header](#header)
      - [Placeholder](#placeholder)
    - [Tag](#tag)
    - [TextField & TextView](#textfield--textview)
    - [UIPageControl](#uipagecontrol)
    - [Web View](#web-view)
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


## Courses

### Getting Started

*Courses, tutorials and guides*

* [Apple- Start Developing with iOS](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/) - Apple Guide.
* [Apple - Object-Oriented Programming with Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html)
* [Apple - Programming with Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [CodeProject](https://www.codeproject.com/articles/88929/getting-started-with-iphone-and-ios-development) - Getting Started with iPhone and iOS Development.
* [Lifehacker](https://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
* [Ray Wenderlich](https://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - Learn to code iOS Apps.
* [Stanford - Developing iOS 7 Apps for iPhone and iPad](https://itunes.apple.com/us/course/developing-ios-7-apps-for-iphone-and-ipad/id733644550)
* [Stanford - Developing iOS 10 Apps with Swift](https://itunes.apple.com/in/course/developing-ios-10-apps-swift/id1198467120) - Stanford's 2017 iTunes U course.
* [Stanford - Developing iOS 11 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-11-apps-with-swift/id1309275316) - Stanford's 2017 iTunes U course updated for iOS 11 and Swift.
* [Swifteducation - Teaching App Development with Swift](https://swifteducation.github.io/teaching_app_development_with_swift/)
* [Udacity - Intro to iOS App Development with Swift](https://www.udacity.com/course/intro-to-ios-app-development-with-swift--ud585)
* [Udemy - ARKit - Beginner to Professional in Swift 4 and iOS 11](https://www.udemy.com/arkit-beginner-to-professional/?couponCode=CREATORS)

## Analytics

 *Analytics platforms, SDK's, error tracking and real-time answers about your app*

* [Instabug](https://instabug.com) - In-app feedback, Bug and Crash reporting, Fix Bugs Faster through user-steps, video recordings, screen annotation, network requests logging.
* [Mixpanel](https://mixpanel.com/) - Advanced analytics platform.
* [Localytics](https://www.localytics.com/) - Brings app marketing and analytics together.
* [Answers by Fabric](https://answers.io/) - Answers gives you real-time insight into people’s experience in your app.
* [Liquid Analytics](https://onliquid.com) - Identify behaviours through Analytics and react with real-time Personalization.
* [GTrack](https://github.com/gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies. :star:86
* [ARAnalytics](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data.
* [Segment](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application.
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions. :star:2
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing

  *Elegant URL routing, navigation frameworks, deep links and more*

* [WAAppRouting](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically! :star:576
* [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links. :star:3107
* [IntentKit](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps. :star:1825
* [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API. :star:4466
* [IKRouter](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :star:96
* [Compass](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :star:716
* [Appz](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :star:922
* [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :star:1641
* [Marshroute](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful. :star:163
* [SwiftRouter](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS. :star:195
* [Router](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS. :star:177
* [ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain. :star:340
* [RxFlow](https://github.com/RxSwiftCommunity/RxFlow) - Navigation framework for iOS applications based on a Reactive Flow Coordinator pattern. :star:779
* [Linker](https://github.com/MaksimKurpa/Linker) - Lightweight way to handle internal and external deeplinks for iOS. :star:123
* [CoreNavigation](https://github.com/aronbalog/CoreNavigation) - 📱📲 Navigate between view controllers with ease. :star:46
* [DZURLRoute](https://github.com/yishuiliunian/DZURLRoute) - Universal route engine for iOS app, it can handle URLScheme between applications and page route between UIViewController. :star:66
* [Crossroad](https://github.com/giginet/Crossroad) - Crossroad is an URL router focused on handling Custom URL Schemes. Using this, you can route multiple URL schemes and fetch arguments and parameters easily. :star:185


## Apple TV

*tvOS view controllers, wrappers, template managers and video players.*

* [Voucher](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts. :star:495
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2340
* [TVMLKitchen](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :star:75
* [BrowserTV](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :star:211
* [Swift-GA-Tracker-for-Apple-tvOS](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :star:71
* [ParallaxView](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :star:356
* [TvOSTextViewer](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :star:29
* [FocusTvButton](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :star:41
* [TvOSMoreButton](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :star:34
* [TvOSPinKeyboard](https://github.com/zattoo/TvOSPinKeyboard) - PIN keyboard for tvOS :star:95
* [TvOSScribble](https://github.com/dcordero/TvOSScribble) - Handwriting numbers recognizer for Siri Remote :star:164
* [TvOSCustomizableTableViewCell](https://github.com/zattoo/TvOSCustomizableTableViewCell) - Light wrapper of UITableViewCell that allows extra customization for tvOS :star:19

## Architecture Patterns

*Clean architecture, Viper, MVVM, Reactive... choose your weapon.*

* [SwiftyVIPER](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner. :star:68
* [CleanArchitectureRxSwift](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :star:1512
* [Viperit](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :star:275
* [Reactant](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS :star:340
* [YARCH](https://github.com/alfa-laboratory/YARCH) - More clean alternative to VIPER with unidirectional data flow (flux-like). :star:64
* [iOS-Viper-Architecture](https://github.com/MindorksOpenSource/iOS-Viper-Architecture) - This repository contains a detailed sample app that implements VIPER architecture in iOS using libraries and frameworks like Alamofire, AlamofireImage, PKHUD, CoreData etc. :star:318
* [Tempura](https://github.com/BendingSpoons/tempura-swift) - A holistic approach to iOS development, inspired by Redux and MVVM. :star:349


## ARKit

*Library and tools to help you build unparalleled augmented reality experiences*

* [ARKit-CoreLocation](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data.
* [Virtual Objects](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality. :star:199
* [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆. :star:701
* [ARKitEnvironmentMapper](https://github.com/svtek/ARKitEnvironmentMapper) - A library that allows you to generate and update environment maps in real-time using the camera feed and ARKit's tracking capabilities. :star:44
* [SmileToUnlock](https://github.com/rsrbk/SmileToUnlock) - This library uses ARKit Face Tracking in order to catch a user's smile. :star:520
* [Placenote](https://github.com/Placenote/PlacenoteSDK-iOS) - A library that makes ARKit sessions persistent to a location using advanced computer vision :star:33
* [Poly](https://github.com/piemonte/Poly) - Unofficial Google Poly SDK – search and display 3D models :star:17

## Authentication

*Oauth and Oauth2 libraries, social logins and captcha tools.*

* [Heimdallr.swift](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :star:490
* [OhMyAuth](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :star:57
* [AuthenticationViewController](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :star:241
* [OAuth2](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift. :star:719
* [OAuthSwift](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :star:2083
* [SimpleAuth](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS. :star:1166
* [AlamofireOauth2](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :star:74
* [SwiftyOAuth](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :star:467
* [Simplicity](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps. :star:656
* [InstagramAuthViewController](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :star:33
* [InstagramSimpleOAuth](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app. :star:83
* [DropboxSimpleOAuth](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app. :star:42
* [BoxSimpleOAuth](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app. :star:15
* [InstagramLogin](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS. :star:25
* [ReCaptcha](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS. :star:79
* [LinkedInSignIn](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn. :star:14

## Blockchain

*Tool for smart contract interactions. Bitcoin protocol implementations and Frameworks for interacting with cryptocurrencies.*

* [Web3.swift](https://github.com/Boilertalk/Web3.swift) - Web3 library for interacting with the Ethereum blockchain. :star:124
* [web3swift](https://github.com/BANKEX/web3swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions. :star:244
* [EthereumKit](https://github.com/D-Technologies/EthereumKit) - EthereumKit is a free, open-source Swift framework for easily interacting with the Ethereum. :star:239
* [BitcoinKit](https://github.com/kishikawakatsumi/BitcoinKit) - Bitcoin protocol toolkit for Swift, BitcoinKit implements Bitcoin protocol in Swift. It is an implementation of the Bitcoin SPV protocol written (almost) entirely in swift. :star:449

## Bridging

*Sharing code between Objective-C and Swift, iOS and macOS, Javascript and Objective-C.*

* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App. :star:10474
* [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews :star:10992
* [MAIKit](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS :star:141

## Cache

*Thread safe, offline and high performance cache libs and frameworks.*

* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift)
* [mattress](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content :star:470
* [Carlos](https://github.com/spring-media/Carlos) - A simple but flexible cache :star:484
* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :star:4700
* [YYCache](https://github.com/ibireme/YYCache) - High performance cache framework for iOS. :star:1806
* [Cache](https://github.com/hyperoslo/Cache) - Nothing but Cache. :star:1303
* [MGCacheManager](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class. :star:8
* [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify :star:1175
* [Track](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :star:204
* [UITableView Cache](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating. :star:68
* [RocketData](https://github.com/plivesey/RocketData) - A caching and consistency solution for immutable models. :star:539
* [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS :star:1954
* [Johnny](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift :star:30
* [Disk](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data. :star:2063
* [Cachyr](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift :star:99
* [Cache](https://github.com/soffes/Cache) - Swift caching library. :star:185

## Charts

*Beautiful, Easy and Fully customized charts*

* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart). :star:18568
* [JTChartView](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart. :star:123
* [PNChart](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS :star:9320
* [XJYChart](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight. :star:641
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library). :star:2715
* [JBChartView](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs. :star:3806
* [XYPieChart](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app. :star:1755
* [TEAChart](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart. :star:1168
* [EChart](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported. :star:643
* [FSLineChart](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS. :star:846
* [chartee](https://github.com/zhiyu/chartee) - a charting library for mobile platforms. :star:907
* [ANDLineChartView](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart. :star:424
* [TWRCharts](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code. :star:368
* [SwiftCharts](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :star:1687
* [FlowerChart](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :star:9
* [Scrollable-GraphView](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :star:4549
* [Dr-Charts](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C. :star:76
* [Graphs](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS. :star:891
* [FSInteractiveMap](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS! :star:491
* [JYRadarChart](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation. :star:407
* [TKRadarChart](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift :star:149
* [MagicPie](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1  🎉 ✨✨✨✨✨ :star:534
* [PieCharts](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :star:384
* [CSPieChart](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :star:31
* [DDSpiderChart](https://github.com/dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift. :star:38
* [core-plot](https://github.com/core-plot/core-plot) - a 2D plotting lib which is highly customizable and capable of drawing many types of plots. :star:2566
* [ChartProgressBar](https://github.com/hadiidbouk/ChartProgressBar-iOS) - Draw a chart with progress bar style. :star:46
* [SMDiagramViewSwift](https://github.com/VRGsoftUA/SMDiagramView) - Meet cute and very flexibility library for iOS application for different data view in one circle diagram. :star:21
* [Swift LineChart](https://github.com/zemirco/swift-linechart) - Line Chart library for iOS written in Swift. :star:527
* [SwiftChart](https://github.com/gpbl/SwiftChart) - Line and area chart library for iOS. :star:670
* [EatFit](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :star:652
* [CoreCharts](https://github.com/cagricolak/CoreCharts) - CoreCharts is a simple powerfull yet Charts library for apple products :star:54

## Code Quality

 *Quality always matters. Code checkers, memory vigilants, syntastic sugars and more.*

* [Bootstrap](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding. :star:1964
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL. :star:106
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle](https://github.com/Cue/ocstyle) - Objective-C style checker. :star:257
* [spacecommander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying. :star:889
* [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling. :star:568
* [Tailor](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs. :star:1212
* [SwiftCop](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :star:518
* [Trackable](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :star:137
* [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time. :star:3547
* [HeapInspector-for-iOS](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments :star:1696
* [FBMemoryProfiler](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage. :star:2987
* [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime. :star:3036
* [Buglife](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps :star:436
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets. :star:438
* [Aardvark](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports. :star:212
* [Stats](https://github.com/shu223/Stats) - In-app memory usage monitoring. :star:155
* [GlueKit](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift. :star:357
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :star:2046
* [PSTModernizer](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods. :star:215
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :star:38
* [ODUIThreadGuard](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :star:699
* [IBAnalyzer](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :star:895
* [DecouplingKit](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project. :star:124
* [Clue](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure. :star:267

### Linter

*Static code analyzers to enforce style and conventions.*

* [OCLint](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects. :star:2666
* [Taylor](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :star:221
* [Swiftlint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions. :star:9626
* [IBLinter](https://github.com/IBDecodable/IBLinter) - A linter tool for Interface Builder. :star:634

## Color

*Hex color extensions, theming, color pickers and other awesome color tools.*

* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :star:11245
* [ColorArt](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11. :star:136
* [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. [e] :star:1846
* [SwiftHEXColors](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. [e] :star:535
* [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier. :star:3004
* [UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :star:887
* [Hue](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need. :star:2524
* [FlatUIColors](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :star:150
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :star:453
* [PFColorHash](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string. :star:17
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift)
* [DKNightVersion](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes :star:3096
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to ECMA Standard 48. :star:151
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :star:17
* [CostumeKit](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app. :star:299
* [CSS3ColorsSwift](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :star:56
* [Colorify](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017. :star:87
* [ChromaColorPicker](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift. :star:163
* [Lorikeet](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation. :star:21
* [Gestalt](https://github.com/regexident/Gestalt) - An unintrusive & light-weight iOS app-theming library with support for animated theme switching. :star:145

## Command Line

*Smart, beauftil and elegant tools to help you create command line applications.*

* [Swiftline](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications. :star:1029
* [CommandLine](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :star:1057
* [Commander](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift :star:1114
* [ColorizeSwift](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift. :star:173
* [Guaka](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :star:1067
* [Marathon](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :star:1571
* [CommandCougar](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications. :star:26

## Concurrency

*Job schedulers, Coroutines, Asynchronous and Type safe threads libs and frameworks written in Swift*

* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :star:1372
* [Concurrent](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives :star:157
* [Flow](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift :star:199
* [Brisk](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :star:25
* [Aojet](https://github.com/aojet/Aojet) - An actor model library for swift. :star:25
* [Overdrive](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :star:832
* [AsyncNinja](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :star:79
* [Kommander](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand. :star:129
* [Threadly](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift :star:50
* [Flow-iOS](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable :star:12
* [Queuer](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD). :star:754
* [SwiftQueue](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more. :star:69
* [GroupWork](https://github.com/quanvo87/GroupWork) - Easy concurrent, asynchronous tasks in Swift. :star:36
* [StickyLocking](https://github.com/stickytools/sticky-locking) - A general purpose embedded hierarchical lock manager used to build highly concurrent applications of all types. Built with Swift and runs on iOS, OSX, and Linux. :star:2

## Core Data

*Core data Frameworks, wrappers, generators and boilerplates.*

* [CWCoreData](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework. :star:70
* [ObjectiveRecord](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C. :star:1334
* [SSDataKit](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code. :star:469
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data. :star:237
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data. :star:1578
* [SLRESTfulCoreData](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping. :star:184
* [Mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation. :star:2978
* [HardCoreData](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread. :star:209
* [encrypted-core-data](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher. :star:679
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data. :star:10691
* [QueryKit](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :star:1312
* [CoreStore](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :star:1953
* [Core Data Query Interface](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data.
* [Graph](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :star:771
* [CoreDataDandy](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :star:33
* [Sync](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :star:2194
* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :star:745
* [AERecord](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :star:294
* [CoreDataStack](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :star:547
* [JSQCoreDataKit](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :star:453
* [Skopelos](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :star:195
* [Cadmium](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :star:98
* [DataKernel](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :star:6
* [DATAStack](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :star:176
* [JustPersist](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box. :star:103
* [PrediKit](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :star:488
* [Records](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift. :star:16
* [PredicateFlow](https://github.com/andreadelfante/PredicateFlow) - Write amazing, strong-typed and easy-to-read NSPredicate, allowing you to write flowable NSPredicate, without guessing attribution names, predicate operation or writing wrong arguments type. :star:66

## Database

*Wrappers, clients, Parse alternatives and safe tools to deal with ephemeral and persistent data.*

* [Realm](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast. :star:12259
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac. :star:3076
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite. :star:12525
* [FCModel](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access. :star:1650
* [Zephyr](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :star:472
* [Prephirences](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :star:458
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :star:55
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :star:3346
* [SugarRecord](https://github.com/modo-studio/SugarRecord)  - Data persistence management library.
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :star:5365
* [GRDB.swift](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :star:1373
* [Fluent](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :star:835
* [ParseAlternatives](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers. :star:2662
* [TypedDefaults](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :star:110
* [realm-cocoa-converter](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :star:159
* [YapDatabaseExtensions](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :star:83
* [RealmGeoQueries](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  [e] :star:113
* [SwiftMongoDB](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :star:277
* [ObjectiveRocks](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage. :star:42
* [OHMySQL](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API. :star:79
* [SwiftStore](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :star:76
* [OneStore](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :star:23
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. :star:48
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. :star:80
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. :star:21
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. :star:37
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. :star:25
* [Nora](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :star:229
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :star:163
* [WCDB](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS. :star:5948
* [StorageKit](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠 :star:190
* [UserDefaults](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS :star:1023
* [Default](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support :star:368
* [IceCream](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit :star:905
* [FirebaseHelper](https://github.com/quanvo87/FirebaseHelper) - Safe and easy wrappers for common Firebase Realtime Database functions. :star:7
* [Shallows](https://github.com/dreymonde/Shallows) - Your lightweight persistence toolbox. :star:539
* [StorageManager](https://github.com/iAmrSalman/StorageManager) - Safe and easy way to use FileManager as Database. :star:25

## Data Structures / Algorithms

*Diffs, keypaths, sorted lists and other amazing data structures wrappers and libraries.*

* [SwiftSortedList](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :star:4
* [Changeset](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :star:749
* [BTree](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees :star:1019
* [SwiftStructures](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :star:1876
* [diff](https://github.com/soffes/diff) - Simple diff library in pure Swift :star:91
* [Brick](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :star:54
* [Algorithm](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :star:655
* [AnyObjectConvertible](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :star:63
* [Dollar](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :star:3852
* [Result](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :star:2136
* [EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C. :star:2333
* [Monaka](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData. :star:21
* [Buffer](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :star:340
* [SwiftGraph](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :star:391
* [SwiftPriorityQueue](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :star:242
* [Pencil](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :star:73
* [HeckelDiff](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :star:121
* [Dekoter](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :star:22
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :star:17549
* [Impeller](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift :star:95
* [Dispatch](https://github.com/alexdrone/Dispatch) - Multi-store Flux implementation in Swift :star:268
* [DeepDiff](https://github.com/onmyway133/DeepDiff) - Diff in Swift :star:1051
* [BinaryKit](https://github.com/Cosmo/BinaryKit) - Access bits and bytes directly in Swift. :star:44
* [Differ](https://github.com/tonyarnold/Differ) - Swift library to generate differences and patches between collections. :star:299
* [Probably](https://github.com/harlanhaskins/Probably) - A Swift probability and statistics library. :star:232
* [RandMyMod](https://github.com/jamesdouble/RandMyMod) - RandMyMod base on your own struct or class create one or a set of randomized instance. :star:13
* [KeyPathKit](https://github.com/vincent-pradeilles/KeyPathKit) - KeyPathKit provides a seamless syntax to manipulate data using typed keypaths. :star:70
* [Differific](https://github.com/zenangst/Differific) - A fast and convenient diffing framework. :star:55

## Date & Time

*Time and NSCalendar libraries. Also contains Sunrise and Sunset time generators, time pickers and NSTimer interfaces.*

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift :star:2516
* [SwiftDate](https://github.com/malcommac/SwiftDate) - The best way to manage Dates and Timezones in Swift. :star:3850
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library. :star:1596
* [DateTools](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C :star:6331
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer :star:978
* [DateHelper](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift :star:971
* [iso-8601-date-formatter](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats. :star:596
* [EmojiTimeFormatter](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :star:73
* [Kronos](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift :star:271
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :star:262
* [10Clock](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :star:465
* [NSDate-TimeAgo](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad. :star:1750
* [AnyDate](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API. :star:158
* [TimeZonePicker](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app. :star:97
* [Time](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. [e] :star:861
* [Chronology](https://github.com/davedelong/Chronology) - Building a better date/time library :star:955
* [Solar](https://github.com/ceeK/Solar) - A Swift micro library for generating Sunrise and Sunset times. :star:185
* [TimePicker](https://github.com/Endore8/TimePicker) - Configurable time picker component based on a pan gesture and its velocity. :star:10
* [LFTimePicker](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :star:54
* [NVDate](https://github.com/novalagung/nvdate) - Swift4 Date extension library :star:148

## Debugging

*Debugging tools, crash reports, logs and console UI's.*

* [Xniffer](https://github.com/xmartlabs/Xniffer) - A swift network profiler built on top of URLSession. :star:446
* [Netfox](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library! :star:2343
* [PonyDebugger](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools. :star:5606
* [DBDebugToolkit](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers. :star:635
* [Flex](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS. :star:9297
* [chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps. :star:6832
* [Alpha](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS. :star:691
* [AEConsole](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :star:102
* [GodEye](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :star:3065
* [NetworkEye](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request. :star:1126
* [Dotzu](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network. :star:1629
* [Hyperion](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations. :star:1552
* [Httper-iOS](https://github.com/MuShare/Httper-iOS) - App for developers to test REST API. :star:306
* [Droar](https://github.com/myriadmobile/Droar) - Droar is a modular, single-line installation debugging window :star:33

## EventBus
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS. :star:658
* [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS. :star:9684
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links). :star:5307
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift. :star:1793
* [When](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift. :star:150
* [then🎬](https://github.com/freshOS/then) - Elegant Async code in Swift. :star:648
* [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :star:1112
* [RWPromiseKit](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C :star:102
* [FutureLib](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :star:37
* [SwiftNotificationCenter](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :star:501
* [FutureKit](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS. :star:706
* [signals-ios](https://github.com/uber/signals-ios) - Typeful eventing :star:508
* [BrightFutures](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :star:1665
* [NoticeObserveKit](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :star:113
* [Hydra](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift :star:1529
* [Promis](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate. :star:76
* [Bluebird.swift](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4. :star:31
* [Promise](https://github.com/khanlou/Promise) - A Promise library for Swift, based partially on Javascript's A+ spec. :star:469
* [promises](https://github.com/google/promises) - Google provides a synchronization construct for Objective-C and Swift to facilitate writing asynchronous code. :star:2084
* [Continuum](https://github.com/marty-suzuki/Continuum) - NotificationCenter based Lightweight UI / AnyObject binder. :star:82
* [Futures](https://github.com/formbound/Futures) - Lightweight promises for iOS, macOS, tvOS, watchOS, and server-side Swift. :star:27

## Files
* [FileKit](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift. :star:1824
* [Zip](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files. :star:1297
* [FileBrowser](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :star:1213
* [Ares](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :star:115
* [FileProvider](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :star:305
* [KZFileWatchers](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :star:857
* [ZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac. :star:3558
* [FileExplorer](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :star:537
* [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift :star:902
* [AppFolder](https://github.com/dreymonde/AppFolder) - AppFolder is a lightweight framework that lets you design a friendly, strongly-typed representation of a directories inside your app's container. :star:845
* [ZipZap](https://github.com/pixelglow/ZipZap) - zip file I/O library for iOS, macOS and tvOS. :star:1141

## Functional Programming
* [Forbind](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift. :star:43
* [Funky](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift. :star:12
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :star:631
* [Oriole](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift protocol extensions. [e] :star:11
* [Prelude](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools. :star:336
* [Swiftx](https://github.com/typelift/Swiftx) - Functional data types and functions for any project. :star:199
* [Swiftz](https://github.com/typelift/Swiftz) -  Functional programming in Swift. :star:3152
* [OptionalExtensions](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. [e] :star:176
* [Argo](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift :star:3363
* [Runes](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift. :star:693

## Games
* [Sage](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift. :star:344
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :star:50
* [SKTiled](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :star:128
* [CollectionNode](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit :star:59
* [AssetImportKit](https://github.com/eugenebokhan/AssetImportKit) - Swifty cross platform library (macOS, iOS) that converts Assimp supported models to SceneKit scenes. :star:18

## GCD
 * [GCDKit](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :star:294
 * [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :star:4266
 * [SwiftSafe](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy :star:157
 * [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue. :star:338
 * [AlecrimAsyncKit](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :star:80
 * [GrandSugarDispatch](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD)
 * [Threader](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution. :star:38
 * [Dispatch](https://github.com/JARMourato/Dispatch) - Just a tiny library to make using GCD easier and intuitive :star:174
 * [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :star:172
 * [Chronos-Swift](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :star:253
 * [Me](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations. :star:194
 * [SwiftyTask](https://github.com/Albinzr/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :star:18

## Gesture
* [Tactile](https://github.com/delba/Tactile) - A better way to handle gestures on iOS :star:646
* [SwiftyGestureRecognition](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :star:148
* [DBPathRecognizer](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :star:1113
* [Sensitive](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :star:497
* [SplitViewDragAndDrop](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode. :star:295
* [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. :star:4989

## Graphics
* [Graphicz](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :star:38
* [PKCoreTechniques](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich. :star:145
* [MPWDrawingContext](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext :star:92
* [DePict](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :star:31
* [SwiftSVG](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :star:1024
* [InkKit](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift! :star:365
* [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display. :star:438
* [NXDrawKit](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :star:1096
* [jot](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images. :star:1720
* [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating). :star:3136
* [Snowflake](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift. :star:838
* [HxSTLParser](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit :star:14
* [ProcessingKit](https://github.com/natmark/ProcessingKit) - Visual designing library for iOS & OSX :star:243
* [EZYGradientView](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :star:327
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :star:48
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. :star:90
* [EPShapes](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder. :star:387
* [Macaw](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :star:3696
* [BlockiesSwift](https://github.com/Boilertalk/BlockiesSwift) - Unique blocky identicons/profile picture generator. :star:21
* [Rough](https://github.com/bakhtiyork/Rough) - lets you draw in a sketchy, hand-drawn-like, style. :star:13
* [GraphLayout](https://github.com/bakhtiyork/GraphLayout) - UI controls for graph visualization. It is powered by Graphviz. :star:11

## Hardware

### Bluetooth

* [Discovery](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background). :star:391
* [LGBluetooth](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code. :star:153
* [PeerKit](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps.
* [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE. :star:1669
* [Bluetonium](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift :star:141
* [BlueCap](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework :star:500
* [Apple Family](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB. :star:39
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U :star:451
* [Bluejay](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps. :star:682
* [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS. :star:3655
* [ExtendaBLE](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates. :star:77
* [PeerConnectivity](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :star:41
* [AZPeerToPeerConnection](https://github.com/AfrozZaheer/AZPeerToPeerConnection) - AZPeerToPeerConnectivity is a wrapper on top of Apple iOS Multipeer Connectivity framework. It provides an easier way to create and manage sessions. Easy to integrate. :star:48

### Camera

* [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects. :star:1445
* [PBJVision](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture. :star:1824
* [Cool-iOS-Camera](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation. :star:1215
* [SCRecorder](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing. :star:2828
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :star:1674
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :star:3732
* [CameraManager](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :star:710
* [RSBarcodes_Swift](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :star:589
* [LLSimpleCamera](https://github.com/omergul/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS. :star:1148
* [Fusuma](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :star:2089
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :star:949
* [HorizonSDK-iOS](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library. :star:166
* [FastttCamera](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters :star:1771
* [DKCamera](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. :star:40
* [NextLevel](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :star:1182
* [CameraEngine](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :star:493
* [SwiftyCam](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :star:1232
* [CameraBackground](https://github.com/yonat/CameraBackground) -  Show camera layer as a background to any UIView. :star:22
* [Lumina](https://github.com/dokun1/Lumina) - Full service camera that takes photos, videos, streams frames, detects metadata, and streams CoreML predictions :largeorangediamond: :star:456
* [RAImagePicker](https://github.com/rallahaseh/RAImagePicker) - RAImagePicker is a protocol-oriented framework that provides custom features from the built-in Image Picker Edit. :star:10
* [FDTake](https://github.com/fulldecent/FDTake) - Easily take a photo or video or choose from library. :star:270
* [YPImagePicker](https://github.com/Yummypets/YPImagePicker) - Instagram-like image picker & filters for iOS :star:858

### Force Touch

* [QuickActions](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts)
* [JustPeek](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :star:68
* [PeekView](https://github.com/itsmeichigo/PeekView) - PeekView supports peek, pop and preview actions for iOS devices without 3D Touch capibility. :star:118

### iBeacon

* [Proxitee](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences. :star:15
* [OWUProximityManager](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth. :star:357
* [Vicinity](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background. :star:367
* [BeaconEmitter](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon. :star:819
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. :star:138

### Location

* [IngeoSDK](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS. :star:94
* [LocationManager](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously. :star:2270
* [SwiftLocation](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :star:1811
* [SOMotionDetector](https://github.com/arturdev/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration. :star:1016
* [LocationPicker](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :star:313
* [BBLocationManager](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS. :star:92
* [set-simulator-location](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :star:223
* [NominatimKit](https://github.com/caloon/NominatimKit) - A Swift wrapper for (reverse) geocoding of OpenStreetMap data. :star:38

### Other Hardware

* [MotionKit](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple. :star:983
* [DarkLightning](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and macOS. :star:197
* [Deviice](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties)
* [DeviceKit](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :star:2016
* [Luminous](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :star:214
* [Device](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :star:1108
* [WatchShaker](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :star:155
* [WatchCon](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️ :star:26
* [TapticEngine](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :star:186
* [UIDeviceComplete](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces. :star:238
* [NFCNDEFParse](https://github.com/jvk75/NFCNDEFParse) - NFC Forum Well Known Type Data Parser for iOS11 and Core NFC. :star:6
* [Device.swift](https://github.com/schickling/Device.swift) - Super-lightweight library to detect used device. :star:150
* [SDVersion](https://github.com/sebyddd/SDVersion) - :iphone: Lightweight Cocoa library for detecting the running device's model and screen size. :star:1288

## Layout

* [FlexboxLayout](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :star:323
* [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax. :star:16512
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code. :star:1518
* [Façade](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative. :star:704
* [PureLayout](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & macOS Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible. :star:6981
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & macOS. :star:12951
* [Cartography](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :star:6447
* [AutoLayoutPlus](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :star:27
* [Neon](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework. :star:4322
* [MisterFusion](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :star:273
* [SwiftBox](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :star:811
* [ManualLayout](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. [e] :star:273
* [Stevia](https://github.com/freshOS/Stevia) - Elegant view layout for iOS. :star:2296
* [Manuscript](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :star:77
* [FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating :star:8974
* [SwiftAutoLayout](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :star:644
* [FormationLayout](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily. :star:52
* [SwiftyLayout](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :star:15
* [Swiftstraints](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :star:101
* [SwiftBond](https://github.com/DeclarativeHub/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :star:3526
* [Restraint](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift :star:77
* [EasyPeasy](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy :star:1637
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices!
* [Anchorman](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :star:66
* [LayoutKit](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :star:2512
* [MarkupKit](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications :star:484
* [Relayout](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :star:576
* [Anchorage](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :star:362
* [Compose](https://github.com/GrupoZapVivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :star:125
* [BrickKit](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :star:613
* [Framezilla](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :star:98
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :star:2589
* [MyLinearLayout](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap. :star:2946
* [SugarAnchor](https://github.com/ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable. :star:19
* [Anchors](https://github.com/onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+ :star:158
* [PinLayout](https://github.com/layoutBox/PinLayout) - Fast Swift Views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable. [iOS/macOS/tvOS] 🔶 :star:961
* [SnapLayout](https://github.com/sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. [e] :star:9
* [Cupcake](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS. :star:210
* [MiniLayout](https://github.com/yonat/MiniLayout) - Minimal AutoLayout convenience layer. Program constraints succinctly. :star:4
* [Bamboo](https://github.com/wordlessj/Bamboo) - Bamboo makes Auto Layout (and manual layout) elegant and concise. :star:48
* [FlexLayout](https://github.com/layoutBox/FlexLayout) - FlexLayout gently wraps the highly optimized [facebook/yoga](https://github.com/facebook/yoga) flexbox implementation in a concise, intuitive & chainable syntax. :star:536
* [Layout](https://github.com/schibsted/layout) - A declarative UI framework for iOS :star:1757
* [CGLayout](https://github.com/k-o-d-e-n/CGLayout) - Powerful autolayout framework based on constraints, that can manage UIView(NSView), CALayer and not rendered views. Not Apple Autolayout wrapper. :star:24
* [YogaKit](https://github.com/facebook/yoga/tree/master/YogaKit) - Powerful layout engine which implements Flexbox. Developed and maintained by Facebook.
* [FlightLayout](https://github.com/AntonTheDev/FlightLayout) -  Balanced medium between manual layout and auto-layout. Great for calculating frames for complex animations. :star:21
* [QLayout](https://github.com/josejuanqm/QLayout) - AutoLayout Utility for iOS. :star:1
* [Layoutless](https://github.com/DeclarativeHub/Layoutless) - Minimalistic declarative layout and styling framework built on top of Auto Layout. :star:260
* [Yalta](https://github.com/kean/Yalta) - An intuitive and powerful Auto Layout library. :star:135
* [GranadaLayout](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater. :star:43
* [SuperLayout](https://github.com/lionheart/SuperLayout) - Simplify Auto Layout with super syntactic sugar. :star:46
* [QuickLayout](https://github.com/huri000/QuickLayout) - QuickLayout offers a simple way, to easily manage Auto Layout in code. :star:50

## Localization

*Tools to manage strings files, translate and enable localization in your apps.*

* [Hodor](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App. :star:524
* [Swifternalization](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :star:559
* [Rubustrings](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files :star:66
* [BartyCrouch](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :star:442
* [LocalizationKit](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission. :star:1009
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :star:1845
* [LocalizedView](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file. :star:8
* [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:52
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language. :star:108
* [IBLocalizable](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :star:421
* [nslocalizer](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings :star:128
* [L10n-swift](https://github.com/Decybel07/L10n-swift) - Localization of an application with ability to change language "on the fly" and support for plural forms in any language. :star:76
* [Localize](https://github.com/andresilvagomez/Localize) - Easy tool to localize apps using JSON or Strings and of course IBDesignables with extensions for UI components. :star:112

## Logging

* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :star:1157
* [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS. :star:10378
* [NSLogger](https://github.com/fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on macOS, iOS and Android. :star:4294
* [QorumLogs](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs.
* [Log](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :star:716
* [Rainbow](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers. :star:1080
* [SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :star:3647
* [SwiftyTextTable](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :star:127
* [Watchdog](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :star:1536
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :star:2984
* [puree](https://github.com/cookpad/puree-ios) - A log collector for iOS :star:153
* [Colors](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! [e] :star:25
* [Loggerithm](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :star:267
* [AELog](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :star:19
* [ReflectedStringConvertible](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :star:51
* [Evergreen](https://github.com/nilsleiffischer/Evergreen) - Most natural Swift logging :star:73
* [SwiftTrace](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :star:132
* [Willow](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :star:1051
* [Bugfender](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps. :star:39
* [LxDBAnything](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly! :star:424
* [XLTestLog](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console :star:60
* [XLFacility](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for macOS & iOS (includes database, Telnet and HTTP servers)
* [Atlantis](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :star:204
* [StoryTeller](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important. :star:8
* [LumberMill](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0 :star:2
* [TinyConsole](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :star:1768
* [Lighty](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :star:37
* [JustLog](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :star:262
* [Twitter Logging Service](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients. :star:177
* [Reqres](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :star:29
* [TraceLog](https://github.com/tonystone/tracelog) - Dead Simple: logging the way it's meant to be! Runs on ios, osx, and Linux. :star:17

## Machine Learning

* [Swift-Brain](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :star:312
* [AIToolbox](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :star:680
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/ios) - The official Google-built powerful neural network library port for iOS.
* [Bender](https://github.com/xmartlabs/Bender) - Easily craft fast Neural Networks. Use TensorFlow models. Metal under the hood. :star:1525
* [Caffe2](https://github.com/caffe2/caffe2) - Lightweight, modular, and scalable deep learning framework. :star:8087
* [CoreML-samples](https://github.com/ytakzk/CoreML-samples) - Sample code for Core ML using ResNet50 provided by Apple and a custom model generated by coremltools. :star:22
* [Revolver](https://github.com/petrmanek/Revolver) - A framework for building fast genetic algorithms in Swift. Comes with modular architecture, pre-implemented operators and loads of examples. :star:16
* [CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models. :star:3048
* [Serrano](https://github.com/pcpLiu/Serrano) - A deep learning library for iOS and macOS. :star:32
* [Swift-AI](https://github.com/Swift-AI/Swift-AI) - The Swift machine learning library. :star:5372
* [TensorSwift](https://github.com/qoncept/TensorSwift) - A lightweight library to calculate tensors in Swift, which has similar APIs to TensorFlow's. :star:297

## Maps

* [Route-me](https://github.com/route-me/route-me) - Open source map library for iOS. :star:1317
* [NAMapKit](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework. :star:259
* [Mapbox GL](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS. :star:2666
* [CMMapLauncher](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications. :star:194
* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine. :star:933
* [PXGoogleDirections](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :star:229
* [Cluster](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering. :star:871
* [JDSwiftHeatMap](https://github.com/jamesdouble/JDSwiftHeatMap) - JDSwiftMap is an IOS Native MapKit Library. You can easily make a highly customized HeatMap. :star:75
* [ClusterKit](https://github.com/hulab/ClusterKit) - An iOS map clustering framework targeting MapKit, Google Maps and Mapbox. :star:292
* [FlyoverKit](https://github.com/SvenTiigi/FlyoverKit) - FlyoverKit enables you to present stunning 360° flyover views on your MKMapView with zero effort while maintaining full configuration possibilities. :star:500
* [MapViewPlus](https://github.com/okhanokbay/MapViewPlus) - Use any custom view as custom callout view of your MKMapView with cool animations. Also, easily use any image as annotation view. :star:67

## Math

* [Euler](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation :star:882
* [SwiftMath](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :star:155
* [Arithmosophi](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :star:58
* [Surge](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :star:4070
* [Upsurge](https://github.com/alejandro-isaza/Upsurge) - Swift math :star:138
* [Swift-MathEagle](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :star:33
* [iosMath](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS. :star:764
* [swift-pons](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :star:211
* [BigInt](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic in pure Swift :star:406
* [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :star:511
* [VectorMath](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :star:187
* [Expression](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :star:373
* [Metron](https://github.com/toineheuvelmans/Metron) - Metron is a comprehensive collection of geometric functions and types that extend the 2D geometric primitives provided by CoreGraphics. :star:944
* [NumericAnnex](https://github.com/xwu/NumericAnnex) - NumericAnnex supplements the numeric facilities provided in the Swift standard library with generic integer algorithms, complex numbers, rational numbers, and pseudorandom number generators (written in, and for, Swift 4)
* [EasyRoot](https://github.com/aaronjsutton/EasyRoot) - A framework to simplify radical expressions
* [SwiftSimplify](https://github.com/malcommac/SwiftSimplify) - Tiny high-performance Swift Polyline Simplification Library. :star:160

## Media

### Audio

* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :star:5494
* [EZAudio](https://github.com/syedhali/EZAudio) - An iOS/macOS audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations. :star:4347
* [novocaine](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and macOS. :star:2121
* [QHSpeechSynthesizerQueue](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech). :star:31
* [Cephalopod](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :star:84
* [Chirp](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :star:306
* [Beethoven](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :star:355
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps.
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :star:368
* [TuningFork](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :star:364
* [MusicKit](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift :star:495
* [SubtleVolume](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :star:644
* [NVDSP](https://github.com/bartolsthoorn/NVDSP) - iOS/macOS DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:88
* [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface. :star:486
* [TheAmazingAudioEngine2](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to. :star:383
* [InteractivePlayerView](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :star:247
* [ESTMusicIndicator](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :star:372
* [QuietModemKit](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. CocoaPods and Carthage compatible. :star:620
* [BPMAnalyser](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :star:22
* [PandoraPlayer](https://github.com/AppliKeySolutions/PandoraPlayer) - A lightweight music player for iOS, based on AudioKit and completely written in Swift :star:727
* [SonogramView](https://github.com/Luccifer/SonogramView) - Audio visualisation of song :star:24
* [AudioIndicatorBars](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :star:191
* [Porcupine](https://github.com/Picovoice/Porcupine) - On-device wake word detection engine for macOS, iOS, and watchOS, powered by deep learning. :star:331

### GIF

* [YLGIFImage](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory. :star:1726
* [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS :star:6682
* [gifu](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :star:2046
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling :star:1050
* [XAnimatedImage](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :star:573
* [SwiftGif](https://github.com/swiftgif/SwiftGif) - :sparkles: A small UIImage extension with gif support :star:875
* [APNGKit](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :star:1387
* [YYImage](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more. :star:1274
* [AImage](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case. :star:964
* [NSGIF2](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url. :star:70
* [SwiftyGif](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :star:809

### Image
* [GPU Image](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. :star:17585
* [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - iOS UIImage processing functions using the vDSP/Accelerate framework for speed. :star:379
* [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI. :star:937
* [SDWebImage](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category. :star:20050
* [DFImageManager](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession. :star:1211
* [MapleBacon](https://github.com/JanGorman/MapleBacon) - An image download and caching library for iOS written in Swift. :star:210
* [NYTPhotoViewer](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer. :star:2423
* [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer. :star:2584
* [Concorde](https://github.com/contentful-labs/Concorde/) - Download and decode progressive JPEGs.
* [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects. :star:2234
* [YXTMotionView](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling. :star:78
* [PINRemoteImage](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher. :star:3408
* [SABlurImageView](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :star:497
* [FastImageCache](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling. :star:7843
* [BKAsciiImage](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art :star:408
* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire. :star:2981
* [Nuke](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating :star:2928
* [FlagKit](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :star:2080
* [YYWebImage](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF). :star:3183
* [RSKImageCropper](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation. :star:2057
* [Silo](https://github.com/josejuanqm/Silo) - Image loading framework with loaders. :star:12
* [Ody](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :star:43
* [Banana](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface. :star:15
* [JDSwiftAvatarProgress](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :star:85
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :star:12018
* [EBPhotoPages](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser. :star:1647
* [UIImageView-BetterFace-Swift](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :star:450
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :star:339
* [Toucan](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift :star:2161
* [ImageLoaderSwift](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :star:270
* [ImageScout](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :star:874
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :star:372
* [Agrume](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :star:251
* [PASImageView](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :star:169
* [Navi](https://github.com/nixzhu/Navi) - Focus on avatar caching. :star:118
* [SwiftPhotoGallery](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :star:128
* [MetalAcc](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift. :star:208
* [MWPhotoBrowser](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections. :star:8224
* [UIImageColors](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. [e] :star:2054
* [CDFlipView](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects. :star:97
* [GPUImage2](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :star:3701
* [TGLParallaxCarousel](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :star:413
* [ImageButter](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth :star:384
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift :star:1596
* [YUCIHighPassSkinSmoothing](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework :star:858
* [CLImageViewPopup](https://github.com/vinbhai4u/CLImageViewPopup/) - A simple Image full screen pop up
* [APKenBurnsView](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :star:60
* [Moa](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. [e] :star:277
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :star:129
* [ImageViewer](https://github.com/Krisiacik/ImageViewer) - An image viewer à la Twitter :star:1823
* [FaceAware](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :star:2457
* [SwiftyAvatar](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard :star:176
* [ShinpuruImage](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :star:67
* [ImagePickerSheetController](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :star:1408
* [ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :star:591
* [ImageSlideshow](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :star:890
* [Imaginary](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :star:450
* [PPAssetsActionController](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :star:54
* [Vulcan](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :star:278
* [FacebookImagePicker](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker written in Swift. :star:128
* [Lightbox](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :star:752
* [AvatarImageView](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :star:237
* [Ebblink](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time. :star:4
* [Sharaku](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController. :star:1345
* [CTPanoramaView](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :star:811
* [Twitter Image Pipline](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application. :star:1571
* [TinyCrayon](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :star:1523
* [FlexibleImage](https://github.com/kawoou/FlexibleImage) - A simple way to play with image! :star:702
* [TLPhotoPicker](https://github.com/tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook. :star:1245
* [YapImageManager](https://github.com/yapstudios/YapImageManager) - A high-performance image downloader written in Swift, powered by YapDatabase. :star:62
* [PhotoEditorSDK](https://www.photoeditorsdk.com) - A fully customizable photo editor for your app.
* [SimpleImageViewer](https://github.com/aFrogleap/SimpleImageViewer) - A snappy image viewer with zoom and interactive dismissal transition. :star:289
* [AZImagePreview](https://github.com/Minitour/AZImagePreview) - A framework that makes image viewing easy. :star:17
* [FaceCropper](https://github.com/KimDarren/FaceCropper) - Crop faces, inside of your image, with iOS 11 Vision api :star:423
* [Paparazzo](https://github.com/avito-tech/Paparazzo) - Custom iOS camera and photo picker with editing capabilities :star:569
* [ZImageCropper](https://github.com/ZaidPathan/ZImageCropper) - A Swift  project to crop image in any shape. :star:49
* [InitialsImageView](https://github.com/bachonk/InitialsImageView) - An UIImageView extension that generates letter initials as a placeholder for user profile images, with a randomized background color. :star:123
* [DTPhotoViewerController](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController, inspired by Facebook photo viewer. :star:84
* [LetterAvatarKit](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars written in Swift. :star:76
* [AXPhotoViewer](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos :star:325
* [TJProfileImage](https://github.com/tejas-ardeshna/TJProfileImage) - Live rendering of componet’s properties in Interface Builder. :star:33
* [Viewer](https://github.com/bakkenbaeck/Viewer) - Image viewer (or Lightbox) with support for local and remote videos and images :star:351
* [OverlayComposite](https://github.com/aaronjsutton/OverlayComposite) - An asynchronous, multithreaded, image compositing framework written in Swift. :star:10
* [MCScratchImageView](https://github.com/Minecodecraft/MCScratchImageView) - A custom ImageView that is used to cover the surface of other view like a scratch card, user can swipe the mulch to see the view below :star:317
* [MetalPetal](https://github.com/MetalPetal/MetalPetal) - A GPU-accelerated image/video processing framework based on [Metal](https://developer.apple.com/metal/). :star:193
* [ShadowImageView](https://github.com/olddonkey/ShadowImageView) - ShadowImageView is a iOS 10 Apple Music style image view, help you create elegent image with shadow. :star:683
* [Avatar](https://github.com/wvabrinskas/Avatar) - Generate random user Avatar images using CoreGraphics and QuartzCore. :star:20
* [Serrata](https://github.com/horitaku46/Serrata) - Slide image viewer library similar to Twitter and LINE. :star:272
* [StyleArt](https://github.com/ileafsolutions/StyleArt) - Style Art library process images using COREML with a set of pre trained machine learning models and convert them to Art style. :star:155
* [greedo-layout-for-ios](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS :star:825
* [ImageDetect](https://github.com/Feghal/ImageDetect) - Detect and crop faces, barcodes and texts inside of your image, with iOS 11 Vision api. :star:219

### Media Processing
* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :star:3273
* [QR Code Scanner](https://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift. :star:557
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :star:2743

### PDF
* [Reader](https://github.com/vfr/Reader) - PDF Reader Core for iOS. :star:4061
* [UIView 2 PDF](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB :star:28
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :star:1697
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :star:368
* [SimplePDF](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :star:133
* [SwiftPDFGenerator](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :star:11
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :star:203
* [FastPdfKit](https://github.com/mobfarm/FastPdfKit) - A Static Library to be embedded on iOS applications to display pdf documents derived from Fast PDF. :star:1179
* [UIImagePlusPDF](https://github.com/DimaMishchenko/UIImagePlusPDF) - UIImage extensions to simply use PDF files. :star:4

### Streaming
* [HaishinKit.swift](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :star:1015
* [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for macOS and iOS. :star:1818
* [Jukebox](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :star:459
* [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate :star:3157
* [Airstream](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay. :star:326
* [OTAcceleratorCore](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox. :star:21
* [webrtc](https://webrtc.org/native-code/ios/) - Provides browsers and mobile applications with Real-Time Communications (RTC) capabilities via simple APIs.

### Video
* [VIMVideoPlayer](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes. :star:270
* [MobilePlayer](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS. :star:2445
* [XCDYouTubeKit](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS :star:2340
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :star:483
* [MHVideoPhotoGallery](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery :star:1965
* [PlayerView](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :star:104
* [SRGMediaPlayer-iOS](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application. :star:88
* [AVPlayerViewController-Subtitles](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. [e] :star:107
* [MPMoviePlayerController-Subtitles](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. [e] :star:179
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress. :star:4516
* [Player](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :star:1132
* [BMPlayer](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :star:1067
* [VideoPager](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available. :star:37
* [ios-360-videos](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer. :star:219
* [swift-360-videos](https://github.com/gsabran/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360. :star:69
* [ABMediaView](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner. :star:60
* [PryntTrimmerView](https://github.com/prynt/PryntTrimmerView) - A set of UI elements to trim, crop and select frames inside a video. :star:186
* [VGPlayer](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player in Swift,Support play local and network,Background playback mode. :star:251
* [YoutubeKit](https://github.com/rinov/YoutubeKit) - A video player that fully supports Youtube IFrame API and YoutubeDataAPI for easily create a Youtube app. :star:206
* [Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player) - Swift library for embedding and controlling YouTube videos in your iOS applications! :star:521
* [JDVideoKit](https://github.com/jamesdouble/JDVideoKit) - You can easily transfer your video into Three common video type via this framework. :star:20

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application. :star:141
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS. :star:5492
* [Chatto](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :star:3386
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features. :star:8470
* [MessageKit](https://github.com/MessageKit/MessageKit) - Eventually, a Swift re-write of JSQMessagesViewController :star:2087
* [NoChat](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS. :star:552
* [NMessenger](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :star:2298
* [Atlas](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer. :star:3834
* [Messenger](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support. :star:3068
* [OTTextChatAccelerator](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices. :star:11
* [chat-sdk-ios](https://github.com/chat-sdk/chat-sdk-ios) - Chat SDK iOS - Open Source Mobile Messenger. :star:535
* [AsyncMessagesViewController](https://github.com/nguyenhuy/AsyncMessagesViewController) - A smooth, responsive and flexible messages UI library for iOS. :star:255
* [MessageViewController](https://github.com/GitHawkApp/MessageViewController) - A SlackTextViewController replacement written in Swift for the iPhone X. :star:1325
* [SwiftyMessenger](https://github.com/abdullahselek/SwiftyMessenger) - Swift toolkit for passing messages between iOS apps and extensions. :star:6

## Networking
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and macOS networking framework. :star:31218
* [RestKit](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun. :star:10280
* [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library. :star:399
* [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone. :star:5789
* [Overcoat](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun. :star:1132
* [ROADFramework](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible. :star:50
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :star:28249
* [Transporter](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :star:438
* [CDZPinger](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping. :star:50
* [NSRails](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails. :star:527
* [NKMultipeer](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :star:14
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS. :star:10185
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking.
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :star:5076
* [OctopusKit](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs. :star:1
* [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. :star:8953
* [TWRDownloadManager](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files. :star:366
* [HappyDns](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record. :star:349
* [Bridge](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :star:93
* [TRON](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :star:450
* [EVCloudKitDao](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :star:538
* [EVURLCache](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :star:271
* [ResponseDetective](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :star:1760
* [Pitaya](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :star:857
* [Just](https://github.com/JustHTTP/Just) - Swift HTTP for Humans :star:1121
* [agent](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS :star:607
* [Reach](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :star:428
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :star:1760
* [Netdiag](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS. :star:80
* [AFNetworkingHelper](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively :star:18
* [NetKit](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :star:4
* [RealReachability](https://github.com/dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do. :star:2622
* [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :star:2036
* [NetworkKit](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :star:28
* [APIKit](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :star:1416
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift. :star:270
* [SPTDataLoader](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client. :star:593
* [SWNetworking](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, macOS and tvOS networking library. :star:21
* [Networking](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :star:1123
* [SOAPEngine](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, macOS app and AppleTV app. :star:446
* [Swish](https://github.com/thoughtbot/Swish) - Nothing but Net(working)
* [Malibu](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :star:346
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking. :star:5374
* [UnboxedAlamofire](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :star:62
* [MMLanScan](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library :star:266
* [Domainer](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table :star:7
* [Restofire](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :star:330
* [AFNetworking+RetryPolicy](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking. :star:167
* [SwiftyZeroMQ](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :star:30
* [Nikka](https://github.com/stremsdoerfer/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :star:15
* [XMNetworking](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking. :star:784
* [Merhaba](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices. :star:38
* [DBNetworkStack](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :star:29
* [EFInternetIndicator](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :star:115
* [AFNetworking-Synchronous](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x. :star:152
* [QwikHttp](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. :star:1
* [NetClient](https://github.com/intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :star:89
* [WANetworkRouting](https://github.com/Wasappli/WANetworkRouting) - An iOS library to route API paths to objects on client side with request, mapping, routing and auth layers :star:10
* [Reactor](https://github.com/RuiAAPeres/Reactor) - Powering your RAC architecture :star:182
* [SWNetworking](https://github.com/isamankumara/skywite) - Powerful high-level iOS, macOS and tvOS networking library. from the creator of SWNetworking :star:6
* [Digger](https://github.com/cornerAnt/Digger) - Digger is a lightweight download framework that requires only one line of code to complete the file download task. :star:416
* [Ciao](https://github.com/AlTavares/Ciao) - Publish and discover services using mDNS(Bonjour, Zeroconf). :star:21
* [PerfectAPIClient](https://github.com/SvenTiigi/PerfectAPIClient) - An API Client based on a network abstraction layer for the Perfect Server-Side Swift Framework :star:25
* [Bamboots](https://github.com/mmoaay/Bamboots) - Bamboots is a network request framework based on Alamofire, aiming at making network request easier for business development :star:410
* [MultiPeer](https://github.com/dingwilson/MultiPeer) - An easy-to-use wrapper for the MultipeerConnectivity framework for automatic offline data transmission between devices :star:25
* [SolarNetwork](https://github.com/ThreeGayHub/SolarNetwork) - Elegant network abstraction layer in Swift. :star:52
* [FGRoute](https://github.com/Feghal/FGRoute) - An easy-to-use library that helps developers to get wifi ssid, router and device ip addresses. :star:50
* [RxRestClient](https://github.com/stdevteam/RxRestClient) - Simple REST Client based on RxSwift and Alamofire. :star:4
* [TermiNetwork](https://github.com/billp/TermiNetwork) - A networking library written with Swift 4.0 that supports multi-environment configuration, routing and automatic deserialization :star:8
* [Dots](https://github.com/iAmrSalman/Dots) - Lightweight Concurrent Networking Framework. :star:29
* [Gem](https://github.com/Albinzr/Gem) - An extreme light weight system with high performance for managing all http request with automated parser with modal. :star:9
* [RMHttp](https://github.com/rogermolas/RMHttp) - Lightweight REST library for iOS and watchOS. :star:2

### Email

* [Mail Core 2](https://github.com/MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP. :star:1833
* [Postal](https://github.com/snipsco/Postal) - A swift framework providing simple access to common email providers. :star:497

## Representations

* [apollo-ios](https://github.com/apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :star:1265
* [JSONRPCKit](https://github.com/bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :star:135
* [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift :star:860
* [swift-protobuf](https://github.com/apple/swift-protobuf) - Plugin and runtime library for using protobuf with Swift. :star:2058

## Notifications

### Push Notifications

* [Orbiter](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS. :star:697
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS). :star:4179
* [FBNotifications](https://github.com/facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework. :star:487
* [NWPusher](https://github.com/noodlewerk/NWPusher) - macOS and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications](https://github.com/acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator :star:1283
* [APNSUtil](https://github.com/pisces/APNSUtil) - Library makes code simple settings and landing for apple push notification service :star:16

### Push Notification Providers

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
* [Pushkin](https://github.com/Nordeus/pushkin) - Free and open-source. :star:187
* [Pusher](https://pusher.com/beams) - Free and unlimited.
* [Swrve](https://www.swrve.com)

### Local Notifications

* [DLLocalNotifications](https://github.com/d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :star:85

## Optimization

* [Unreachable](https://github.com/nvzqz/Unreachable) - Unreachable code path optimization hint for Swift. :star:92

## Parsing

### CSV
* [CSwiftV](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :star:129
* [CSV.swift](https://github.com/yaslab/CSV.swift) - CSV reading and writing library written in Swift. :star:152

### JSON
* [JSON-Framework](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C. :star:3807
* [Mantle](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch. :star:11021
* [Groot](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects. :star:495
* [PropertyMapper](https://github.com/krzysztofzablocki/PropertyMapper) - Data mapping and validation with minimal amount of code. :star:1139
* [JSONModel](https://github.com/JSONModel/JSONModel) - Magical Data Modeling Framework for JSON. Create rapidly powerful, atomic and smart data model classes. :star:6556
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :star:17120
* [FastEasyMapping](https://github.com/Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast. :star:546
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :star:7293
* [JASON](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators. :star:1012
* [Gloss](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift. :star:1627
* [Cereal](https://github.com/Weebly/Cereal) - Swift object serialization :star:380
* [SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :star:703
* [JSONCodable](https://github.com/matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :star:614
* [Tailor](https://github.com/zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :star:252
* [alexander](https://github.com/hodinkee/alexander) - An extremely simple JSON helper written in Swift. :star:34
* [Freddy](https://github.com/bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :star:1126
* [mapper](https://github.com/lyft/mapper) - A JSON deserialization library for Swift :star:1075
* [AlamofireJsonToObjects](https://github.com/evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :star:154
* [Jay](https://github.com/DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & macOS ready. :star:131
* [YYModel](https://github.com/ibireme/YYModel) - High performance model framework for iOS/macOS. :star:3576
* [Alembic](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :star:113
* [Wrap](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :star:631
* [Arrow 🏹](https://github.com/freshOS/Arrow) - Elegant JSON Parsing in Swift. :star:276
* [Decodable](https://github.com/Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :star:1078
* [Genome](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux)
* [Unbox](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :star:1903
* [JSONJoy-Swift](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :star:358
* [LazyObject](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :star:10
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - JSONExport is a desktop application for macOS which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :star:3344
* [Elevate](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :star:620
* [MJExtension](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file. :star:7655
* [AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :star:2242
* [GuardedSwiftyJSON](https://github.com/wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initializers for data models. :star:4
* [JAYSON](https://github.com/muukii/JAYSON) - Strict and Scalable JSON library. :star:229
* [HandyJSON](https://github.com/alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :star:2108
* [Marshal](https://github.com/utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based). :star:644
* [Motis](https://github.com/mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC). :star:253
* [NSTEasyJSON](https://github.com/bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON). :star:9
* [Serpent](https://github.com/nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :star:275
* [MagicMapper](https://github.com/adrianmateoaea24/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :star:27
* [FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift) - This project brings FlatBuffers (an efficient cross platform serialization library) to Swift. :star:493
* [CodableAlamofire](https://github.com/Otbivnoe/CodableAlamofire) - An extension for Alamofire that converts JSON data into Decodable objects (Swift 4). :star:647
* [WAMapping](https://github.com/Wasappli/WAMapping) - A library to turn dictionary into object and vice versa for iOS. Designed for speed! :star:9
* [json-swift](https://github.com/owensd/json-swift) - A basic library for working with JSON in Swift. :star:754
* [Himotoki](https://github.com/ikesyo/Himotoki) - A type-safe JSON decoding library purely written in Swift. :star:705
* [PMHTTP](https://github.com/postmates/PMHTTP) - Swift/Obj-C HTTP framework with a focus on REST and JSON. :star:495
* [NativeJSONMapper](https://github.com/DimaMishchenko/NativeJSONMapper) - Simple Swift 4 encoding & decoding. :star:2
* [PMJSON](https://github.com/postmates/PMJSON) - Pure Swift JSON encoding/decoding library. :star:286
* [jsoncafe.com](http://www.jsoncafe.com/) - Online Template driven Model Class Generator from JSON.
* [Mappable](https://github.com/leavez/Mappable) - lightweight and powerful JSON object mapping library, specially optimized for immutable properties. :star:13

### XML & HTML
* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :star:771
* [Ji](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :star:767
* [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS :star:2283
* [AlamofireXmlToObjects](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :star:65
* [Fuzi](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :star:685
* [Kanna](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for macOS/iOS.
* [SwiftyXMLParser](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :star:178
* [HTMLKit](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs. :star:138
* [SWXMLHash](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :star:978
* [SwiftyXML](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 4 :star:28

### Other Parsing
* [WKZombie](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/macOS to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :star:952
* [URLPreview](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :star:185
* [FeedKit](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :star:473
* [Erik](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :star:291
* [URLEmbeddedView](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :star:467
* [SwiftyConfiguration](https://github.com/ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :star:111
* [JSONFeed](https://github.com/totocaster/JSONFeed) - Swift parser for JSON Feed, a format similar to RSS and Atom but in JSON. :star:28
* [SwiftCssParser](https://github.com/100mango/SwiftCssParser) - A Powerful , Extensible CSS Parser written in pure Swift. :star:239
* [RLPSwift](https://github.com/bitfwdcommunity/RLPSwift) - Recursive Length Prefix encoding written in Swift. :star:14

## Passbook
* [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+. :star:215
* [Dubai](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes. :star:320
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :star:683
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://moltin.com/swift-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit](https://github.com/MosheBerman/PatronKit) - A framework to add patronage to your apps. :star:367
* [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and macOS 9.0+ :star:3068
* [InAppFramework](https://github.com/sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :star:38
* [SwiftInAppPurchase](https://github.com/rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :star:17
* [monza](https://github.com/gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions :star:96
* [PayPal](https://github.com/paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal. :star:921
* [card.io-iOS-SDK](https://github.com/card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps :star:2068
* [SwiftLuhn](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :star:115
* [ObjectiveLuhn](https://github.com/MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm :star:122
* [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases :star:2142
* [MFCard](https://github.com/mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI :star:292
* [TPInAppReceipt](https://github.com/tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :star:43
* [iCard](https://github.com/eliakorkmaz/iCard) - Bank Card Generator with Swift using SnapKit DSL :star:268
* [CreditCardForm-iOS](https://github.com/orazz/CreditCardForm-iOS) - CreditCardForm is iOS framework that allows developers to create the UI which replicates an actual Credit Card. :star:1154
* [merchantkit](https://github.com/benjaminmayo/merchantkit) - A modern In-App Purchases management framework for iOS. :star:653
* [TipJarViewController](https://github.com/lionheart/TipJarViewController) - Easy, drop-in tip jar for iOS apps. :star:29

## Permissions
* [Proposer](https://github.com/nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :star:778
* [ICanHas](https://github.com/wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :star:87
* [VWWPermissionKit](https://github.com/zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS. :star:137
* [ISHPermissionKit](https://github.com/iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions. :star:589
* [JLPermissions](https://github.com/jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request. :star:408
* [ClusterPrePermissions](https://github.com/rsattar/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request. :star:1219
* [Permission](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS :star:2429
* [STLocationRequest](https://github.com/SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :star:592
* [PAPermissions](https://github.com/pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :star:677
* [AREK](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :star:858
* [RequestPermission](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI :star:1853

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io](https://github.com/openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google. :star:331

## Reactive Programming
* [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift :star:13688
* [RxOptional](https://github.com/thanegill/RxOptional) - RxSwift extensions for Swift optionals and "Occupiable" types :star:7
* [ReactiveTask](https://github.com/Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :star:124
* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Streams of values over time. :star:18817
* [RxMediaPicker](https://github.com/RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :star:113
* [ReactiveCoreData](https://github.com/apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world. :star:272
* [ReSwift](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :star:5128
* [ReactiveKit](https://github.com/DeclarativeHub/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :star:978
* [RxPermission](https://github.com/sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :star:218
* [RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :star:976
* [RxRealm](https://github.com/RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :star:682
* [RxMultipeer](https://github.com/RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :star:50
* [RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit) - iOS & macOS Bluetooth library for RxSwift :star:788
* [RxGesture](https://github.com/RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :star:605
* [NSObject-Rx](https://github.com/RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :star:322
* [RxCoreData](https://github.com/RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :star:96
* [RxAutomaton](https://github.com/inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :star:636
* [ReactiveArray](https://github.com/Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :star:54
* [Interstellar](https://github.com/JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :star:1009
* [ReduxSwift](https://github.com/lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :star:33
* [Aftermath](https://github.com/hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :star:62
* [RxKeyboard](https://github.com/RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :star:774
* [JASONETTE-iOS](https://github.com/Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON. :star:5068
* [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group :star:1942
* [Listenable](https://github.com/msaps/Listenable) - Swift object that provides an observable platform. :star:5
* [Reactor](https://github.com/ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :star:152
* [Snail](https://github.com/UrbanCompass/Snail) - An observables framework for Swift :star:86
* [RxWebSocket](https://github.com/fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :star:38
* [ACKReactiveExtensions](https://github.com/AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :star:12
* [ReactiveLocation](https://github.com/AckeeCZ/ReactiveLocation) - CoreLocation made reactive :star:17
* [Hanson](https://github.com/blendle/Hanson) - Lightweight observations and bindings in Swift, with support for KVO and NotificationCenter. :star:474
* [Observable](https://github.com/roberthein/Observable) - The easiest way to observe values in Swift. :star:191
* [SimpleApiClient](https://github.com/jaychang0917/SimpleApiClient-ios) - A configurable api client based on Alamofire4 and RxSwift4 for iOS. :star:68
* [VueFlux](https://github.com/ra1028/VueFlux) - Unidirectional Data Flow State Management Architecture for Swift - Inspired by Vuex and Flux :star:210
* [RxAnimated](https://github.com/RxSwiftCommunity/RxAnimated) - Animated RxCocoa bindings :star:395
* [BindKit](https://github.com/electricbolt/bindkit) - Two-way data binding framework for iOS. Only one API to learn. :star:5
* [STDevRxExt](https://github.com/stdevteam/STDevRxExt) - STDevRxExt contains some extension functions for RxSwift and RxCocoa which makes our live easy. :star:2
* [RxReduce](https://github.com/RxSwiftCommunity/RxReduce) - Lightweight framework that ease the implementation of a state container pattern in a Reactive Programming compliant way. :star:33

### React-Like
* [Render](https://github.com/alexdrone/Render) - Swift and UIKit a la React. :star:1833
* [Katana](https://github.com/BendingSpoons/katana-swift) - Swift apps a la React and Redux. :star:1749
* [TemplateKit](https://github.com/mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :star:147
* [Komponents 📦](https://github.com/freshOS/Komponents) - React-inspired UIKit Components. :star:166

## Reflection
* [Reflection](https://github.com/Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :star:432
* [Reflect](https://github.com/CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :star:310
* [EVReflection](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :star:840
* [JSONNeverDie](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :star:479
* [SwiftKVC](https://github.com/bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :star:114
* [Runtime](https://github.com/wickwirew/Runtime) - A Swift Runtime library for viewing type info, and the dynamic getting and setting of properties. :star:301

## Regex
* [Regex](https://github.com/sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :star:479
* [SwiftRegex](https://github.com/kasei/SwiftRegex) - Perl-like Regex =~ operator for Swift :star:117
* [PySwiftyRegex](https://github.com/cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :star:210
* [Regex](https://github.com/crossroadlabs/Regex) - Regular expressions for swift :star:236
* [Regex](https://github.com/brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :star:65

## SDK

### Official

* [Spotify](https://github.com/spotify/ios-sdk) Spotify iOS SDK.
* [SpotifyLogin](https://github.com/spotify/SpotifyLogin) Spotify SDK Login in Swift.
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
* [PacketZoom](https://www.packetzoom.com/) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure](https://github.com/Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device :star:59
* [1Password](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps :star:2474
* [CareKit](https://github.com/carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :star:1425
* [Shopify](https://github.com/Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app. :star:225
* [Pinterest](https://github.com/pinterest/ios-pdk) - Pinterest iOS SDK :star:101
* [playkit-ios](https://github.com/kaltura/playkit-ios) - PlayKit: Kaltura Player SDK for iOS. :star:20
* [algoliasearch-client-swift](https://github.com/algolia/algoliasearch-client-swift) - Algolia Search API Client for Swift :star:100
* [twitter-kit-ios](https://github.com/twitter/twitter-kit-ios) - Twitter Kit is a native SDK to include Twitter content inside mobile apps. :star:512
* [rides-ios-sdk](https://github.com/uber/rides-ios-sdk) - Uber Rides iOS SDK (beta). :star:283

### Unofficial

* [STTwitter](https://github.com/nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine](https://github.com/natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy](https://github.com/heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit](https://github.com/sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API. :star:98
* [InstagramKit](https://github.com/shyambhat/InstagramKit) - Instagram iOS SDK. :star:920
* [DribbbleSDK](https://github.com/agilie/dribbble-ios-sdk) - Dribbble iOS SDK. :star:79
* [objectiveflickr](https://github.com/lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C. :star:724
* [Easy Social](https://github.com/pjebs/EasySocial) - Twitter & Facebook Integration. :star:129
* [das-quadrat](https://github.com/Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and macOS. :star:171
* [SocialLib](https://github.com/darkcl/SocialLib) - SocialLib handles sharing message to multiple social media. :star:10
* [PokemonKit](https://github.com/ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :star:77
* [TJDropbox](https://github.com/timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C :star:48
* [Lyft](https://github.com/genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :star:61
* [Github.swift](https://github.com/onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :star:163
* [CloudRail SI](https://github.com/CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more. :star:203
* [Medium SDK - Swift](https://github.com/96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project. :star:8
* [Swifter](https://github.com/mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & macOS written in Swift. :star:1905
* [SlackKit](https://github.com/SlackKit/SlackKit) - a Slack client library for iOS and macOS written in Swift. :star:706
* [RandomUserSwift](https://github.com/dingwilson/RandomUserSwift) - Swift Framework to Generate Random Users - An Unofficial SDK for randomuser.me. :star:83
* [PPEventRegistryAPI](https://github.com/pantuspavel/PPEventRegistryAPI/) - Swift 3 Framework for Event Registry API (eventregistry.org).
* [UnsplashKit](https://github.com/modo-studio/UnsplashKit) - Swift client for Unsplash. :star:161
* [Swiftly Salesforce](https://github.com/mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :star:77
* [Spartan](https://github.com/Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :star:50
* [BigBoard](https://github.com/Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :star:53
* [BittrexApiKit](https://github.com/saeid/BittrexApiKit) - Simple and complete Swift wrapper for Bittrex Exchange API. :star:9
* [SwiftyVK](https://github.com/SwiftyVK/SwiftyVK) Library for easy interact with VK social network API written in Swift.
* [ARKKit](https://github.com/sleepdefic1t/ARKKit) - ARK Ecosystem Cryptocurrency API Framework for iOS & macOS, written purely in Swift 4.0. :star:19
* [SwiftInstagram](https://github.com/AnderGoig/SwiftInstagram) - Swift Client for Instagram API. :star:456
* [SwiftyArk](https://github.com/Awalz/SwiftyArk) - A simple, lightweight, fully-asynchronous cryptocurrency framework for the ARK Ecosystem. :star:9
* [PerfectSlackAPIClient](https://github.com/SvenTiigi/PerfectSlackAPIClient) - A Slack API Client for the Perfect Server-Side Swift Framework. :star:8
* [Mothership](https://github.com/thecb4/MotherShip) - Tunes Connect Library inspired by FastLane. :star:69
* [SwiftFlyer](https://github.com/rinov/SwiftFlyer) - An API wrapper for bitFlyer that supports all providing API. :star:32
* [waterwheel.swift](https://github.com/kylebrowning/waterwheel.swift) - The Waterwheel Swift SDK provides classes to natively connect iOS, macOS, tvOS, and watchOS applications to Drupal 7 and 8. :star:414
* [ForecastIO](https://github.com/sxg/ForecastIO) - A Swift library for the Forecast.io Dark Sky API. :star:138
* [JamfKit](https://github.com/ethenyl/JamfKit) - A JSS communication framework written in Swift. :star:17

## Security
* [cocoapods-keys](https://github.com/orta/cocoapods-keys) - A key value store for storing environment and application keys. :star:1053
* [simple-touch](https://github.com/simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS. :star:102
* [SwiftPasscodeLock](https://github.com/yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :star:599
* [Smile-Lock](https://github.com/recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View. :star:518
* [zxcvbn-ios](https://github.com/dropbox/zxcvbn-ios) - A realistic password strength estimator. :star:167
* [TPObfuscatedString](https://github.com/Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :star:12
* [LTHPasscodeViewController](https://github.com/rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support. :star:615
* [iOS-App-Security-Class](https://github.com/karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment. :star:42
* [BiometricAuth](https://github.com/vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application :star:19
* [SAPinViewController](https://github.com/siavashalipour/SAPinViewController) - Simple and easy to use default iOS PIN screen. This simple library allows you to draw a fully customisable PIN screen same as the iOS default PIN view. My inspiration to create this library was form THPinViewController, however SAPinViewController is completely implemented in Swift. Also the main purpose of creating this library was to have simple, easy to use and fully customisable PIN screen. :star:16
* [VoiceItAPI1IosSDK](https://github.com/voiceittech/VoiceItAPI1IosSDK) - A super easy way to add Voice Authentication(Biometrics) to your iOS apps, conveniently usable via cocoapods :star:6
* [TOPasscodeViewController](https://github.com/timoliver/TOPasscodeViewController) - A modal passcode input and validation view controller for iOS :star:271
* [BiometricAuthentication](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication :star:463
* [KKPinCodeTextField](https://github.com/kolesa-team/ios_pinCodeTextField) - A customizable verification code textField for phone verification codes, passwords etc. :star:23
* [🗄 Vault](https://github.com/umbri/Vault) - Simple and Secure container for passwords and other sensitive data :star:13
* [Virgil SWIFT PFS SDK](https://github.com/VirgilSecurity/virgil-sdk-pfs-x) - An SDK that allows developers to add the Perfect Forward Secrecy (PFS) technologies to their digital solutions to protect previously intercepted traffic from being decrypted even if the main Private Key is compromised. :star:4
* [Virgil Security Objective-C/Swift SDK](https://github.com/VirgilSecurity/virgil-sdk-x) - An SDK which allows developers to add full end-to-end security to their existing digital solutions to become HIPAA and GDPR compliant and more using Virgil API. :star:13

### Encryption
* [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works. :star:739
* [IDZSwiftCommonCrypto](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :star:380
* [Arcane](https://github.com/onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :star:226
* [SwiftMD5](https://github.com/mpurland/SwiftMD5) - A pure Swift implementation of MD5 :star:11
* [SwiftHash](https://github.com/onmyway133/SwiftHash) - 🍕 Hash in Swift :star:82
* [SweetHMAC](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :star:36
* [SwCrypt](https://github.com/soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and macOS :star:455
* [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :star:188
* [SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :star:506
* [EnigmaKit](https://github.com/mikaoj/EnigmaKit) - Enigma encryption in Swift :star:101
* [Themis](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/macOS, Android and different server side platforms. :star:536
* [Obfuscator-iOS](https://github.com/pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings. :star:459
* [swift-sodium](https://github.com/jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :star:245
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :star:5694
* [SCrypto](https://github.com/sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :star:19
* [SipHash](https://github.com/attaswift/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :star:209
* [RNCryptor](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift. -- For ObjC, see RNCryptor/RNCryptor-objc. :star:2881
* [CatCrypto](https://github.com/ImKcat/CatCrypto) - An easy way for hashing and encryption. :star:21
* [SecureEnclaveCrypto](https://github.com/trailofbits/SecureEnclaveCrypto) - Demonstration library for using the Secure Enclave on iOS. :star:163
* [RSASwiftGenerator](https://github.com/4taras4/RSASwiftGenerator) - Util for generation RSA keys on your client and save to keychain or cover into Data 🔑 🔐 :star:9
* [Virgil Security Objective-C/Swift Crypto Library](https://github.com/VirgilSecurity/virgil-foundation-x) - A high-level cryptographic library that allows to perform all necessary operations for securely storing and transferring data. :star:18

### Keychain
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS. :star:2657
* [Valet](https://github.com/square/Valet) - Securely store data in the iOS or macOS Keychain without knowing a thing about how the Keychain works. :star:2969
* [Locksmith](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :star:2597
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and macOS :star:3918
* [Keychains](https://github.com/hyperoslo/Keychains) - Because you should care... about the security... of your shit. :star:65
* [Lockbox](https://github.com/granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain. :star:850
* [SAMKeychain](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS. :star:4887
* [SwiftKeychainWrapper](https://github.com/jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. :star:738

## Server

*Server side projects supporting coroutines, Linux, MacOS, iOS, Apache Modules, Async calls, libuv and more.*

* [Perfect](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :star:12982
* [Swifter](https://github.com/httpswift/swifter) - Tiny http server engine written in Swift programming language. :star:2320
* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for macOS or iOS applications. :star:4667
* [Curassow](https://github.com/kylef-archive/Curassow) - Swift HTTP server using the pre-fork worker model. :star:400
* [Zewo](https://github.com/Zewo/Zewo) - Lightweight library for web server applications in Swift on macOS and Linux powered by coroutines. :star:1777
* [Vapor](https://github.com/vapor/vapor) - Elegant web framework for Swift that works on iOS, macOS, and Ubuntu. :star:14229
* [swiftra](https://github.com/takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :star:271
* [blackfire](https://github.com/elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :star:943
* [swift-http](https://github.com/huytd/swift-http) - HTTP Implementation for Swift on Linux and macOS :star:462
* [Trevi](https://github.com/Yoseob/Trevi) - libuv base Swift web HTTP server framework :star:47
* [Express](https://github.com/crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :star:852
* [Taylor](https://github.com/izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :star:929
* [Frank](https://github.com/kylef-archive/Frank) - Frank is a DSL for quickly writing web applications in Swift :star:381
* [Kitura](https://github.com/IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :star:6553
* [Swifton](https://github.com/necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and macOS :star:2045
* [Dynamo](https://github.com/johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :star:63
* [Redis](https://github.com/vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. macOS + Linux compatible. :star:371
* [NetworkObjects](https://github.com/colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux)
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift.
* [Lightning](https://github.com/skylab-inc/Lightning) - A Swift Multiplatform Web and Networking Framework. :star:310
* [SwiftGD](https://github.com/twostraws/swiftgd) - A simple Swift wrapper for libgd. :star:219
* [Jobs](https://github.com/BrettRToomey/Jobs) - A job system for Swift backends. :star:208
* [ApacheExpress](https://github.com/ApacheExpress/ApacheExpress) - Write Apache Modules in Swift! :star:167
* [GCDWebServer](https://github.com/swisspol/GCDWebServer) - Lightweight GCD based HTTP server for macOS & iOS (includes web based uploader & WebDAV server)
* [Embassy](https://github.com/envoy/Embassy) - Super lightweight async HTTP server library in pure Swift runs in iOS / MacOS / Linux. :star:245

## Text
* [Twitter Text Obj](https://github.com/twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library. :star:1944
* [Nimbus](https://github.com/jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers. :star:6424
* [NSStringEmojize](https://github.com/diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters. :star:632
* [MMMarkdown](https://github.com/mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML. :star:1168
* [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText. :star:5450
* [DTRichTextEditor](https://github.com/Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS. :star:304
* [NBEmojiSearchView](https://github.com/neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view. :star:84
* [Pluralize.swift](https://github.com/joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :star:146
* [RichEditorView](https://github.com/cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :star:1151
* [Money](https://github.com/danthorpe/Money) - Swift value types for working with money & currency :star:884
* [PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :star:2435
* [YYText](https://github.com/ibireme/YYText) - Powerful text framework for iOS to display and edit rich text. :star:7385
* [Format](https://github.com/marmelroy/Format) - A Swift Formatter Kit. :star:1169
* [Tribute](https://github.com/zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :star:60
* [EmojiKit](https://github.com/dasmer/EmojiKit) - Effortless emoji-querying in Swift :star:85
* [Roman](https://github.com/nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :star:34
* [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view. :star:2885
* [pangu.Objective-C](https://github.com/Cee/pangu.objective-c) - Paranoid text spacing in Objective-C. :star:108
* [SwiftString](https://github.com/amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :star:1456
* [Marklight](https://github.com/macteo/Marklight) - Markdown syntax highlighter for iOS :star:400
* [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :star:591
* [TextAttributes](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings. [e] :star:1987
* [Reductio](https://github.com/fdzsergio/Reductio) - Automatic summarizer text in Swift :star:357
* [SmarkDown](https://github.com/SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :star:63
* [SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :star:895
* [SZMentions](https://github.com/szweier/SZMentions) - Library to help handle mentions :star:9
* [SZMentionsSwift](https://github.com/szweier/SZMentionsSwift) - Library to help handle mentions. :star:38
* [Heimdall](https://github.com/henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :star:315
* [NoOptionalInterpolation](https://github.com/T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.[e] :star:42
* [Smile](https://github.com/onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601](https://github.com/onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift [e]
* [Translucid](https://github.com/Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :star:523
* [FormatterKit](https://github.com/mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set :star:4127
* [BonMot](https://github.com/Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :star:2081
* [SwiftValidators](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator). :star:149
* [StringStylizer](https://github.com/kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :star:45
* [SwiftyAttributes](https://github.com/eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :star:977
* [MarkdownKit](https://github.com/bmoliveira/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :star:151
* [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and macOS. :star:976
* [Apodimark](https://github.com/loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :star:442
* [Notepad](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :star:371
* [KKStringValidator](https://github.com/krizhanovskii/KKStringValidator) - Fast and simple string validation for iOS. With UITextField extension. :star:15
* [ISO8859](https://github.com/Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :star:11
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne](https://github.com/emojione/emojione). :star:59
* [SwiftRichString](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :star:1637
* [libPhoneNumber-iOS](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library). :star:1854
* [AttributedTextView](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions). :star:265
* [StyleDecorator](https://github.com/dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts :star:9
* [Mustard](https://github.com/mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :star:679
* [Input Mask](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :star:217
* [Attributed](https://github.com/Nirma/Attributed) - Modern Swift µframework for attributed strings. :star:635
* [Atributika](https://github.com/psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :star:281
* [Guitar](https://github.com/ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :star:575
* [RealTimeCurrencyFormatter](https://github.com/kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility. :star:13
* [Down](https://github.com/iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. :star:800
* [Marky Mark](https://github.com/m2mobi/Marky-Mark) - Highly customizable Markdown parsing and native rendering in Swift. :star:109
* [MarkdownView](https://github.com/keitaoouchi/MarkdownView) - Markdown View for iOS. :star:1156
* [Highlighter](https://github.com/younatics/Highlighter) - Highlight whatever you want! Highlighter will magically find UI objects such as UILabel, UITextView, UITexTfield, UIButton in your UITableViewCell or other Class. :star:717
* [Sprinter](https://github.com/nicklockwood/Sprinter) - A library for formatting strings on iOS and macOS :star:158
* [Highlightr](https://github.com/raspu/Highlightr) - An iOS & macOS syntax highlighter, supports 176 languages and comes with 79 styles. :star:496
* [fuse-swift](https://github.com/krisk/fuse-swift) - A lightweight fuzzy-search library, with zero dependencies. :star:479
* [EFMarkdown](https://github.com/EyreFree/EFMarkdown) - A lightweight Markdown library for iOS. :star:288
* [Croc](https://github.com/jkalash/croc) - A lightweight Swift library for Emoji parsing and querying. :star:101

### Font
* [FontBlaster](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :star:904
* [GoogleMaterialIconFont](https://github.com/kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :star:141
* [ios-fontawesome](https://github.com/alexdrone/ios-fontawesome) - NSString+FontAwesome. :star:1766
* [FontAwesome.swift](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :star:1008
* [SwiftFontName](https://github.com/morizotter/SwiftFontName) - OS font complements library. Localized font supported :star:97
* [SwiftIconFont](https://github.com/0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon)
* [FontAwesomeKit](https://github.com/PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons. :star:2682
* [Iconic](https://github.com/dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS :star:1465
* [GoogleMaterialDesignIcons](https://github.com/dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :star:368
* [OcticonsKit](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :star:35
* [IoniconsKit](https://github.com/keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :star:299
* [FontAwesomeKit.Swift](https://github.com/qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :star:165
* [UIFontComplete](https://github.com/Nirma/UIFontComplete) - Font management (System & Custom) for iOS and tvOS :star:977
* [Swicon](https://github.com/UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :star:36
* [SwiftIcons](https://github.com/ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :star:504
* [Font-Awesome-Swift](https://github.com/Vaberer/Font-Awesome-Swift) - Font Awesome swift library for iOS. :star:697
* [JQSwiftIcon](https://github.com/josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :star:5

## Testing

### TDD / BDD
* [Kiwi](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development. :star:3819
* [Specta](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa. :star:2163
* [Quick](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C. :star:7556
* [XcodeCoverage](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects. :star:713
* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers! :star:3762
* [Dixie](https://github.com/Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours. :star:202
* [gh-unit](https://github.com/gh-unit/gh-unit) - Test Framework for Objective-C. :star:1913
* [Nimble](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C :star:2846
* [Sleipnir](https://github.com/railsware/Sleipnir) - BDD-style framework for Swift :star:863
* [SwiftCheck](https://github.com/typelift/SwiftCheck) - QuickCheck for Swift :star:964
* [Spry](https://github.com/Quick/Spry) - A Mac and iOS Playgrounds Unit Testing library based on Nimble. :star:293
* [swift-corelibs-xctest](https://github.com/apple/swift-corelibs-xctest) - The XCTest Project, A Swift core library for providing unit test support. :star:652
* [PlaygroundTDD](https://github.com/app-shack/PlaygroundTDD) - Small library to easily run your tests directly within a Playground. :star:317

### A/B Testing
* [Switchboard](https://github.com/KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users. :star:276
* [SkyLab](https://github.com/mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac :star:693
* [MSActiveConfig](https://github.com/mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS :star:78
* [ABKit](https://github.com/recruit-mp/ABKit) - AB testing framework for iOS :star:102

### UI Testing
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary](https://github.com/serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework. :star:167
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework. :star:5330
* [Subliminal](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing. :star:784
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any iOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Remote](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing. :star:679
* [LayoutTest-iOS](https://github.com/linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations. :star:514
* [EarlGrey](https://github.com/google/EarlGrey) - :tea: iOS UI Automation Test Framework. :star:4279
* [UI Testing Cheat Sheet](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :star:1445
* [Floater_](https://github.com/Buglife/Floater_) - Add a floating fingertip to your app demo :star:231
* [Bluepill](https://github.com/linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine :star:2666
* [Flawless App](https://flawlessapp.io/) - tool for visual quality check of mobile app in a real-time. It compares initial design with the actual implementation right inside iOS simulator.
* [TouchVisualizer](https://github.com/morizotter/TouchVisualizer) - Lightweight touch visualization library in Swift. A single line of code and visualize your touches! :star:620
* [UITestHelper](https://github.com/evermeer/UITestHelper) - UITest helper library for creating readable and maintainable tests :star:22

### Other Testing
* [NaughtyKeyboard](https://github.com/Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device. :star:585
* [Fakery](https://github.com/vadymmarkov/Fakery) - Swift fake data generator. :star:904
* [DVR](https://github.com/venmo/DVR) - Network testing for Swift :star:541
* [Cuckoo](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :star:784
* [Parallel iOS Tests](https://github.com/plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :star:1
* [Vinyl](https://github.com/Velhotes/Vinyl) - Network testing à la VCR in Swift :star:212
* [Mockit](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :star:74
* [Cribble](https://github.com/maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :star:279
* [second_curtain](https://github.com/ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3 :star:118
* [trainer](https://github.com/KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports :star:110
* [Buildasaur](https://github.com/buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :star:749
* [Kakapo](https://github.com/devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :star:751
* [AcceptanceMark](https://github.com/bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit](https://github.com/metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :star:18
* [MirrorDiffKit](https://github.com/Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :star:117
* [SnappyTestCase](https://github.com/tooploox/SnappyTestCase) - iOS Simulator type agnostic snapshot testing, built on top of the FBSnapshotTestCase. :star:11
* [XCTestExtensions](https://github.com/shindyu/XCTestExtensions) - XCTestExtensions is a Swift extension that provides convenient assertions for writing Unit Test. :star:7
* [OCMock](http://ocmock.org) - Mock objects for Objective-C.
* [Mockingjay](https://github.com/kylef/Mockingjay) - An elegant library for stubbing HTTP requests with ease in Swift. :star:1083
* [PinpointKit](https://github.com/Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :star:1020

## UI
* [FlatUIKit](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS. :star:7776
* [Motif](https://github.com/erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS. :star:856
* [Texture](https://github.com/TextureGroup/Texture) - Smooth asynchronous user interfaces for iOS apps. :star:3942
* [GaugeKit](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :star:925
* [SAHistoryNavigationViewController](https://github.com/marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :star:1525
* [iCarousel](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS. :star:10612
* [tapkulibrary](https://github.com/devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework. :star:4002
* [HorizontalDial](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :star:118
* [ComponentKit](https://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center. :star:2933
* [phone-number-picker](https://github.com/hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :star:124
* [EXTView](https://github.com/recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable. :star:154
* [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :star:1557
* [Splitflap](https://github.com/yannickl/Splitflap) - A simple split-flap display for your Swift applications :star:807
* [EZSwipeController](https://github.com/goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :star:755
* [Curry](https://github.com/devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit. :star:34
* [Pages](https://github.com/hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :star:411
* [BothamUI](https://github.com/Karumi/BothamUI) - Model View Presenter Framework written in Swift. :star:349
* [APCustomBlurView](https://github.com/collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :star:163
* [BAFluidView](https://github.com/antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion :star:1298
* [WZDraggableSwitchHeaderView](https://github.com/wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers :star:531
* [SCTrelloNavigation](https://github.com/SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation. :star:796
* [CRParticleEffect](https://github.com/Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects. :star:352
* [Spots](https://github.com/hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :star:1293
* [APAddressBook](https://github.com/Alterplay/APAddressBook) - Easy access to iOS address book :star:1426
* [AZExpandableIconListView](https://github.com/Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :star:203
* [FlourishUI](https://github.com/thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :star:212
* [Navigation Stack](https://github.com/Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :star:2081
* [UIView-draggable](https://github.com/andreamazz/UIView-draggable) - UIView category that adds dragging capabilities. :star:403
* [PeekPop](https://github.com/marmelroy/PeekPop) - Backwards-compatible Peek and Pop. :star:1925
* [EPSignature](https://github.com/ipraba/EPSignature) - Signature component for iOS in Swift :star:684
* [CoreDragon](https://github.com/nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [EVFaceTracker](https://github.com/evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face. :star:229
* [Fashion](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :star:79
* [LeeGo](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :star:928
* [MEVHorizontalContacts](https://github.com/manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items. :star:331
* [Ripple](https://github.com/RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :star:60
* [ScalePicker](https://github.com/kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app. :star:153
* [VisualEffectView](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :star:515
* [Cacao](https://github.com/PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux)
* [StateView](https://github.com/sahandnayebaziz/StateView) - Views that automatically update themselves. :star:505
* [JDFlipNumberView](https://github.com/calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays. :star:732
* [ISTimeline](https://github.com/instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :star:913
* [JFCardSelectionViewController](https://github.com/atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :star:403
* [DCKit](https://github.com/agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :star:104
* [BackgroundVideoiOS](https://github.com/Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views. :star:532
* [NightNight](https://github.com/Draveness/NightNight) - Elegant way to integrate night mode to swift projects :star:657
* [SwiftTheme](https://github.com/jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :star:1251
* [FDStackView](https://github.com/forkingdog/FDStackView) - Use UIStackView directly in iOS6+ :star:2429
* [YangMingShan](https://github.com/yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps. :star:634
* [nui](https://github.com/tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS :star:3783
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material](https://github.com/CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :star:9983
* [DistancePicker](https://github.com/qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :star:97
* [OAStackView](https://github.com/nsomar/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView. :star:2199
* [StyleKit](https://github.com/146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. :star:1148
* [PageController](https://github.com/hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :star:221
* [StatusProvider](https://github.com/mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :star:830
* [ASBubbleDrag](https://github.com/scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :star:42
* [StackLayout](https://github.com/bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns. :star:76
* [NightView](https://github.com/Boris-Em/NightView) - Dazzling Nights on iOS. :star:162
* [SwiftVideoBackground](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementing a video background :star:148
* [MRArticleViewController](https://github.com/mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :star:104
* [ConfettiView](https://github.com/OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :star:219
* [BouncyPageViewController](https://github.com/BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :star:687
* [LTHRadioButton](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :star:206
* [CRRulerControl](https://github.com/Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument. :star:98
* [Macaw-Examples](https://github.com/exyte/Macaw-Examples) - Various usages of the Macaw library. :star:189
* [Reactions](https://github.com/yannickl/Reactions) - Fully customizable Facebook reactions control :star:477
* [Newly](https://github.com/dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :star:183
* [CardStackController](https://github.com/jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :star:392
* [Material Components](https://github.com/material-components/material-components-ios) - Google developed UI components that help developers execute Material Design. :star:2490
* [RKMultiUnitRuler](https://github.com/farshidce/RKMultiUnitRuler/) - Simple customizable ruler control that supports multiple units.
* [FAQView](https://github.com/mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :star:398
* [CRPageViewController](https://github.com/Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further. :star:393
* [OXPatternLock](https://github.com/oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :star:19
* [LMArticleViewController](https://github.com/lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts :star:6
* [FSPagerView](https://github.com/WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :star:3192
* [PanelKit](https://github.com/louisdh/panelkit) - A UI framework that enables panels on iOS. :star:3423
* [ElongationPreview](https://github.com/Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :star:719
* [Pageboy](https://github.com/uias/Pageboy) - A simple, highly informative page view controller. :star:1039
* [IGColorPicker](https://github.com/iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift :star:103
* [KPActionSheet](https://github.com/khuong291/KPActionSheet) -  A replacement of default action sheet, but has very simple usage. :star:6
* [SegmentedProgressBar](https://github.com/D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :star:219
* [Magnetic](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). :star:825
* [AmazingBubbles](https://github.com/GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. :star:52
* [Haptica](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator. :star:247
* [GDCheckbox](https://github.com/saeid/GDCheckbox) - An easy to use custom checkbox/radio button component for iOS, with support of IBDesign Inspector. :star:9
* [HamsterUIKit](https://github.com/Howardw3/HamsterUIKit) - A simple and elegant UIKit(Chart) for iOS. :star:17
* [AZEmptyState](https://github.com/Minitour/AZEmptyState) - A UIControl subclass that makes it easy to create empty states. :star:74
* [URWeatherView](https://github.com/jegumhon/URWeatherView) - Show the weather effects onto view written in Swift3. :star:357
* [LCUIComponents](https://github.com/linhcn/LCUIComponents) - A framework supports creating transient views on top of other content onscreen such as popover with a data list. :star:5
* [ViewComposer](https://github.com/Sajjon/ViewComposer) - `let lbl: UILabel = [.text("Hello"), .textColor(.red)]` - Create views using array literal of enum expressing view attributes. :star:20
* [BatteryView](https://github.com/yonat/BatteryView) - Simple battery shaped UIView. :star:10
* [ShadowView](https://github.com/PierrePerrin/ShadowView) - Make shadows management easy on UIView :star:265
* [Pulley](https://github.com/52inc/Pulley) - A library to imitate the iOS 10 Maps UI :star:1147
* [N8iveKit](https://github.com/n8iveapps/N8iveKit) - A set of frameworks making iOS development more fun. :star:18
* [Panda](https://github.com/wordlessj/Panda) - Create view hierarchies declaratively. :star:20
* [NotchKit](https://github.com/HarshilShah/NotchKit) - A simple way to hide the notch on the iPhone X :star:1822
* [Overlay](https://github.com/TintPoint/Overlay) - Overlay is a flexible UI framework designed for Swift. It allows you to write CSS like Swift code. :star:47
* [SwiftyUI](https://github.com/haoking/SwiftyUI) - High performance and lightweight(one class each UI) UIView, UIImage, UIImageView, UIlabel, UIButton, Promise and more. :star:110
* [NotchToolkit](https://github.com/AFathi/NotchToolkit) - A framework for iOS that allow developers use the iPhone X notch in creative ways. :star:41
* [PullUpController](https://github.com/MarioIannotta/PullUpController) - Pull up controller with multiple sticky points like in iOS Maps. :star:562
* [DrawerKit](https://github.com/Babylonpartners/DrawerKit) - DrawerKit lets an UIViewController modally present another UIViewController in a manner similar to the way Apple's Maps app works. :star:513
* [Shades](https://github.com/aaronjsutton/Shades) - Easily add drop shadows, borders, and round corners to a UIView. :star:8
* [ISPageControl](https://github.com/Interactive-Studio/ISPageControl) - A page control similar to that used in Instagram. :star:169
* [Mixin](https://github.com/oney/Mixin) - React.js like Mixin. More powerful Protocol-Oriented Programming. :star:38
* [Shiny](https://github.com/efremidze/Shiny) - Iridescent Effect View (inspired by Apple Pay Cash). :star:550
* [StackViewController](https://github.com/seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :star:674
* [UberSignature](https://github.com/uber/UberSignature) - Provides an iOS view controller allowing a user to draw their signature with their finger in a realistic style. :star:465
* [SwViewCapture](https://github.com/startry/SwViewCapture) - A nice iOS View Capture Swift Library which can capture all content. :star:420
* [HGRippleRadarView](https://github.com/HamzaGhazouani/HGRippleRadarView) - A beautiful radar view to show nearby items (users, restaurants, ...) with ripple animation, fully customizable :star:128
* [GDGauge](https://github.com/saeid/GDGauge) - Full Customizable, Beautiful, Easy to use gauge view Edit. 🔶 :star:20


### Activity Indicator
* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :star:7075
* [TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator) - Rubber Indicator in Swift :star:1099
* [RPLoadingAnimation](https://github.com/naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :star:183
* [LiquidLoader](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation :star:1076
* [iOS-CircleProgressView](https://github.com/CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :star:416
* [iOS Circle Progress Bar](https://github.com/Eclair/CircleProgressBar) - iOS Circle Progress Bar :star:375
* [LinearProgressBar](https://github.com/PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :star:104
* [STLoadingGroup](https://github.com/saitjr/STLoadingGroup) - loading views :star:365
* [ALThreeCircleSpinner](https://github.com/AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :star:38
* [MHRadialProgressView](https://github.com/mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view. :star:81
* [Loader](https://github.com/Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :star:93
* [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. :star:14610
* [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app. :star:11034
* [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD. :star:1126
* [M13ProgressSuite](https://github.com/Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS. :star:3755
* [PKHUD](https://github.com/pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :star:2878
* [EZLoadingActivity](https://github.com/goktugyil/EZLoadingActivity) - Lightweight loading activity HUD. :star:539
* [FFCircularProgressView](https://github.com/elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view :star:1016
* [MRProgress](https://github.com/mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress :star:2604
* [BigBrother](https://github.com/marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :star:455
* [AlamofireNetworkActivityIndicator](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :star:505
* [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :star:730
* [DACircularProgress](https://github.com/danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties. :star:2309
* [KYNavigationProgress](https://github.com/ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. [e] :star:213
* [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :star:583
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module. :star:3886
* [MKRingProgressView](https://github.com/maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. :star:756
* [Hexacon](https://github.com/gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. :star:275
* [ParticlesLoadingView](https://github.com/BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :star:835
* [RPCircularProgress](https://github.com/iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :star:142
* [MBCircularProgressBar](https://github.com/MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable. :star:794
* [WSProgressHUD](https://github.com/devSC/WSProgressHUD) - This is a beautiful hud view for iPhone & iPad :star:559
* [DBMetaballLoading](https://github.com/dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :star:69
* [FillableLoaders](https://github.com/polqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :star:1877
* [VHUD](https://github.com/xxxAIRINxxx/VHUD) Simple HUD.
* [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :star:1744
* [SnapTimer](https://github.com/andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :star:259
* [LLSpinner](https://github.com/alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :star:12
* [SVUploader](https://github.com/kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy. :star:53
* [YLProgressBar](https://github.com/yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics. :star:1112
* [FlexibleSteppedProgressBar](https://github.com/amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar. :star:158
* [GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar. :star:139
* [DSGradientProgressView](https://github.com/DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :star:269
* [GradientProgressBar](https://github.com/fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :star:51
* [BPCircleActivityIndicator](https://github.com/ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :star:37
* [DottedProgressBar](https://github.com/nikola9core/DottedProgressBar) - Simple and customizable animated progress bar with dots for iOS. :star:23
* [RSLoadingView](https://github.com/roytornado/RSLoadingView) - Awesome loading animations using 3D engine written with Swift. :star:281
* [SendIndicator](https://github.com/LeonardoCardoso/SendIndicator) - Yet another task indicator :star:44
* [StepProgressView](https://github.com/yonat/StepProgressView) - Step-by-step progress view with labels and shapes. A good replacement for UIActivityIndicatorView and UIProgressView. :star:86
* [BPBlockActivityIndicator](https://github.com/ppth0608/BPBlockActivityIndicator) - A simple and awesome Loading Activity Indicator(with funny block animation) for your iOS app. :star:34
* [JustHUD](https://github.com/shubh10/JustHUD) - JustHUD is an iOS drop-in class written in Swift that displays a translucent HUD. :star:23
* [JDBreaksLoading](https://github.com/jamesdouble/JDBreaksLoading) - You can easily start up a little breaking game indicator by one line. :star:136
* [SkeletonView](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting. :star:5030
* [Windless](https://github.com/Interactive-Studio/Windless) - Windless makes it easy to implement invisible layout loading view. :star:681
* [Skeleton](https://github.com/gonzalonunez/Skeleton) - An easy way to create sliding CAGradientLayer animations! Works great for creating skeleton screens for loading content. :star:400
* [StatusBarOverlay](https://github.com/IdleHandsApps/StatusBarOverlay) - Automatically show/hide a "No Internet Connection" bar when your app loses/gains connection. It supports apps which hide the status bar and "The Notch" :star:56
* [RetroProgress](https://github.com/hyperoslo/RetroProgress) - Retro looking progress bar straight from the 90s. :star:34
* [LinearProgressBar](https://github.com/Recouse/LinearProgressBar) - Material Linear Progress Bar for your iOS apps. :star:21
* [MKProgress](https://github.com/kamirana4/MKProgress) - A lightweight ProgressHUD written in Swift. Looks similar to /MBProgressHUD/SVProgressHUD/KVNProgressHUD. :star:11
* [RHPlaceholder](https://github.com/robertherdzik/RHPlaceholder) - Simple library which give you possibility to add Facebook like loading state for your views. :star:71

### Animation
* [Pop](https://github.com/facebook/pop) - An extensible iOS and macOS animation library, useful for physics-based interactions. :star:19048
* [AnimationEngine](https://github.com/intuit/AnimationEngine) - Easily build advanced custom animations on iOS. :star:1048
* [RZTransitions](https://github.com/Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions. :star:1795
* [DCAnimationKit](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations. :star:758
* [Spring](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift. :star:12319
* [Canvas](https://github.com/CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io :star:5325
* [Fluent](https://github.com/matthewcheok/Fluent) - Swift animation made easy :star:306
* [Cheetah](https://github.com/suguru/Cheetah) - Easy animation library on iOS with Swift2. :star:576
* [RadialLayer](https://github.com/soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :star:55
* [Pop By Example](https://github.com/hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example. :star:182
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation](https://github.com/icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :star:2589
* [Animo](https://github.com/eure/Animo) - SpriteKit-like animation builders for CALayers. :star:204
* [CurryFire](https://github.com/devinross/curry-fire) - A framework for creating unique animations. :star:92
* [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :star:7439
* [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :star:1655
* [DaisyChain](https://github.com/alikaragoz/DaisyChain) - :link: Easy animation chaining :star:27
* [SYBlinkAnimationKit](https://github.com/shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :star:110
* [PulsingHalo](https://github.com/shu223/PulsingHalo) - iOS Component for creating a pulsing animation. :star:1678
* [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit) - Chainable animations in Swift :star:1835
* [JDAnimationKit](https://github.com/JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :star:590
* [Advance](https://github.com/timdonnelly/Advance) - A powerful animation framework for iOS. :star:4168
* [UIView-Shake](https://github.com/andreamazz/UIView-Shake) - UIView category that adds shake animation :star:487
* [Walker](https://github.com/RamonGilabert/Walker) - A new animation engine for your app. :star:150
* [Morgan](https://github.com/RamonGilabert/Morgan) - An animation set for your app. :star:97
* [MagicMove](https://github.com/patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :star:14
* [Shimmer](https://github.com/facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app. :star:8555
* [SAConfettiView](https://github.com/sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :star:1138
* [CCMRadarView](https://github.com/cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :star:181
* [Pulsator](https://github.com/shu223/Pulsator) - Pulse animation for iOS :star:906
* [Interpolate](https://github.com/marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :star:1591
* [ADPuzzleAnimation](https://github.com/Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :star:116
* [Wave](https://github.com/onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :star:80
* [Stellar](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift :star:2593
* [MotionMachine](https://github.com/poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :star:343
* [JRMFloatingAnimation](https://github.com/carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views. :star:185
* [AHKBendableView](https://github.com/fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :star:598
* [FlightAnimator](https://github.com/AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :star:575
* [ZoomTransitioning](https://github.com/WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :star:582
* [Ubergang](https://github.com/RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :star:49
* [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C :star:3118
* [Popsicle](https://github.com/DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :star:1131
* [WXWaveView](https://github.com/WelkinXie/WXWaveView) - Add a pretty water wave to your view. :star:323
* [Twinkle](https://github.com/piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :star:478
* [MotionBlur](https://github.com/fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations. :star:1514
* [RippleEffectView](https://github.com/alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :star:302
* [Keyframes](https://github.com/facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices. :star:4990
* [SwiftyAnimate](https://github.com/rchatham/SwiftyAnimate) - Composable animations in Swift. :star:170
* [SamuraiTransition](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collectio :star:219

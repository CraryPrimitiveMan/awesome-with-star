# Information comes from [JStumpp/awesome-android](https://github.com/JStumpp/awesome-android)
# Awesome Android
[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/master/awesome-android.png">](https://github.com/jstumpp/awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
  <a href="https://travis-ci.org/JStumpp/awesome-android"><img alt="Build Status" src="https://api.travis-ci.org/JStumpp/awesome-android.svg?branch=master" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

# About
A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java](https://github.com/akullpp/awesome-java).

## Supported with ❤️ by [Instabug](https://instabug.com/android/sdk?utm_source=toolsofthetrade&utm_medium=spon&utm_content=header)
### Understand How Your Android App is Doing with Real-Time Contextual Insights From Your Users
[![instabug-github](https://user-images.githubusercontent.com/10850625/65512691-fd45f280-ded9-11e9-8921-3528b98c30a7.png)](https://instabug.com/android/sdk?utm_source=awesomeandroid&utm_medium=spon&utm_content=banner)
>Instabug helps Android developers and product teams easily collect bugs and feedback from beta testers and users to iterate faster and ship quality apps. Instabug automatically attaches screenshots, device details, network logs, repro steps, and tons of other critical insights needed to resolve issues and prioritize product backlogs. 
> Mobile teams accelerate their workflows by seamlessly integrating with third-party tools like Github, Jira, Slack, Zendesk and much more. [Instabug is offering Awesome Android community an exclusive 15% discount on all paid plans. Get Started!](https://instabug.com/android/sdk/?utm_source=awesomeandroid&utm_medium=spon&utm_content=get-started)
[![](https://instabug-ga.appspot.com/UA-41982088-6/github/awesomeandroid?pixel)](https://instabug.com)


# How to Use
Awesome-Android is an amazing list for people who need a certain feature on their app, so the best ways to use are:
 - Simply press command + F to search for a keyword
 - Go through our Content Menu

# Content
- [Emulators](#emulators)
- [Libraries](#libraries)
    - [Charts](#charts)
    - [Cloud Services](#cloud-services)
    - [Dependency Injection](#dependency-injection)
    - [Android Services](#android-services)
    - [Game Development](#game-development)
	- [Security](#security)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
        - [Media Picker](#media-picker)
        - [Video](#video)
        - [Camera](#camera)
        - [Field Validation](#field-validation)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Logger](#logger)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Maps](#maps)
    - [Utility](#utility)
    - [Debugging tools](#debugging-tools)
    - [Wireless](#wireless)
    - [Chat and Messaging](#chat--messaging)
    - [Custom Dialog](#custom-dialog)
    - [Version Checking](#version-checking)
    - [Date & Time](#date--time)
    - [Runtime Permissions](#runtime-permissions)
    - [Other](#other)
- [Resources](#resources)
    - [Code examples](#code-examples)
    - [Podcasts](#podcasts)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
    - [Flutter](#flutter)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Emulators
- [AndY](https://andyroid.net)
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](https://www.bluestacks.com)
- [Genymotion](https://www.genymotion.com)
- [nox](https://www.bignox.com)

## Libraries

### Charts

- [AChartEngine](https://github.com/ddanny/achartengine) - Charting Engine. :star:682
- [EazeGraph](https://github.com/blackfizz/EazeGraph) - Chart and graph library. :star:1463
- [WilliamChart](https://github.com/diogobernardino/WilliamChart) - Chart library with good motion capabilities. :star:4236
- [HelloCharts](https://github.com/lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations. :star:6779
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture. :star:29110
- [ArcChartView](https://github.com/imaNNeoFighT/ArcChartView) - Draw Creative Statistic Arc Charts. :star:86
- [AnyChart](https://github.com/AnyChart/AnyChart-Android) - Data visualization library, Interactive charts. :star:956

### Cloud Services

- [CloudRail](https://cloudrail.com) - Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs.

### Data binding

- [Anvil](https://github.com/anvil-ui/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM. :star:1363
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [Dagger 2](https://github.com/google/dagger) - A fast dependency injector for Android and Java. :star:14435
- [Butter Knife](http://jakewharton.github.io/butterknife/) - View "injection" library for Android.
- [ActivityStarter](https://github.com/MarcinMoskala/ActivityStarter) - Android Library that provide simpler way to start the Activities with multiple arguments. :star:376
- [AndroidAnnotations](https://github.com/androidannotations/androidannotations) - Java annotations with dependency injection at compile time. :star:10942
- [Toothpick](https://github.com/stephanenicolas/toothpick) - A scope tree based Dependency Injection (DI) library for Java. :star:914

### Android Services
- [Remoter](https://github.com/josesamuel/remoter) - An alternative to Android AIDL for Android Remote IPC services using plain java interfaces. :star:36
- [Service Connector](https://github.com/josesamuel/serviceconnector) - Bind Android services and callbacks to fields and methods. :star:8

### Game Development

- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source](https://github.com/libGDX/libGDX) :star:16137
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](https://unity3d.com/unity/features/multiplatform) - Cross-platform game creation system.
- [Rajawali](https://github.com/Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine :star:1917
- [Cocos2d-x](https://cocos2d-x.org/) - Cross-platform 2d game framework.
- [JustWeEngine](https://github.com/lfkdsk/JustWeEngine) - An easy open source Android Native Game FrameWork. :star:743

### Security

- [libsignal-protocol-java](https://github.com/signalapp/libsignal-protocol-java) - A ratcheting forward secrecy protocol that works in synchronous and asynchronous messaging environments. :star:1034
- [Themis](https://github.com/cossacklabs/themis) - Multi-language framework for making typical encryption schemes easy to use: data at rest, authenticated data exchange, transport protection, authentication, and so on. :star:891

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout) - A swipe refresh layout is available in the v4 support library.
- [Cardslib](https://github.com/gabrielemariotti/cardslib) - Android Library to build a UI Card. :star:4786
- [AndroidStaggeredGrid](https://github.com/etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes. :star:4782
- [Flow](https://github.com/square/flow) - Library that helps with describing an app as a collection of moderately independent screens. :star:2785
- [SortableTableView](https://github.com/ISchwarz23/SortableTableView) - An Android library containing a simple TableView and an advanced SortableTableView providing a lot of customisation possibilities to fit all needs. :star:968
- [MaterialProgressBar](https://github.com/zhanghai/MaterialProgressBar) - Material design ProgressBar with consistent appearance. :star:1937
- [AndroidFillableLoaders](https://github.com/JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos. :star:1901
- [NexusDialog](https://github.com/dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code. :star:182
- [Snap RecyclerView Utils](https://github.com/prashantsolanki3/Snap-RecyclerView-Utils) - Populate Single or multiple Layout RecyclerView without creating an Adapter. :star:74
- [MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView) - Android library for multiple snapping of RecyclerView :star:1883
- [SwipeableCard](https://github.com/michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView!! :star:783
- [ElasticProgressBar](https://github.com/michelelacorte/ElasticProgressBar) - Beautiful loading bar. :star:306
- [EntryScreenManager](https://github.com/kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens. :star:40
- [EasyIntro](https://github.com/meNESS/EasyIntro) - The flexible, easy to use, all in one app intro library for your Android project. :star:91
- [Material-Calendar-View](https://github.com/BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+ :star:354
- [CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar) - A material calendar widget with infinite scrolling, date range selection and color customization. :star:419
- [SmoothOverscrollableScrollView](https://github.com/vovaksenov99/OverscrollableScrollView) - Small custom view with smooth overscroll. You can add header with scale background :star:14
- [SectionedRecyclerViewAdapter](https://github.com/luizgrp/SectionedRecyclerViewAdapter) - An Adapter that allows a RecyclerView to be split into Sections with headers and/or footers. :star:1402
- [DragListView](https://github.com/woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board. :star:518
- [Animated Expanding ListView](https://github.com/LeonardoCardoso/Animated-Expanding-ListView) - Animated Expanding ListView provides a fancy animation on expanding or collapsing the content of a listview item. :star:128
- [TastyToast](https://github.com/yadav-rahul/TastyToast) - Toasts with icons and color. :star:1963
- [DotLoader](https://github.com/bhargavms/DotLoader) - A customizable loading animation with Dots. :star:127
- [PodSlider](https://github.com/bhargavms/PodSLider) - A customizable slider widget adhering to material design specs. :star:125
- [TapTargetView](https://github.com/KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery. :star:4654
- [ShowCaseView](https://github.com/mreram/ShowCaseView) - The ShowcaseView library is designed to highlight and showcase specific parts of apps to the user with a attractive and flat overlay. :star:173
- [MaterialIntroScreen](https://github.com/TangoAgency/material-intro-screen) - Material Intro Screen implementation with easily extensible API. :star:2594
- [FloatingView](https://github.com/UFreedom/FloatingView) - FloatingView can make the target view floating above the anchor view with cool animation. :star:1731
- [Timecon](https://github.com/alxrm/animated-clock-icon) - Easy-to-use animated clock icon :star:221
- [Audiogram](https://github.com/alxrm/audiowave-progressbar) - Lightweight audiowave progressbar :star:292
- [Bubbles for Android](https://github.com/txusballesteros/bubbles-for-android) - Facebook like chat bubble library :star:1406
- [Litho (By Facebook)](https://github.com/facebook/litho) - A declarative framework for building efficient UIs on Android. :star:6397
- [MultiViewAdapter](https://github.com/DevAhamed/MultiViewAdapter) - Recyclerview Adapter library to create composable view holders. :star:655
- [LGSnackbar](https://github.com/loregr/LGSnackbar) - An easy to use and customisable wrapper of the native Android Snackbar which stays visible across multiple activities. :star:47
- [ShimmerLayout](https://github.com/team-supercharge/ShimmerLayout) - Memory efficient shimmering effect for Android applications. :star:2154
- [CircleProgressBar](https://github.com/emre1512/CircleProgressBar) - A simple library for creating circular progressbars for Android. :star:55
- [Easy-Signature-Android](https://github.com/smalam119/Easy-Signature-Android) - An simple ui library that provides a plugable signature view. :star:23
- [Flashbar](https://github.com/aritraroy/Flashbar) - A highly customizable, powerful and easy-to-use alerting library for Android. :star:1571
- [YuanaItemSettingView](https://github.com/andhikayuana/YuanaItemSettingView) - Customizable Item Setting View for Android. :star:9
- [Gradients](https://github.com/bakhtiyork/gradients) - A curated collection of splendid gradients. :star:37
- [OneAdapter](https://github.com/ironSource/OneAdapter) - RecyclerView Adapter with multiple modules and hooks to simplify and enhance the use while preventing common mistakes. :star:155

#### Paginate
- [NoPaginate](https://github.com/NoNews/NoPaginate) - Simple Android pagination library :star:164

#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [FadingActionBar](https://github.com/ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app. :star:2930

#### Navigation
- [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus. :star:11206
- [SlidingTutorial](https://github.com/Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials. :star:2471
- [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager. :star:47
- [Page View indicator](https://github.com/JakeWharton/ViewPagerIndicator) - Support for horizontally scrolling ViewPager. :star:10184
- [RecyclerTabLayout](https://github.com/nshmura/RecyclerTabLayout) - An efficient TabLayout library implemented with RecyclerView. :star:1258
- [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer. :star:10719
- [Debug-Artist](https://github.com/BaristaVentures/android-debug-artist) - Debug menu to enable leakcanary, scalpel and others easy. :star:49
- [Floating-Navigation-View](https://github.com/andremion/Floating-Navigation-View) - A simple Floating Action Button that shows an anchored Navigation View. :star:1054

#### Animations
- [Rebound](https://github.com/facebook/rebound) - Rebound is a Java library that models spring dynamics. :star:5410
- [Android View Animations](https://github.com/daimajia/AndroidViewAnimations) - Cute view animation collection. :star:10976
- [Android-Transition](https://github.com/kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs. :star:607
- [Android-View-Actions](https://github.com/dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy. :star:133
- [Swipper](https://github.com/mdg-iitr/Swipper) - Android library for swipeable gestures to control volume , brightness and seek . :star:76
- [Spotlight](https://github.com/TakuSemba/Spotlight) - Android Library that lights items for tutorials or walk-throughs etc... :star:2285

#### Images

- [Crescento](https://github.com/developer-shivam/crescento) - Explore new style in material design by adding curve below image view. :star:1274
- [android-crop](https://github.com/jdamcd/android-crop) - Library project for cropping images. :star:4412
- [CircularImageView](https://github.com/Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance. :star:1198
- [Android-Image-Filter](https://github.com/ragnraok/android-image-filter) - Library project for applying image filters easily. :star:608
- [Compressor](https://github.com/zetbaitsu/Compressor) - Compressor is a lightweight and powerful android image compression library. :star:4807
- [ShapeImageView](https://github.com/siyamed/android-shape-imageview) - Library to display images in different shapes. :star:2486

#### Inputs

- [FloatingLabel](https://github.com/hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.* :star:270
- [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors. :star:5902
- [EmojiCompat](https://github.com/googlearchive/android-EmojiCompat) - Adds emoticons to your app :star:690
- [MaterialSearchBar](https://github.com/mancj/MaterialSearchBar) - Material Design Search Bar for Android :star:1765
- [InputMask](https://github.com/RedMadRobot/input-mask-android) - Pattern-based user input formatter, parser and validator. :star:904
- [SweetPassword](https://github.com/jesusmartinoza/Sweet-Password) - Password EditText that allows to custom toggle button :star:17
- [VoiceOverlay](https://github.com/algolia/voice-overlay-android) - An overlay that gets your user’s voice permission and input as text in a customizable UI. :star:162

#### View Pagers
- [Material Dots Indicators](https://github.com/tommybuonomo/dotsindicator) - Three Material Dots Indicators styles for View Pagers. :star:1493

#### Loading Images

- [Picasso](https://github.com/square/picasso) - A powerful image downloading and caching library for Android. :star:17149
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images. :star:16629
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google. :star:27675
- [Fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use. :star:15932
- [Glide Bitmap Pool](https://github.com/amitshekhariitbhu/GlideBitmapPool) - Glide Bitmap Pool is a memory management library for reusing the bitmap memory. :star:511
- [Coil](https://github.com/coil-kt/coil) - Image loading for Android backed by Kotlin Coroutines. :star:2323

#### Media Picker

- [MediaPicker](https://github.com/alhazmy13/MediaPicker) - Android Library that lets you to select multiple images, video or voice for Android :star:212
- [Android Image Picker](https://github.com/esafirm/android-image-picker) - A library that makes images and videos selection from gallery feels easy. It also support GIF and simple camera action :star:606

#### Video

- [ijkplayer](https://github.com/Bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.2, with MediaCodec, VideoToolbox support. :star:25085
- [Exoplayer](https://github.com/google/ExoPlayer) - ExoPlayer is an application level media player for Android, allow  playing audio and video both locally and over the Internet. :star:14360
   Supports features like Dynamic adaptive streaming over HTTP (DASH), SmoothStreaming and Common Encryption
- [VideoPlayView](https://github.com/MarcinMoskala/VideoPlayView) - Custom Android view with video player, play/stop, loader and placeholder image. :star:83

#### Camera

- [MagicalCamera](https://github.com/fabian7593/MagicalCamera) - Simple way to take or select photos of your gallery, with other features for manage pictures. :star:310
- [Camera](https://github.com/duanhong169/Camera) - Use Android camera to take pictures and videos, based on camera2 api. :star:92

#### Field Validation
- [Convalida](https://github.com/WellingtonCosta/convalida) - A simple and annotation-based way to validate your input fields. :star:195

### JSON

- [Gson](https://github.com/google/gson) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON. :star:16834
- [Jackson JSON Processor](https://github.com/FasterXML/jackson) - High-performance JSON processor. :star:5109
- [Moshi](https://github.com/square/moshi) - A modern JSON library for Android and Java. :star:5636
### Crash monitoring

- [Fabric Crashlytics](https://get.fabric.io/) - Easy crash reporting solution.
- [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real time data, Statistic.
- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data.
- [Catcho](https://github.com/alhazmy13/Catcho) - No Force Close any more. :star:37
- [Apteligent](https://www.apteligent.com/) - Cross platform crash reporting/analytics solution. Supports NDK log.
- [Instabug](https://instabug.com/) - Bug reporting, Crash Reporting, In-app Feedback.

### Networking

- [Ion](https://github.com/koush/ion) - Good networking library for android. :star:6068
- [OkHttp](https://github.com/square/okhttp) - An HTTP+SPDY client for Android and Java applications. :star:34994
- [RoboSpice](https://github.com/stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy. :star:3032
- [IceNet](https://github.com/anton46/IceNet) - Fast, Simple and Easy Networking for Android :star:61
- [Android Volley](https://developer.android.com/training/volley/) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap](https://github.com/AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android. :star:78
- [node-android](https://github.com/InstantWebP2P/node-android) - Run Node.js on Android. :star:562
- [HappyDns](https://github.com/qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record. :star:200
- [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests. :star:710
- [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2. :star:4643

### Logger
- [logger](https://github.com/orhanobut/logger) - Simple, pretty and powerful logger for android :star:11848
- [timber](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class. :star:7526
- [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data. :star:1004
- [Bugfender](https://github.com/bugfender/BugfenderSDK-android-sample) - Upload your logs and check them online, specially made for mobile :star:26
- [EzyLogger](https://github.com/afiqiqmal/EzyLogger) - Simple Lightweight logger :star:7
- [Logback Android](https://github.com/tony19/logback-android) - Logback port to Android which provides a highly configurable logging framework for Android apps. :star:823

### Notifications
- [android-remote-notifications](https://github.com/kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app. :star:87
- [Android HeartBeat Fixer](https://github.com/joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM. :star:55

### Database
- [Cupboard](https://bitbucket.org/littlerobots/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector](https://github.com/infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes. :star:836
- [SQLite Asset Helper](https://github.com/jgilfelt/android-sqlite-asset-helper) - manage database creation and version management using an application's raw asset files. :star:2104
- [Realm](https://github.com/realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support. :star:10734
- [Realm Asset Helper](https://github.com/eggheadgames/android-realm-asset-helper) - Copies a realm database from the apk assets folder. Efficiently handles versioning of read-only realm databases. :star:30
- [RestorableSQLiteDatabase](https://github.com/yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability. :star:17
- [Nitrite Database](https://github.com/dizitart/nitrite-database) - A NoSQL embedded document store for Android with MongoDb like API. :star:393

#### ORM

- [requery](https://github.com/requery/requery) - Compile time ORM and SQL query library for Java & Android. :star:2902
- [GreenDAO](http://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow](https://github.com/agrosner/DBFlow) - Fast and powerful ORM with compile-time annotation processing. :star:4711
- [NexusData](https://github.com/dkharrat/NexusData) - Object graph and persistence framework for Android. :star:71
- [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code. :star:398
- [RxSimpleNoSQL](https://github.com/xmartlabs/RxSimpleNoSQL) - Reactive extensions for SimpleNoSQL. Manipulate entities using Observables. :star:41

### REST

- [Retrofit](https://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.
- [Spring for Android - Rest Template](https://github.com/spring-projects/spring-android) - A Rest Client for Android. :star:704

### Testing

- [Robotium](https://github.com/robotiumtech/robotium) - Test automation framework for black-box UI tests. :star:2602
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android](https://github.com/square/assertj-android) - AssertJ assertions geared towards Android. :star:1593
- [Green Coffee](https://github.com/mauriciotogneri/green-coffee) - Run your Cucumber tests in your Android instrumentation tests. :star:211

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events

### Maps

- [Google-Directions-Android](https://github.com/jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API. :star:923
- [Android Maps Extensions](https://github.com/mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things :star:399
- [MapScaleView](https://github.com/pengrad/MapScaleView) - Scale bar for Google Maps Android API :star:88
- [GLMap](https://globus.software) - Crossplatform offline vector map with MapCSS styling. Offline search and offline navigation are included.

### Utility
- [Conceal SharedPreferences](https://github.com/afiqiqmal/SharedChamber) - Secured Preferences using Facebook Secure Encryption called Conceal. :star:89
- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto](https://github.com/square/otto) - Event Bus for Android. :star:5226
- [Weak handler](https://github.com/badoo/android-weak-handler) - Memory safer implementation of android.os.Handler. :star:1426
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager](https://github.com/prashantsolanki3/Secure-Pref-Manager) - Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences. :star:73
- [LeakCanary](https://github.com/square/leakcanary) - Catch memory leaks as they occur. :star:23922
- [Drekkar](https://github.com/coshx/drekkar) - An Android event bus for WebView and JS. :star:23
- [Androl4b](https://github.com/sh4hin/Androl4b) - A vm for assessing android applications. :star:782
- [DroidMVP](https://github.com/andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app. :star:230
- [EasyDeviceInfo](https://github.com/nisrulz/easydeviceinfo) - Get device information in a super easy way. :star:1549
- [Shutter-Android](https://github.com/levibostian/Shutter-Android) - Capture photos/videos from device camera or get photos/video from gallery app with no runtime permissions needed. :star:44
- [Validator](https://github.com/anderscheow/Validator) - An utilities class to validate text inside TextInputLayout. :star:74
- [Keyboard Visibility Event](https://github.com/viniciusmo/keyboard-visibility-event-android/) - A DSL to handle soft keyboard visibility change event. :star:9
- [TimeIt](https://github.com/yashovardhan99/timeit) - A stopwatch library for android which makes it easy to start, pause, display and maintain multiple stopwatches in an app. :star:26
- [Reactor](https://github.com/oky2abbas/reactor) - Reactor is a fast and secure key-value library for Android. :star:26
 
### Debugging Tools

- [Linx](https://github.com/pedrovgs/Lynx) - Show logcat inside the device for debug builds :star:692
- [Scalpel](https://github.com/JakeWharton/scalpel) - View the entire hierarchy in 3d in the phone. :star:2728
- [Stetho](https://github.com/facebook/stetho) - Debug hierarchy and network from chrome. :star:11562
- [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database) - Android Debug Database is a powerful library for debugging databases and shared preferences in Android applications. :star:6641
- [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md) - a command-line tool to assist in debugging Android-powered devices :star:6472
- [ADB Enhanced](https://github.com/ashishb/adb-enhanced) - a command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands :star:593
- [Pidcat](https://github.com/JakeWharton/pidcat) - a colored command-line ADB wrapper that only shows log entries for a specific application package :star:4021
- [AppSpector](https://appspector.com) - Remote Android and iOS debugging and data collection service. You can debug networking, logs, SQLite and mock device's geo location.


### Wireless

- [SmartGattLib](https://github.com/movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0). :star:256

### Chat & Messaging

- [Applozic Android Chat SDK](https://github.com/AppLozic/Applozic-Android-SDK) - Android Chat and Messaging SDK for adding real time chat and in-app messaging into your android application. :star:559
- [Qiscus SDK](https://github.com/qiscus/qiscus-sdk-android) - Qiscus SDK is a lightweight and powerful android chat library. Qiscus SDK will allow you to easily integrating Qiscus engine with your apps to make cool chatting application. :star:157
- [Kommunicate Live Chat SDK](https://github.com/Kommunicate-io/Kommunicate-Android-Chat-SDK) - Kommunicate provides open source live chat sdk in android. Kommunicate lets you add real time live chat and in-app messaging in your mobile (android, iOS) applications and website for customer support. :star:41
- [CometChat Voice, Video and Text Chat SDK with UI](https://github.com/cometchat-go/android-chat-sdk-demo) - Add voice, video and text chat to your app (and website) in minutes using CometChat. CometChat's SDK includes a complete ready UI so that you don't have to spend any time building one! That's not all, CometChat has out-of-the-box support for real-time translation, whiteboards, screen sharing, friends sync, role based access control, credits deduction and more. :star:1
- [Build a one-on-one Android chat app using Kotlin](https://www.cometchat.com/tutorials/build-one-on-one-chat-in-your-android-app-using-kotlin/) - Build a one-one-one Android chat app in Kotlin within few minutes using CometChat Pro. This tutorial discusses the features such as login, getting list of contacts, user presence indicators, sending/receiving messages etc.
- [Stream Chat](https://getstream.io/tutorials/android-chat/) - Comprehensive SDK & Components for real-time chat, powered by [Stream](https://getstream.io/chat/).
- [Add Push Notifications to Your Android Chat App Using Kotlin](https://www.cometchat.com/tutorials/android-chat-push-notifications/) - Add push notifications in your Android chat apps in Kotlin with the help of CometChat Pro and Firebase Cloud Messaging (FCM).

#### Custom Dialog

- [MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog) - Custom Dialog to record audio, store it and play it in your phone. :star:68
- [HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker) - offers a hijri (Islamic Calendar) Date Picker designed on Google's Material Design Principals For Pickers. :star:90
- [Noty](https://github.com/emre1512/Noty) - A simple library for creating animated alerts/dialogs/warnings. :star:108

### Version Checking

 - [AppUpdater](https://github.com/javiersantos/AppUpdater) - comprehensive and feature rich library, including support for checks at Amazon and FDroid. :star:1493
 - [Gandalf](https://github.com/btkelly/gandalf) - comprehensive features and a "companion" iOS solution. :star:287
 - [Siren](https://github.com/eggheadgames/Siren) - focused feature set that mimicks the popular iOS library of the same name. Supports Play and Amazon. :star:117
 - [Fit](https://github.com/KeithYokoma/Fit) - version checking callback framework with no UI. :star:57

### Date & Time

- [ThreeTen Android Backport](https://github.com/JakeWharton/ThreeTenABP) - An adaptation of the JSR-310 backport for Android. :star:3072
- [Joda-Time Android](https://github.com/dlew/joda-time-android) - Joda-Time library with Android specialization. :star:2441
- [True Time](https://github.com/instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes. :star:967

### Runtime Permissions

- [Permission Dispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher) - Simple annotation-based API to handle runtime permissions. :star:9546
- [RxPermissions](https://github.com/tbruyelle/RxPermissions) - Android runtime permissions powered by RxJava. :star:9164
- [NoPermission](https://github.com/NoNews/NoPermission) - Simple Android library for permissions request. Consists of only one class. :star:100
- [Ask-Permission](https://github.com/Kishanjvaghela/Ask-Permission) - Simple RunTime permission manager. :star:72
- [Gota](https://github.com/alhazmy13/Gota) - Simplifying Android Permissions. :star:71
- [EasyPermissions](https://github.com/googlesamples/easypermissions) - EasyPermissions is a wrapper library to simplify basic system permissions logic when targeting Android M or higher. :star:8009

### Payments

- [Square In-App Payments for Android](https://developer.squareup.com/docs/in-app-payments-sdk/build-on-android) - Integrate Square payments into your mobile app with Digital wallet and stored card support for quick checkout.

### Other

- [Android Support library](https://developer.android.com/topic/libraries/support-library/) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape](https://github.com/square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java. :star:2332
- [Guava: Google Core Libraries for Java](https://github.com/google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth. :star:34615
- [Android Scripting](https://github.com/damonkohler/sl4a) - Allows to run scripting languages on Android. :star:1975
- [Android Priority Job Queue](https://github.com/yigit/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability. :star:3363
- [RateMeMaybe](https://github.com/nspo/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application. :star:98
- [Easy Rating Dialog](https://github.com/fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app. :star:111
- [ZXing Android-Integration](https://github.com/zxing/zxing) - Integration with Barcode Scanner via Intent. :star:24112
- [Gradle Retrolambda Plugin](https://github.com/evant/gradle-retrolambda) - Java 8 Lambdas on Android! :star:5394
- [RxJava](https://github.com/ReactiveX/RxJava)- RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Adds minimum RxJava bindings for easy writing of reactive Android java code. :star:18619
- [RxBinding](https://github.com/JakeWharton/RxBinding)- RxBinding – RxJava binding APIs for Android UI widgets from the platform and support libraries.
- [Caffeine](https://github.com/percolate/caffeine) - A collection of utility classes that help make Android development faster. :star:422
- [AboutLibraries](https://github.com/mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries. :star:2374
- [AudioPlayerView](https://github.com/HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools. :star:83
- [andle](https://github.com/Jintin/andle) - command line tool help you sync dependencies, sdk or build tool version. :star:54
- [Typography](https://github.com/workarounds/typography) - An Android library that makes it easy to use custom fonts in views. :star:40
- [Calligraphy](https://github.com/chrisjenx/Calligraphy) - Custom fonts in Android an OK way. :star:8446
- [transai](https://github.com/Jintin/transai) - command line tool help you manage localization string files. :star:57
- [Android-Link-Preview](https://github.com/LeonardoCardoso/Android-Link-Preview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. :star:386
- [Sensey](https://github.com/nisrulz/sensey) - Detecting gestures in a snap. :star:2494
- [UserAwareVideoView](https://github.com/kevalpatel2106/UserAwareVideoView) - A customized video view that will automatically pause video is user is not looking at device screen! :star:53
- [Flexbox Layout](https://github.com/google/flexbox-layout) - FlexboxLayout is a library which brings the similar capabilities of CSS Flexible Box Layout Module to Android.  :star:14791
- [Agile Boiler Plate](https://github.com/xresco/Android-Agile-Boiler-Plate) - The boiler plate is based on MVP architecture and it is fully based on Dependency Injection design pattern using Dagger2. :star:45
- [Gradle buildSrcVersions](https://github.com/jmfayard/buildSrcVersions) - A kotlin dsl to simplify dependencies management :star:416
- [Teller](https://github.com/levibostian/Teller-Android/) - Teller facilitates the downloading, saving, and reading of the cached data of your app. Keep your user's data fresh and remove those annoying loading screens! :star:12

## Resources

- [Programming Community Curated Resources for Learning Android Development](https://hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
- [Vogella Tutorials](https://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler Chet Hasae and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](https://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](https://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
- [Android UI design resources](https://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project](https://pencil.evolus.vn/) - An open source prototyping software.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs](https://github.com/vbauer/android-blogs) - List with blogs about Android. :star:477
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Picasso, Glide & Gson.
- [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development. :star:4015
- [Associate Android Developer Certification Materials](https://github.com/Amejia481/Associate-Android-Developer-Certification) - A collection of materials for getting ready for the test. :star:888
- [Google Developers Training](https://developer.android.com/courses/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.
- [Mindorks](https://mindorks.com/) - Become a complete and happy Android developer.
- [AndroidVille](https://ayusch.com/) - Become a better Android Engineer. A website dedicated to Android Development covering advanced topics such as RxJava, Android Zygote and much more.

### Code examples
- [Android Architecture Blueprints](https://github.com/android/architecture-samples) - The Android Architecture Blueprints project demonstrates strategies to help solve or avoid common android problems. :star:34797
- [Kotlin MVVM example](https://github.com/emedinaa/kotlin-mvvm) - Example about MVVM (Model View ViewModel) Pattern. :star:80
- [Kotlin VIPER example](https://github.com/OmiSoftNet/AndroidViperTemplate) - Example about VIPER (View Interactor Presenter Entity Router) Pattern. :star:5
- [Complete-Google-Map-API-Tutorial](https://github.com/mohammadima3oud/Complete-Google-Map-API-Tutorial) - Learn How to use Google Map API for Android from Basic to Advance with complete examples. :star:23

### Podcasts
- [Fragmented](https://fragmentedpodcast.com/) is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](http://androidbackstage.blogspot.com/) is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [The Context](https://github.com/artem-zinnatullin/TheContext-Podcast) a podcast about Android Development with Hannes Dorfmann, Artem Zinnatullin and wonderful guests!
- [Talking Kotlin](https://talkingkotlin.com/) - A Podcast on Kotlin and more.
- [Android Authority](https://www.androidauthority.com/podcast/) is a weekly Android podcast hosted by Adam Doud, Joe Hindy, and Jonathan Feist from the Android Authority team.
- [Android Central](https://www.androidcentral.com/podcast) - is a weekly Android podcast hosted by the Android Central team.

### More lists of libraries
- [The Android Arsenal](https://android-arsenal.com/) - Large list of android libraries
- [Square libraries](https://square.github.io/) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.
- [Android Store](https://mindorks.com/android/store) - Search Android Libraries, Projects, and Tools.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code but it adds to many methods (Multidex required). Kotlin is a modern language with 100% interoperatibility with java projects **without multidex**. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](https://visualstudio.microsoft.com/xamarin/) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](https://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/mobile-app-development-products/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native](https://github.com/facebook/react-native) - A framework for building native apps with React by Facebook. :star:82650
- [Ionic Framework](https://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova](https://github.com/apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript. :star:2803
- [Capacitor](https://github.com/ionic-team/capacitor) - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative.  :star:3314

### Lua
- [Corona SDK](https://coronalabs.com/product/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scaloid](https://github.com/pocorall/scaloid) - Library for less painful Android development with Scala. :star:2117
- [Macroid](https://github.com/47deg/macroid) - A modular functional UI language for Android. :star:539

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android](https://github.com/groovy/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android. :star:831
- [SwissKnife](https://github.com/Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations. :star:253

### Kotlin
- [Anko](https://github.com/Kotlin/anko) - DSL for Android written in Kotlin by JetBrains. :star:15364
- [Kotterknife](https://github.com/JakeWharton/kotterknife) - Android view injection written in Kotlin based on ButterKnife :star:2255
- [Android Kotlin Samples](https://github.com/irontec/android-kotlin-samples) - Some basic Android code samples written in Kotlin. :star:272
- [Kotlin coding puzzles](https://github.com/igorwojda/kotlin-coding-puzzle) - Set of programming challenges thats helps to improve whiteboard coding and problem-solving skills. :star:192
- [KAndroid](https://github.com/pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK. :star:851
- [RxKotlin/Pocket](https://github.com/RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly. :star:25
- [Android Clean Architecture - Kotlin](https://github.com/patrickyin/clean-architecture-android-kotlin) - A base project using the Uncle Bob's clean architecture with Kotlin language and the latest Android technologies. :star:292
- [Koin](https://insert-koin.io/) - Lightweight dependency injection framework for Kotlin

### Flutter
- [Flutter](https://flutter.dev/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.

# Performance
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization. :star:2553
- [Booster](https://github.com/didi/booster) - Booster is an optimization toolkit for Android applications. :star:2278

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.


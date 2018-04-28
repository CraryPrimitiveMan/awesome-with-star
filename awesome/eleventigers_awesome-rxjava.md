# Information comes from [eleventigers/awesome-rxjava](https://github.com/eleventigers/awesome-rxjava)
# Awesome RxJava [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="http://reactivex.io/assets/Rx_Logo_S.png" align="right" width="100">](http://reactivex.io/)

> Useful resources for working with [RxJava](https://github.com/ReactiveX/RxJava)

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

## Bindings

* [RxAndroid](https://github.com/ReactiveX/RxAndroid) - Android specific bindings for RxJava. :star:15739
* [RxBinding](https://github.com/JakeWharton/RxBinding) - RxJava binding APIs for Android UI widgets from the platform and support libraries. :star:7357
* [rx-preferences](https://github.com/f2prateek/rx-preferences) - Reactive `SharedPreferences` for Android. :star:1340
* [RxPermissions](https://github.com/tbruyelle/RxPermissions) - Android M runtime permissions powered by RxJava. :star:6095
* [SQLBrite](https://github.com/square/sqlbrite) - A lightweight wrapper around SQLiteOpenHelper and ContentResolver which introduces reactive stream semantics to queries. :star:4604
* [Android-ReactiveLocation](https://github.com/mcharmas/Android-ReactiveLocation) - Small library that wraps Google Play Service API in brilliant RxJava Observables reducing boilerplate to minimum. :star:1972
* [ReactiveNetwork](https://github.com/pwittchen/ReactiveNetwork) - Android library listening network connection state and change of the WiFi signal strength with RxJava Observables. :star:1795
* [ReactiveSensors](https://github.com/pwittchen/ReactiveSensors) - Android library monitoring hardware sensors with RxJava Observables. :star:124
* [RxPalette](https://github.com/hzsweers/RxPalette) - RxJava bindings for the Palette library on Android. :star:195
* [rxjava-jdbc](https://github.com/davidmoten/rxjava-jdbc) - Efficient execution and functional composition of database calls using jdbc and RxJava Observables. :star:668
* [rxjava-file](https://github.com/davidmoten/rxjava-file) - RxJava observables for files including NIO events. :star:69
* [RxTuples](https://github.com/pakoito/RxTuples) - Simple tuples to use with RxJava. :star:116
* [RxAnimationBinding](https://github.com/blipinsk/RxAnimationBinding) - RxJava binding APIs for Android's animations. :star:80

## Utilities
* [RxJavaAsyncUtil](https://github.com/ReactiveX/RxJavaAsyncUtil) - Async utilities for RxJava. :star:120
* [RxJavaJoins](https://github.com/ReactiveX/RxJavaJoins) - Joins operators for RxJava. :star:92
* [RxJavaMath](https://github.com/ReactiveX/RxJavaMath) - Math operators for RxJava. :star:94
* [RxJavaString](https://github.com/ReactiveX/RxJavaString) - 
String and Byte operators for RxJava.
* [RxJavaComputationExpressions](https://github.com/ReactiveX/RxJavaComputationExpressions) - Computation expressions for RxJava. :star:59
* [rxjava-extras](https://github.com/davidmoten/rxjava-extras) - Utilities for use with RxJava. :star:250
* [RxActions](https://github.com/pakoito/RxActions) - Simple ActionN composition to use with RxJava. :star:35
* [RxRelay](https://github.com/JakeWharton/RxRelay) - RxJava types that are both an Observable and an Action1. :star:1762
* [Frodo](https://github.com/android10/frodo) - Android Library for Logging RxJava Observables and Subscribers. :star:1403
* [RxPartialApplication](https://github.com/pakoito/RxPartialApplication) - Simple partial application for FuncN and ActionN on RxJava. :star:33
* [RxCurrying](https://github.com/pakoito/RxCurrying) - Simple currying for FuncN and ActionN on RxJava. :star:39
* [RxEither](https://github.com/eleventigers/rxeither) - Either type for RxJava. :star:82
* [RxReplayingShare](https://github.com/JakeWharton/RxReplayingShare) - An RxJava transformer which combines replay(1), publish(), and refCount() operators. :star:494
* [RxFunctions](https://github.com/pakoito/RxFunctions) - Advanced Function composition to use with RxJava. :star:52
* [rxlint](https://bitbucket.org/littlerobots/rxlint) - An Android lint rule for RxJava code.
* [RxComprehensions](https://github.com/pakoito/RxComprehensions) - Reduce boilerplate in RxJava by abstracting chained flatMaps, concatMaps and switchMaps. :star:80

## Testing
* [assertj-rx](https://github.com/ribot/assertj-rx) - AssertJ assertions for RxJava Observables. :star:128
* [rxpresso](https://github.com/novoda/rxpresso) - Easy Espresso UI testing for Android applications using RxJava. :star:377

## Guides

* [RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples) - Learning RxJava for Android by example. :star:6430
* [Intro-To-RxJava](https://github.com/Froussios/Intro-To-RxJava) - An extensive tutorial on RxJava. :star:1637

## Articles

* [Rx glitches aren't actually a problem](http://staltz.com/rx-glitches-arent-actually-a-problem.html) - Glitches are temporary inconsistencies emitted by Observables. André Staltz looks at why it's not really a problem.
* [RxJava's repeatWhen and retryWhen, explained](http://blog.danlew.net/2016/01/25/rxjavas-repeatwhen-and-retrywhen-explained/) - `repeatWhen` and `retryWhen` are fairly baffling at first glance. Dan Lew explains the operators in depth.
* [RxJava - The Problem with Subjects](http://tomstechnicalblog.blogspot.co.uk/2016/03/rxjava-problem-with-subjects.html) - Thomas Nield explains why `Subject` is not a panacea.
* [Using RxJava Observable's Completion Semantics for Greater Good](https://adelnizamutdinov.github.io/blog/2015/01/23/using-rxjavas-observable-semantics-for-greater-good/) - Adel Nizamutdinov talks about `Observable`’s completion semantics and `Subscriber.add(Subscription)` method.

## Tools

* [RxMarbles](http://rxmarbles.com/) - Interactive diagrams of Rx Observables.

## Community

* [Google Group](http://groups.google.com/d/forum/rxjava)
* [StackOverflow](http://stackoverflow.com/search?q=rx-java)
* [`@RxJava` on Twitter](http://twitter.com/RxJava)
* [`ReactiveX/RxJava` on Gitter](https://gitter.im/ReactiveX/RxJava)
* [GitHub Issues](https://github.com/ReactiveX/RxJava/issues)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jokubas Dargis](http://jokubasdargis.net/) has waived all copyright and related or neighboring rights to this work.


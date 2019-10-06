# Information comes from [transitive-bullshit/awesome-ffmpeg](https://github.com/transitive-bullshit/awesome-ffmpeg)
# Awesome FFmpeg [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> [FFmpeg](http://ffmpeg.org) is a cross-platform solution to record, convert and stream audio and video.

<p align="center">
  <img width="400" src="https://cdn.rawgit.com/transitive-bullshit/awesome-ffmpeg/master/ffmpeg-logo.svg">
</p>


## Contents

- [Docs](#docs)
- [JavaScript](#javascript)
- [Native](#native)
- [Mobile](#mobile)
- [Tutorials](#tutorials)
- [Community](#community)


## Docs

FFmpeg's official docs are notoriously difficult for beginners to understand due to the scope and complexity of FFmpeg's capabilities. With that being said, they're still very useful as a reference.

- [FFmpeg.org](http://ffmpeg.org) - Where it all starts.
- [Filters](https://ffmpeg.org/ffmpeg-filters.html) - Docs for FFmpeg's powerful filter chains (scaling, cropping, concatenating, merging, etc.). This is one of my most visited links when working with FFmpeg.
- [Man page](https://man.cx/ffmpeg) - Official FFmpeg man page.
- [Wiki & Bug Tracker](https://trac.ffmpeg.org) - Lots of great info on here.
- [CLI flags](https://github.com/transitive-bullshit/ffmpeg-cli-flags/blob/master/readme.md) - A comprehensive list of all FFmpeg commandline flags. Really useful for searching random flags that you come across in the wild. :star:12


## JavaScript

- [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) - A fluent API to [FFmpeg](http://www.ffmpeg.org). If you only use one tool from this list, it should be this one. :star:4201
- [ffmpeg-probe](https://github.com/transitive-bullshit/ffmpeg-probe) - Wrapper around ffprobe for getting info about media files. :star:8
- [ffmpeg-concat](https://github.com/transitive-bullshit/ffmpeg-concat) - Concats a list of videos together using FFmpeg with sexy OpenGL transitions. :star:194
- [ffmpeg-generate-video-preview](https://github.com/transitive-bullshit/ffmpeg-generate-video-preview) - Generates an attractive image strip or GIF preview from a video. :star:51
- [ffmpeg-extract-frame](https://github.com/transitive-bullshit/ffmpeg-extract-frame) - Extracts a single frame from a video. :star:4
- [ffmpeg-extract-frames](https://github.com/transitive-bullshit/ffmpeg-extract-frames) - Extracts screenshots from a video using FFmpeg. :star:13
- [gif-extract-frames](https://github.com/transitive-bullshit/gif-extract-frames) - Extracts frames from GIFs including inter-frame coalescing. :star:9
- [ffmpeg-extract-audio](https://github.com/transitive-bullshit/ffmpeg-extract-audio) - Extracts an audio stream from a media file. :star:5
- [ffmpeg-on-progress](https://github.com/transitive-bullshit/ffmpeg-on-progress) - Utility for robustly reporting progress with fluent-ffmpeg. :star:7
- [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) - Port of FFmpeg to JavaScript via Emscripten. Allows for limited FFmpeg use on the client-side. :star:967
- [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static) - Provides static FFmpeg binaries for macOS, Linux, and Windows. Very useful for CI testing. :star:199
- [tangerine](https://github.com/niftylettuce/tangerine) - Webcam streaming service using Node.js, FFmpeg, WebSockets, and Lad. :star:10
- [ffparser](https://github.com/NiKlimenko/FFParser) - Parse input stream by frames directly into your code as a buffer.


## Native

- [ffmpeg-gl-transition](https://github.com/transitive-bullshit/ffmpeg-gl-transition) - FFmpeg filter for applying GLSL transitions between video streams ([gl-transitions](https://gl-transitions.com/)). :star:153


## Mobile

- [simplest ffmpeg mobile](https://github.com/leixiaohua1020/simplest_ffmpeg_mobile) - FFmpeg examples for Android and iOS. :star:1615
- [ijkplayer](https://github.com/Bilibili/ijkplayer) - Android / iOS video player based on FFmpeg. :star:24698


## Tutorials

- [How to Write a Video Player in Less Than 1k Lines](http://dranger.com/ffmpeg)
- [Learn FFmpeg libav the Hard Way](https://github.com/leandromoreira/ffmpeg-libav-tutorial) :star:4422
- [Applying OpenGL Shaders with FFmpeg](https://nervous.io/ffmpeg/opengl/2017/01/31/ffmpeg-opengl) - And [follow-up](https://nervous.io/ffmpeg/opengl/2017/05/15/ffmpeg-pbo-yuv).


## Community

- [Stack Overflow](https://superuser.com/questions/tagged/ffmpeg)
- [Mailing Lists](https://www.ffmpeg.org/contact.html#MailingLists)
- [IRC](https://www.ffmpeg.org/contact.html#IRCChannels)


## Contribute

Contributions welcome! Please read the [contributing guideline](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Travis Fischer](https://github.com/transitive-bullshit) has waived all copyright and related or neighboring rights to this work.


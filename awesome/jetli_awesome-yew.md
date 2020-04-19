# Information comes from [jetli/awesome-yew](https://github.com/jetli/awesome-yew)
# Awesome Yew [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="logo.svg" align="right" width="100" title="Awesome Yew">](https://github.com/yewstack/yew)

> A curated list of awesome things related to Yew.

[Yew](https://github.com/yewstack/yew) is a modern Rust framework inspired by Elm and React for creating multi-threaded frontend apps with WebAssembly.

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents

- [Official](#official)
- [Projects](#projects)
- [Templates](#templates)
- [Crates](#crates)
- [Toolings](#toolings)
- [Articles](#articles)
- [Books](#books)
- [Alternatives](#alternatives)
- [Related lists](#related-lists)

## Official

- [Yew](https://github.com/yewstack/yew) - Rust / WebAssembly framework for building client web apps. :star:11269
- [Yew router](https://github.com/yewstack/yew_router) - A routing library for the Yew frontend framework. :star:84
- [Yewtil](https://github.com/yewstack/yewtil) - Utilities for Yew. :star:11
- [Live demo](https://yew-todomvc.netlify.com) - A todomvc demo.
- [Examples](https://github.com/yewstack/yew/tree/master/examples) - Smaller examples included in official repo. :star:11269
- [API Docs](https://docs.rs/yew) - Docs on docs.rs.
- [Website](https://yew.rs/) - Official website.
- [Gitter chatroom](https://gitter.im/yewframework/Lobby) - It is pretty active and is a great place to ask questions.
- [Financial Contribute](https://opencollective.com/yew) - Become a financial contributor and help us sustain our community.

## Projects

- [Realworld example](https://github.com/jetli/rust-yew-realworld-example-app) - Exemplary real world app built with Rust + Yew + WebAssembly. :star:81
- [webapp.rs](https://github.com/saschagrunert/webapp.rs) - A web application completely written in Rust, frontend is built with Yew. :star:1302
- [Rust-Full-Stack](https://github.com/steadylearner/Rust-Full-Stack) - Easily testable and working Rust codes with blog posts to explain them. :star:396
- [Bucket Questions](https://github.com/hgzimmerman/BucketQuestions) - A webapp written entirely in Rust for a dumb party game. :star:2
- [web-view todomvc desktop app](https://github.com/Extrawurst/rust-webview-todomvc-yew) - Demo how to use yew for a todomvc that compiles to WebAssembly and is bundled as a lightweight(~2mb) desktop app by [web-view](https://github.com/Boscop/web-view), as an alternative to Electron, [web-view](https://github.com/Boscop/web-view) also has a [demo](https://github.com/Boscop/web-view/tree/master/examples#todo-yew). :star:38
- [yew-react-example](https://github.com/hobofan/yew-react-example) - This project shows how to create a web app using a React component inside a Yew component. :star:23
- [yew-mdc](https://github.com/Follpvosten/yew-mdc) - Material Design Components for the Yew framework. :star:19
- [muicss-yew](https://github.com/AlephAlpha/muicss-yew) - MUI-CSS Components for Yew framework. :star:4
- [Kirk](https://github.com/stkevintan/Kirk) - Just A Rust WebAssembly Blog. :star:14
- [rust-async-wasm-demo](https://github.com/extraymond/rust-async-wasm-demo) - Toy project to learn Rust and async that can be deoplyed to the web. :star:11
- [styled-yew](https://github.com/IcyDefiance/styled-yew) - CSS in Rust, similar to styled-components, but for Yew. :star:3
- [karaoke-rs](https://github.com/tarkah/karaoke-rs) - A simple, network enabled karaoke player in Rust. :star:75
- [I Love Hue! (rs)](https://github.com/noc7c9/i-love-hue-rs) - A clone of the mobile game I Love Hue in Yew (Rust). :star:2
- [Yew Form](https://github.com/jfbilodeau/yew_form) - Components to simplify handling forms with Yew. :star:32
- [yew-styles-page](https://github.com/spielrs/yew-styles-page) - This is an initial project of a framework style for yew. :star:4
- [caniuse.rs](https://github.com/jplatte/caniuse.rs) - Rust feature search. :star:37
- [Rust electron yew demo](https://github.com/Extrawurst/rust-electron-demo) - An example of building a Rust based web app (Yew) into a native app using electron. :star:1
- [covplot](https://github.com/jbowens/covplot) - Live graphs of worldwide CoVID-19 data. :star:3

## Templates

- [Create Yew App](https://github.com/jetli/create-yew-app) - Set up a modern Yew web app by running one command, `npx create-yew-app my-app`. :star:10
- [yew-wasm-pack-template](https://github.com/yewstack/yew-wasm-pack-template) - A template for starting a Yew project to be used with wasm-pack. :star:47
- [yew-wasm-pack-minimal](https://github.com/yewstack/yew-wasm-pack-minimal) - A minimal template for starting a Yew project using wasm-bindgen and wasm-pack. :star:30
- [yew-parcel-template](https://github.com/spielrs/yew-parcel-template) - Awesome Yew with Yew-Router and Parcel application. :star:27

## Crates

- [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) - Facilitating high-level interactions between WebAssembly modules and JavaScript. :star:3082
- [stdweb](https://github.com/koute/stdweb) - Provides Rust bindings to the Web APIs and to allow a high degree of interoperability between Rust and JavaScript. :star:2933

## Toolings

- [wasm-pack](https://github.com/rustwasm/wasm-pack) - Your favorite Rust -> WebAssembly workflow tool. :star:2562
- [wasm-pack-action](https://github.com/jetli/wasm-pack-action) - Github action to install `wasm-pack` by downloading the executable to speed up CI/CD. :star:1
- [cargo-web](https://github.com/koute/cargo-web) - A Cargo subcommand for the client-side Web. :star:947
- [wabt](https://github.com/WebAssembly/wabt) - The WebAssembly Binary Toolkit, for the `wasm-strip` and `wasm-objdump` tools to reduce .wasm file size. :star:2444
- [binaryen](https://github.com/WebAssembly/binaryen) - Compiler infrastructure and toolchain library for WebAssembly, for the `wasm-opt` tool to reduce .wasm file size. :star:3985

## Articles

- [Let's Build a Rust Frontend with Yew](https://dev.to/deciduously/lets-build-a-rust-frontend-with-yew---part-1-3k2o)
- [How to use Rust Yew](https://www.steadylearner.com/blog/read/How-to-use-Rust-Yew)
- [How to use a modal in Rust](https://www.steadylearner.com/blog/read/How-to-use-a-modal-in-Rust)
- [How to use routers in Rust Frontend](https://www.steadylearner.com/blog/read/How-to-use-routers-in-Rust-Frontend)
- [How to modulize your Rust Frontend](https://www.steadylearner.com/blog/read/How-to-modulize-your-Rust-Frontend)
- [How to use NPM packages with Rust Frontend](https://www.steadylearner.com/blog/read/How-to-use-NPM-packages-with-Rust-Frontend)
- [How to use markdown with Rust Frontend](https://www.steadylearner.com/blog/read/How-to-use-markdown-with-Rust-Frontend)
- [Fullstack Rust with Yew](https://www.steadylearner.com/blog/read/Fullstack-Rust-with-Yew)
- [How to write Full Stack Rust code](https://www.steadylearner.com/blog/read/How-to-write-Full-Stack-Rust-code)
- [How to render a YouTube vlog with Rust Yew fetch API](https://www.steadylearner.com/blog/read/How-to-render-a-YouTube-vlog-with-Rust-Yew-fetch-API)
- [How to render blog posts with Rust Yew mounted API](https://www.steadylearner.com/blog/read/How-to-render-blog-posts-with-Rust-Yew-mounted-API)
- [A Web Application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
- [Yew - Rust & WebAsse-frontend framework](https://sudonull.com/posts/16392-Yew-Rust-WebAsse-frontend-framework)

## Books

- [The WebAssembly Book](https://rustwasm.github.io/docs/book/) - Working with the web and producing .wasm files.
- [The wasm-bindgen Guide](https://rustwasm.github.io/docs/wasm-bindgen/) - How to bind Rust and JavaScript APIs.
- [The wasm-pack Guide](https://rustwasm.github.io/docs/wasm-pack/) - How to build and work with rust-generated WebAssembly.
- [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) - Includes a chapter `Advanced JavaScript Integration with Yew` on creating an app with Yew.

## Alternatives

Yew team love to share ideas with other projects and believe we can all help each other reach the full potential of this exciting new technology.

- [Draco](https://github.com/utkarshkukreti/draco) - A Rust library for building client side web applications with WebAssembly. :star:244
- [Percy](https://github.com/chinedufn/percy) - A modular toolkit for building isomorphic web apps with Rust + WebAssembly. :star:1345
- [Sauron](https://github.com/ivanceras/sauron) - Sauron is an HTML web framework for building web-apps. :star:902
- [Seed](https://github.com/seed-rs/seed) - A Rust framework for creating web apps. :star:1024
- [Smithy](https://github.com/rbalicki2/smithy) - A framework for building WebAssembly apps in Rust. :star:222

## Related lists

- [Awesome Rust and WebAssembly](https://github.com/rustwasm/awesome-rust-and-webassembly) - A list of awesome Rust and WebAssembly projects, libraries, tools, and resources. :star:303
- [Awesome WebAssembly](https://github.com/mbasso/awesome-wasm) - Collection of awesome things regarding WebAssembly ecosystem. :star:4713
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) - A curated list of Rust code and resources. :star:14937


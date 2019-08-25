# Information comes from [avajs/awesome-ava](https://github.com/avajs/awesome-ava)
# Awesome AVA [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://github.com/avajs/ava/raw/master/media/header.png" width="280" align="right" alt="AVA">](https://ava.li)

> [AVA](https://ava.li) is a minimal & futuristic JavaScript test runner


## Contents

- [Articles](#articles)
- [Videos](#videos)
- [Packages](#packages)
- [Works with AVA](#works-with-ava)
- [Tutorials](#tutorials)
- [Miscellaneous](#miscellaneous)
- [Support](#support)


## Articles

- [Recipes](https://github.com/avajs/ava/tree/master/docs/recipes) :star:16720
- [Testing React Native apps with AVA](https://shift.infinite.red/testing-the-bejeezus-out-of-react-native-apps-with-ava-330f51f8f6c3)
- [Getting Started with Create React App and AVA](https://semaphoreci.com/community/tutorials/getting-started-with-create-react-app-and-ava)
- [Effortless unit testing with AVA](https://wecodetheweb.com/2016/04/19/effortless-unit-testing-with-ava/)


## Videos

- [JavaScript Air episode with the AVA team](http://jsair.io/ava)
- [AVA Casts](http://avacasts.com) - Short screencasts about AVA.
- [Testing React components with AVA](https://www.youtube.com/watch?v=RxLW6-3dk5A)


## Packages

- [eslint-plugin-ava](https://github.com/avajs/eslint-plugin-ava) - ESLint rules. :star:184
- [ava-codemods](https://github.com/jamestalmage/ava-codemods) - Codemods that simplifies upgrading to newer versions. :star:69
- [sublime-ava](https://github.com/avajs/sublime-ava) - Snippets for Sublime. :star:43
- [atom-ava](https://github.com/avajs/atom-ava) - Snippets for Atom. :star:96
- [vscode-ava](https://github.com/samverschueren/vscode-ava) - Snippets for Visual Studio Code. :star:56
- [vim-ava-snippets](https://github.com/ahmedelgabri/vim-ava-snippets) - Snippets for Vim. :star:20
- [ava-spec](https://github.com/sheerun/ava-spec) - Drop-in BDD helpers. :star:150
- [redux-ava](https://github.com/sotojuan/redux-ava) - Test helpers for Redux. :star:180
- [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) - Generate AVA tests for Redux reducers in a React app. :star:473
- [gulp-ava](https://github.com/avajs/gulp-ava) - Run tests with Gulp. :star:56
- [grunt-ava](https://github.com/avajs/grunt-ava) - Run tests with Grunt. :star:7
- [fly-ava](https://github.com/pine/fly-ava) - Run tests with Fly. :star:12
- [start-ava](https://github.com/start-runner/ava) - Run tests with Start. :star:7
- [sigh-ava](https://github.com/unlight/sigh-ava) - Run tests with Sigh.
- [ava-rethinkdb](https://github.com/rrdelaney/ava-rethinkdb) - Test helpers for RethinkDB. :star:25
- [eslint-ava-rule-tester](https://github.com/jfmengels/eslint-ava-rule-tester) - Test [ESLint](https://github.com/eslint/eslint) plugins with AVA. :star:14
- [jscodeshift-ava-tester](https://github.com/jfmengels/jscodeshift-ava-tester) - Test [jscodeshift](https://github.com/facebook/jscodeshift) codemods with AVA. :star:11
- [ava-preact-init](https://github.com/avajs/ava-preact-init) - Set up AVA for Preact. :star:8
- [ava-fixture](https://github.com/unional/ava-fixture) - Run fixture/baseline tests. :star:4
- [ava-playback](https://github.com/dempfi/ava-playback) - Record and playback HTTP requests. :star:117
- [ava-fast-check](https://github.com/dubzzz/ava-fast-check) - Property based testing. :star:28
- [ava-fixture-docker-db](https://github.com/cdaringe/ava-fixture-docker-db) - Add docker databases to your test contexts.
- [ava-webcomponents](https://github.com/Wildhoney/ava-webcomponents) - Testing web components via Puppeteer. :star:1
- [ava-tap-json](https://github.com/yovasx2/ava-tap-json) - JSON output with AVA compatibility. :star:1

## Works with AVA

- [Spectron](https://github.com/electron/spectron#with-ava) - Test Electron apps using AVA and ChromeDriver. :star:1290
- [Chūhai](https://github.com/Hypercubed/chuhai) - Run and verify benchmarks using AVA and benchmark.js. :star:79
- [Leakage](https://github.com/andywer/leakage#usage-with-ava--tape) - Memory leak testing. :star:1387
- [pify](https://github.com/sindresorhus/pify) - Promisify callback-style functions for better testing. [(Example)](https://github.com/sindresorhus/registry-url/blob/eb1f0e01722208366c9199b96235fd043ec162ae/test.js#L6) :star:35
- [p-event](https://github.com/sindresorhus/p-event) - Promisify an event. [(Example)](https://github.com/sindresorhus/gulp-debug/blob/4db5871594742a346d17aa9b34f43c87d4e54934/test.js#L42-L44) :star:220
- [execa](https://github.com/sindresorhus/execa) - Test your CLI tools. [(Example)](https://github.com/sindresorhus/active-win-cli/blob/d01813762b304102d1fee147855481e9f38c8517/test.js#L5-L6) :star:26
- [delay](https://github.com/sindresorhus/delay) - Add delays to your tests. [(Example)](https://github.com/sindresorhus/p-queue/blob/a3a5cadefc2b54269f4939bb34e8dc180c3bd800/test.js#L39) :star:721
- [get-stream](https://github.com/sindresorhus/get-stream) - Test the output of streams. [(Example)](https://github.com/sindresorhus/ora/blob/4ceeedd51795bb88a8033229d198e70cd8a2aff7/test.js#L33-L35) :star:5111
- [create-test-server](https://github.com/lukechilds/create-test-server) - Creates a minimal Express server for testing. [(Example)](https://github.com/lukechilds/clone-response/blob/11f5870e4e1b039e2d9a8f1f72d45fd1b9706bf3/test/clone-response.js) :star:12


## Tutorials

- [Testing a React & Redux Codebase](http://silvenon.com/testing-react-and-redux/) - A comprehensive series of tutorials about testing a React and Redux project using AVA.


## Miscellaneous

- [Stickers, t-shirts, etc](https://www.redbubble.com/people/sindresorhus/works/30330590-ava-logo) - The products are sold at production price without any markup.
- [Slides from AVA talk at London Node User Group](https://speakerdeck.com/novemberborn/ava-at-lnug) - By core team member [Mark Wubben](https://github.com/novemberborn).


## Support

- [Stack Overflow](https://stackoverflow.com/questions/tagged/ava)
- [Spectrum](https://spectrum.chat/ava)
- [Twitter](https://twitter.com/ava__js)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.


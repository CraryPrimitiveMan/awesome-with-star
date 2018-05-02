# Information comes from [sindresorhus/awesome-tap](https://github.com/sindresorhus/awesome-tap)
# Awesome TAP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)


> Useful resources for the [Test Anything Protocol](https://testanything.org)<br>
> A simple text-based interface between testing modules in a test harness

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*


## Contents

- [Reporters](#reporters)
- [Producers](#producers)
- [Consumers](#consumers)
- [Tools](#tools)
- [Articles](#articles)
- [Tutorials](#tutorials)
- [Documentation](#documentation)
- [Community](#community)


## Reporters

### JavaScript

- [tap-dot](https://github.com/scottcorgan/tap-dot) - Dotted output. :star:24
- [tap-spec](https://github.com/scottcorgan/tap-spec) - Mocha-like spec reporter. :star:235
- [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) - Nyan cat. :star:118
- [tap-min](https://github.com/gummesson/tap-min) - Minimal output. :star:29
- [tap-difflet](https://github.com/namuol/tap-difflet) - Minimal output with diffing. :star:39
- [tap-diff](https://github.com/axross/tap-diff) - Human-friendly output with diffing. :star:71
- [tap-simple](https://github.com/joeybaker/tap-simple) - Simple output. :star:6
- [faucet](https://github.com/substack/faucet) - Human-readable summarizer. :star:490
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - Use any of the [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters). :star:14
- [tap-summary](https://github.com/zoubin/tap-summary) - Summarized output. :star:29
- [tap-pessimist](https://github.com/clux/tap-pessimist) - Only shows failed tests. :star:13
- [tap-prettify](https://github.com/toolness/tap-prettify) - Nice readable output with diffing. :star:30
- [tap-colorize](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability. :star:27
- [tap-bail](https://github.com/juliangruber/tap-bail) - Bail out when the first test fails. :star:19
- [tap-notify](https://github.com/axross/tap-notify) - Notifier for macOS, Linux and Windows. :star:53
- [tap-json](https://github.com/gummesson/tap-json) - JSON output. :star:18
- [tap-xunit](https://github.com/aghassemi/tap-xunit) - xUnit output. :star:29
- [tap-teamcity](https://github.com/smockle/tap-teamcity) - Output for TeamCity. :star:7


## Producers

Things that produce TAP output.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - Futuristic test runner. `$ ava --tap` :star:13678
- [tap](https://github.com/isaacs/node-tap) - TAP test framework for Node.js. :star:1216
- [tape](https://github.com/substack/tape) - TAP-producing test harness for Node.js and browsers. :star:4580
- [ESLint](http://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter. `$ eslint --format=tap`
- [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers. `$ mocha reporter=tap`
- [qunit-tap](https://github.com/twada/qunit-tap) - TAP output for QUnit. :star:73
- [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) - TAP output for Jasmine. :star:386
- [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) - TAP output for Karma. :star:7
- [mos](https://github.com/zkochan/mos) - Markdown file generator and tester. `$ mos test --tap` :star:87

### Fish

- [Fishtape](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish. :star:213

### Bash


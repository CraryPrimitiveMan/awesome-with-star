# Information comes from [bcoe/awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs)
<div align="center">
  <img src="https://raw.githubusercontent.com/bcoe/awesome-cross-platform-nodejs/master/logo.svg?sanitize=true" width="500"/>
  <br>
  <a href="https://awesome.re">
	  <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <p>A curated list of awesome developer tools for writing cross-platform Node.js code.</p>
</div>

## Contents

- [Resources](#resources)
- [Applications](#applications)
  - [Development environment](#development-environment)
  - [Continuous integration](#continuous-integration)
  - [Virtualization](#virtualization)
  - [Compatibility](#compatibility)
  - [Databases](#databases)
- [Libraries](#libraries)
  - [OS identification](#os-identification)
  - [Shell](#shell)
  - [Environment](#environment)
  - [Filesystem](#filesystem)
  - [Signals](#signals)
  - [Processes](#processes)
  - [Streams](#streams)
  - [Desktop UI](#desktop-ui)
  - [Windows registry](#windows-registry)
- [Known issues](#known-issues)
- [Support](#support)

## Resources

- [Core Node.js documentation](https://nodejs.org/en/docs/) - Especially the [`os`](https://nodejs.org/api/os.html), [`path`](https://nodejs.org/api/path.html), [`fs`](https://nodejs.org/api/fs.html), [`process`](https://nodejs.org/api/process.html) and [`child_process`](https://nodejs.org/api/child_process.html) modules.
- [Cross-platform Node.js guide](https://github.com/ehmicky/cross-platform-node-guide) - How to write cross-platform Node.js code. :star:1033
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms. :star:2152
- [Writing Cross-Platform Node.js](http://shapeshed.com/writing-cross-platform-node/) - Great tutorial covering many common issues that arise when writing cross-platform code: path creation, script execution, newline characters.

## Applications

### Development environment

- [Node.js](https://nodejs.org/en/download/) - Node.js installer for various platforms.
- [nvm-windows](https://github.com/coreybutler/nvm-windows) - Manage multiple installations of Node.js on a Windows computer. :star:11941
- [nvm](https://github.com/creationix/nvm) / [n](https://github.com/tj/n) - Node version manager for macOS/Linux. :star:12851
- [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) - Upgrade npm on Windows. :star:2012
- [windows-build-tools](https://github.com/felixrieseberg/windows-build-tools) - Install C++ Build Tools for Windows using npm. :star:2793

### Continuous integration

- [AppVeyor](http://www.appveyor.com/) - Focused on Windows. Free tiers are available for OSS projects.
- [Travis](https://travis-ci.org/) - Windows/macOS/Linux. Free for OSS projects.
- [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) - Windows/macOS/Linux. Free for OSS projects with 10 parallel jobs.

### Virtualization

- [ievms](https://github.com/amichaelparker/ievms) - Automated installer for the free virtual machine images that Microsoft provides for testing on multiple versions of IE. These images can be useful for cross-platform testing various technologies, however make sure you read and understand Microsofts' licensing. :star:65
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - General purpose software for running x86 virtual machines.
- [Docker](https://www.docker.com/) - Software platform to create, deploy and manage virtualized application containers on a common operating system, with an ecosystem of allied tools.

### Compatibility

- [Wine](https://www.winehq.org/) - Run Windows API calls on Linux, Mac, BSD and Solaris.
- [Cygwin](https://www.cygwin.com/) - Run POSIX on Windows.
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) - Run the Linux command line on Windows (ELF binary execution, system calls, filesystem, Bash, core utilities, common applications).
- [MinGW](http://www.mingw.org/) - `gcc` on Windows.
- [msys](http://www.mingw.org/wiki/msys) / [Git Bash](https://gitforwindows.org/) - Bash on Windows.

### Databases

- [Redis](https://github.com/tporadowski/redis) - Native port of Redis for Windows. :star:974

## Libraries

### OS identification

- [is-windows](https://github.com/jonschlinkert/is-windows) - Detect whether the current platform is Windows. :star:37
- [is-wsl](https://github.com/sindresorhus/is-wsl) - Detect whether current platform is WSL (Windows Subsystem for Linux). :star:98
- [getos](https://github.com/retrohacker/getos) - Retrieve the current OS, including Linux distribution. :star:60
- [os-name](https://github.com/sindresorhus/os-name) - Get the name of the current operating system. :star:77
- [systeminformation](https://github.com/sebhildebrandt/systeminformation) - Hardware/software system information. :star:1063

### Shell

- [execa](https://github.com/sindresorhus/execa) - Cross-platform implementation of `child_process.{execFile,exec}`. :star:3030
- [gulp-execa](https://github.com/ehmicky/gulp-execa) - Cross-platform command execution in Gulp.js. :star:42
- [cross-spawn](https://github.com/IndigoUnited/node-cross-spawn) - Cross-platform implementation of `child_process.spawn()`. :star:696
- [shelljs](https://github.com/shelljs/shelljs) - Cross-platform Unix shell commands. :star:10845
- [node-windows](https://github.com/coreybutler/node-windows) - Windows support for Node.js scripts (daemons, eventlog, UAC, etc). :star:1885
- [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels with Windows fallbacks. :star:505
- [figures](https://github.com/sindresorhus/figures) - Unicode symbols with Windows fallbacks. :star:390
- [clipboardy](https://github.com/sindresorhus/clipboardy) / [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - Cross-platform copy/paste. :star:352

### Environment

- [cross-env](https://github.com/kentcdodds/cross-env) - Set environment variables cross-platform. :star:4572
- [user-home](https://github.com/sindresorhus/user-home) - Get the path to the user home directory. Cross-platform. :star:140
- [username](https://github.com/sindresorhus/username) - Get the current username. :star:114
- [osenv](https://github.com/npm/osenv) - Cross-platform environment variables. :star:132
- [is-elevated](https://github.com/sindresorhus/is-elevated) - Check if the process is running with elevated privileges. :star:24
- [which](https://github.com/npm/node-which) - Cross-platform implementation of Unix's `which`. :star:193

### Filesystem

- [rimraf](https://github.com/isaacs/rimraf) / [del](https://github.com/sindresorhus/del) - Delete files and folders. Cross-platform. :star:1057
- [make-dir](https://github.com/sindresorhus/make-dir) - Cross-platform `mkdir -p`. :star:400
- [readdirp](https://github.com/paulmillr/readdirp) - Recursive version of `fs.readdir()`. :star:264
- [cpy](https://github.com/sindresorhus/cpy) - Copy files. Cross-platform. :star:260
- [chokidar](https://github.com/paulmillr/chokidar) - Improved cross-platform file watching. :star:6384
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - Improves the `fs` module, especially on Windows. :star:944
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - Combines `graceful-fs` with better JSON file reading and promises. :star:6673
- [any-path](https://github.com/bcoe/any-path) - Use Windows and POSIX paths interchangeably when fetching values from an object. :star:4
- [dev-null-cli](https://github.com/sindresorhus/dev-null-cli) - Cross-platform `/dev/null`. :star:86

### Signals

- [fkill](https://github.com/sindresorhus/fkill) - Kill processes. Cross-platform. :star:536
- [signal-exit](https://github.com/tapjs/signal-exit) - Cross-platform `exit` handler. :star:117

### Processes

- [ps-list](https://github.com/sindresorhus/ps-list) - Get running processes. :star:146
- [process-exists](https://github.com/sindresorhus/process-exists) - Check if a process exists. :star:32

### Streams

- [noop-stream](https://github.com/sindresorhus/noop-stream) - Cross-platform `fs.createReadStream('/dev/null')`. :star:39
- [random-bytes-readable-stream](https://github.com/sindresorhus/random-bytes-readable-stream) - Cross-platform `fs.createReadStream('/dev/urandom')`. :star:72

### Desktop UI

- [open](https://github.com/sindresorhus/open) - Opens stuff like websites, files, executables. Cross-platform. :star:1903
- [node-notifier](https://github.com/mikaelbr/node-notifier) - Cross-platform desktop notifications. :star:4246

### Windows registry

- [node-winreg](https://github.com/fresc81/node-winreg) - Access the Windows registry. :star:176
- [rage-edit](https://github.com/MikeKovarik/rage-edit) - Access/modify the Windows registry. :star:27
- [windows-registry-node](https://github.com/CatalystCode/windows-registry-node) - Access/modify the Windows registry and set file associations. :star:68

## Known issues

- [cmd.exe unicode woes](https://github.com/nodejs/node-v0.x-archive/issues/7940) - By default, `cmd.exe` does not display Unicode characters on Windows. :star:35239
- [spawn issues](https://github.com/nodejs/node-v0.x-archive/issues/2318) - `child_process.spawn()` behavior is not consistent between Windows and Linux. :star:35239
- [exec() behavior between shells](https://github.com/isaacs/spawn-wrap#contracts-and-caveats) - Depending on the shell being used, e.g., bash vs. dash, `child_process.exec()` has inconsistent exit behavior. :star:30

## See also

- [awesome-desktop-js](https://github.com/styfle/awesome-desktop-js) - List of tools to build JavaScript applications on the desktop. :star:357

## Support

If you found an error or would like to add more information, _don't hesitate_ to
[submit an issue on GitHub](../../issues).

Everyone is welcome regardless of personal background. We enforce a
[Code of conduct](CODE_OF_CONDUCT.md) in order to promote a positive and
inclusive environment.

## Contributing

This project was made with ❤️. The simplest way to give back is by starring and
sharing it online.

If the documentation is unclear or has a typo, please click on the page's `Edit`
button (pencil icon) and suggest a correction.

If you would like to help us fix an error or add more information, please check
our [guidelines](contributing.md). Pull requests are welcome!

Thanks go to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://twitter.com/benjamincoe"><img src="https://avatars3.githubusercontent.com/u/194609?v=4" width="100px;" alt="Benjamin E. Coe"/><br /><sub><b>Benjamin E. Coe</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Code">💻</a> <a href="#ideas-bcoe" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=bcoe" title="Documentation">📖</a></td><td align="center"><a href="https://twitter.com/ehmicky"><img src="https://avatars2.githubusercontent.com/u/8136211?v=4" width="100px;" alt="ehmicky"/><br /><sub><b>ehmicky</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Code">💻</a> <a href="#ideas-ehmicky" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ehmicky" title="Documentation">📖</a></td><td align="center"><a href="https://sindresorhus.com"><img src="https://avatars1.githubusercontent.com/u/170270?v=4" width="100px;" alt="Sindre Sorhus"/><br /><sub><b>Sindre Sorhus</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Code">💻</a> <a href="#ideas-sindresorhus" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=sindresorhus" title="Documentation">📖</a></td><td align="center"><a href="https://fb.com/RemoveU"><img src="https://avatars1.githubusercontent.com/u/19208123?v=4" width="100px;" alt="Hongarc"/><br /><sub><b>Hongarc</b></sub></a><br /><a href="#design-Hongarc" title="Design">🎨</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Documentation">📖</a> <a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Hongarc" title="Code">💻</a></td><td align="center"><a href="https://kentcdodds.com"><img src="https://avatars0.githubusercontent.com/u/1500684?v=4" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="#ideas-kentcdodds" title="Ideas, Planning, & Feedback">🤔</a></td><td align="center"><a href="https://nz.linkedin.com/in/jsonc11"><img src="https://avatars0.githubusercontent.com/u/5185660?v=4" width="100px;" alt="Jason Cooke"/><br /><sub><b>Jason Cooke</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Jason-Cooke" title="Documentation">📖</a></td><td align="center"><a href="http://aronhafner.com"><img src="https://avatars0.githubusercontent.com/u/3322693?v=4" width="100px;" alt="Aron Hafner"/><br /><sub><b>Aron Hafner</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=alonalon" title="Documentation">📖</a></td></tr><tr><td align="center"><a href="https://github.com/ShPelles"><img src="https://avatars0.githubusercontent.com/u/43875468?v=4" width="100px;" alt="ShPelles"/><br /><sub><b>ShPelles</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=ShPelles" title="Documentation">📖</a></td><td align="center"><a href="https://github.com/Frederick-S"><img src="https://avatars1.githubusercontent.com/u/1182395?v=4" width="100px;" alt="Xiaodan Mao"/><br /><sub><b>Xiaodan Mao</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=Frederick-S" title="Documentation">📖</a></td><td align="center"><a href="https://github.com/jamestalmage"><img src="https://avatars0.githubusercontent.com/u/4082216?v=4" width="100px;" alt="James Talmage"/><br /><sub><b>James Talmage</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=jamestalmage" title="Documentation">📖</a></td><td align="center"><a href="http://sylvain.pontoreau.com"><img src="https://avatars3.githubusercontent.com/u/3357643?v=4" width="100px;" alt="Sylvain PONTOREAU"/><br /><sub><b>Sylvain PONTOREAU</b></sub></a><br /><a href="https://github.com/bcoe/awesome-cross-platform-nodejs/commits?author=spontoreau" title="Documentation">📖</a></td><td align="center"><a href="https://www.ceriously.com"><img src="https://avatars1.githubusercontent.com/u/229881?v=4" width="100px;" alt="Steven"/><br /><sub><b>Steven</b></sub></a><br /><a href="#ideas-styfle" title="Ideas, Planning, & Feedback">🤔</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification.

## License

[![License](https://img.shields.io/github/license/bcoe/awesome-cross-platform-nodejs.svg?color=4cc61e&logo=github)](https://creativecommons.org/licenses/by-sa/4.0/)


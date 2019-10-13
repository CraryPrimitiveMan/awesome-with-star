# Information comes from [jakoch/awesome-composer](https://github.com/jakoch/awesome-composer)
## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php](https://github.com/ziadoz/awesome-php).

*Please read the [contribution guidelines](contributing.md) before contributing.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues) :star:21189
- [Github](https://github.com/composer/composer) :star:21189
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.
- [Composer Installers](https://github.com/composer/installers) - Composer installers for multiple frameworks. :star:1174

### Support

#### Stack Overflow

- You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC channels are on `irc.freenode.org`: [#composer](https://webchat.freenode.net/#composer) for users and [#composer-dev](https://webchat.freenode.net/#composer-dev) for development.

---------------------------------------------------------

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
- [Composer-Asset-Plugin](https://github.com/fxpio/composer-asset-plugin) - A npm/Bower Dependencies Manager for Composer. :star:868
- [Composer-AWS](https://github.com/naderman/composer-aws) - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories). :star:70
- [Composer-Composition](https://github.com/bamarni/composition) - Provides an API, for checking your environment at runtime. :star:108
- [Composer-Suggest](https://github.com/nfreear/composer-suggest) - Enables you to install a custom group of suggested packages, based on keyword patterns. :star:4
- [Composer-Versions-Check](https://github.com/Soullivaneuh/composer-versions-check) - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z"). :star:188
- [Composer-Changelogs](https://github.com/pyrech/composer-changelogs) - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file. :star:510
- [Composer-Merge-Plugin](https://github.com/wikimedia/composer-merge-plugin) - Merges multiple `composer.json` files at Composer runtime. :star:582
- [Composer-Bin-Plugin](https://github.com/bamarni/composer-bin-plugin) - Adds support for managing dependencies for multiple packages in a single repository or isolate bin dependencies. :star:202
- [Composer-Inheritance-Plugin](https://github.com/theofidry/composer-inheritance-plugin) - Opinionated version of Wikimedia composer-merge-plugin to work in pair with Bamarni composer-bin-plugin. :star:12
- [Composer-MonoRepo-Plugin](https://github.com/beberlei/composer-monorepo-plugin) - The plugin helps to manage dependencies for multiple packages in a single repository. :star:234
- [Composer-Patches-Plugin](https://github.com/netresearch/composer-patches-plugin) - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top. :star:65
- [Composer-Patches](https://github.com/cweagans/composer-patches) - The plugin applies a patch from a local or remote file to any required package. :star:692
- [Composer-Patches](https://github.com/vaimo/composer-patches) - Applies a patch from a local or remote file to any package that is part of a given composer project. :star:120
- [Composer-Patchset](https://github.com/creativestyle/composer-plugin-patchset) - Automatically fetch, update and apply patches to any composer package with a twist - store the patchset as a composer package itself. :star:1
- [Composer-Plugin-QA](https://github.com/Webysther/composer-plugin-qa) - Comprehensive Plugin for composer to execute PHP Quality assurance Tools. :star:23
- [Composer-Cleanup-Plugin](https://github.com/barryvdh/composer-cleanup-plugin) - Removes tests & documentation folders from the vendor dir. :star:92
- [Composer-Cleaner](https://github.com/dg/composer-cleaner) - The tool removes unnecessary files and directories from the vendor directory. :star:97
- [Composer-Ignore-Plugin](https://github.com/lichunqiang/composer-ignore-plugin) - Enables you to remove files and folders from the vendor folder (to make a cleaner and smaller deployment to production). It's an alternative to `.gitattributes`. :star:17
- [Composer-Shared-Package-Plugin](https://github.com/Letudiant/composer-shared-package-plugin) - Allows you to share selected packages between your projects by creating symlinks. :star:163
- [Composer-Symlinker](https://github.com/dg/composer-symlinker) - Enables you to load packages from different directories (instead of loading them from /vendor). :star:22
- [Prestissimo](https://github.com/hirak/prestissimo) - A parallel downloader using `phpext_curl`. :star:5242
- [Composer-Curl-Plugin](https://github.com/ngyuki/composer-curl-plugin) - The plugin use phpext_curl for downloading packages. :star:4
- [Composer-Custom-Directory-Installer](https://github.com/mnsami/composer-custom-directory-installer) - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (vendor folder). :star:106
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.
- [Graph-Composer](https://github.com/clue/graph-composer) - Provides a graph visualization for your project's `composer.json` and its dependencies. :star:616
- [PackageVersions](https://github.com/Ocramius/PackageVersions) - Provides a very quick and easy access to installed composer dependency versions. :star:2487
- [Composer Locator](https://github.com/mindplay-dk/composer-locator) - Provides a means of locating the installation path for a given Composer package name. :star:58
- [PackageInfo](https://github.com/ThaDafinser/PackageInfo) - Enables you to retrieve all package informations (like version, tag, release date, description). :star:5
- [Composer-Git-Hooks](https://github.com/BrainMaestro/composer-git-hooks) - A library for easily managing git hooks in your composer config. :star:621
- [Symfony-Flex](https://github.com/symfony/flex) - Provides [recipe-based](https://github.com/symfony/recipes) installation and configuration management for Symfony packages. :star:2675
- [Narrowspark-Automatic](https://github.com/narrowspark/automatic) - Automates the most common tasks of applications, boost package downloads, adds a composer security audit and more. :star:7
- [PHPCodeSniffer-Composer-Installer](https://github.com/DealerDirect/phpcodesniffer-composer-installer) - The plugin enables you to install [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) coding standards (rulesets). :star:144
- [Composer-Warmup](https://github.com/jderusse/composer-warmup) - The plugin adds the command `warmup-opcode` to Composer, which triggers the compilation of all PHP files discovered in your project into the Opcache. :star:162
- [Foxy](https://github.com/fxpio/foxy) - Composer plugin that executes npm/yarn packages installation operations, when composer package is installed or updated. :star:98
- [NodeJS-Installer](https://github.com/thecodingmachine/nodejs-installer) - Downloads and installs NodeJS and npm as composer package.  :star:98
- [Imposter-Plugin](https://github.com/typisttech/imposter-plugin) - Wrapping all composer vendor packages inside your own namespace. Intended for WordPress plugins. :star:29
- [Composer Preload](https://github.com/Ayesh/Composer-Preload) - The plugin generates a `vendor/preload.php` file to warm up the Opcache. :star:86
- [PHP Inc](https://github.com/krakphp/php-inc) - Automatically includes files for autoload and autoload-dev to facilitate using functions and grouped definitions within composer loaded applications. :star:3
- [Composer Registry Manager](https://github.com/slince/composer-registry-manager) - Enables you to switch between different composer repositories. :star:250
- [Production-Dependencies-Guard](https://github.com/kalessil/production-dependencies-guard) - Prevents development packages from being added into require and getting into production environment. :star:70
- [Composer Exclusive Install](https://github.com/erickskrauch/composer-exclusive-install) - Prevents more than one install or update operation at a time.
- [Composer-Downloads-Plugin](https://github.com/civicrm/composer-downloads-plugin) - Lightweight mechanism to download external resources (ZIP/TAR files) with only a `url` and `path`.

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
- [Composer-Yaml](https://github.com/igorw/composer-yaml) - This tool converts `composer.yml` to `composer.json`. :star:50
- [Studio](https://github.com/franzliedke/studio) - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project. :star:808
- [OctoLinker Browser Extension](https://github.com/OctoLinker/OctoLinker) - Enables you to navigate Composer/NPM dependencies on Github. :star:3917
- [ComposerRequireChecker](https://github.com/maglnet/ComposerRequireChecker) - A CLI tool to analyze dependencies and verify that no unknown imported symbols are used in the sources of a package. :star:380
- [Composer-Normalize](https://github.com/localheinz/composer-normalize) - The plugin helps to keep your `composer.json` file(s) consistent by restructuring and sorting entries (normalizing). :star:367
- [Composer-Service](https://github.com/pborreli/composer-service) - Enables you to run Composer as a service on a remote server. :star:171
- [Composer PreferLowest Checker](https://github.com/dereuromark/composer-prefer-lowest) - Strictly compare the specified minimum versions of your composer.json with the ones actually used by the prefer-lowest composer update command option. :star:6
- [Bramus/Composer-Autocomplete](https://github.com/bramus/composer-autocomplete) - A Bash/Shell autocompletion script for Composer. :star:57
- [Composer/Xdebug-Handler](https://github.com/composer/xdebug-handler) - Helps you to restart a CLI process without loading the xdebug extension. :star:1382

## Scripts

- [ParameterHandler](https://github.com/Incenteev/ParameterHandler) - Allows you to manage your ignored parameters when running a composer install or update. :star:838
- [Tooly](https://github.com/tommy-muehle/tooly-composer-script) - Manage needed PHAR files in your project `composer.json`. Every PHAR file will be saved in the composer binary directory. Optional with GPG verification for every PHAR. :star:96
- [Melody](https://github.com/sensiolabs/melody) - One-file composer scripts. :star:380
- [Composer-Travis-Lint](https://github.com/raphaelstolt/composer-travis-lint) - Allows you to lint the Travis CI configuration file (`.travis.yml`). :star:5
- [Composer-Multitest](https://github.com/raphaelstolt/composer-multitest) - Enables you to run a Composer script against multiple, locally installed PHP versions, which are managed by PHPBrew or phpenv. :star:5
- [ScriptsDev](https://github.com/neronmoon/scriptsdev) - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode. :star:60
- [PhantomJS-Installer](https://github.com/jakoch/phantomjs-installer)- A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.
- [Composer-Vendor-Cleanup](https://github.com/0xch/composer-vendor-cleanup)- A script which removes whitelisted unnecessary files (like tests/docs etc.) from the vendor directory

## GUI 

- [Composercat](https://www.getcomposercat.com/) - Composercat is a comprehensive GUI for the Composer package manager, designed both for professionals and people taking their first steps with Composer.

## Services

- [Dependabot](https://dependabot.com/) - Dependabot is a dependency update service. It monitors and updates your dependencies by sending a pull-request. The service is free for public repos and personal account repos.

---------------------------------------------------------

## Tutorials

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/re-introducing-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](https://alanstorm.com/php_composer_magento_tutorial/ )

## Books

- [Creating and Using Composer Packages](https://hub.packtpub.com/creating-and-using-composer-packages/)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](http://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Composer Best Practices 2018 - Nils Adermann @ phpday 2018](https://www.youtube.com/watch?v=EpvihKaQyLs)
- [Managing dependencies is more than running "composer update" -  Nils Adermann @ phpsrb17](https://www.youtube.com/watch?v=QL6w8H2eHQE)
- [Composer Best Practices — Jordi Boggiano @ php[tek] 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
- [Wonderful World of Composer](https://symfonycasts.com/screencast/composer)
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Slides

- Slides by Nils Adermann 
  - Source: http://www.naderman.de/slippy/slides/
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](http://www.naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
  - [Composer Update](http://www.naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](http://www.naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  - [Managing dependencies is
more than running
"composer update"](http://naderman.de/slippy/slides/2017-06-30-DPC-Dependency-Management-is-more-than-composer-update.pdf)
  - [Composer
Best Practices @ T3DD17](http://www.naderman.de/slippy/slides/2017-07-13-T3DD17-Composer-Best-Practices.pdf)
  - [Gain Control over your
Dependencies with
Private Packagist](http://www.naderman.de/slippy/slides/2017-07-14-T3DD17-Gain-control-over-your-dependencies-with-private-packagist.pdf)
  - [Composer.lock demystified](http://www.naderman.de/slippy/slides/2018-01-26-composer-lock-demystified.pdf)
  - [Compoer In-Depth @ Contao Konferenz 2018](http://www.naderman.de/slippy/slides/2018-06-08-Contao-Konferenz-2018-Composer-In-Depth.pdf)
  - [Composer Best Practices 2018](http://www.naderman.de/slippy/slides/2018-06-27-Composer-Best-Practices-2018.pdf)
  - [Developing and Deploying Magento with Composer Best Practices](http://www.naderman.de/slippy/slides/2018-06-18-Developing-and-Deploying-Magento-with-Composer-Best-Practices.pdf)
  - [Composer Platform Config (check-platform-reqs) @ SymfonCon 2018](http://www.naderman.de/slippy/slides/2018-12-07-SymfonCon-Composer-Platform-Config.pdf)
- Slides by Jordi Boggiano
  - Source: http://slides.seld.be/
  - [Dependency Management with Composer (2013)](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)
  - [In Depth with Composer (2013)](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Composer Best Practices (2015)](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer (2015)](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [Composer in 2016](http://slides.seld.be/?file=2016-07-22+Composer+in+2016.html)

---------------------------------------------------------

## Packagist

[Packagist](https://packagist.org) is the PHP Package Repository.

### Setup a Packagist Mirror 

- [Packagist Mirror](https://github.com/Webysther/packagist-mirror) - This script helps to setup a packagist mirror. It is the maintained and stable version of [Packagist Crawler](https://github.com/hirak/packagist-crawler). :star:85
- [Docker Image](https://github.com/Webysther/packagist-mirror-docker) - This Docker image helps to create a customized packagist mirror. :star:23
- [Packagist Mirror from Indonesia](https://github.com/IndraGunawan/packagist-mirror) - Another implementation for creating a packagist mirror. :star:28

### Packagist Mirrors

About metadata mirrors: https://packagist.org/mirrors

- North America
  - Canada - [packagist.org](https://packagist.org) *Main mirror*
- South America
  - Brazil - [packagist.com.br](https://packagist.com.br)
- Africa
  - South Africa - [packagist.co.za](packagist.co.za)
- Asia
  - China - [php.cnpkg.org](https://php.cnpkg.org), [https://pkg.phpcomposer.com/](https://pkg.phpcomposer.com/), [https://mirrors.aliyun.com/composer/](https://mirrors.aliyun.com/composer/)
  - India - [https://packagist.in/](https://packagist.in/)
  - Indonesia - [packagist.phpindonesia.id](https://packagist.phpindonesia.id)
  - Japan - [packagist.jp](https://packagist.jp)

## Composer Repositories

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories.
- [Private Packagist Enterprise](https://packagist.com) - On-premise self-hosted version of Private Packagist.
- [Private Packagist API Client](https://github.com/packagist/private-packagist-api-client) - A PHP client for the Private Packagist API. The client handles authentication, signature generation and access to all endpoints. :star:16

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) - Mirrors the WordPress plugin and theme directories as a Composer repository.
- [Asset Packagist](https://asset-packagist.org/) - Enables installation of Bower and NPM packages as native Composer packages.
- [Firegento](https://packages.firegento.com/) - A Composer Repository providing Magento Modules.
- [Drupal Packagist](https://www.drupal.org/node/2822344) - Composer repositories for Drupal 7 and 8 core, modules, and themes.
- [Satis Server](https://github.com/lukaszlach/satis-server) - This docker container provides a Satis Server and enables you to run a private, self-hosted Composer repository with support for Git, Mercurial, and Subversion, HTTP API, HTTPs support, webhook handler and scheduled builds. :star:69
- [Cloudsmith](https://cloudsmith.io) - A fully managed package management SaaS with PHP/Composer support (and many others).
- [Release Belt](https://github.com/Rarst/release-belt) - Self–hosted Composer repository implementation to quickly integrate ZIP files of third party non–Composer releases. :star:98

### Satis

- [Gitlab-Composer](https://github.com/wemakecustom/gitlab-composer) - This is a branch/tag indexer for Gitlab repositories. :star:151
- [Satisfy](https://github.com/ludofleury/satisfy) - Satis composer repository manager with a Web UI. :star:334
- [Satis Control Panel](https://github.com/realshadow/satis-control-panel) - A simple web UI for managing your Satis Repository with optional CI integration. :star:125
- [Satis Go](https://github.com/benschw/satis-go) - A web server for managing Satis configuration and hosting the generated Composer repository. :star:81

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) (deprecated) - In addition to providing a composer repository ToranProxy acts as a proxy server for Packagist and GitHub.

---------------------------------------------------------

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.


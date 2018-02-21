# Information comes from [chiraggude/awesome-laravel](https://github.com/chiraggude/awesome-laravel)
# Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/chiraggude/awesome-laravel/master.svg?style=flat)](https://travis-ci.org/chiraggude/awesome-laravel)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Code Snippets](#code-snippets)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
- [Videos](#videos)
- [Conferences](#conferences)
- [Books](#books)
- [Starter Projects](#starter-projects)
- [Codebases for Reference](#codebases-for-reference)
- [Content Management Systems](#content-management-systems)
- [Newsletters](#newsletters)
- [Podcasts](#podcasts)
- [Community](#community)
- [Jobs](#jobs)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)

## Essentials

* [Laravel](https://laravel.com)
* [Laravel Documentation](https://laravel.com/docs)
* [Laravel API Reference](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com)
* [Lumen Documentation](https://lumen.laravel.com/docs)
* [Laracasts](https://laracasts.com)
* [Laravel News](https://laravel-news.com)

## Code Snippets

* [Laravel Cheat Sheet](http://cheats.jesse-obrien.ca)
* [Laravel 5.1 LTS Cheat Sheet ](https://summerblue.github.io/laravel5-cheatsheet/) ([Chinese version](https://cs.phphub.org/))
* [Laravel Tricks](http://laravel-tricks.com/)
* [Laravel Recipes](http://laravel-recipes.com/)

## Packages

* [Packagist](https://packagist.org/)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Cartalyst](https://cartalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## Popular Packages

> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel :star:517
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion :star:6129
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators :star:1736
* [Laravel API/Scaffold/CRUD Generator](http://labs.infyom.com/laravelgenerator/) - Generator for APIs, CRUD scaffolds etc.
* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app.
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation from your existing Laravel routes. :star:1208
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages :star:462
* [Workbench Export to Migrations](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - Workbench plugin for exporting Models to Laravel migrations :star:495
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - List all installed packages, their dependencies, app & server details :star:327

##### Debugging & Profiling
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps :star:1651
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel :star:6616
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer :star:1484
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer for Laravel 5 :star:972
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - LERN is a Laravel 5 package that will record exceptions into a database and will send you a notification
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client :star:565
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger :star:285
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes :star:237

##### Authentication & Authorization

* [Bouncer](https://github.com/JosephSilber/bouncer) - Roles & Permissions :star:1411
* [Laratrust](https://github.com/santigarcor/laratrust) - Roles, Permissions and teams :star:816
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions :star:5519
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs :star:5498
* [Laravel Permission](https://github.com/spatie/laravel-permission) - Associate users with roles and permissions :star:2920
* [Defender](https://github.com/artesaos/defender) - Roles & Permissions :star:327
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server :star:2338
* [Laravel Roles](https://github.com/romanbican/roles) - Roles And Permissions :star:1166
* [Sentinel](https://github.com/cartalyst/sentinel) - Framework agnostic authentication & authorization system :star:1053
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc. :star:2933
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100+ social authentication providers for Socialite with Lumen support
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module :star:749
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - Handle the user verification flow and validate email :star:513
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP authentication and Active Directory management :star:362
* [Doorman](https://github.com/clarkeash/doorman) - Limit access to your Laravel applications by using invite codes. :star:584

##### Utilities

* [Artisan View](https://github.com/svenluijten/artisan-view) - Manage the views in Laravel projects via artisan. :star:338
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Captcha](https://github.com/mewebstudio/captcha) - Captcha for Laravel 5 - An anti-bot image captcha system. :star:982
* [Charts](https://github.com/ConsoleTVs/Charts) - Multi-library chart package to create interactive charts. :star:1286
* [Datatable](https://github.com/Chumper/Datatable) - Server-side and client-side integration for jQuery Datatables plugin :star:407
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - An Eloquent Way To Filter Laravel Models And Their Relationships :star:290
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models :star:1873
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Sortable behaviour for Eloquent models :star:363
* [Presenter](https://github.com/laracasts/Presenter) - Presenter for Models :star:605
* [HTML](https://github.com/LaravelCollective/html) - HTML and Form Builders for Laravel :star:1447
* [Hyn/multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of a.o. routes, assets and databases :star:541
* [Laravel 5 form builder](https://github.com/kristijanhusak/laravel-form-builder) - Form builder for Laravel 5 inspired by Symfony's form builder. :star:803
* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images :star:6489
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - Log activity inside your Laravel app :star:1367
* [Laravel Auditing](https://github.com/owen-it/laravel-auditing) - Audit for Eloquent models :star:795
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - A Blade directive to export variables to JavaScript :star:281
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs :star:1251
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - A set of handy collection macros :star:459
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - Make your Laravel app comply with the crazy EU cookie law :star:272
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - jQuery DataTables API for Laravel 4|5 :star:1949
* [Laravel Dot Env Generator](https://github.com/mathiasgrimm/laravel-dot-env-gen) - Generate .env.gen file based on the project source code :star:175
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files :star:4517
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - Get notified when a queued job fails :star:337
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the geographical location of website visitors based on their IP addresses :star:640
* [Laravel Glide](https://github.com/spatie/laravel-glide) - Easily convert images with Glide :star:249
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users :star:382
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser :star:660
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models :star:1844
* [Laravel Menu](https://github.com/spatie/laravel-menu) - Html menu generator for Laravel :star:327
* [Laravel Talk](https://github.com/nahid/talk) - Realtime User messaging system :star:897
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system :star:1419
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - A simple Moderation System for Laravel 5.* that allows you to Approve or Reject resources like posts, comments, users, etc. :star:322
* [Laravel Paginateroute](https://github.com/spatie/laravel-paginateroute) - Laravel router extension to easily use Laravel's paginator without the query string :star:264
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - A pjax middleware for Laravel 5 :star:347
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up a Laravel app by caching the entire response :star:628
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf :star:896
* [Laravel DOMPDF](https://github.com/barryvdh/laravel-dompdf) - HTML to PDF generator using [dompdf](https://github.com/dompdf/dompdf) :star:4434
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager :star:539
* [Laravel url signer](https://github.com/spatie/laravel-url-signer) - Create and validate signed URLs with a limited lifetime :star:428
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command :star:249
* [Laravel Tags](https://github.com/spatie/laravel-tags) - Add tags and taggable behaviour to your Laravel app :star:368
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - A powerful and easy to configure uptime and ssl monitor :star:464
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store :star:1460
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model :star:102
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Purifier](https://github.com/mewebstudio/purifier) - HTMLPurifier for Laravel 5 - HTML filter :star:732
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models :star:1493
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques :star:862
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - Persistent configuration settings that are stored in JSON files :star:355
* [Friendship](https://github.com/hootlex/laravel-friendships) - Friendship management system - send, receive, accept, deny friend requests :star:420
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system :star:568
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models :star:736
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations :star:529
* [Laravel Uuid](https://github.com/webpatser/laravel-uuid) - Laravel package to generate a UUID according to the RFC 4122 standard :star:878
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - Laravel package to allow users to install your application just by following the setup wizard, like WordPress :star:771
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models :star:334
* [Laravel-modules](https://github.com/nWidart/laravel-modules) - Easy Module Management In Laravel :star:1092
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - Phone number validator and formatter. :star:617
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - Laravel Ban simplify blocking and banning Eloquent models. :star:161
* [Laravel Proxy](https://github.com/fideloper/TrustedProxy) - Laravel Proxy Package for handling sessions when behind load balancers or other intermediaries. :star:1836

##### Working with Javascript

* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript :star:620
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - Pass server-side string/array/collection/whatever to JavaScript :star:1569
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client side without need to write any Javascript code :star:452
* [ziggy](https://github.com/tightenco/ziggy) - Use your Laravel named routes in JavaScript :star:717

##### Databases, ORMs, Migrations & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc. :star:487
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - Nested Sets pattern implementation :star:1305
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation :star:263
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models :star:319
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table :star:931
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver for Laravel 4|5 via OCI8 :star:344
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app :star:2254
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation :star:463
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB :star:3136
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database :star:1849
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM :star:752
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager :star:368
* [Laravel Repository](https://github.com/andersao/l5-repository) - Repositories to abstract the database layer for Laravel 5 :star:2293

##### Search

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM :star:237
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models :star:646
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch :star:368
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch :star:284
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch :star:345
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models :star:1214
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP :star:1310

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys :star:607
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs :star:7108
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support :star:2340
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal in Laravel and Lumen :star:982
* [Laravel GraphQL](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5. It supports Relay, eloquent models, validation and GraphiQL. :star:1069
* [Laravel Responder](https://github.com/flugger/laravel-responder) - A Laravel Fractal package for building API responses, giving you the power of Fractal with Laravel's elegancy. :star:347

##### Tasks, Commands and Scheduling

* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands :star:1026
* [Elixir](https://github.com/laravel/elixir) - Node(NPM) package to run Gulp tasks that watch files, run tests, minify CSS, concatenate scripts etc. :star:1094
* [Mix](https://github.com/JeffreyWay/laravel-mix) - Laravel Mix provides a clean, fluent API for defining basic webpack build steps for your Laravel application. Mix supports several common CSS and JavaScript pre-processors. :star:2010
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner :star:1012

##### Payments

* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe :star:1235
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library :star:307

##### Optimization

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class :star:335
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier :star:540
* [Rememberable](https://github.com/dwightwatson/rememberable) - Query caching for Laravel 5 (eloquent)
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Page Partial caching for Laravel 5 :star:316
* [Widgets for Laravel](https://github.com/arrilot/laravel-widgets) - A powerful alternative to view composers. Asynchronous widgets, reloadable widgets, console generator, caching - everything you can think of. :star:381

##### Localization

* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages :star:2565
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes :star:1564
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON. :star:442
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances :star:1442
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - Translate Eloquent models into multiple languages :star:259
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon :star:1122
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - Manage language files from Artisan Console :star:743
* [Laravel Translation](https://github.com/waavi/translation) - Allow live edit/caching of translation entries, and localization of urls and Eloquent Model attributes. :star:238
* [Linguist](https://github.com/keevitaja/linguist) - i18n localization support for Laravel :star:176

##### Third-party Service Integration

* [Laravel Algolia](https://github.com/vinkla/laravel-algolia) - Algolia API bridge :star:65
* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - An opinionated Laravel 5 package to retrieve pageviews and other data from Google Analytics :star:1298
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge :star:211
* [Laravel Dropbox](https://github.com/GrahamCampbell/Laravel-Dropbox) - Dropbox bridge :star:122
* [Laravel Facebook](https://github.com/vinkla/laravel-facebook) - Facebook API bridge :star:79
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge :star:247
* [Laravel GitLab](https://github.com/vinkla/laravel-gitlab) - GitLab API bridge :star:145
* [Laravel Googletagmanager](https://github.com/spatie/laravel-googletagmanager) - Easily setup and send data to Google Tag Manager :star:126
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API bridge :star:300
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp :star:660
* [Laravel Parse](https://github.com/GrahamCampbell/Laravel-Parse) - PHP Parse SDK bridge :star:115
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API bridge :star:322
* [Laravel Pushwoosh](https://github.com/hoymultimedia/Laravel-Pushwoosh) - Pushwoosh API bridge :star:31
* [Laravel Vimeo](https://github.com/vinkla/laravel-vimeo) - Vimeo API bridge :star:175


## Development Setup

* [Homestead](https://laravel.com/docs/5.3/homestead) - Official Vagrant box for Laravel
  * [Getting Started with Laravel Homestead](https://scotch.io/tutorials/getting-started-with-laravel-homestead)
  * [Installation on macOS and Linux](https://laracasts.com/series/laravel-5-from-scratch/episodes/3)
  * [Installation on  Windows](http://blog.teamtreehouse.com/laravel-homestead-on-windows)
* [Valet](https://laravel.com/docs/5.3/valet/) - Development environment for Mac users
* [Valet Linux](https://github.com/cpriego/valet-linux) - Development environment for Linux users :star:491
* [LaraDock](https://github.com/LaraDock/laradock) - Run Laravel on Docker (Like Homestead but for Docker instead of Vagrant)
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - Homestead environment in a single Docker container :star:357
* [Laragon](https://laragon.org/) -  Isolated development environment on Windows
* [Stacker](https://maxlab.github.io/stacker/) - The environment for local web development on Docker.

## Application Hosting

* [Forge](https://forge.laravel.com/)
  * [Server Management with Forge](https://laracasts.com/series/server-management-with-forge) (Laracasts)
  * [Getting your first site up and running in Laravel Forge](https://mattstauffer.co/blog/getting-your-first-site-up-and-running-in-laravel-forge) (Matt Stauffer)
  * [ForgeRecipes](http://forgerecipes.com/)
* [FortRabbit](https://www.fortrabbit.com/laravel-hosting) ([Video](https://laracasts.com/lessons/from-zero-to-deploy-with-fortrabbit))
* [PagodaBox](https://pagodabox.io/) ([Documentation](https://pagodabox.io/docs/framework_laravel))
* [Heroku](https://www.heroku.com/) ([Tutorial](https://mattstauffer.co/blog/installing-a-laravel-app-on-heroku))
* [IBM BlueMix](https://console.ng.bluemix.net/) ([Tutorial](https://developer.ibm.com/bluemix/2014/06/17/getting-started-laravel-bluemix/))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([Tutorial](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html#php-laravel-tutorial-deploy))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)

## Application Deployment

* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
 * [Deployments with Envoyer](https://laracasts.com/series/envoyer) (Laracasts)
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package :star:2570

## Articles, Tutorials, Blogs etc.

* [Tuts+](http://code.tutsplus.com/categories/laravel)
* [SitePoint](https://www.sitepoint.com/php/page/0/?filter[4047]=on)
* [Medium](https://medium.com/tag/laravel/latest)
* [Christopher Pitt](https://medium.com/laravel-4)
* [Culttt](http://culttt.com/tag/cribbb/)
* [Scotch](https://scotch.io/tag/laravel)
* [Fideloper](http://fideloper.com/tag/laravel)
* [Maxoffsky](https://maxoffsky.com/tag/laravel/)
* [KodeInfo](http://kodeinfo.com/main_category/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/tags/laravel)
* [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
* [Ryan Tablada](http://ryantablada.com/tag/Laravel)
* [Mohamed Said](https://themsaid.com/)
* [Mohammad Gufran](http://www.gufran.me/tag/Laravel/)
* [Adam Engebretson](http://blog.enge.me/4)
* [CodeHeaps](http://www.codeheaps.com/)
* [Laravel India](http://blog.laravel.in/)
* [Vegi Bit](http://vegibit.com/tag/laravel/)
* [WSnippets](http://wsnippets.com/category/laravel/)
* [Kirk Bushell](http://kirkbushell.me/)
* [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
* [DeveloPHP](http://www.develophp.org/category/web/laravel/)
* [Jason Lewis](http://jasonlewis.me/category/laravel)
* [Eric Barnes](https://ericlbarnes.com/tag/laravel/)
* [Jens Segers](https://jenssegers.com/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Stidges](http://blog.stidges.com/)
* [Scott Wilcox](https://dor.ky/tag/laravel/)
* [Clivern](http://clivern.com/tag/laravel/)
* [Code Gains](http://codegains.com/tag/laravel-2/)
* [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Bosnadev](https://bosnadev.com/tag/laravel-2/)
* [Vedovelli (PT-BR)](http://www.vedovelli.com.br/tag/laravel/)
* [CodeTutorial](https://www.codetutorial.io/tag/laravel/)
* [Ryan Chenkie](http://ryanchenkie.com/tag/laravel/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](https://tuts.codingo.me/category/web-development/laravel)
* [Antonio Carlos Ribeiro](https://antoniocarlosribeiro.com/technology)
* [Laravel Coding](http://laravelcoding.com/blog)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/cursos/) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel)(ES)
* [Laravel Daily](http://laraveldaily.com/)
* [Freek Van der Herten](https://murze.be/tag/laravel/)
* [ForLaravel](https://forlaravel.com/)
* [Good Heads](http://goodheads.io/category/laravel/)
* [Ryan Stelmat](http://ryanstelmat.com/tag/laravel/)
* [Cloudways Laravel Blog](http://cloudways.com/blog/laravel)

## Videos

* [Laracasts](https://laracasts.com/)
* [Codecourse](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel&lang=en)
* [Treehouse](https://teamtreehouse.com/library/q:laravel)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Lynda](https://www.lynda.com/Laravel-training-tutorials/2779-0.html)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Laracademy](https://laracademy.co/)
* [Dev Marketer](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)

## Conferences

* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [Laraconf Brasil](http://laraconfbrasil.com.br/)
* [Laracon Online](https://laracon.net/)

##### Videos

* [Laracon EU 2017](https://www.youtube.com/watch?v=JPxhnRh1Rr8&list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Larcaon US 2017](https://streamacon.com/video/laracon-us-2017)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon US 2016](https://streamacon.com/video/laracon-us)
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* [Laracon EU 2014](http://laracon.eu/2014/#schedule)
* [Laracon US 2014](http://userscape.com/laracon/2014/)
* [Laracon EU 2013](http://laracon.eu/2013/talks/)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## Books

* [Laravel Starter](https://www.packtpub.com/web-development/laravel-starter) by Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: Code Smart](https://leanpub.com/codesmart) by Dayle Rees
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way
* [Refactoring to Collections](https://adamwathan.me/refactoring-to-collections/) by Adam Wathan
* [Implementing Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel) by Chuck Heintzelman
* [Laravel Application Development Blueprints](https://www.packtpub.com/web-development/laravel-application-development-blueprints) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by Phil Sturgeon
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel Design Patterns and Best Practices](https://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Step by Step Real World Application with Laravel 4](https://leanpub.com/real-world-laravel4) by Ibrahim Yusuf
* [Learning Laravel 4 Application Development](https://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Getting Started with Laravel 4](https://www.packtpub.com/web-development/getting-started-laravel-4) by Raphaël Saunier
* [Laravel Application Development Cookbook](https://www.packtpub.com/web-development/laravel-application-development-cookbook) by Terry Matula
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api) by Mhd Zaher Ghaibeh
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework) by Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) by W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce) by W. Jason Gilmore and Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign) by Kelt Dockins
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) by Christopher John Pecoraro
* [How to Build Real-Time Laravel Apps with Pusher](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [Learning Laravel's Eloquent](https://www.packtpub.com/web-development/learning-laravel%E2%80%99s-eloquent) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel and AngularJS](https://leanpub.com/laravel-and-angularjs) by Daniel Schmitz and Daniel Pedrinha Georgii
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [Writing APIs With Lumen](https://leanpub.com/lumen-apis) by Paul Redmond
* [The Laravel Survival Guide](https://leanpub.com/laravelsurvivalguide) by Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck
* [Laravel 5.3 For Beginners](https://leanpub.com/laravel-5-3-for-beginners) by Bill Keck
* [Laravel Up & Running](https://laravelupandrunning.com/)

## Starter Projects

* [LaraAdmin](http://laraadmin.com/)
* [Laracogs](https://github.com/yabhq/laracogs) :star:828
* [Laravel 5.2 Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate) :star:2715
* [Laravel 5 Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter) :star:1692
* [Acacha adminlte-laravel](https://github.com/acacha/adminlte-laravel) :star:1433
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter) :star:1323
* [Laravel API](https://github.com/joselfonseca/laravel-api) :star:168
* [Laravel Angular AdminLTE](https://github.com/silverbux/laravel-angular-admin) :star:843
* [Backpack for Laravel](https://backpackforlaravel.com)
* [Starter Someline](https://starter.someline.com)
* [Laravel-admin](https://github.com/z-song/laravel-admin) :star:2948
* [Voyager](https://the-control-group.github.io/voyager/)
* [Orchid](https://github.com/TheOrchid/Platform) :star:741
* [Laravel REST API Boilerplate](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt) :star:698
* [Hello API](https://github.com/Porto-SAP/Hello-API) :star:1174
* [REST API With Lumen 5.4](https://github.com/hasib32/rest-api-with-lumen) :star:289
* [Laravel Zero - Console application](https://github.com/laravel-zero/laravel-zero) :star:1045
* [Apiato - A framework for building scalable API-Centric Applications with PHP.](https://github.com/apiato/apiato) :star:1174

## Codebases for Reference

* [92Five](https://github.com/chintanbanugaria/92five) - Project management application :star:1079
* [Cachet](https://github.com/cachethq/Cachet) - Status page system for websites and APIs :star:7667
* [Deployer](https://github.com/REBELinBLUE/deployer) - Application deployment system :star:617
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - Task management of the day-to-day. Git + Scrum = Team More Productive :star:2063
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - Invoicing, expenses, & time-tracking application :star:3366
* [Koel](https://github.com/phanan/koel) - Personal music streaming server :star:8770
* [Laravel Tricks](https://github.com/CodepadME/laravel-tricks) - Source for the Laravel Tricks website :star:928
* [Laravel.io](https://github.com/laravelio/laravel.io) - Source for the Laravel.io Community Portal :star:1281
* [Paperwork](https://github.com/twostairs/paperwork) - Note-taking & archiving application :star:6304
* [PHPHub](https://github.com/summerblue/phphub) - Forum and source for the PHP & Laravel China community :star:1836
* [Flarum](https://github.com/flarum/flarum) - Delightfully simple forum :star:7281
* [Attendize](https://github.com/Attendize/Attendize) - Ticket selling and event management platform :star:1964
* [Katana](https://github.com/themsaid/katana) - Static site/blog generator with markdown support :star:373
* [Antvel](https://github.com/ant-vel/App) - Ecommerce platform :star:322
* [Jigsaw](http://jigsaw.tighten.co) - Static site generator
* [Canvas](https://github.com/austintoddj/Canvas) - Minimal Blogging Application For Developers. :star:1422
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo is blog platform, built with Laravel and Vue.js :star:1647
* [Screeenly](https://github.com/stefanzweifel/screeenly) - Create website screenshots through an API :star:129
* [Voten](https://github.com/voten-co/voten) - A real-time social bookmarking for the 21st century :star:792

## Content Management Systems

* [OctoberCMS](http://octobercms.com/)
* [PyroCMS](https://www.pyrocms.com/)
* [Lavalite](http://www.lavalite.org/)
* [Bootstrap CMS](https://github.com/BootstrapCMS/CMS) :star:2312
* [TypiCMS](https://github.com/typicms/base) :star:576
* [Asgard CMS](https://asgardcms.com/)
* [Microweber](https://microweber.com/)
* [Coaster CMS](https://www.coastercms.org/)
* [Statamic](https://statamic.com/)
* [Quarx](https://github.com/yabhq/quarx) :star:375
* [WebEd CMS](https://github.com/sgsoft-studio/webed) :star:382
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/)
* [PJ Blog](https://github.com/jcc/blog/)
* [Laralum](https://laralum.com/)

## Newsletters

* [Laravel News](https://laravel-news.com/) ([archive](https://laravel-news.com/archive/))
* [Laravel Weekly](http://laravelweekly.com/)

## Podcasts

* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](https://laravel-news.com/podcast/ )
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (Spanish)](http://hechoenlaravel.com)

## Community

* [Laracasts Forum](https://laracasts.com/discuss)
* [Laracasts Forum](https://laracasts.com/discuss)
* [Laravel.io Forum](http://laravel.io/forum)
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.co/slack))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](https://www.quora.com/topic/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/4419933/profile)
* [Laraveles Slack](https://laraveles.slack.com) ([Signup](http://laraveles.com/blog/wp-login.php?action=slack-invitation))
* [Laravel UK](https://twitter.com/UKLaravel), [Slack Signup](http://laraveluk.signup.team)
##### Local User Groups

* [Laravel Russia](https://laravel.ru/) ([VK group](http://m.vk.com/laravel_rus))
* [Laravel France](https://laravel.fr/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook group](https://www.facebook.com/groups/laravel/))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook group](https://www.facebook.com/groups/laravelbrasil/), [Slack](http://slack.laravel.com.br), [Telegram](https://telegram.me/laravelbr), [Google+](https://plus.google.com/communities/116661672628675028624), [GitHub](https://github.com/laravelbrasil))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook group](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laranaija.com/) ([Facebook group](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](https://phphub.org/)
* [Laravel Taiwan](https://laravel.tw/) ([Facebook group](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](https://www.laravel.co.kr/) ([Facebook group](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Japan](http://laravel.jp/) ([Facebook group](https://www.facebook.com/groups/laravel.jp/))
* [Laravel Tokyo](https://laravel.tokyo/) ([Facebook group](https://www.facebook.com/groups/laraveltokyo/))
* [Laravel Malaysia](https://www.facebook.com/groups/laravel.my/)
* [Laravel Algeria Facebook Group](https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel Greece](http://www.laravel.gr) ([Facebook page](https://www.facebook.com/laravelgr))
* [Laravel Middle East](http://laravelme.com/) ([Facebook page](https://www.facebook.com/laravelme))
* [Laravel Georgia](https://www.facebook.com/groups/laravel.georgia/)
* [Laravel Italy](http://laravel-italia.it)
* [Laravel Viet Nam](https://www.facebook.com/groups/vietnam.laravel/)
* [Laravel Slovenia](https://www.facebook.com/groups/laravelslovenija/)
* [Laravel Hungary](https://laravel.hu)

##### Meetups

* [All Meetups](http://www.meetup.com/topics/laravel/)
* [London Meetup](https://www.meetup.com/London-Laravel/)
* [Buenos Aires, Argentina Meetup](https://www.meetup.com/Laravel-Buenos-Aires/)
* [Morocco Meetup](https://www.meetup.com/moroccophp/)
* [Athens-Greece Meetup](https://www.meetup.com/athens-laravel-meetup/)
* [Copenhagen Meetup](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [Detroit Meetup](https://www.meetup.com/Laravel-Detroit/)
* [Paris Meetup](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [Melbourne, Australia Meetup](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [Budapest Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

## Jobs

* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](https://laravelgurus.com/)

## Hosted Development Tools

* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Versions {x.y.z}](https://laraver.xyz/) - Monitor Laravel for updates
* [Laragen](http://makzumi.com/laragen/) - View generator
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [Laravel Database Designer](http://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - Graphical tool to create database schemas
* [StyleCI](https://styleci.io) - PHP Coding Style Service
* [DependenCI](https://dependenci.miguelpiedrafita.com) - Continous integration tool for Composer

## Miscellaneous

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins

## Contributing

Found an awesome package, blog, video etc.? Send me a pull request!

#### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the Travis tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome Laravel is licensed under a  [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


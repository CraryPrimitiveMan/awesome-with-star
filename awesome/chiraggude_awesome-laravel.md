# Information comes from [chiraggude/awesome-laravel](https://github.com/chiraggude/awesome-laravel)
# Awesome Laravel [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://img.shields.io/travis/chiraggude/awesome-laravel/master.svg?style=flat)](https://travis-ci.org/chiraggude/awesome-laravel)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

Inspired by [ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)

## Table of Contents

- [Essentials](#essentials)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Code Snippets](#code-snippets)
- [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
- [Videos](#videos)
- [Conferences](#conferences)
- [Books](#books)
- [Starter Projects](#starter-projects)
- [Codebases for Reference](#codebases-for-reference)
- [Content Management Systems](#content-management-systems)
- [Podcasts](#podcasts)
- [Community](#community)
- [Jobs](#jobs)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)

## Essentials

* [Laravel](https://laravel.com) ([Documentation](https://laravel.com/docs))
* [Laravel API Reference](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com) ([Documentation](https://lumen.laravel.com/docs))
* [Laracasts](https://laracasts.com)
* [Laravel News](https://laravel-news.com) ([Archive](https://laravel-news.com/archive/))

## Packages

* [Packagist](https://packagist.org/)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## Popular Packages

> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel :star:647
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion :star:7364
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators :star:1976
* [Laravel API/Scaffold/CRUD Generator](https://github.com/InfyOmLabs/laravel-generator) - Generator for APIs, CRUD scaffolds etc. :star:2080
* [Laravel Tinx](https://github.com/furey/tinx) - Reload your Laravel Tinker session from inside Tinker :star:283
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation :star:1645
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages :star:564
* [Workbench Export to Migrations](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - Workbench plugin for exporting Models to Laravel migrations :star:621
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - List all installed packages, their dependencies, app & server details :star:385
* [LaRecipe](https://github.com/saleem-hadad/larecipe) - Write gorgeous documentations for your products using Markdown inside your Laravel app. :star:598

##### Testing & Debugging

* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models :star:382
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps :star:2002
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel :star:8244
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer :star:1838
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer :star:1244
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - Record exceptions into a database and will send you a notification :star:381
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client :star:598
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger :star:328
* [Laravel Terminal](https://github.com/recca0120/laravel-terminal) - run artisan in a web browser :star:522
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes :star:259
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command :star:351

##### Authentication & Authorization

* [Bouncer](https://github.com/JosephSilber/bouncer) - Roles & Permissions :star:1859
* [Laratrust](https://github.com/santigarcor/laratrust) - Roles, Permissions and teams :star:1055
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions :star:5924
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs :star:6835
* [Laravel Permission](https://github.com/spatie/laravel-permission) - Associate users with roles and permissions :star:4738
* [Defender](https://github.com/artesaos/defender) - Roles & Permissions :star:357
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server :star:2381
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc. :star:3507
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100+ social authentication providers for Socialite with Lumen support
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module :star:899
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - Handle the user verification flow and validate email :star:641
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP authentication and Active Directory management :star:494
* [Doorman](https://github.com/clarkeash/doorman) - Limit access to your Laravel applications by using invite codes :star:662

##### Utilities

* [Artisan View](https://github.com/svenluijten/artisan-view) - Manage the views in Laravel projects via artisan :star:440
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup :star:574
* [Captcha](https://github.com/mewebstudio/captcha) - An anti-bot image captcha system :star:1229
* [Charts](https://github.com/ConsoleTVs/Charts) - Multi-library chart package to create interactive charts :star:1530
* [Lavacharts](https://github.com/kevinkhill/lavacharts) - Charts and Graphs for PHP Powered by the Google Chart API :star:466
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - Filter models and their Relationships :star:462
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models :star:2261
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Sortable behaviour for Eloquent models :star:495
* [HTML](https://github.com/LaravelCollective/html) - HTML and Form Builders for Laravel :star:2209
* [Multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of routes, assets and databases :star:1104
* [Laravel Form Builder](https://github.com/kristijanhusak/laravel-form-builder) - Form builder inspired by Symfony's form builder :star:1067
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - Log activity inside your Laravel app :star:1899
* [Laravel Auditing](https://github.com/owen-it/laravel-auditing) - Audit for Eloquent models :star:1125
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs :star:1679
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - A set of handy collection macros :star:566
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - Make your Laravel app comply with the crazy EU cookie law :star:415
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - jQuery DataTables API :star:2504
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the location of website visitors based on their IP addresses :star:1154
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users :star:562
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser :star:772
* [Laravel Menu](https://github.com/spatie/laravel-menu) - Html menu generator for Laravel :star:449
* [Laravel Talk](https://github.com/nahid/talk) - Realtime User messaging system :star:1062
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system :star:1596
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - Approve or reject resources like posts, comments, users, etc. :star:372
* [Laravel Paginateroute](https://github.com/spatie/laravel-paginateroute) - Use Laravel's paginator without the query string :star:309
* [Laravel URL Signer](https://github.com/spatie/laravel-url-signer) - Create and validate signed URLs with a limited lifetime :star:506
* [Laravel Tags](https://github.com/spatie/laravel-tags) - Add tags and taggable behaviour :star:517
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store :star:1737
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model :star:118
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA) :star:236
* [Purifier](https://github.com/mewebstudio/purifier) - HTML filter :star:959
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models :star:1698
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques :star:1132
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - Persistent configuration settings that are stored in JSON files :star:437
* [Friendship](https://github.com/hootlex/laravel-friendships) - Friendship management system :star:487
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system :star:647
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models :star:771
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations :star:602
* [Laravel UUID](https://github.com/webpatser/laravel-uuid) - Generate a UUID according to the RFC 4122 standard :star:1175
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - Allow users to install your application just by following the setup wizard, like WordPress :star:936
* [Laravel Modules](https://github.com/nWidart/laravel-modules) - Easy module management :star:1706
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - Phone number validator and formatter :star:836
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - Simplify blocking and banning Eloquent models :star:263
* [Laravel Proxy](https://github.com/fideloper/TrustedProxy) - Handling sessions when behind load balancers or other intermediaries. :star:3980
* [Laravel Video Chat](https://github.com/PHPJunior/laravel-video-chat) - Video Chat using Socket.IO and WebRTC :star:337
* [Widgets for Laravel](https://github.com/arrilot/laravel-widgets) - A powerful alternative to view composers. :star:583

##### Media & Document Management

* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images :star:8095
* [Laravel ImageUp](https://github.com/qcod/laravel-imageup) - Yet another image manipulation package, adds tons of extra functionality :star:329
* [Laravel Glide](https://github.com/spatie/laravel-glide) - Easily convert images with Glide :star:270
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models :star:2537
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf :star:1200
* [Laravel DOMPDF](https://github.com/barryvdh/laravel-dompdf) - HTML to PDF generator using [dompdf](https://github.com/dompdf/dompdf) :star:5218
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager :star:559
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files :star:5889
* [Fast Excel](https://github.com/rap2hpoutre/fast-excel) - Fast XLSX, CSV and ODT import and export for Laravel :star:287

##### Integration with Javascript

* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript :star:688
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - Pass server-side string/array/collection/whatever to JavaScript :star:1776
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client-side :star:651
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - A Pjax middleware :star:397
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - A Blade directive to export variables to JavaScript :star:338
* [Ziggy](https://github.com/tightenco/ziggy) - Use your Laravel named routes in JavaScript :star:1011

##### Databases, ORMs, Migrations & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc. :star:530
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - Nested Sets pattern implementation :star:1658
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation :star:294
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models :star:340
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table :star:1193
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver via OCI8 :star:419
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app :star:2835
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation :star:537
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB :star:3668
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database :star:2289
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM :star:860
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager :star:402
* [Laravel Repository](https://github.com/andersao/l5-repository) - Repositories to abstract the database layer :star:2804
* [Lada Cache](https://github.com/spiritix/lada-cache) - A Redis based, fully automated and scalable database cache layer :star:214

##### Search

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM :star:237
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models :star:816
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch :star:430
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch :star:320
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch :star:372
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models :star:1402
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP :star:1549
* [TNTSearch driver](https://github.com/teamtnt/laravel-scout-tntsearch-driver) - Driver for [Laravel Scout](https://github.com/laravel/scout) search package based on TNTSearch :star:502

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys :star:657
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs :star:7862
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support :star:3216
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal :star:1222
* [Laravel GraphQL](https://github.com/Folkloreatelier/laravel-graphql) - Supports Relay, eloquent models, validation and GraphiQL :star:1614
* [Lighthouse](https://github.com/nuwave/lighthouse) - An up and coming GraphQL library for Laravel :star:251
* [Laravel Responder](https://github.com/flugger/laravel-responder) - Build custom API responses with Fractal :star:400

##### Tasks, Commands and Scheduling

* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands :star:1035
* [Elixir](https://github.com/laravel/elixir) - Node (NPM) package to run Gulp tasks :star:1100
* [Mix](https://github.com/JeffreyWay/laravel-mix) - Fluent API for defining basic webpack build steps :star:2835
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner :star:1116

##### Payments

* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe :star:1395
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library :star:352

##### Optimization

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class :star:408
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier :star:634
* [Rememberable](https://github.com/dwightwatson/rememberable) - Query caching for Eloquent :star:618
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Page Partial caching :star:419
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up app by caching the entire response :star:869

##### Monitoring

* [Horizon](https://github.com/laravel/horizon) - Monitor and configure queues with a simple web UI :star:2287
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - Get notified when a queued job fails :star:374
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - A powerful and easy to configure uptime and ssl monitor :star:541

##### Localization

* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages :star:3145
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes :star:1860
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON :star:602
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances :star:1704
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - Translate Eloquent models into multiple languages :star:273
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon :star:1369
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - Manage language files from Artisan Console :star:772
* [Laravel Translation](https://github.com/waavi/translation) - Translation and localization management :star:266
* [Linguist](https://github.com/keevitaja/linguist) - i18n localization support for Laravel :star:182

##### Third-party Service Integration

* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - Retrieve pageviews and other data from Google Analytics :star:1565
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge :star:242
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge :star:287
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API bridge :star:358
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp :star:835
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API bridge :star:360

## Development Setup

* [Homestead](https://laravel.com/docs/master/homestead) - Official Vagrant box for Laravel
* [Valet](https://laravel.com/docs/master/valet) - Development environment for Mac users
* [Valet Linux](https://github.com/cpriego/valet-linux) - Development environment for Linux users :star:623
* [LaraDock](https://github.com/LaraDock/laradock) - Run Laravel on Docker (Like Homestead but for Docker instead of Vagrant) :star:6459
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - Homestead environment in a single Docker container :star:394
* [Laragon](https://laragon.org/) -  Isolated development environment on Windows
* [Stacker](https://github.com/Maxlab/stacker) - The environment for local web development on Docker :star:329
* [Devilbox](https://github.com/cytopia/devilbox) - A dockerized and general-purpose LAMP/MEAN stack for every PHP version :star:1648
* [Vessel](https://vessel.shippingdocker.com) - Simple Docker development environments for Laravel.

## Application Hosting

* [Forge](https://forge.laravel.com/) ([ForgeRecipes](https://forgerecipes.com/))
* [FortRabbit](https://www.fortrabbit.com/laravel-hosting)
* [Heroku](https://www.heroku.com/) ([Documentation](https://devcenter.heroku.com/articles/getting-started-with-laravel))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([Tutorial](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)
* [Ploi](https://ploi.io/)
* [CodePier](https://codepier.io?ref=awesome-laravel)

## Application Deployment

* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package :star:2669

## Code Snippets

* [Laravel LTS Cheat Sheet ](https://summerblue.github.io/laravel5-cheatsheet/) ([Chinese version](https://cs.phphub.org/))
* [Laravel Tricks](http://laravel-tricks.com/)

## Articles, Tutorials, Blogs etc.

* [Tuts+](https://code.tutsplus.com/categories/laravel)
* [SitePoint](https://www.sitepoint.com/php/laravel-php/)
* [Medium](https://medium.com/tag/laravel/latest)
* [Scotch](https://scotch.io/tag/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/blog)
* [Mohamed Said](https://themsaid.com/)
* [Vegi Bit](https://vegibit.com/tag/laravel/)
* [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
* [Eric Barnes](https://ericlbarnes.com/tag/laravel/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Stidges](https://blog.stidges.com/)
* [Dor.ky](https://dor.ky/tag/laravel/)
* [Stillat](https://stillat.com/explore/categories/laravel-5)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](https://tuts.codingo.me/category/web-development/laravel)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/cursos/) (ES)
* [Laravel Daily](http://laraveldaily.com/blog/)
* [Freek Van der Herten](https://murze.be/tag/laravel/)
* [Cloudways Laravel Blog](http://cloudways.com/blog/laravel)
* [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices) :star:1528
* [KernelDev](https://www.kerneldev.com/category/web-development/laravel/)
* [Pusher Laravel Tutorials](https://pusher.com/tutorials?tag=Laravel)
* [Josip Crnkovic](https://crnkovic.me/tag/laravel/)

## Videos

* [Laracasts](https://laracasts.com/)
* [Codecourse](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Servers for Hackers](https://serversforhackers.com/laravel-perf)
* [Test-Driven Laravel](https://course.testdrivenlaravel.com/)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel) (ES)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Laracademy](https://laracademy.co/)
* [Dev Marketer](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel)
* [Lynda](https://www.lynda.com/search?q=laravel)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Bitfumes](https://www.youtube.com/bitfumes)

## Conferences

* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [Laracon Online](https://laracon.net/)
* [Laraconf Brasil](http://laraconfbrasil.com.br/)
* [Laracon Australia](https://laracon.com.au/)
* [Laravel Live UK](https://laravellive.uk/)
* [Laravel Live India](http://laravellive.in/)

##### Videos

* [Laracon US 2018](https://www.youtube.com/watch?v=3eyftAR5ilo&list=PL-yJve--iT5oM2LgF37VXsBb8Os4ZulIc)
* [Laracon EU 2017](https://www.youtube.com/watch?v=JPxhnRh1Rr8&list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Larcaon US 2017](https://streamacon.com/video/laracon-us-2017)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon US 2016](https://streamacon.com/video/laracon-us-2016)
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
* [Laravel 5.4 For Beginners](https://leanpub.com/laravel-5-4-for-beginners) by Bill Keck
* [Laravel Up & Running](https://www.amazon.com/gp/product/1491936088) by Matt Stauffer
* [Laravel Companion](https://leanpub.com/laravelcompanion-secondedition) by Johnathon Koster
* [Deploy Laravel on AWS with CloudFormation](https://leanpub.com/laravel-aws) by Lionel Martin
* [React Native and Laravel for Future Mobile Development](https://leanpub.com/rn_laravel) by Ega Radiegtya
* [Servers for Hackers](https://book.serversforhackers.com) by Chris Fidao
* [Full-Stack Vue.js 2 and Laravel 5](https://www.amazon.com/Full-Stack-Vue-js-Laravel-frontend-together/dp/1788299582) by Anthony Gore

## Starter Projects

* [Spark](https://spark.laravel.com/)
* [LaraAdmin](https://github.com/dwijitsolutions/laraadmin) :star:1094
* [Grafite Builder](https://github.com/GrafiteInc/Builder) :star:907
* [Laravel Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate) :star:3182
* [Laravel Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter) :star:1710
* [AdminLTE Laravel](https://github.com/acacha/adminlte-laravel) :star:1625
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter) :star:1401
* [Laravel API Starter Kit](https://github.com/joselfonseca/laravel-api) :star:217
* [Backpack for Laravel](https://github.com/Laravel-Backpack/Base) :star:674
* [SomelineStarter](https://github.com/someline/someline-starter) :star:817
* [Laravel Admin](https://github.com/z-song/laravel-admin) :star:4867
* [Voyager](https://github.com/the-control-group/voyager) :star:7116
* [Orchid](https://github.com/TheOrchid/Platform) :star:901
* [Laravel REST API Boilerplate](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt) :star:857
* [Hello API](https://github.com/Porto-SAP/Hello-API) :star:1596
* [REST API With Lumen](https://github.com/hasib32/rest-api-with-lumen) :star:358
* [Laravel Zero - Console application](https://github.com/laravel-zero/laravel-zero) :star:1496
* [Apiato](https://github.com/apiato/apiato) :star:1596
* [Laravel Adminpanel - A Laravel 5 Adminpanel](https://github.com/viralsolani/laravel-adminpanel) :star:335

## Codebases for Reference

* [Cachet](https://github.com/cachethq/Cachet) - Status page system for websites and APIs :star:8818
* [Deployer](https://github.com/REBELinBLUE/deployer) - Application deployment system :star:702
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - Task management with Git and Scrum :star:2284
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - Invoicing, expenses, & time-tracking application :star:3825
* [Koel](https://github.com/phanan/koel) - Personal music streaming server :star:9567
* [Laravel.io](https://github.com/laravelio/portal) - Source for the Laravel.io Community Portal :star:1390
* [Attendize](https://github.com/Attendize/Attendize) - Ticket selling and event management platform :star:2265
* [Antvel](https://github.com/ant-vel/App) - Ecommerce platform :star:465
* [Jigsaw](https://github.com/tightenco/jigsaw) - Static site generator :star:964
* [Canvas](https://github.com/austintoddj/Canvas) - Minimal Blogging Application For Developers :star:1528
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo is blog platform, built with Laravel and Vue.js :star:1879
* [Screeenly](https://github.com/stefanzweifel/screeenly) - Create website screenshots through an API :star:148
* [Voten](https://github.com/voten-co/voten) - A real-time social bookmarking for the 21st century :star:1017
* [Monica](https://github.com/monicahq/monica) - Personal relationship management system :star:5171
* [Snipe-IT](https://github.com/snipe/snipe-it) - IT asset/license management system :star:2422
* [Akaunting](https://github.com/akaunting/akaunting) - Accounting software for small businesses and freelancers :star:1204

## Content Management Systems

* [OctoberCMS](https://github.com/octobercms/october) :star:7611
* [SleepingOwlAdmin](https://github.com/LaravelRUS/SleepingOwlAdmin) :star:526
* [PyroCMS](https://github.com/pyrocms/pyrocms) :star:2837
* [Lavalite](https://github.com/LavaLite/cms) :star:1481
* [TypiCMS](https://github.com/typicms/base) :star:658
* [Asgard CMS](https://github.com/AsgardCms/Platform) :star:571
* [Microweber](https://github.com/microweber/microweber) :star:1016
* [Coaster CMS](https://github.com/web-feet/coastercms) :star:339
* [Statamic](https://statamic.com/)
* [Grafite CMS](https://github.com/GrafiteInc/CMS) :star:442
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/) :star:272
* [PJ Blog](https://github.com/jcc/blog/) :star:2090
* [Laralum](https://github.com/Laralum/Laralum) :star:280

## Podcasts

* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](https://laravel-news.com/podcast/ )
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (Spanish)](http://hechoenlaravel.com)

## Community

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
* [Laravel UK](https://laravelphp.uk/), [Slack Signup](https://laravelphp.uk/login/slack)

##### Local User Groups

* [Laravel Global Community](https://www.facebook.com/groups/group.laravel/)
* [Laravel Russia](https://laravel.ru/) ([VK group](http://m.vk.com/laravel_rus))
* [Laravel France](https://laravel.fr/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook group](https://www.facebook.com/groups/laravel/), [Telegram](https://t.me/laravelindonesia))
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
* [Laravel Cameroon](https://laravelcm.com/) ([Slack](https://laravelcm.slack.com), [GitHub](https://github.com/laravelcm), [Facebook page](https://www.facebook.com/laravelcm), [Twitter](https://twitter.com/laravelcm))

##### Meetups

* [All Meetups](http://www.meetup.com/topics/laravel/)
* [London Meetup](https://www.meetup.com/London-Laravel/)
* [Buenos Aires Meetup](https://www.meetup.com/Laravel-Buenos-Aires/)
* [Athens-Greece Meetup](https://www.meetup.com/athens-laravel-meetup/)
* [Copenhagen Meetup](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [Detroit Meetup](https://www.meetup.com/Laravel-Detroit/)
* [Paris Meetup](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [Melbourne Meetup](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [Budapest Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

## Jobs

* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](https://laravelgurus.com/)
* [Laravel Certification](https://laravel.com/certification/)

## Hosted Development Tools

* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Versions {x.y.z}](https://laraver.xyz/) - Monitor Laravel for updates
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [StyleCI](https://styleci.io) - PHP Coding Style Service
* [DependenCI](https://dependenci.miguelpiedrafita.com) - Continous integration tool for Composer

## Miscellaneous

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins

## Contributing

Found an awesome package, blog, course or video? Send me a pull request!

#### Guidelines

* Please make an individual pull request for each suggestion
* Make sure the Travis tests pass on your pull request
* Use the following format for links: \[Resource\]\(URL\)
* Want to suggest a package? Read the [Contribution Guide](https://github.com/chiraggude/awesome-laravel/blob/master/CONTRIBUTING.md)
* New categories or improvements to the existing categorization are welcome

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Awesome Laravel is licensed under a  [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


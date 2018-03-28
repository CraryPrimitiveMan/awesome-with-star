# Information comes from [hothero/awesome-rails-gem](https://github.com/hothero/awesome-rails-gem)
# Awesome Rails Gem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails product/service.

* [Rails Gem List](#rails-gem-list)
  * [User](#user)
  * [Active Record](#active-record)
  * [Plugins](#plugins)
  * [API](#api)
  * [Email](#email)
  * [File Uploading](#file-uploading)
  * [Searching](#searching)
  * [Scheduled/Recurrence Jobs](#scheduledrecurrence-jobs)
  * [View Helper](#view-helper)
  * [Environment Variables](#environment-variables)
  * [Admin Panel](#admin-panel)
  * [Logging](#logging)
  * [Debug](#debug)
  * [Coding Style](#coding-style)
  * [Testing](#testing)
  * [Production](#production)
  * [Error Logging](#error-logging)
  * [Database](#database)

## User

### Authentication
* [Devise](https://github.com/plataformatec/devise/) - Devise is a flexible authentication solution for Rails based on Warden.
* [Knock](https://github.com/nsarno/knock) - Seamless JWT authentication for Rails API. :star:1428
* [Clearance](https://github.com/thoughtbot/clearance) - Rails authentication with email & password. :star:2847
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs. :star:2340
* [Sorcery](https://github.com/Sorcery/sorcery) - Magical Authentication for Rails. Supports ActiveRecord, DataMapper, Mongoid and MongoMapper. :star:451

### Authorization
* [Pundit](https://github.com/elabs/pundit) - Pundit provides a set of helpers which guide you in leveraging regular Ruby classes and object oriented design patterns to build a simple, robust and scaleable authorization system. :star:5746
* [cancancan](https://github.com/CanCanCommunity/cancancan) - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries. :star:3950
* [rolify](https://github.com/RolifyCommunity/rolify) - Role management library with resource scoping. :star:2325
* [acl9](https://github.com/be9/acl9/) - Acl9 is a role-based authorization system that provides a concise DSL for securing your Rails application.


### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook) :star:1122
* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2) :star:949
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2) :star:139
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter) :star:514
* [omniauth-github](https://github.com/intridea/omniauth-github) :star:334
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2) :star:85

## Active Record
* [Enumerize](https://github.com/brainspec/enumerize) - Enumerated attributes with I18n and ActiveRecord/Mongoid support. It can be integrated with Simple Form. :star:1350
* [counter_culture](https://github.com/magnusvk/counter_culture) - Turbo-charged counter caches for your Rails app. Huge improvements over the Rails standard counter caches. :star:907
* [custom_counter_cache](https://github.com/cedric/custom_counter_cache) - A simple approach to creating a custom counter cache that can be used across multiple models. :star:52
* [Sequenced](https://github.com/djreimer/sequenced) - Sequenced is a simple gem that generates scoped sequential IDs for ActiveRecord models. :star:164
* [FriendlyId](https://github.com/norman/friendly_id) - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models. :star:4894
* [AASM](https://github.com/aasm/aasm) - State machines for Ruby classes (plain Ruby, Rails Active Record, Mongoid). :star:3253
* [PaperTrail](https://github.com/airblade/paper_trail) - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning. :star:5020
* [paranoia](https://github.com/rubysherpas/paranoia) - ActiveRecord plugin allowing you to hide and restore records without actually deleting them. :star:2226
* [Validates](https://github.com/kaize/validates) - Validates provides collection of useful custom validators for Rails applications, including: :star:136
  * EmailValidator
  * UrlValidator
  * SlugValidator
  * MoneyValidator
  * IpValidator
  * AssociationLengthValidator
  * AbsolutePathValidator
  * UriComponentValidator
  * ColorValidator
  * EanValidator (EAN-8 & EAN-13)
* [globalize](https://github.com/globalize/globalize) - Rails I18n de-facto standard library for ActiveRecord model/data translation. :star:1699
* [deep_cloneable](https://github.com/moiristo/deep_cloneable) - This gem gives every ActiveRecord::Base object the possibility to do a deep clone that includes user specified associations. :star:445
* [social_shares](https://github.com/Timrael/social_shares) - Check how many times url was shared in social networks. :star:298
* [public_activity](https://github.com/chaps-io/public_activity) - Easy activity tracking for models - similar to Github's Public Activity. :star:2512
* [goldiloader](https://github.com/salsify/goldiloader) - Automatic ActiveRecord eager loading to reduce the number of database queries run by your application. :star:679
* Tagging
  * [ActsAsTaggableOn](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts. :star:4225
  * [closure_tree](https://github.com/mceachen/closure_tree) - Easily and efficiently make your ActiveRecord models support hierarchies. :star:1183
* [ActionStore](https://github.com/rails-engine/action-store) - Store different kind of actions (Like, Follow, Star, Block ...) in one table via ActiveRecord Polymorphic Association. :star:222

## Plugins
* [Spreadsheet](https://github.com/zdavatz/spreadsheet) - Library is designed to read and write Spreadsheet Documents. :star:835
* [Chartkick](https://github.com/ankane/chartkick) - Chartkick helps your to create beautiful Javascript charts with one line of Ruby. :star:4734
* [kaminari](https://github.com/amatsuda/kaminari) - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3 and 4. :star:7013
* [CKEditor](https://github.com/galetahub/ckeditor) - CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor. [ckeditor.com](http://ckeditor.com)
* [HTML::Pipeline](https://github.com/jch/html-pipeline) - GitHub HTML processing filters and utilities. This module includes a small framework for defining DOM based content filters and applying them to user provided content. :star:1878
* [Slack Notifier](https://github.com/stevenosloan/slack-notifier) is a simple wrapper to send notifications to [Slack](https://slack.com/) webhooks.
* [Rails ERD](https://github.com/voormedia/rails-erd) - Generate Entity-Relationship Diagrams for Rails applications. :star:2539
* [Parity](https://github.com/thoughtbot/parity) - Shell commands for development, staging, and production parity for Heroku apps. :star:620
* [Airbrussh](https://github.com/mattbrictson/airbrussh) - Airbrussh pretties up your SSHKit and Capistrano output :star:493

## API
* [Grape](https://github.com/ruby-grape/grape) - Microframework to create REST-ful APIs in Ruby. :star:8386
* [ActiveModel::Serializers](https://github.com/rails-api/active_model_serializers) - Serializer brings convention over configuration to your JSON generation. :star:4499
* [Jbuilder](https://github.com/rails/jbuilder) - Jbuilder gives you a simple DSL for declaring JSON structures that beats massaging giant hash structures. This is particularly helpful when the generation process is fraught with conditionals and loops. :star:3293
* [rest-client](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions. :star:4310
* [has_scope](https://github.com/plataformatec/has_scope) - Map incoming controller parameters to named scopes in your resources. :star:1283
* Documentation
	* [Grape Swagger](https://github.com/ruby-grape/grape-swagger) - Autogenerate documentation on Grape API. :star:854
	* [Grape Swagger UI](https://github.com/swagger-api/swagger-ui) - Display documentation that is generated using Grape Swagger. :star:11042
	* [apiary](https://apiary.io/) - Work together to quickly design, prototype, document and test APIs.
	* [apiblueprint](https://apiblueprint.org) - API Documentation with powerful tooling.

## Email
* [letter_opener](https://github.com/ryanb/letter_opener) - Preview mail in the browser instead of sending. :star:2783

## File Uploading
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) - Carrierwave is a classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks. :star:7908
  * [carrierwave_backgrounder](https://github.com/lardawge/carrierwave_backgrounder) - Offload CarrierWave's image processing and storage to a background process using Delayed Job, Resque, Sidekiq, Qu, Queue Classic or Girl Friday. :star:677
  * [CarrierWave Crop](https://github.com/kirtithorat/carrierwave-crop/) - Carrierwave extension to crop uploaded images using Jcrop plugin with preview.
  * [CarrierWave ImageOptimizer](https://github.com/jtescher/carrierwave-imageoptimizer) - This gem allows you to simply optimize CarrierWave images via jpegoptim or optipng using the image_optimizer gem. :star:180
* [remotipart](https://github.com/JangoSteve/remotipart) - Rails jQuery file uploads via standard Rails "remote: true" forms. :star:987
* [MiniMagick](https://github.com/minimagick/minimagick) - MiniMagick is a ruby wrapper for ImageMagick or GraphicsMagick command line. :star:2201
* [fog](https://github.com/fog/fog) - Fog is the Ruby cloud services library, top to bottom. :star:4110
* [refile](https://github.com/refile/refile) - Refile is a modern file upload library for Ruby applications. It is simple, yet powerful. :star:2432
* [Paperclip](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord. :star:8918
* [Dragonfly](http://markevans.github.io/dragonfly) - Dragonfly is for on-the-fly file processing - suitable for images or other attachments
* [shrine](https://github.com/janko-m/shrine) -File Attachment toolkit for Ruby applications  

## Searching
* [ransack](https://github.com/activerecord-hackery/ransack) - Ransack enables the creation of both simple and advanced search forms for your Ruby on Rails application. :star:3769
* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails. :star:2227
* [Chewy](https://github.com/toptal/chewy) - High-level Elasticsearch Ruby framework based on the official elasticsearch-ruby client. :star:1260
* [pg_search](https://github.com/Casecommons/pg_search) - pg_search builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search :star:2117
* [sunspot](https://github.com/sunspot/sunspot) - Sunspot is a Ruby library for expressive, powerful interaction with the Solr search engine. Sunspot is built on top of the RSolr library, which provides a low-level interface for Solr interaction; Sunspot provides a simple, intuitive, expressive DSL backed by powerful features for indexing objects and searching for them. :star:2798
* [searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy with Rails and Elasticsearch. :star:4176

## Scheduled/Recurrence Jobs
* [Whenever](https://github.com/javan/whenever) - Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs. :star:7518
* [Resque](https://github.com/resque/resque) - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later. :star:8158
* [Rufus-Scheduler](https://github.com/jmettraux/rufus-scheduler) - Rufus-scheduler is a Ruby gem for scheduling pieces of code (jobs). It understands running a job AT a certain time, IN a certain time, EVERY x time or simply via a CRON statement. :star:1824
* [Delayed Job](https://github.com/collectiveidea/delayed_job) - Database based asynchronous priority queue system. :star:4267
* [Sidekiq](https://github.com/mperham/sidekiq) - Simple, efficient background processing for Ruby. :star:8462
  * [sidetiq](https://github.com/tobiassvn/sidetiq) - Recurring jobs for sidekiq. :star:1201
  * [sidekiq-cron](https://github.com/ondrejbartas/sidekiq-cron) - Scheduler / Cron for Sidekiq jobs :star:767
  * [sidekiq-scheduler](https://github.com/Moove-it/sidekiq-scheduler) - Lightweight job scheduler extension for Sidekiq :star:632
* [Sucker Punch](https://github.com/brandonhilkert/sucker_punch) - Sucker punch is a single-process Ruby asynchronous processing library. :star:2204

## View Helper
* [formtastic](https://github.com/justinfrench/formtastic) - Formtastic is a Rails FormBuilder DSL (with some other goodies) to make it far easier to create beautiful, semantically rich, syntactically awesome, readily stylable and wonderfully accessible HTML forms in your Rails applications :star:5038
* [Simple Form](https://github.com/plataformatec/simple_form) - Simple form aims to be as flexible as possible while helping you with powerful components to create your forms. The basic goal of Simple Form is to not touch your way of defining the layout, letting you find the better design for your eyes. :star:7002
* [Nested Form](https://github.com/ryanb/nested_form) - This is a Rails gem for conveniently manage multiple nested models in a single form. It does so in an unobtrusive way through jQuery or Prototype. It can also be integrated with Simple Form. :star:1783
* [meta-tags](https://github.com/kpumuk/meta-tags) - Search Engine Optimization (SEO) plugin for Ruby on Rails applications. :star:1965
* [active_link_to](https://github.com/comfy/active_link_to) - active_link_to adds css 'active' class to your links. :star:655
* [cells](https://github.com/apotonick/cells) - Cells allow you to encapsulate parts of your UI into components into view models. View models, or cells, are simple ruby classes that can render templates. :star:2862
* [i18n Country Code Select](https://github.com/onomojo/i18n_country_select) - I18n Country Code Select Form Helper for Rails 3 & 4. :star:25
* [Subdivision Select](https://github.com/cllns/subdivision_select) - A Rails plugin to populate a state/province select box from country_select. :star:15
* [cocoon](https://github.com/nathanvda/cocoon) - Dynamic nested forms using jQuery made easy :star:2599

## Environment Variables
* [Config](https://github.com/railsconfig/config) - Multi-environment YAML style configurations that helps easily manage environment specific settings in an easy and usable manner. :star:1387
* [Figaro](https://github.com/laserlemon/figaro) - Figaro is very simple, Heroku-friendly Rails app configuration using ENV and a single YAML file. :star:3310
* [dotenv](https://github.com/bkeepers/dotenv) - Dotenv is a gem that allows you to set your environment variables in .env file, and it will load it in to ENV. :star:4546
* [opsworks-dotenv](https://github.com/mikamai/opsworks-dotenv) - Opsworks-dotenv let you configure the environment for you Rails application using OpsWorks, Chef and Dotenv. :star:8

## Admin Panel
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.
  - [active_skin](https://github.com/rstgroup/active_skin): Flat skin for active admin.
* [RailsAdmin](https://github.com/sferik/rails_admin) - RailsAdmin is a Rails engine that provides an easy-to-use interface for managing your data. :star:6764
* [Typus](https://github.com/typus/typus) - Typus is a control panel for Ruby on Rails applications to allow trusted users edit structured content. :star:1134
* [administrate](https://github.com/thoughtbot/administrate) - A Rails engine that helps you put together a super-flexible admin dashboard. :star:3825

## Logging
* [Impressionist](https://github.com/charlotte-ruby/impressionist) - Impressionist can log page impressions (technically action impressions), but it is not limited to that. You can log impressions multiple times per request. And you can also attach it to a model. The goal of this project is to provide customizable stats that are immediately accessible in your application as opposed to using Google Analytics and pulling data using their API. :star:1133
* [Ahoy](https://github.com/ankane/ahoy) - Ahoy provides a solid foundation to track visits and events in Ruby, JavaScript, and native apps. :star:2208
* [Lograge](https://github.com/roidrage/lograge) - An attempt to tame Rails' default policy to log everything. :star:2250

## Debug
* [byebug](https://github.com/deivid-rodriguez/byebug) - Byebug is a simple to use, feature rich debugger for Ruby 2. It uses the new TracePoint API for execution control and the new Debug Inspector API for call stack navigation, so it doesn't depend on internal core sources. :star:2499
  * [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) - Pry navigation commands via byebug. :star:1258
* [pry-rails](https://github.com/rweng/pry-rails) - Avoid repeating yourself, use pry-rails instead of copying the initializer to every rails project. This is a small gem which causes rails console to open pry. It therefore depends on pry. :star:1056
* [awesome_print](https://github.com/awesome-print/awesome_print) - Awesome Print is a Ruby library that pretty prints Ruby objects in full color exposing their internal structure with proper indentation. :star:3287
* [web-console](https://github.com/rails/web-console) - Web Console is a debugging tool for your Ruby on Rails applications. :star:1094
* [spring](https://github.com/rails/spring) - Spring is a Rails application preloader. It speeds up development by keeping your application running in the background so you don't need to boot it every time you run a test, rake task or migration. :star:2366
* [rails-footnotes](https://github.com/josevalim/rails-footnotes) - Rails footnotes displays footnotes in your application for easy debugging, such as sessions, request parameters, cookies, filter chain, routes, queries, etc. :star:1444
* [g](https://github.com/jugyo/g) - The Kernel.g that works like Kernel.p by using terminal-notifier or growl. :star:103
* [terminal-notifier](https://github.com/julienXX/terminal-notifier) - terminal-notifier is a command-line tool to send Mac OS X User Notifications, which are available in Mac OS X 10.8 and higher. :star:4440
* [letter_opener](https://github.com/ryanb/letter_opener) - Preview email in the default browser instead of sending it. This means you do not need to set up email delivery in your development environment, and you no longer need to worry about accidentally sending a test email to someone else's address. :star:2783
* [Better Errors](https://github.com/charliesome/better_errors) - Better errors replaces the standard Rails error page with a much better and more useful error page. :star:6316
  * If you would like to use Better Errors' advanced features (REPL, local/instance variable inspection, pretty stack frame names), you need to add the [binding_ _of__caller](https://github.com/banister/binding_of_caller).
* [RailsPanel](https://github.com/dejan/rails_panel) - RailsPanel is a Chrome extension for Rails development that will end your tailing of development.log. :star:3225

## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop) - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide). :star:8853
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - Rails best practice is a code metric tool to check the quality of rails codes. :star:3509
* [Metric Fu]( https://github.com/metricfu/metric_fu) - A fist full of code metrics
* [Pronto](https://github.com/mmozuras/pronto) - Quick automated code review of your changes :star:1801

## Testing
* [rspec-rails](https://github.com/rspec/rspec-rails) - Rspec-rails is a testing framework for Rails 3.x and 4.x. :star:3625
* [Capybara](https://github.com/jnicklas/capybara) - Capybara helps you test web applications by simulating how a real user would interact with your app. And drivers: :star:8289
  - [capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - Capybara-webkit is a capybara driver that uses Webkit via QtWebkit. :star:1936
  - [selenium-webdriver](https://github.com/vertis/selenium-webdriver) - Selenium-webdriver provides ruby bindings for WebDriver. :star:24
  - [poltergeist](https://github.com/teampoltergeist/poltergeist) - Poltergeist allows you to run your Capybara tests on a headless WebKit browser, provided by PhantomJS. :star:2461
  - [page-object](https://github.com/cheezy/page-object) - Page-object is a simple gem that assists in creating flexible page objects for testing browser based applications. :star:579
* [factory_bot](https://github.com/thoughtbot/factory_bot) - Factory_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance. :star:5866
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails) - Factory_bot_rails provides Rails integration for factory_bot. :star:2083
* [factory_factory_girl](https://github.com/st0012/factory_factory_girl) - FactoryFactoryGirl lets you generate factory files more efficiently with naming rules. :star:45
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis. :star:2249
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Shoulda-matchers provides serveral matchers for testing common Rails functionality. :star:2255
* [ResponseCodeMatchers](https://github.com/r7kamura/response_code_matchers) - ResponseCodeMatchers provides rspec matchers to match http response code. :star:53
* [SimpleCov](https://github.com/colszowka/simplecov) - SimpleCov is a code coverage analysis tool for Ruby. :star:3319
* [Timecop](https://github.com/travisjeffery/timecop) - A gem providing "time travel" and "time freezing" capabilities, making it dead simple to test time-dependent code. :star:2580
* [VCR](https://github.com/vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests. :star:3902

### Security
* [brakeman](https://github.com/presidentbeef/brakeman) - Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities. :star:4725
* [bundle-audit](https://github.com/rubysec/bundler-audit) - bundler-audit is a patch-level verification tool for Bundler which checks for vulnerable versions of gems and insecure gem sources. :star:1686
* [Secure Headers](https://github.com/twitter/secureheaders) -  Secure Headers will automatically apply several headers that are related to security. :star:2425

## Production
* [Capistrano](https://github.com/capistrano/capistrano) - Remote multi-server automation tool. :star:10295
* [Slowpoke](https://github.com/ankane/slowpoke) - Rack::Timeout is great. Slowpoke makes it better. :star:145
* [Rack Attack](https://github.com/kickstarter/rack-attack) - Rack middleware to blocking & throttling. :star:3694
* [Responders](https://github.com/plataformatec/responders) - A set of Rails responders to dry up your application. :star:1653
* [production_rails](https://github.com/ankane/production_rails) - Best practices for running Rails in production. :star:889
* [Mina](https://github.com/mina-deploy/mina) - fast deployer and server automation tool. :star:3772

## Error Logging
* [Rollbar](https://github.com/rollbar/rollbar-gem) - Exception tracking and logging from Ruby to Rollbar. :star:330
* [Airbrake](https://github.com/airbrake/airbrake) - Notifier gem for integrating apps with Airbrake :star:825
* [Errbit](https://github.com/errbit/errbit) - Open source notifier gem compliant with Airbrake. :star:3836

## Database
* [rails_db](https://github.com/igorkasyanchuk/rails_db) - Rails Database Viewer and SQL Query Runner :star:968

## Asset Pipeline
* [Alaska](https://github.com/mavenlink/alaska) - ExecJS runtime with persistent connection to nodejs, speeds up your coffeescript compilation process during development and deployment. :star:47

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


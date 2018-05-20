# Information comes from [rosarior/awesome-django](https://github.com/rosarior/awesome-django)
# <a href="http://awesome-django.com"><img src="https://raw.githubusercontent.com/rosarior/awesome-django/gh-pages/images/logo-small.png" align="absmiddle"/> Awesome Django</a>

[![Repository](https://img.shields.io/badge/GitLab-URL-orange.svg)](https://gitlab.com/rosarior/awesome-django) [![Build status](https://gitlab.com/rosarior/awesome-django/badges/master/build.svg)](https://gitlab.com/rosarior/awesome-django/commits/master) ![license](https://img.shields.io/github/license/rosarior/awesome-django.svg)



If you find Awesome Django useful, [please consider donating](https://www.paypal.me/RobertoRosario) to help maintain it. Thank you!

A curated list of awesome Django apps, projects and resources.

*Q: What is an awesome Django package?*

**A: An awesome package is one that is mature (not recently released), is well
maintained, has a good amount of users, has good documentation, follows the best
practices, and which latest release is less than 1 year old. Awesome Django packages
and projects are the ones that inspire and serve as examples.**

Twitter feed: [twitter.com/AwesomeDjango](https://twitter.com/AwesomeDjango)

- [Awesome Django](#awesome-django)
    - [Admin Interface](#admin-interface)
    - [Analytics](#analytics)
    - [Asset Management](#asset-management)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Blog Management](#blog-management)
    - [Boilerplate](#boilerplate)
    - [Caching](#caching)
    - [Compatibility](#compatibility)
    - [CRM](#crm)
    - [Dashboards](#dashboards)
    - [Data Sciences](#data-sciences)
    - [Database](#database)
    - [Debugging](#debugging)
    - [Email](#email)
    - [Fields](#fields)
    - [File Transfers](#file-transfers)
    - [Forms](#forms)
    - [GIS](#gis)
    - [Image handling](#image-handling)
    - [Import/Export](#importexport)
    - [Migrations](#migrations)
    - [Mobile Support](#mobile-support)
    - [Model Extensions](#model-extensions)
    - [Multi-tenancy](#multitenancy)
    - [Payment Processing](#payment-processing)
    - [Project Management](#project-management)
    - [Reporting](#reporting)
    - [RESTful API](#restful-api)
    - [SEO](#seo)
    - [Search](#search)
    - [Security](#security)
    - [Settings](#settings)
    - [Storage](#storage)
    - [Tagging](#tagging)
    - [Task Queue](#task-queue)
    - [Testing](#testing)
    - [Thumbnail](#thumbnail)
    - [Translations](#translations)
    - [Views](#views)
    - [Web front-end integration](#web-frontend-integration)
    - [Wiki apps](#wiki-apps)
    - [Workflows](#workflows)
    - [WYSIWYG Editors](#wysiwyg-editors)
    - [Other](#other)
- [Projects](#projects)
    - [CMS](#cms)
    - [Document Management](#document-management)
    - [Project Management](#project-management)
    - [e-Commerce](#e-commerce)
    - [Other](#other)
- [Resources](#resources)
    - [Books](#books)
    - [Conferences](#conferences)
    - [External documentation](#external-documentation)
    - [Videos](#videos)
    - [Websites](#websites)
- [Utilities](#utilities)
- [Contributing](#contributing)

## Admin interface

*Packages that extend the Admin interface, adding or improving features.*

* [djamin](https://github.com/hersonls/djamin/) - A new style for Django admin.
* [django-admin-bootstrap](https://github.com/douglasmiranda/django-admin-bootstrap) - Responsive Skin for Django Admin :star:574
* [django-admin-bootstrapped](https://github.com/django-admin-bootstrapped/django-admin-bootstrapped/) - A Django admin theme using Twitter Bootstrap.
* [django-admin-easy](https://github.com/ebertti/django-admin-easy) - Collection of admin fields and decorators. :star:133
* [django-admin-interface](https://github.com/fabiocaccamo/django-admin-interface) - The ultimate admin interface, based on a modern flat theme, it lets you customize the admin title, logo and colors by the admin itself. :star:203
* [django-admin-tools](https://github.com/django-admin-tools/django-admin-tools) - A collection of extensions/tools for the default django administration interface :star:333
* [django-admin2](https://github.com/jazzband/django-admin2/) - Extendable, adaptable rewrite of django.contrib.admin
* [django-flat-theme](https://github.com/elky/django-flat-theme) - A flat theme for Django admin interface. Modern, fresh, simple. ([merged into Django 1.9+](https://docs.djangoproject.com/en/1.9/releases/1.9/#new-styling-for-contrib-admin))
* [django-flat-responsive](https://github.com/elky/django-flat-responsive) - An extension for Django admin and django-flat-theme that makes interface mobile friendly. :star:228
* [django-fluent-dashboard](https://github.com/django-fluent/django-fluent-dashboard) - An improved django-admin-tools dashboard for Django projects :star:199
* [django-grappelli](https://github.com/sehmaschine/django-grappelli/) - A jazzy skin for the Django Admin-Interface.
* [django-hijack](https://github.com/arteria/django-hijack/) - Allows superusers to hijack (=login as) and work on behalf of another user.
* [django-jet](https://github.com/geex-arts/django-jet) - Modern responsive template for the admin interface with improved functionality. :star:1490
* [django-material](https://github.com/viewflow/django-material) Material design for Django Forms and Admin. Template driven.
* [django-object-actions](https://github.com/crccheck/django-object-actions) A Django app for adding object tools for models in the admin
* [django-suit](https://github.com/darklow/django-suit/) - Modern theme for Django admin interface.
* [django-wpadmin](https://github.com/barszczmm/django-wpadmin/) - WordPress look and feel for Django administration panel.
* [django-xadmin](https://github.com/sshwsfc/xadmin/) - Drop-in replacement of Django admin comes with lots of goodies, fully extensible with plugin support, pretty UI based on Twitter Bootstrap
* [yawd-admin](https://github.com/yawd/yawd-admin/) - An administration website for Django

## Analytics

*Packages that do web analytics or integrate web analytics services.*

* [django-analytical](https://github.com/jcassee/django-analytical) - Integrates analytics services with a generic interface, templates stay clean. :star:568

## Asset Management

*Packages that help manage the static assets of a project.*

* [django-compressor](https://github.com/django-compressor/django-compressor/) - Compresses linked and inline JavaScript or CSS into a single cached file.
* [django-gears](https://github.com/gears/django-gears/) - Compiles and concatenates JavaScript and CSS assets.
* [django-htmlmin](https://github.com/cobrateam/django-htmlmin/) - HTML minifier for Python with full support for HTML 5 and Django.
* [django-pipeline](https://github.com/jazzband/django-pipeline) - Asset packaging for Django. :star:1243
* [django-systemjs](https://github.com/sergei-maertens/django-systemjs) - Django SystemJS brings the JavaScript of tomorrow to Django, today. (JSPM integration in Django)
* [django-webpack-loader](https://github.com/owais/django-webpack-loader) - Transparent webpack integration for django. :star:1378
* [python-webpack](https://github.com/markfinger/python-webpack) - Python bindings for webpack with django integration. :star:58
* [django-webpacker](https://github.com/MicroPyramid/django-webpacker) - A django compressor tool which bundles CSS, JS files to a single CSS, JS file with webpack and updates your HTML files with respective CSS, JS file path. :star:52

## Authentication

*Packages that improve or extend the authentication methods of Django.*

* [django-allauth](https://github.com/pennersr/django-allauth/) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
* [django-organizations](https://github.com/bennylope/django-organizations) - Multi-user accounts for Django projects. :star:437
* [django-otp](https://bitbucket.org/psagers/django-otp/) - A pluggable framework for adding two-factor authentication to Django using one-time passwords.
* [django-registration](https://github.com/macropin/django-registration/) -  Simple user-registration application for Django, designed to make allowing user sign-ups as painless as possible.
* [django-rest-auth](https://github.com/Tivix/django-rest-auth) -  A set of REST API endpoints to handle User Registration and Authentication tasks. :star:1223
* [django-two-factor-auth](https://github.com/Bouke/django-two-factor-auth/) - User-friendly Two-Factor authentication.
* [django-userena](https://github.com/bread-and-pepper/django-userena/) - Accounts for Django made beautifully simple
* [djoser](https://github.com/sunscrapers/djoser) - REST implementation of Django authentication system. :star:976
* [python-social-auth](https://github.com/omab/python-social-auth/) - Python Social Auth is an easy-to-setup social authentication/registration mechanism with support for several frameworks and auth providers.

## Authorization

*Packages related to authorization infrastructure and permissions.*

* [django-guardian](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions as authorization backend. :star:1835
* [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth2 goodies for the Djangonauts! :star:1284
* [django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider) - Provide OAuth2 access to your app :star:317
* [django-oml](https://github.com/angvp/django-oml/) - Object Moderation Layer, mixin for models that allows you moderate several content types.
* [django-permission](https://github.com/lambdalisue/django-permission/) An enhanced permission library which enables a *logic-based permission system* to handle complex permissions in Django
* [django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database. At its core, it is a generic framework for building rule-based systems, similar to decision trees. It can also be used as a standalone library in other contexts and frameworks. :star:658

## Blog Management

*Packages to build and manage a blog app.*

* [django-blog-zinnia](https://github.com/Fantomas42/django-blog-zinnia) -  Simple yet powerful and really extendable application for managing a blog within your Django Web site. :star:1761
* [puput](https://github.com/APSL/puput) - A Django blog app implemented in Wagtail. :star:268

* [django-blog-it](https://github.com/MicroPyramid/django-blog-it) - complete customizable and ready to use blog with one click installer. :star:62

## Boilerplate

*Packages related to starting a new project.*

* [cookiecutter](https://github.com/audreyr/cookiecutter/) - A command-line utility that creates projects from cookiecutters (project templates).
* [django-hackathon-starter](https://github.com/DrkSephy/django-hackathon-starter) - A boilerplate for Django web applications, containing various social authentication methods and several popular API examples. :star:1216
* [edge](https://github.com/arocks/edge) - A Django project skeleton that is modern and cutting edge. :star:603
* [demo-allauth-bootstrap](https://github.com/aellerton/demo-allauth-bootstrap) - Django sample app with users including social auth via Django-AllAuth. :star:121

## Caching

*Packages that help with caching.*

* [django-cachalot](https://github.com/BertrandBordage/django-cachalot) - Caches your Django ORM queries and automatically invalidates them. :star:558
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models through the ORM. :star:699
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation. :star:876
* [django-memoize](https://github.com/tvavrys/django-memoize) - An implementation of [memoization](https://en.wikipedia.org/wiki/Memoization) technique for Django. :star:66
* [django-ormcache](https://github.com/educreations/django-ormcache/) - A cache manager mixin that provides some caching of objects for the ORM.
* [django-redis-cache](https://github.com/sebleier/django-redis-cache/) - A Redis cache backend for django.
* [johnny-cache](https://github.com/jmoiron/johnny-cache/) - Johnny Cache is a caching framework for django applications.
* [diskcache](http://www.grantjenks.com/docs/diskcache/) - Fast SQLite and file backed cache backend for Django.

## Compatibility

*Packages that help to keep compatibility of reusable apps between different Django versions.*

* [django-compat](https://github.com/arteria/django-compat) - Forward and backwards compatibility layer for the officially supported Django versions. :star:104
* [django-compat-lint](https://github.com/ubernostrum/django-compat-lint) - Check Django compatibility of your code. :star:38

## CRM

*Packages that help to manage business relationships of the organization.*

* [Django-CRM](https://github.com/MicroPyramid/Django-CRM) - Customer relationship management dashboard where you can manage customers at sales of the organization. It Provides to manage leads information and its activity, track issues from leads, manage contacts to send emails of leads and accounts. :star:85

## Dashboards

*Packages that create information dashboards to visualize data.*

* [django-dashing](https://github.com/talpor/django-dashing/) - a customisable, modular dashboard application framework for Django to visualize interesting data about your project. Inspired in the exceptionally handsome dashboard framework Dashing.

## Data sciences

*Packages that make it easier to work with large volumes of data.*

* [rest-pandas](https://github.com/wq/django-rest-pandas/) - Serves up your Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and offline analysis (e.g. Excel).

## Database

*Packages that add support for 3rd party databases or database specific features.*

* [dj-database-url](https://github.com/kennethreitz/dj-database-url/) - Use Database URLs in your Django Application.
* [django-mysql](https://github.com/adamchainz/django-mysql/) - Extensions to Django for use with MySQL/MariaDB.
* [django-postgres-fuzzycount](https://github.com/stephenmcd/django-postgres-fuzzycount) - Fast / fuzzy PostgreSQL counts for Django. :star:69
* [django-postgrespool](https://github.com/kennethreitz/django-postgrespool/) - Postgres Connection Pooling for Django, powered by SQLAlchemy. :star:281

## Debugging

*Packages that help hunt down bugs.*

* [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar/) - A configurable set of panels that display various debug information about the current request/response.
* [django-devserver](https://github.com/dcramer/django-devserver/) - A drop in replacement for Django's built-in runserver command.
* [django-querycount](https://github.com/bradmontgomery/django-querycount/) - Middleware that Prints the number of DB queries to the runserver console.
* [django-silk](https://github.com/jazzband/django-silk) - Silky smooth profiling for Django :star:1591
* [nplusone](https://github.com/jmcarp/nplusone/) - Auto-detecting the n+1 queries problem in Django (and other ORMs)
* [sentry](https://github.com/getsentry/sentry) - A modern error logging and aggregation platform. :star:16647
* [django-web-profiler](https://github.com/MicroPyramid/django-web-profiler) - A django profiling tool which logs, stores debug toolbar statistics and also a set of URL's statistics using a management command. :star:30

## Email

*Packages that help manage email sending.*

* [django-celery-email](https://github.com/pmclanahan/django-celery-email/) - A Django email backend that uses a celery task for sending the email.
* [django-db-mailer](https://github.com/LPgenerator/django-db-mailer/) - Django module to easily send email/sms/push/tts using django templates stored on database and managed through the Django Admin.
* [django-drip](https://github.com/zapier/django-drip) - Django Admin based management for drip email campaigns :star:574
* [django-email-extras](https://github.com/stephenmcd/django-email-extras) - Various email utilities: PGP encryption, multipart templates, web browser test backend. :star:68
* [django-email-gateway](https://github.com/MicroPyramid/django-email-gateway) - A django package which act as a gateway to send emails from SES. Receiving its' corresponding email replys, parsing reply email content with amazon SES. :star:19
* [django-mailgun](https://github.com/BradWhittington/django-mailgun/) - A Django email backend for Mailgun.
* [django-post_office](https://github.com/ui/django-post_office/) - A simple app to send and manage your emails in Django, supports templates and can be easily integrated with task queues.
* [django-ses](https://github.com/django-ses/django-ses) - A Django email backend for Amazon's Simple Email Service. :star:567
* [django-spoolgore](https://github.com/20tab/django-spoolgore) - A django email backed for the Spoolgore daemon. :star:7
* [django-templated-email](https://github.com/vintasoftware/django-templated-email) - Django module to easily send templated emails using django templates, or using a transactional mail provider (mailchimp, silverpop, etc.)
* [django-yubin](https://github.com/APSL/django-yubin) - django-mailer2 + django-mailviews with some extras. :star:27
* [djmail](https://github.com/bameda/djmail) - A simple and nonobstructive django email middleware. :star:65
* [djrill](https://github.com/brack3t/Djrill/) - Email backend and new message class for Mandrill transactional email service from MailChimp.

## Fields

*Packages that extend the functionality of existing field type or add new field types.*

* [django-audiofield](https://github.com/areski/django-audiofield) -  Allows audio files upload, management and conversion to different audio format (mp3, wav & ogg). :star:119
* [django-bitfield](https://github.com/disqus/django-bitfield/) - A BitField extension for Django models.
* [django-countries](https://github.com/SmileyChris/django-countries/) - Provides country choices for forms, flag icons, and a CountryField.
* [django-enumfield](https://github.com/5monkeys/django-enumfield/) - Custom Django field for using enumerations of named constants.
* [django-image-tools](https://github.com/bonsaistudio/django-image-tools/) - A package to handle images in Django.
* [django-imagekit](https://github.com/matthewwithanm/django-imagekit/) - Automated image processing for Django.
* [django-jsonfield](https://pypi.python.org/pypi/django-jsonfield) - JSONField for Django models.
* [django-location-field](https://github.com/caioariede/django-location-field/) - Location field and widget integrated with google maps.
* [django-macaddress](https://github.com/django-macaddress/django-macaddress) - MAC Address model and form fields for Django. :star:34
* [django-money](https://github.com/django-money/django-money) - A little Django app that uses py-moneyed to add support for Money fields in your models and forms. :star:585
* [django-phonenumber-field](https://github.com/stefanfoulis/django-phonenumber-field/) - A Django library which interfaces with [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) to validate, pretty print and convert
phone numbers.
* [django-picklefield](https://github.com/gintas/django-picklefield/) - A pickled object field for Django
* [django-searchable-select](https://github.com/and3rson/django-searchable-select) - A better and faster multiple choice widget with suggestions. :star:53
* [django-uuidfield](https://github.com/dcramer/django-uuidfield/) - A UUIDField for Django.
* [django-versatileimagefield](https://github.com/respondcreate/django-versatileimagefield/) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.

## File Transfers

*Packages that help transfer files between projects and users.*

* [django-downloadview](https://github.com/benoitbryon/django-downloadview/) - Serve files with Django.
* [django-sendfile](https://github.com/johnsensible/django-sendfile/) - This is a wrapper around web-server specific methods for sending files to web clients.
* [django-filer](https://github.com/divio/django-filer/) - Makes multiple files(text/image) uploading easy and provides interface with precise details.

## Forms

*Packages that extend the functionality of forms or add new types of forms.*

* [django-autocomplete-light](https://github.com/yourlabs/django-autocomplete-light/) - django-autocomplete-light's purpose is to enable autocompletes quickly and properly in a django project.
* [django-bootstrap-form](https://github.com/tzangms/django-bootstrap-form/) - Twitter Bootstrap for Django Form
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3/) - Use Bootstrap in your Django templates, the Django way.
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms/) - The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.
* [django-floppyforms](https://github.com/gregmuellegger/django-floppyforms/) - django-floppyforms is an application that gives you full control of the output of forms rendering. The forms API and features are exactly the same as Django’s, the key difference is that fields and widgets are rendered in templates instead of using string interpolation, giving you full control of the output using Django templates.

## GIS

*Packages that make it easier to work with geographical information system projects.*

* [django-geoposition](https://github.com/philippbosch/django-geoposition/) - A model field that can hold a geoposition (latitude/longitude), and corresponding admin/form widget.
* [django-location-field](https://github.com/caioariede/django-location-field/) - Location field and widget integrated with Google Maps.
* [django-spillway](https://github.com/bkg/django-spillway/) -  Geodata extensions for Django REST Framework.
* [djangorestframework-gis](https://github.com/djangonauts/django-rest-framework-gis/) - Geographic add-ons for Django Rest Framework.

## Image handling

*Packages that help to manipulate, alter, or convert images.*

* [django-image-cropping](https://github.com/jonasundderwolf/django-image-cropping) - helper application to easily and non-destructively crop arbitrarily large images in admin and frontend. :star:444
* [django-versatileimagefield](https://github.com/respondcreate/django-versatileimagefield/) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.

## Import/Export

* [django-import-export](https://github.com/django-import-export/django-import-export) - Django application and library for importing and exporting data with admin integration. :star:1160

## Migrations

*Packages that help migrate the database when there are schema updates.*

* [South](https://bitbucket.org/andrewgodwin/south/src/) - Django application to provide schema and data migrations that supports Django up to 1.6.x. ([Django 1.7 and up have an integrated migration system, based on but not compatible with South](https://docs.djangoproject.com/en/dev/topics/migrations/))
* [django-migrations-graph](https://github.com/dizballanze/django-migrations-graph) - Django-admin command to display migrations with dependencies. :star:35

## Mobile Support

*Packages that help you support for mobile iOS, Android and Others.*

* [django-push-notifications](https://github.com/jazzband/django-push-notifications) - A minimal Django app that implements Device models that can send messages through APNS and GCM. :star:1180
* [django-pushy](https://github.com/rakanalh/django-pushy) - Django app that provides push notifications functionality with celery. The main purpose of this app is to help you send push notifications to your users at scale. If you have lots of registered device keys, django-pushy will split your keys into smaller groups which run in parallel making the process of sending notifications faster. :star:167

## Model Extensions

*Packages that extend the functionality of models or add new classes of models.*

* [django-aggregate-if](https://github.com/henriquebastos/django-aggregate-if/) - Conditional aggregates for Django queries, just like the famous SumIf and CountIf in Excel.
* [django-localflavor](https://github.com/django/django-localflavor/) - Country-specific Django helpers, formerly of contrib fame.
* [django-model-utils](https://github.com/jazzband/django-model-utils/) - Django model mixins and utilities.
* [django-mptt](https://github.com/django-mptt/django-mptt/) - Utilities for implementing a modified pre-order traversal tree in django.
* [django-treebeard](https://github.com/django-treebeard/django-treebeard/) -Alternative tree data structures for Django (provides 3 different methods for storing hierarchical data, including MPTT )

## Multitenancy

*Packages that allow a single install of Django to serve multiple organizations.*

* [django-tenant-schemas](https://github.com/bernardopires/django-tenant-schemas/) - Tenant support for Django using PostgreSQL schemas.

## Payment Processing

*Packages that provide payment processing provider integration.*

* [dj-stripe](https://github.com/dj-stripe/dj-stripe/) - Django + Stripe Made Easy.
* [django-merchant](https://github.com/agiliq/merchant/) - A Django app that provides helpers for multiple pluggable payment backends.
* [django-oscar-adyen](https://github.com/django-oscar/django-oscar-adyen/) - This package provides integration with the Adyen payment gateway. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without Oscar.
* [django-oscar-paymentexpress](https://github.com/django-oscar/django-oscar-paymentexpress/) - This package provides integration with the payment gateway, PaymentExpress using their PX POST API. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without it.
* [django-oscar-paypal](https://github.com/django-oscar/django-oscar-paypal/) - PayPal integration for django-oscar. Can be used without Oscar too.
* [django-paypal](https://github.com/spookylukey/django-paypal) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro. :star:453
* [django-pinpayments](https://github.com/rossp/django-pinpayments/) - Django library to simplify payment processing with pin.
* [django-zebra](https://github.com/GoodCloud/django-zebra/) - Forms, widgets, template tags and examples that make Stripe + Django easier.
* [django-payu](https://github.com/MicroPyramid/django-payu) - A Django app that provides integration between Django and PayU Payment Gateway. :star:22

## Project Management

*Packages for project management and time-tracking.*

* [django-timepiece](https://github.com/caktus/django-timepiece/) - A multi-user Django application for tracking people's time on projects.

## Reporting
*Packages for creating reports*

* [django-model-report](https://github.com/juanpex/django-model-report/) - Django reports integrated with highcharts.
* [django-report-builder](https://github.com/burke-software/django-report-builder/) - A GUI for Django ORM. Build custom queries and display results. Targets sys admins and capable end users who might not be able to program.

## RESTful API

*Packages for developing RESTful APIs.*

* [django-nap](https://github.com/funkybob/django-nap/) - A minimalist approach to object serialization, RESTful views, and RPC views.
* [django-rest-auth](https://github.com/Tivix/django-rest-auth/) - This app makes it extremely easy to build Django powered SPA's (Single Page App) or Mobile apps exposing all registration and authentication related functionality as CBV's (Class Base View) and REST (JSON).
* [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-rest-localflavor](https://github.com/gilsondev/django-rest-localflavor/) - Localized flavors of some serializers to use with Django Rest Framework.
* [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger/) - Swagger Documentation Generator for Django REST Framework
* [drfdocs](https://github.com/manosim/django-rest-framework-docs) - Document Web APIs made with Django REST Framework :star:489
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps since 2010.
* [restless](https://github.com/toastdriven/restless/) - A lightweight REST miniframework for Python
* [djangorestframework-recursive](https://github.com/heywbj/django-rest-framework-recursive/) - Recursive Serialization for Django REST framework

## Search

*Packages that provide search capabilities to projects.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django. :star:2415
* [django-watson](https://github.com/etianen/django-watson/) - Fast multi-model full-text search plugin.
* [djangoql](https://github.com/ivelum/djangoql) - Advanced search language for Django :star:345
* [djorm-ext-pgfulltext](https://github.com/linuxlewis/djorm-ext-pgfulltext) - PostgreSQL full-text search integration with django orm. :star:245

## Security

*Packages that improve the security of a project.*

* [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot/) - A fake Django admin login screen to notify admins of attempted unauthorized access.
* [django-axes](https://github.com/jazzband/django-axes/) - is a very simple way for you to keep track of failed login attempts, both for the Django admin and for the rest of your site.
* [django-debreach](https://github.com/lpomfrey/django-debreach/) - BREACH mitigation for Django apps.
* [django-password-session](https://github.com/atugushev/django-password-session/) - Invalidate all active sessions after change password ([not needed for Django 1.7+](https://docs.djangoproject.com/en/dev/topics/auth/default/#session-invalidation-on-password-change)).
* [django-secure-auth](https://github.com/gotlium/django-secure-auth) - Secure authentication by TOTP, SMS, Codes & Question. Login protection with ban by IP and captcha. :star:28
* [django-security](https://github.com/sdelements/django-security/) - A collection of models, views, middlewares, and forms to help secure a Django project.
* [django-sslify](https://github.com/rdegges/django-sslify/) - Force SSL on your Django site.
* [django-stronghold](https://github.com/mgrouchy/django-stronghold/) - Stronghold is middleware to default all your views to login required.
* [django-sudo](https://github.com/mattrobenolt/django-sudo) - Sudo mode is an extra layer of security for your most sensitive pages. This is an implementation of GitHub's Sudo Mode for Django. :star:245
* [django-mfa](https://github.com/MicroPyramid/django-mfa) - Django app for providing MFA (Multi-Factor Authentication). :star:56
* [django-user-sessions](https://github.com/Bouke/django-user-sessions) - Extend Django sessions with a foreign key back to the user, allowing enumerating all user's sessions. :star:215

## SEO

*Packages that help improve SEO ( Search Engine Optimization ) of projects.*

* [django-meta](https://github.com/nephila/django-meta/) - a pluggable app to allow Django developers to quickly add meta tags and OpenGraph, Twitter, and Google Plus properties to their HTML responses.
* [django-robots](https://github.com/jazzband/django-robots) - A Django app for managing robots.txt files following the robots exclusion protocol. :star:245
* [django-seo2](https://github.com/romansalin/django-seo2/) - Provides a set of tools for managing Search Engine Optimisation (SEO) metadata for Django sites.

## Settings

*Packages that help manage the configurability of projects.*

* [django-configurations](https://github.com/jazzband/django-configurations) - A helper for organizing Django project settings by relying on well established programming patterns. :star:592
* [django-constance](https://github.com/jazzband/django-constance) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app. :star:868
* [python-decouple](https://github.com/henriquebastos/python-decouple/) - Strict separation of config from code.
* [django-environ](https://github.com/joke2k/django-environ) - Allows you to utilize 12factor inspired environment variables to configure your Django application. :star:994
* [django-split-settings](https://github.com/sobolevn/django-split-settings) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and optional settings files. :star:299
* [django-dynamic-preferences](https://github.com/EliotBerriot/django-dynamic-preferences) - Dynamic global and instance settings for your django project. :star:115

## Storage

*Packages that extend the functionality of the existing storage backend or provide new storage backends.*

* [django-selectel-storage](https://github.com/marazmiki/django-selectel-storage) - This application allows you easily save media and static files into [Selectel](https://selectel.ru/) cloud storage. :star:14
* [django-storages](https://github.com/jschneier/django-storages) - django-storages is a collection of custom storage backends for Django. :star:899
* [django-queued-storage](https://github.com/jazzband/django-queued-storage) - Provides a proxy for Django storage backends that allows you to upload files locally and eventually serve them remotely. :star:265
* [django-webdav-storage](https://github.com/marazmiki/django-webdav-storage) - Django storage backend that stores files in custom WebDAV storage. :star:12

## Tagging

*Packages for adding tags to Django models.*

* [django-taggit](https://github.com/alex/django-taggit/) - Simple tagging for Django.
* [django-taggit-helpers](https://github.com/mfcovington/django-taggit-helpers) - Django admin helper classes for django-taggit tags. :star:22

## Task Queue

*Packages that make working with task/background queues easier.*

* [django-celery](http://celery.github.io/django-celery/) - Celery Integration for Django. (no longer required for Celery 3.1 and up)
* [django-q](https://github.com/Koed00/django-q) - A native multiprocessing task queue for Django. :star:609
* [django-rq](https://github.com/rq/django-rq) - The easiest way to monitor and use [RQ](http://python-rq.org) in your Django projects. :star:788
* [huey](https://github.com/coleifer/huey/) - A little multi-threaded task queue for python.

## Testing

*Packages that help test code or generate test data.*

* [behave-django](https://github.com/behave/behave-django) - Behave BDD integration for Django :star:67
* [django-behave](https://github.com/django-behave/django-behave/) - TestRunner for the Behave BDD module.
* [django-dynamic-fixture](https://github.com/paulocheque/django-dynamic-fixture) - A complete library to create dynamic model instances for testing purposes. :star:270
* [django-faker](https://github.com/joke2k/django-faker/) - Fake-factory to generate test data.
* [django-jenkins](https://github.com/kmmbvnr/django-jenkins) - Plug and play continuous integration with django and jenkins. :star:862
* [django-nose](https://github.com/django-nose/django-nose/) - Test runner using nose.
* [django-selenium](https://github.com/dragoon/django-selenium/) - Selenium testing support.
* [django-shotgun](https://github.com/stephenmcd/django-shotgun) - Test entire Django sites. :star:13
* [django-slowtests](https://github.com/realpython/django-slow-tests) - Locate your slowest tests. :star:121
* [django-test-plus](https://github.com/revsys/django-test-plus) - Useful addons to Django's default TestCase that greatly reduces boilerplate code :star:273
* [factory_boy](https://github.com/FactoryBoy/factory_boy/) - A test fixtures replacement for Python
* [hitchtest](http://hitchtest.com/) - High level integration testing framework for Django.
* [lettuce-django-terrain](https://github.com/stringfellow/lettuce-django-terrain/) - Terrain file for lettuce in django projects
* [mixer](https://github.com/klen/mixer) - An application to generate instances of Django or SQLAlchemy models. Fast and convenient test-data generation. :star:499
* [mock-django](https://github.com/dcramer/mock-django) - A simple library for mocking certain Django behavior, such as the ORM. :star:206
* [model-mommy](https://github.com/vandersonmota/model_mommy/) - Smart fixtures for better tests.
* [pytest-django](https://pypi.python.org/pypi/pytest-django/) - Test runner using py.test
* [splinter](https://github.com/cobrateam/splinter/) - Test framework for web applications.
* [django-eraserhead](https://github.com/dizballanze/django-eraserhead) - Django package that provides hints to optimize database usage by deferring unused fields (and more). :star:170

## Thumbnail

*Packages that help generate thumbnails.*

* [django-stdimage](https://github.com/codingjoe/django-stdimage/) - Thumbnails and image utils for Django.
* [django-versatileimagefield](https://github.com/respondcreate/django-versatileimagefield/) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.
* [easy-thumbnails](https://github.com/SmileyChris/easy-thumbnails) - Easy thumbnails for Django. :star:992
* [sorl-thumbnail](https://github.com/jazzband/sorl-thumbnail/) - Thumbnails for Django.

## Translations

*Packages help with the task of translating projects.*

* [django-hvad](https://github.com/KristianOellegaard/django-hvad) - Painless translations in django, using the regular ORM. Integrates easily into existing projects and apps. Easy convertible from django-multilingual-ng. :star:472
* [django-klingon](https://github.com/angvp/django-klingon/) - An attempt to make django model translations suckless and with no integrations pain in your app.
* [django-modeltranslation](https://github.com/deschler/django-modeltranslation/) - Translate dynamic content of existing Django models to an arbitrary number of languages without having to change the original model classes.
* [django-parler](https://github.com/django-parler/django-parler) - Simple Django model translations without nasty hacks :star:291
* [django-rosetta](https://github.com/mbi/django-rosetta/) - Rosetta is a Django application that eases the translation process of your Django projects.

## Views

*Packages that enhance or provide new view classes.*

* [django-extra-views](https://github.com/AndrewIngram/django-extra-views/) - Django's class-based generic views are awesome, let's have more of them.
* [django-vanilla-views](https://github.com/tomchristie/django-vanilla-views/) - Beautifully simple class-based views.

## Web frontend integration

*Packages for integrating and managing front-end packages.*

* [django-angular](https://github.com/jrief/django-angular/) - Let AngularJS play well with Django.
* [django-bower](https://github.com/nvbn/django-bower) - Easy way to use [bower](https://bower.io) with your Django project. :star:509
* [django-js-reverse](https://github.com/ierror/django-js-reverse) - Javascript url handling for Django that doesn't hurt. :star:418
* [djangular](https://github.com/appliedsec/djangular/) - A reusable Django app that provides better integration and tools for Angular.js.

## WYSIWYG Editors

*Packages that makes text editing awesome.*

* [django-ckeditor](https://github.com/django-ckeditor/django-ckeditor/) - Django admin CKEditor integration.
* [django-summernote](https://github.com/summernote/django-summernote/) - Summernote is a simple WYSIWYG editor. django-summernote allows you to embed Summernote into Django very handy. Support admin mixins and widgets.
* [django-tinymce](https://github.com/aljosa/django-tinymce/) - TinyMCE integration for Django.
* [django-redactoreditor](https://github.com/mazelife/django-redactoreditor/) - This package helps integrate the Redactor Javascript WYSIWYG-editor in Django.
* [django-wysiwyg](https://github.com/pydanny-archive/django-wysiwyg/) - A Django application for making Django textareas rich text editors. Certainly as a template tag and possibly as a form widget.

## Wikis

*Packages for adding wiki functionality to a project.*

* [django-wiki](https://github.com/django-wiki/django-wiki) A wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.
* [waliki](https://github.com/mgaitan/waliki) An extensible wiki app for Django with a Git backend.

## Workflows

*Packages that do process, procedure and/or business tasks management.*

* [django-flows](https://github.com/carlio/django-flows/) - django-flows keeps state and position in complicated flows of logic, allowing optional branches and complicated paths through a series of individual user actions.
* [django-fsm](https://github.com/kmmbvnr/django-fsm/) - Django friendly finite state machine support.
* [django-river](https://github.com/javrasya/django-river/) - Django state machine and workflow library provides on the fly changes.
* [django-states](https://github.com/vikingco/django-states2/) - State machine for django models.
* [django-viewflow](https://github.com/viewflow/viewflow) - Reusable workflow library for Django. :star:1134
* [django-workflows](https://bitbucket.org/jerzyk/django-workflows/) - django-workflows provides a generic workflow engine for Django.
* [django-xworkflows](https://github.com/rbarrois/django_xworkflows/) - Library to plug xworkflows into django models.

## Other

*Other awesome Django packages.*

* [django-activeurl](https://github.com/hellysmile/django-activeurl) - Easy to use active URL highlighting for django :star:124
* [django-activity-stream](https://github.com/justquick/django-activity-stream/) - Generate generic activity streams from the actions on your site. Users can follow any actors' activities for personalized streams.
* [django-adminactions](https://github.com/saxix/django-adminactions/) - Collection of useful actions to use with django.contrib.admin.ModelAdmin and/or django.contrib.admin.AdminSite
* [django-autoadmin](https://github.com/rosarior/django-autoadmin/) - Automatic admin users for Django projects.
* [django-braces](https://github.com/brack3t/django-braces/) - Reusable, generic mixins for Django.
* [django-calendarium](https://github.com/bitlabstudio/django-calendarium/) - A reusable app to manage and display a calendar in your templates.
* [django-changuito](https://github.com/angvp/django-changuito/) - A cart app for your django site, an updated fork of django-cart
* [django-cors-headers](https://github.com/ottoyiu/django-cors-headers) - Django app for handling the server headers required for Cross-Origin Resource Sharing (CORS). :star:2199
* [django-dfp](https://github.com/praekelt/django-dfp) - App that provides tags to fetch Google DFP ads. :star:4
* [django-dynamic-scraper](https://github.com/holgerd77/django-dynamic-scraper/) - Creating Scrapy scrapers via the Django admin interface.
* [django-extensions](https://github.com/django-extensions/django-extensions/) - This is a repository for collecting global custom management extensions for the Django Framework.
* [django-filter](https://github.com/carltongibson/django-filter/) - A generic system for filtering Django QuerySets based on user selections.
* [django-friendship](https://github.com/revsys/django-friendship/) - Django app to manage following and bi-directional friendships.
* [django-gravatar2](https://github.com/twaddington/django-gravatar/) - Essential Gravatar support for Django. Features helper methods, templatetags and a full test suite!
* [django-hackathon-starter](https://github.com/DrkSephy/django-hackathon-starter) - A boilerplate for Django web applications, containing various social authentication methods and several popular API examples. :star:1216
* [django-ipware](https://github.com/un33k/django-ipware) - A Django application to retrieve user's IP address. :star:431
* [django-macros-url](https://github.com/phpdude/django-macros-url/) - Django Macros URL. Routing must be simple as possible.
* [django-magic-embed](https://github.com/kronoscode/django-magicembed) - an easy and simple Django template tag and tool to embed video and get thumbnails from video providers. :star:18
* [django-markitup](https://github.com/zsiciarz/django-markitup) - A Django reusable application for end-to-end markup handling. :star:44
* [django-mmc](https://github.com/LPgenerator/django-mmc) - App for monitoring management commands on Django.. :star:39
* [django-overextends](https://github.com/stephenmcd/django-overextends) - Circular template inheritance for Django. :star:100
* [django-pagination](https://github.com/ericflo/django-pagination) - https://github.com/ericflo/django-pagination. :star:512
* [django-el-pagination](https://github.com/shtalinberg/django-el-pagination) - Django EL(Endless) Pagination can be used to provide Twitter-style or Digg-style pagination, with optional Ajax support. :star:179
* [django-simple-pagination](https://github.com/MicroPyramid/django-simple-pagination) - A Simple Django app for digg-style pagination with little effort. :star:35
* [django-quiz-app](https://github.com/tomwalker/django_quiz/) - This is a configurable quiz app for Django.
* [django-recaptcha](https://github.com/praekelt/django-recaptcha/) - Django reCAPTCHA form field/widget integration app.
* [django-smuggler](https://github.com/semente/django-smuggler/) - Django Smuggler is a pluggable application for Django Web Framework that helps you to import/export fixtures via the automatically-generated administration interface.
* [django-solo](https://github.com/lazybird/django-solo/) - Helps working with singletons - things like global settings that you want to edit from the admin site.
* [django-sql-explorer](https://github.com/groveco/django-sql-explorer/) - Easily share data via SQL queries, right from Django
* [django-stored-messages](https://github.com/evonove/django-stored-messages/) - Store Django messages on your project's backend.
* [django-ratelimit](https://github.com/jsocol/django-ratelimit/) - provides a decorator to rate-limit views. Limiting can be based on IP address or a field in the request--either a GET or POST variable.
* [django-uuslug](https://github.com/un33k/django-uuslug/) - a slugify application that guarantees Uniqueness and handles Unicode.
* [django-watchman](https://github.com/mwarkentin/django-watchman/) - django-watchman exposes a status endpoint for your backing services like databases, caches, etc.
* [django-websocket-redis](https://github.com/jrief/django-websocket-redis) - Websockets for Django applications using Redis as message queue. :star:712
* [metamon](http://tryolabs.github.io/metamon/) - Collection of Ansible playbooks to quickly start your Django Application
* [micawber](https://github.com/coleifer/micawber/) - A small library for extracting rich content from urls.
* [towel](https://github.com/matthiask/towel/) - a collection of tools which make your life easier if you are building a web application using Django.
* [django-admin-env-notice](https://github.com/dizballanze/django-admin-env-notice) - Visually distinguish environments in Django Admin. :star:88

# Projects

*Outstanding Django projects.*

## CMS

* [django-cms](https://github.com/divio/django-cms/) - The easy-to-use and developer-friendly CMS.
* [django-fiber](https://github.com/django-fiber/django-fiber/) - Django Fiber, a simple, user-friendly CMS for all your Django projects
* [feincms](https://github.com/feincms/feincms/) - A Django-based CMS with a focus on extensibility and concise code.
* [Mezzanine](https://github.com/stephenmcd/mezzanine/) - A content management platform built using the Django framework.
* [wagtail](https://github.com/wagtail/wagtail/) - A Django content management system focused on flexibility and user experience.
* [leonardo](https://github.com/django-leonardo/django-leonardo/) - A new Django content management system built on top of FeinCMS and OpenStack Horizon.


## Document Management

* [mayan-edms](https://gitlab.com/mayan-edms/mayan-edms) - Open source, Django based DMS (document management system) with custom metadata indexing, file serving integration, OCR capabilities, document versioning and electronic signature verification.

## e-Commerce

* [Cartridge](https://github.com/stephenmcd/cartridge) - Ecommerce for Django/Mezzanine. :star:562
* [django-oscar](https://github.com/django-oscar/django-oscar) - Domain-driven e-commerce for Django. :star:3149
* [Lighting Fas Shop](http://www.getlfs.com/) - Lighting Fas Shop is Ecommerce made with Django.
* [Saleor](http://getsaleor.com) - An e-commerce storefront for Python and Django.
* [Satchless](http://satchless.com) - Satchless brings e-commerce and Python together.
* [Satchmo](https://bitbucket.org/chris1610/satchmo/src/) - Satchmo is an eCommerce framework created in Django which allows you to develop unique and robust online stores.
* [Django-Shop](http://www.django-shop.org) - A Django based shop system.

## Other

* [Django packages](https://github.com/djangopackages/djangopackages/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [Django-QA](https://github.com/swappsco/django-qa/) - A simple Q&A App.
* [django-salted](https://github.com/wunki/django-salted/) - Full stack SaltStack configuration for Django with the help of Vagrant.
* [Drum](https://github.com/stephenmcd/drum) - Reddit / Hacker News clone for Django/Mezzanine. :star:365
* [koalixcrm](https://github.com/tfroehlich82/koalixcrm) - Beautiful CRM/ERP for small business. :star:77
* [OmniDB](https://github.com/OmniDB/OmniDB) - Web tool for database management and conversion, built with Django. :star:1117

## Project Management

* [ITSY](https://github.com/yetkinozturk/ITSY/) - Issue Tracking System
* [taiga](https://github.com/taigaio/taiga-back) - Agile, Free and Open Source Project Management Tool :star:4178

# Resources

*Where to discover new Django apps and projects.*

## Books

* [Django by Example](https://github.com/kevinlondon/django-by-example) (1.2)
* [Djen of Django](https://www.agiliq.com/books/djenofdjango/) (< 1.7)
* [Effective Django](http://www.effectivedjango.com/) (1.5)
* [Getting started with Django](http://www.gettingstartedwithdjango.com/) (video)
* [High Performance Django](https://highperformancedjango.com/) (1.7) - Deploying fast, scalable Django sites.
* [Lightweight Django](http://shop.oreilly.com/product/0636920032502.do) (1.7) - Using REST, WebSockets, and Backbone with Django
* [Tango With Django](http://www.tangowithdjango.com/) (1.5)
* [Test-Driven Web Development with Python](https://web.archive.org/web/20170914220113/http://chimera.labs.oreilly.com/books/1234000000754/index.html) (1.7)
* [Two Scoops of Django: Best Practices for Django 1.11](https://www.twoscoopspress.com/products/two-scoops-of-django-1-11/) - A best practice book for making Python and Django as fun as ice cream.

## Websites

* [Django Girls Tutorial](https://tutorial.djangogirls.org/) - A fun and engaging tutorial showing how to build a blog using Django and deploy it to Heroku.
* [Mozilla Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django) - Tutorial that shows how to set up a development environment, and how to get started with using it to create your own web applications.
* [Django Introduction](http://www.django-introduction.com/) - A reusable set of slides to educate more people about Django.
* [Django Packages](https://djangopackages.org/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [Django Sites](https://www.djangosites.org) - Django Sites is a showcase of websites powered by Django.
* [Full Stack Python's Django page](https://www.fullstackpython.com/django.html) - contains explanations for Django's philosophy and its components along with links to other resources and tutorials.
* [Simple is Better Than Complex](https://simpleisbetterthancomplex.com) - A blog about Django, Python and Web Development. Weekly updates containing tutorials, tips, featured packages, reference guides and code snippets.
* [Marina Mele's site](http://www.marinamele.com/) - A blog about Django and Python. Includes deployment to Heroku, a Django project boilerplate for best practices, testing and more.

## Conferences

* [Django Beer](https://www.djangobeer.com/) - the new meeting of the Django community of Florence.
* [Django Village](http://djangovillage.it/) - the Italian Django community conference. An opportunity to meet djangonauts from all over Italy and abroad.
* [Django Weekend](https://twitter.com/djangoweekend) - is a Django/Python non-profit community event, organised and run entirely by volunteers. The conference is Django-focused, but all aspects of Python fall within its remit.
* [Django: Under The Hood](https://www.djangounderthehood.com/) - is an exciting new Django conference for experienced Django developers. Come and learn about the internals of Django, and help to shape its future.
* [DjangoCon Europe](http://www.djangocon.eu/) - is the annual largest European-based Django conference that is usually held in late spring.
* [DjangoCon US](https://2016.djangocon.us/) - is the largest North American Django conference generally held the first week in September each year.

# Non Python packages

* [cookiecutter-django](https://github.com/pydanny/cookiecutter-django) - A cookiecutter template for creating Django projects quickly. :star:3858

## External documentation

*Additional sources of information about django features.*

* [Classy Class-Based Views](http://ccbv.co.uk/) - Detailed descriptions, with full methods and attributes, for each of Django's class-based generic views.
* [Classy Django REST Framework](http://www.cdrf.co/) - Detailed descriptions, with full methods and attributes, for each of Django REST Framework's class-based views and serializers.

## Videos

* [CodingforEntrepreneur](https://www.codingforentrepreneurs.com/projects/) - One of the best collection of Django Videos and all the projects are written in Django.
* [Code School - Try Django](https://www.codeschool.com/courses/try-django) - An introduction to the basics of Django.
* [GoDjango](https://godjango.com) - Django videos from basics to advanced. Covering 3rd party apps to core Django compontents.
* [Must Watch Django Videos](https://gitlab.com/rosarior/django-must-watch) - Must-watch videos about Django (or about Python as applied to Django)

# Utilities

*Non Django projects that make it easier to work with Django.*

* [Django-manage.py-anywhere](https://github.com/timonweb/Django-manage.py-anywhere/) - Run manage.py commands from anywhere. Finds closest to current path manage.py file and runs commands against it.
* [Logan](https://github.com/dcramer/logan) - A toolkit for running standalone Django applications. It provides you with tools to create a CLI runner, manage settings, and the ability to bootstrap the process. :star:197


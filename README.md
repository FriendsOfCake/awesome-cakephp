# Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome **CakePHP 3.x** plugins, resources and shiny things.

If you are looking for CakePHP 2.x resources please visit:
- the [CakePHP 2.x version](https://github.com/FriendsOfCake/awesome-cakephp/tree/cake2) of this awesome list
- this wiki with a [list of not-yet upgraded plugins](https://github.com/FriendsOfCake/awesome-cakephp/wiki#plugins-not-yet-upgraded-from-2x-to-3x)

Additional lists you might find useful:
- [CakePHP Plugins](https://plugins.cakephp.org)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

> For those wondering; this list differs from plugins.cakephp.org by supporting
> plugin subparts (instead of only the whole plugin/repo), more granular
> grouping and the primary focus on task specific functionality.

## Table of Contents

- [Plugins](#plugins)
	- [APM](#apm)
	- [Asset Management](#asset-management)
	- [Auditing / Logging](#auditing--logging)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Caching](#caching)
	- [Code Analysis](#code-analysis)
	- [Debugging](#debugging)
	- [Dependency Injection](#dependency-injection)
	- [E-commerce](#e-commerce)
	- [Email](#email)
	- [Environment](#environment)
	- [Files](#files)
	- [Filtering and Validation](#filtering-and-validation)
	- [Geolocation](#geolocation)
	- [I18n](#i18n)
	- [Imagery](#imagery)
	- [Libs](#libs)
	- [Markup](#markup)
	- [Migration](#migration)
	- [Miscellaneous](#miscellaneous)
	- [Navigation](#navigation)
	- [NoSQL](#nosql)
	- [Notifications](#notifications)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [PDF](#pdf)
	- [Queue](#queue)
	- [REST and API](#rest-and-api)
	- [Search](#search)
	- [Security](#security)
	- [SEO](#seo)
	- [Skeleton](#skeleton)
	- [Social](#social)
	- [Templating](#templating)
	- [Testing](#testing)
	- [Third Party APIs](#third-party-apis)
- [Software](#software)
	- [Development Environment](#development-environment)
- [Web Applications](#web-applications)
	- [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
	- [Demo](#demo)
- [Resources](#resources)
	- [Help](#help)
	- [CakePHP Websites](#cakephp-websites)
	- [CakePHP Books and Articles](#cakephp-books-and-articles)
	- [CakePHP Videos](#cakephp-videos)
	- [CakePHP Tutorials](#cakephp-tutorials)
	- [CakePHP Reading and Listening](#cakephp-reading-and-listening)
	- [CakePHP Internals Reading](#cakephp-internals-reading)
- [Conferences](#conferences)
- [Contributing](#contributing)

# Plugins

## APM
*Plugins for Application Performance Monitoring.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - A complete plugin that enables full New Relic integration for a CakePHP application, including CLI naming, exceptions sending, custom timings, etc. It does not depend on New Relic agent.

- [Brunitto/NewRelic plugin](https://github.com/brunitto/cakephp-new-relic) - A simple plugin that enables just name transaction and browser timing for a CakePHP 3 application using the New Relic PHP agent.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
- [Assets plugin](https://github.com/mirko-pagliai/assets) - Dynamic and "on the fly" asset files.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) - Less parser plugin for CakePHP.
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - Compress HTML output.

## Auditing / Logging
*Plugins for auditing and logging.*

- [AuditStash plugin](https://github.com/lorenzo/audit-stash) - Flexible and rock solid audit log tracking.
- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Simple and stand-alone logging to database instead of files.
- [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities.

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [Acl plugin](https://github.com/cakephp/acl/) - Managing ACL as database approach.
- [ADmad/HybridAuth plugin](https://github.com/ADmad/CakePHP-HybridAuth) - A plugin which allows using the [HybridAuth](https://github.com/hybridauth/hybridauth) social sign on library with CakePHP.
- [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - A plugin for authenticating using JSON Web Tokens.
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - A simple Cake 3 plugin to automatically authenticate users with Cookies.
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) - A CakePHP plugin for hierarchical, role based, simple authorization.
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - OAuth2 authentication using the [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client).
- [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - Event driven behavior for easily generating single-use security tokens.
- [MultiTenant plugin](https://github.com/pronique/multitenant) - Easily build SaaS enabled web applications.
- [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - Authentication and role based (single/multi) authorization as very light-weight approach.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) for a DRY approach on password hashing.
- [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth) - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) library.
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) -  Allow groups of users or single users to view a specific page.
- [Users plugin](https://github.com/CakeDC/users) - Complete user management (admin panel, remember me, etc), Facebook/Twitter login, RBAC, API and more.

## Caching
*Plugins for caching data.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code.

## Debugging
*Plugins for debugging.*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) A plugin to seamlessly integrate Airbrake with CakePHP for errors and exceptions.
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [ErrorEmail plugin](https://github.com/ebrigham1/cakephp-error-email) - A plugin to email exception/error information to your dev team.
- [Execution order](https://github.com/dereuromark/executionorder) - A demo app to display the execution order of files, methods and callbacks.
- [Psa/FixtureCheck plugin](https://github.com/World-Architects/cakephp-fixture-check) - A plugin to help detect mismatches in live DB and fixtures in order to make fixture based tests more reliable and deployments safer.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools.
- [Whoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops).

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [PimpleDi plugin](https://github.com/rochamarcelo/cake-pimple-di) Allows dependency injection based on Pimple library.
- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - Dependency injection container plugin that adds the ability to configure object instances and their dependencies before they are used, and to store them into a container class for easy access.

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- [PaypalWPP plugin](https://github.com/cpierce/paypal-wpp) - A package for communicating with Paypal Web Payments Pro for transactions and information about your account.

## Email
*Plugins for sending and parsing email.*

- [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - Email queue plugin with a preview and sender shell.
- [Gourmet/Email plugin](https://github.com/gourmet/email) - Email helper, layout and more.
- [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - Email transport plugin for sending email via Mailgun.
- [SparkPost plugin](https://github.com/syntaxera/cakephp-sparkpost-plugin) - Email transport plugin for sending email via the SparkPost API.

## Environment
*Plugins for environment.*

- [Environments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle environments.
- [Gourmet/Aroma plugin](https://github.com/gourmet/aroma) - Database based configuration.
- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - A plugin to manage your settings via your database.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic environments.

## Files
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - Abstract filesystem access using Flysystem.
- [FriendsOfCake/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - A customisable plugin that uses [Flysystem](http://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.).
- [Image plugin](https://github.com/josbeir/image) - Image behavior that works much like Cake's built in TranslateBehavior.
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - A customisable upload plugin with thumbnail generation.
- [Upload plugin](https://github.com/Xety/Cake3-Upload) - A little plugin to upload file.

## Filtering and Validation
*Plugins for filtering and validating data.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - Extra dispatcher filters (maintenance, robots, ip, etc).
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - Extra validation providers (Respect, IsoCodes, etc.) and rules.
- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier) - Purifier Plugin that features a trait, behavior and helper to allow you to get sanitization and filtering where you need it. You can configure multiple sets of filter rules as well.
- [HtmlPurifier plugin](https://github.com/chrisShick/CakePHP3-HtmlPurifier) - Purifier Plugin Behavior that cleanses data before it is marshaled into the entity and/or before saving.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- [Geo plugin](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMapsV3 helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization).*

- [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools.
- [Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.
- [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - A plugin with shadow table based replacement for core's Translate behavior.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - Managing i18n PO files and translations via Transifex API.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate) - Manage translations of your static content the easy way via web backend, incl. import from POT files, auto-suggest and auto-translate via API.
- [Translation plugin](https://github.com/ava007/wnk_translation) - Extract pot files, translate string (manually, google, community), export translations to pot files.

## Imagery
*Plugins for manipulating images.*

- [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](http://glide.thephpleague.com/) image manipulation library.
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - An image manipulation plugin and wrapper around [Imagine](https://github.com/avalanche123/Imagine).
- [Thumber plugin](https://github.com/mirko-pagliai/cakephp-thumber) - A plugin to create thumbnails using [intervention/image](https://github.com/Intervention/image).

## Libs
*Useful libraries or tools that don't fit in any of the other categories.*

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library - used in CakePHP 3.x core.
- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano.
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP task runner and deployment package.
- [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.
- [YamlRoute](https://github.com/makallio85/yaml-route) - Configure routes with simple YAML files.

## Markup
*Plugins for working with markup.*

- [Gourmet/CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](http://commonmark.org/) Markdown parsing.
- [Markup plugin](https://github.com/dereuromark/cakephp-markup) - Allows to use PHP or JS based syntax highlighting.

## Migration
*Plugins and resources around migration and upgrading.*

- [Migrations plugin](https://github.com/cakephp/migrations) - (DB) Migration plugin.
- [Upgrade app](https://github.com/cakephp/upgrade) - Official upgrade app for 2.x=>3.x.
- [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - An extended upgrade app for 2.x=>3.x and between 3.x.
- [Upgrade/Migration Guide](http://book.cakephp.org/3.0/en/appendices.html) - Official migration guide.

## Miscellaneous
*Misc plugins and libraries.*

- [ActionsClass plugin](https://github.com/HavokInspiration/cakephp-actions-class) - Gives you the ability to manage your Controller actions as single classes.
- [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests.
- [CakeAdmin plugin](https://github.com/cakemanager/cakephp-cakeadmin) - A non-stable user management plugin with a built-in admin area.
- [CakeMiddlewares](https://github.com/chrisShick/CakeMiddlewares) - A collection of Cakephp Middlewares.
- [Comments plugin](https://github.com/Kareylo/CakePHP-Comments) - A fully customizable Comments plugin.
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - A plugin to convert currency into another one.
- [Dashboard plugin](https://github.com/gourmet/dashboard) - Build beautiful dashboards for your cakes.
- [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) - A plugin to export, import and manage database backups.
- [Feedback plugin](https://github.com/dereuromark/cakephp-feedback) - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form.
- [Flash plugin](https://github.com/dereuromark/cakephp-flash) - More powerful flash messages for your application.
- [Hashid plugin](https://github.com/dereuromark/cakephp-hashid) - Allows to use hashids to not expose the database ids to the user.
- [Interval plugin](https://github.com/LubosRemplik/CakePHP-Interval) - Converts seconds to human readable string (string to seconds), uses business hours (1 week = 5 days, 1 day = 8 hours).
- [Robotusers/Tactician plugin](https://github.com/robotusers/cakephp-tactician) - Tools for Tactician command bus integration.
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
- [TokenVerify plugin](https://github.com/mosaxiv/cakephp-token-verify) - Easily issue tokens that can be used for mail authentication.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells and more.
- [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins.
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools) - User tools for login, registration, password reset and more. Works out of the box CRUD like and is highly configurable.
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - Containing useful components (Authorizer, Menu) and behaviors (WhoDidIt, Uploadable, Metas, Stateable).
- [Wrench plugin](https://github.com/HavokInspiration/wrench) - Maintenance Mode plugin. Easily extensible and customizable.
- [Yaml plugin](https://github.com/guemidiborhane/Cake-Yaml) - For using YAML config files instead of PHP arrays.

## Navigation
*Tools for building navigation structures.*

- [Icings/Menu plugin](https://github.com/icings/menu) - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) seasoned menu plugin for CakePHP.

## NoSQL
*Plugins for working with "NoSQL" backends.*

- [Monga plugin](https://github.com/lewestopher/cakephp-monga) - Provides access to MongoDB datasource using [`thephpleague/monga`](https://github.com/thephpleague/monga).

## Notifications
*Plugins for working with notification software.*

- [ker0x/CakeGcm plugin](https://github.com/ker0x/CakeGCM) - A plugin to send downstream messages to an Android or iOS device through Google Cloud Messaging.
- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - A plugin that makes creating and reading notifications easy.
- [ker0x/Push plugin](https://github.com/ker0x/cakephp-push) - A plugin to send push notifications through services like Firebase Cloud Messaging.

## ORM and Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records.
- [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - Behavior for duplicating entities including related data.
- [JeremyHarris/LazyLoad plugin](https://github.com/jeremyharris/cakephp-lazyload) - An association lazy loader for entities.
- [Money plugin](https://github.com/gourmet/money) - Money data type for CakePHP entities using [sebastianbergmann/money](https://github.com/sebastianbergmann/money).
- [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - Allows setting default order for your tables.
- [Muffin/Trash plugin](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP.
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - Behavior for persisting selected fields of related models.
- [Robotusers/Excel plugin](https://github.com/robotusers/cakephp-excel) - ORM wrapper for PHPExcel.
- [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - Singe Table Inheritance (STI) plugin.
- [RowLocker plugin](https://github.com/lorenzo/row-locker) - Exclusive locks for rows in your tables.
- [Serializeable Data Types plugin](https://github.com/burzum/cakephp-serialize-data-types) - Serialize DB content as JSON or using phps serializing functions.
- [Webservices ORM plugin](https://github.com/usemuffin/webservice) - An ORM like interface for webservices.

## PDF
*Plugins and software for working with PDF files.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## Queue
*Plugins for working with event and task queues.*

- [CakeResque plugin](https://github.com/wa0x6e/Cake-Resque) - A plugin for Resque, a library for creating background jobs.
- [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - A plugin that provides queueing integration with a variety of backends (BeanstalkD, MySQL, Redis, etc.).
- [Gearman plugin](https://github.com/cvo-technologies/cakephp-gearman) - A plugin for offloading CakePHP tasks to a Gearman Job Server.
- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal and dependency-free queue solution.

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - Swagger 2.0 documentation for your CakePHP APIs using swagger-php and swagger-ui.
- [Alt3/ValidationExposer plugin](https://github.com/alt3/cakephp-validation-exposer) - Easily expose your application's validation rules.
- [ApiPagination plugin](https://github.com/bcrowe/cakephp-api-pagination) - Injects pagination information from CakePHP's Paginator into serialized JsonView and XmlView responses.
- [Cors plugin](https://github.com/ozee31/cakephp-cors) - Activate CORS with Middleware.
- [Cors plugin](https://github.com/snelg/cakephp-cors) - A lightweight plugin for adding CORS headers to specified endpoints.
- [CrudJsonApi plugin](https://github.com/FriendsOfCake/crud-json-api) - Crud listener for building [JSON API](http://jsonapi.org/) compliant APIs.
- [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - A plugin which allows using [Fractal transformers](http://fractal.thephpleague.com/transformers/) for your API output.
- [JsonApi plugin](https://github.com/josbeir/cakephp-json-api) - Implements the [JSON API](http://jsonapi.org/) format.
- [RestApi plugin](https://github.com/multidots/cakephp-rest-api) - Provides basic support for building REST API services.

## Search
*Plugins and software for indexing and performing search queries on data.*

- [ElasticSearch plugin](https://github.com/cakephp/elastic-search) - Alternative ORM using Elastic Search as its backend.
- [PlumSearch plugin](https://github.com/skie/plum_search) - Search plugin implements custom, flexible and extendable search strategies. Implements PRG pattern.
- [FriendsOfCake/Search plugin](https://github.com/FriendsOfCake/search) - Search provides a searching/filter module for CakePHP applications.
- [SphinxSearch plugin](https://github.com/voycey/cakephp-sphinxsearch) - Basic behaviour implementation for querying SphinxSearch indexes.
- [Tags plugin](https://github.com/dereuromark/cakephp-tags) - For tagging and finding tagged records.

## Security
*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

- [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - Simple, unobstrusive and extendable captcha solution providing by default an image based math captcha.
- [CipherBehavior plugin](https://github.com/adayth/cakephp-cipher-behavior) - Cipher your entities data with this behavior. Encryption is done at PHP level using CakePHP Security class.
- [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - Primary key obfuscation using HashIds, Optimus, Tiny and/or custom obfuscation strategies.
- [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - A plugin for rate limiting (API) requests.
- [Recaptcha plugin](https://github.com/agiletechvn/Recaptcha) - Simple, lightweight Google Recaptcha v2.
- [Recaptcha Mailhide plugin](https://github.com/mirko-pagliai/cakephp-recaptcha-mailhide) - A plugin that allows you to hide email addresses using reCAPTCHA.

## SEO
*Search Engine Optimization.*

- [Muffin/Slug plugin](https://github.com/UseMuffin/Slug) - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.
- [Seo plugin](https://github.com/orgasmicnightmare/cakephp-seo) - Auto-creates and manages your SEO tags.
- [Sluggable plugin](https://github.com/Xety/Cake3-Sluggable) - A simple Cake3 plugin to slug fields and find records by slug.
- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.

## Skeleton
*Plugins and repositories around app skeletons.*

- [App template](https://github.com/cakephp/app) - An empty CakePHP project for use with composer.
- [App template with material ui](https://github.com/coolops/web-app) - CakePHP material ui admin template project for use with composer.
- [Crud plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.
- [Plugin Skeleton](https://github.com/Xety/Cake3-PluginSkeleton) - A skeleton example to create a Cake3 plugin.

## Social
*Plugins around social features.*

- [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - Allows users to rate records.
- [SocialShare plugin](https://github.com/drmonkeyninja/cakephp-social-share) - Link generator for sharing content on social networks.

## Templating
*Plugins for templating and lexing.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - An address helper that outputs a marked up address.
- [Bake plugin](https://github.com/cakephp/bake) - Provides code generation functionality.
- [Bootstrap plugin](https://github.com/elboletaire/twbs-cake-plugin) - A Bootstrap 3 plugin with support for LESS.
- [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 3 integration.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel) - An Excel view to generate XLSX files.
- [Chocolate plugin](https://github.com/commercial-hippie/chocolate) - Front-End framework FormHelper extensions.
- [CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](http://commonmark.org) (markdown) support to models and views.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view class to easily generate CSV.
- [Feed plugin](https://github.com/dereuromark/cakephp-feed) - Containing an RssView class to easily generate (complex) RSS feeds.
- [InlineCss plugin](https://github.com/drmonkeyninja/cakephp-inline-css) - A plugin to convert HTML style blocks to inline CSS on a View template (intended for use with email templates).
- [JadeView plugin](https://github.com/clthck/cakephp-jade) - Jade template engine plugin.
- [Liquid plugin](https://github.com/gourmet/liquid) - A plugin to use the Liquid templating language for views.
- [Meta plugin](https://github.com/dereuromark/cakephp-meta) - Makes handling meta tags and SEO relevant HTML markup DRY and easy.
- [SocialMeta plugin](https://github.com/gourmet/social-meta) - Adds support for Facebook's OpenGraph and Twitter's Card meta tags.
- [TwigView plugin](https://github.com/WyriHaximus/TwigView) - A plugin to use the Twig Templating Language for views.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - Helper for embedding YouTube, Vimeo and Dailymotion videos.

## Testing
*Plugins/Tools for testing codebases and generating test data.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - The official CakePHP integration with [Codeception](http://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- [CodeSniffer plugin](https://github.com/dereuromark/cakephp-codesniffer) - Auto-find code issues/smells and auto-fix CS errors.
- [CodeSniffer plugin sniffs](https://github.com/dereuromark/codesniffer-standards) - Sniff packages/rules compatible with phpcs-fixer branch and the CodeSniffer plugin.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) support for CakePHP fixtures.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) - Fixtures plugin to read existing fixtures and create table/insert data for quick start with app.
- [FriendsOfCake/fixturize](https://github.com/FriendsOfCake/fixturize) - More efficient inserting fixtures when running test suites by decreasing amount of inserts (mysql only).
- [Gourmet/Muffin plugin](https://github.com/gourmet/muffin) - [FactoryMuffin](https://github.com/thephpleague/factory-muffin) support for CakePHP fixture records.

## Third Party APIs
*Plugins for accessing third party APIs.*

- [CakeTmdb plugin](https://github.com/drmonkeyninja/cakephp-tmdb) - The Movie Database (TMDB) API integration.
- [GitHub plugin](https://github.com/cvo-technologies/cakephp-github) - Allows access to the GitHub REST APIs using the [Webservice](https://github.com/UseMuffin/Webservice) ORM.
- [Ratchet plugin](https://github.com/WyriHaximus/Ratchet) - Brings the Ratchet websocket package to CakePHP.
- [Salesforce plugin](https://github.com/voycey/cakephp-salesforce) - Allows use of CakePHP's ORM to Query and Interact with Salesforce Enterprise Instances.
- [Twitter plugin](https://github.com/cvo-technologies/cakephp-twitter) - Allows access to the Twitter REST and streaming APIs using the [Webservice](https://github.com/UseMuffin/Webservice) ORM.

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- [Cakebox](https://github.com/alt3/cakebox) - A Vagrant development environment powered by the CakePHP 3.x Console.
- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) - The .gitignore file proposals.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - Tool for spinning up multiple CakePHP 3.x Vanilla Dev Environments.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) - CakePHP in a docker container environment.
- [Mixer](https://github.com/CakeDC/mixer) - A plugin to discover and manage CakePHP plugins.
- [NetBeans plugin](https://github.com/junichi11/cakephp3-netbeans) -  This plugin provides support for CakePHP in NetBeans 8.1+.
- [Oven](https://github.com/CakeDC/oven) - Setup your favorite framework with 1 file and 1 click.
- [PhpStorm plugin](https://github.com/skie/PhpStorm) -  CakePHP auto-completion support for console commands in PhpStorm IDE.
- [PuPHPet](https://puphpet.com/) - Web interface for building a Vagrant + Puppet box.
- [Puppet](https://puppetlabs.com/) - A server automation framework and application.
- [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

## Web Applications

## CMS and applications built on CakePHP

- [CakeBlog](https://github.com/gwhitcher/CakeBlog) - Open source blog software.
- [QuickApps-CMS](https://github.com/quickapps/cms) - Open source content management system.

## Demo
*Web-based (demo) applications and tools.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - A simple Blog example with CakePHP based on [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) A bookmarking application built with the CRUD plugin.
- [CakeFest](http://cakefest.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - Example CakePHP codebase containing real world examples (CRUD, auth, advanced patterns and more) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.
- [Sandbox](http://sandbox.dereuromark.de) - A sandbox CakePHP application with lots of demos and plugin showcasings.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
- [Xeta](https://github.com/XetaIO/Xeta) - A resource to help people starting with CakePHP.

# Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help
*Where to get help.*

- [cakephpbrasil.com.br](http://cakephpbrasil.com.br/) - The brazilian community website.
- [CakePHP-FR.org](http://cakephp-fr.org) - The french community website.
- [CakePHP.ir](http://forum.cakephp.ir/) - discussion with other devs and generic questions for Persian community.
- [Official CakePHP Forum](http://discourse.cakephp.org/) - This is for generic questions and alike.
- [IRC Channel](http://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - Live chat/discussion with other devs and core devs.
- [stackoverflow.com/questions/tagged/cakephp](http://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

- [AD7six.com](http://AD7six.com) - A CakePHP core dev blog.
- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.
- [dereuromark.de](http://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [florian-kraemer.net](http://florian-kraemer.net) - A CakePHP related core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
- [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.
- [waltherlalk.com](http://waltherlalk.com) - A CakePHP related core dev blog.

## CakePHP Books and Articles
*Fantastic CakePHP-related (e)books and other reading material.*

## CakePHP Videos
*Fantastic CakePHP-related videos.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.


## CakePHP Tutorials
*Must-do tutorials.*

- [Official Blog tutorial](http://book.cakephp.org/3.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-releated reading and listening materials.*

- [CakePHP Cookbook(!)](http://book.cakephp.org/) - The official CakePHP documentation.
- [CakePHP Reporter](http://www.scoop.it/t/cakephp-reporter) - a newspaper and collection of material about CakePHP.

## CakePHP Internals Reading
*Reading materials related to the CakePHP internals and decisions.*

- [Core Google Group](https://groups.google.com/forum/#!forum/cakephp-core) - Discussions around the CakePHP core.
- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - Give 'em a hand.

# Conferences

## Official
*International conference.*

- [cakefest.org](http://cakefest.org/) - Annual CakePHP Conference.

## MeetUps
*Regional meet-ups.*

- [CakePHP-DE](http://www.meetup.com/CakePHP-DE) - MeetUps in Germany.
- [CakePHP-France](http://www.meetup.com/CakePHP-France) - MeetUps in France.
- [CakePHP-NL](http://www.meetup.com/CakePHP-NL) - MeetUps in Netherlands.

# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits
awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors), too.

# Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome **CakePHP 3.x+** plugins, resources and shiny things.

Plugins with the ":strawberry:" icon have CakePHP 4 compatible release too.

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
	- [Architecture](#architecture)
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
	- [File Manipulation](#file-manipulation)
	- [Filtering and Validation](#filtering-and-validation)
	- [Geolocation](#geolocation)
	- [HTTP](#http)
	- [I18n](#i18n)
	- [Imagery](#imagery)
	- [Libs](#libs)
	- [Markup](#markup)
	- [Migration](#migration)
	- [Miscellaneous](#miscellaneous)
	- [Navigation](#navigation)
	- [NoSQL](#nosql)
	- [Notifications](#notifications)
	- [ORM / Database / Datamapping](#orm--database--datamapping)
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

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - A complete plugin that enables full New Relic integration for a CakePHP application, including CLI naming, exceptions sending, custom timings, etc.
- [NewRelic plugin](https://github.com/brunitto/cakephp-new-relic) - A simple plugin that enables just name transaction and browser timing using the New Relic PHP agent.

## Architecture

- :strawberry: [Burzum/CakeServiceLayer plugin](https://github.com/burzum/cakephp-service-layer) - Service layer and domain/business model implementation.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- :strawberry: [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
- :strawberry: [AssetMix plugin](https://github.com/ishanvyas22/asset-mix) - Provides integration with [Laravel Mix](https://laravel-mix.com) asset compilation.
- [Assets plugin](https://github.com/mirko-pagliai/cakephp-assets) - Dynamic and "on the fly" asset files.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) - Less parser plugin for CakePHP.
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - Compress HTML output.

## Auditing / Logging
*Plugins for auditing and logging.*

- :strawberry: [AuditStash plugin](https://github.com/lorenzo/audit-stash) - Flexible and rock solid audit log tracking.
- :strawberry: [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Simple and stand-alone logging to database instead of files.
- :strawberry: [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities.

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- :strawberry: [Acl plugin](https://github.com/cakephp/acl/) - Managing ACL as database approach.
- :strawberry: [ADmad/JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - A plugin for authenticating using JSON Web Tokens.
- :strawberry: [ADmad/SocialAuth plugin](https://github.com/ADmad/cakephp-social-auth) - A plugin which allows you to authenticate using social providers like Facebook/Google/Twitter etc. using [SocialConnect/auth](https://github.com/SocialConnect/auth) social sign on library.
- :strawberry: [Authentication plugin](https://github.com/cakephp/authentication) - Official CakePHP authentication middleware plugin.
- :strawberry: [Authorization plugin](https://github.com/cakephp/authorization) - Official CakePHP authorization stack.
- [CakeDC/NavAuth plugin](https://github.com/CakeDC/cakephp-nav-auth) - A plugin for authenticating against Navision® service using SOAP or OData services. It includes NTLM authentication and more.
- :strawberry: [CakeDC/Users plugin](https://github.com/CakeDC/users) - Complete user management (admin panel, remember me, etc), Social login (FB, Twitter, LinkedIn, Google, Instagram), RBAC, API and more.
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - A simple Cake 3 plugin to automatically authenticate users with Cookies.
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) - A CakePHP plugin for hierarchical, role based, simple authorization.
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - OAuth2 authentication using the [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client).
- :strawberry: [Muffin/Tokenize plugin](https://github.com/UseMuffin/Tokenize) - Event driven behavior for easily generating single-use security tokens.
- [MultiTenant plugin](https://github.com/pronique/multitenant) - Easily build SaaS enabled web applications.
- :strawberry: [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - Authentication and role based (single/multi) authorization as very light-weight approach.
- :strawberry: [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/master/docs/Behavior/Passwordable.md) for a DRY approach on password hashing.
- :strawberry: [TwoFactorAuth plugin](https://github.com/andrej-griniuk/cakephp-two-factor-auth) - Allows two factor authentication using Google Authenticator or similar app to generate one-time codes. Based on [RobThree/TwoFactorAuth](https://github.com/RobThree/TwoFactorAuth) library.
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) -  Allow groups of users or single users to view a specific page.

## Caching
*Plugins for caching data.*

- :strawberry: [Cache plugin](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- :strawberry: [CakeDC/PHPStan](https://github.com/CakeDC/cakephp-phpstan) - A PHPStan extension to resolve CakePHP magic around getter return types for the static analyzer.
- :strawberry: [IdeHelper plugin](https://github.com/dereuromark/cakephp-ide-helper) - Helps to make IDE support better by adding annotations to your existing code similar to what baking does to new code.
- :strawberry: [TestHelper plugin](https://github.com/dereuromark/cakephp-test-helper) - Provides testing enhancements and TDD support as browser backend.

## Debugging
*Plugins for debugging and local development.*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) A plugin to seamlessly integrate Airbrake with CakePHP for errors and exceptions.
- [AssociationsDebugger plugin](https://github.com/zunnu/associations-debugger) - A plugin that draws your model associations as diagram.
- :strawberry: [CakephpWhoops plugin](https://github.com/dereuromark/cakephp-whoops) - PHP errors and exceptions for cool kids with [filp/whoops](https://github.com/filp/whoops).
- :strawberry: [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [ErrorEmail plugin](https://github.com/ebrigham1/cakephp-error-email) - A plugin to email exception/error information to your dev team.
- :strawberry: [Execution order](https://github.com/dereuromark/executionorder) - A demo app to display the execution order of files, methods and callbacks.
- [Psa/FixtureCheck plugin](https://github.com/World-Architects/cakephp-fixture-check) - A plugin to help detect mismatches in live DB and fixtures in order to make fixture based tests more reliable and deployments safer.
- :strawberry: [Sentry plugin](https://github.com/Connehito/cake-sentry) A plugin to seamlessly integrate Sentry with CakePHP for errors and exceptions.
- :strawberry: [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [PimpleDi plugin](https://github.com/rochamarcelo/cake-pimple-di) Allows dependency injection based on Pimple library.
- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - Dependency injection container plugin that adds the ability to configure object instances and their dependencies before they are used, and to store them into a container class for easy access.

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- [PaypalWPP plugin](https://github.com/cpierce/paypal-wpp) - For communicating with Paypal Web Payments Pro for transactions and information about your account.

## Email
*Plugins for sending and parsing email.*

- [Elastic Email plugin](https://github.com/sprintcube/cakephp-elastic-email) - Email transport plugin for sending email via Elastic Email API.
- :strawberry: [EmailQueue plugin](https://github.com/lorenzo/cakephp-email-queue) - Email queue plugin with a preview and sender shell.
- [Gourmet/Email plugin](https://github.com/gourmet/email) - Email helper, layout and more.
- :strawberry: [Mailgun plugin](https://github.com/narendravaghela/cakephp-mailgun) - Email transport plugin for sending email via Mailgun.
- [SendGrid plugin](https://github.com/sprintcube/cakephp-sendgrid) - Email transport plugin for sending email via SendGrid API.

## Environment
*Plugins for environment.*

- [Environments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle environments.
- [Gourmet/Aroma plugin](https://github.com/gourmet/aroma) - Database based configuration.
- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - A plugin to manage your settings via your database.

## File Manipulation
*Plugins for file manipulation.*

- :strawberry: [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - Abstract filesystem access using Flysystem.
- [Image plugin](https://github.com/josbeir/image) - Image behavior that works much like Cake's built in TranslateBehavior.
- :strawberry: [Josbeir/Filesystem plugin](https://github.com/josbeir/cakephp-filesystem) - Abstract [Flysystem](https://flysystem.thephpleague.com/) + file entity based upload plugin.
- :strawberry: [Josegonzalez/Upload plugin](https://github.com/FriendsOfCake/cakephp-upload) - A customisable plugin that uses [Flysystem](https://flysystem.thephpleague.com/) to write to multiple backends (Dropbox, FTP, S3, Local, etc.).
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - A customisable upload plugin with thumbnail generation.
- [Xety/Cake3Upload plugin](https://github.com/Xety/Cake3-Upload) - A little plugin to upload file.

## Filtering and Validation
*Plugins for filtering and validating data.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - Extra dispatcher filters (maintenance, robots, ip, etc).
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - Extra validation providers (Respect, IsoCodes, etc.) and rules.
- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier) - Purifier Plugin that features a trait, behavior and helper to allow you to get sanitization and filtering where you need it. You can configure multiple sets of filter rules as well.
- [HtmlPurifier plugin](https://github.com/chrisShick/CakePHP3-HtmlPurifier) - Purifier Plugin Behavior that cleanses data before it is marshaled into the entity and/or before saving.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- :strawberry: [Geo plugin](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](https://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMaps helper](https://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).

## HTTP
*Plugins for HTTP and client abstraction*

- :strawberry: [Http/Adapter/Cake library](https://github.com/php-http/cakephp-adapter) - Adapter for [HTTPlug](https://github.com/php-http/httplug) HTTP client abstraction.

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization).*

- :strawberry: [ADmad/I18n plugin](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools.
- :strawberry: [Cake/Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.
- :strawberry: [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - A plugin with shadow table based replacement for core's Translate behavior.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - Managing i18n PO files and translations via Transifex API.
- [Translate plugin](https://github.com/dereuromark/cakephp-translate) - Manage translations of your static content the easy way via web backend, incl. import from POT files, auto-suggest and auto-translate via API.
- [Translation plugin](https://github.com/ava007/wnk_translation) - Extract pot files, translate string (manually, google, community), export translations to pot files.

## Imagery
*Plugins for manipulating images.*

- :strawberry: [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](https://glide.thephpleague.com/) image manipulation library.
- [HtmlToImageView plugin](https://github.com/andrej-griniuk/cakephp-html-to-image-view) - Render HTML view as image (jpg or png) using [wkhtmltoimage](https://wkhtmltopdf.org).
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - An image manipulation plugin and wrapper around [Imagine](https://github.com/avalanche123/Imagine).
- [Thumber plugin](https://github.com/mirko-pagliai/cakephp-thumber) - A plugin to create thumbnails using [intervention/image](https://github.com/Intervention/image).

## Libs
*Useful libraries or tools that don't fit in any of the other categories.*

- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano.
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Composer](https://getcomposer.org/)/[Packagist](https://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Rocketeer](https://github.com/rocketeers/rocketeer) - PHP task runner and deployment package.
- [makallio85/YamlRoute plugin](https://github.com/makallio85/yaml-route) - Configure routes with simple YAML files.

## Markup
*Plugins for working with markup.*

- [Gourmet/CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](https://commonmark.org/) Markdown parsing.
- :strawberry: [Markup plugin](https://github.com/dereuromark/cakephp-markup) - Allows to use PHP or JS based syntax highlighting.

## Migration
*Plugins and resources around migration and upgrading.*

- :strawberry: [Migrations plugin](https://github.com/cakephp/migrations) - (DB) Migration plugin.
- :strawberry: [Upgrade app](https://github.com/cakephp/upgrade) - Official upgrade app for 2.x=>3.x and 3.x=>4.x.
- :strawberry: [Upgrade app (extended)](https://github.com/dereuromark/upgrade) - An extended upgrade app for 2.x=>3.x, between 3.x and some 4.x snippets.
- [Upgrade/Migration Guide](https://book.cakephp.org/3.0/en/appendices.html) - Official migration guide.

## Miscellaneous
*Misc plugins and libraries.*

- [ActionsClass plugin](https://github.com/HavokInspiration/cakephp-actions-class) - Gives you the ability to manage your Controller actions as single classes.
- :strawberry: [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests.
- [CakeAdmin plugin](https://github.com/cakemanager/cakephp-cakeadmin) - A non-stable user management plugin with a built-in admin area.
- :strawberry: [CakeDC/Enum plugin](https://github.com/CakeDC/enum) - A plugin to add enumeration list support to your app.
- :strawberry: [CakeDto plugin](https://github.com/dereuromark/cakephp-dto) - Quickly generate useful data transfer objects for your app (mutable/immutable), replacing messy arrays and leveraging your IDE through typehinting and autocomplete.
- :strawberry: [CakeImpersonate plugin](https://github.com/jomweb/CakeImpersonate) - A component that stores the current authentication session and creates new session for impersonating Users. User can revert back to original authentication sessions without the need to re-login.
- [CakeMiddlewares](https://github.com/chrisShick/CakeMiddlewares) - A collection of Cakephp Middlewares.
- :strawberry: [Calendar plugin](https://github.com/dereuromark/cakephp-calendar) - For generating basic calendars. Includes IcalView for ICS calendar file generation.
- [Comments plugin](https://github.com/Kareylo/CakePHP-Comments) - A fully customizable Comments plugin.
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - A plugin to convert currency into another one.
- [Dashboard plugin](https://github.com/gourmet/dashboard) - Build beautiful dashboards for your cakes.
- [DatabaseBackup plugin](https://github.com/mirko-pagliai/cakephp-database-backup) - A plugin to export, import and manage database backups.
- :strawberry: [Feedback plugin](https://github.com/dereuromark/cakephp-feedback) - Allow visitors to send quick and easy feedback incl. a screenshot via sidebar form.
- :strawberry: [Flash plugin](https://github.com/dereuromark/cakephp-flash) - More powerful flash messages for your application.
- :strawberry: [OPCache Preloader](https://github.com/cnizzardini/cakephp-preloader) - An OPCache Preloader for CakePHP 4.x applications. 
- [OrcaServices/Heartbeat plugin](https://github.com/orca-services/cakephp-heartbeat/) - Monitor the hearbeat of your application (e.g. whether the database is available and up-to-date).
- [Inertia plugin](https://github.com/ishanvyas22/cakephp-inertiajs) - Server side adapter for Inertia.js.
- [Interval plugin](https://github.com/LubosRemplik/CakePHP-Interval) - Converts seconds to human readable string (string to seconds), uses business hours (1 week = 5 days, 1 day = 8 hours).
- [LinkScanner plugin](https://github.com/mirko-pagliai/cakephp-link-scanner) - A plugin for recursively scanning links.
- [Robotusers/Tactician plugin](https://github.com/robotusers/cakephp-tactician) - Tools for Tactician command bus integration.
- :strawberry: [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/master/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
- :strawberry: [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
- [TokenVerify plugin](https://github.com/mosaxiv/cakephp-token-verify) - Easily issue tokens that can be used for mail authentication.
- :strawberry: [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells and more.
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools) - User tools for login, registration, password reset and more. Works out of the box CRUD like and is highly configurable.
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - Containing useful components (Authorizer, Menu) and behaviors (WhoDidIt, Uploadable, Metas, Stateable).
- [Wrench plugin](https://github.com/HavokInspiration/wrench) - Maintenance Mode plugin. Easily extensible and customizable.
- [Yaml plugin](https://github.com/guemidiborhane/Cake-Yaml) - For using YAML config files instead of PHP arrays.

## Navigation
*Tools for building navigation structures.*

- :strawberry: [Icings/Menu plugin](https://github.com/icings/menu) - A [KnpMenu](https://github.com/KnpLabs/KnpMenu) seasoned menu plugin for CakePHP.

## NoSQL
*Plugins for working with "NoSQL" backends.*

- [Monga plugin](https://github.com/lewestopher/cakephp-monga) - Provides access to MongoDB datasource using [`thephpleague/monga`](https://github.com/thephpleague/monga).

## Notifications
*Plugins for working with notification software.*

- [ker0x/CakeGcm plugin](https://github.com/ker0x/CakeGCM) - A plugin to send downstream messages to an Android or iOS device through Google Cloud Messaging.
- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - A plugin that makes creating and reading notifications easy.
- [ker0x/Push plugin](https://github.com/ker0x/cakephp-push) - A plugin to send push notifications through services like Firebase Cloud Messaging.

## ORM / Database / Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- :strawberry: [ADmad/Sequence plugin](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records.
- :strawberry: [CakeDecimal plugin](https://github.com/dereuromark/cakephp-decimal) - A value object approach on handling decimals.
- :strawberry: [Duplicatable plugin](https://github.com/riesenia/cakephp-duplicatable) - Behavior for duplicating entities including related data.
- [Fetchable plugin](https://github.com/riesenia/cakephp-fetchable) - Behavior for fetching entities from cache / memory.
- :strawberry: [Lampager/Cake plugin](https://github.com/lampager/lampager-cakephp) - Rapid pagination without using OFFSET.
- [JeremyHarris/LazyLoad plugin](https://github.com/jeremyharris/cakephp-lazyload) - An association lazy loader for entities.
- [Lqdt/OrmJson plugin](https://github.com/liqueurdetoile/cakephp-orm-json) - Behavior and Trait for selecting, finding, getting and setting properties and values inside JSON type fields through CakePHP ORM.
- [Money plugin](https://github.com/gourmet/money) - Money data type for CakePHP entities using [sebastianbergmann/money](https://github.com/sebastianbergmann/money).
- :strawberry: [Muffin/Orderly plugin](https://github.com/usemuffin/orderly) - Allows setting default order for your tables.
- :strawberry: [Muffin/Sti plugin](https://github.com/UseMuffin/Sti) - Single Table Inheritance for CakePHP. 
- :strawberry: [Muffin/Trash plugin](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP.
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - Behavior for persisting selected fields of related models.
- [Robotusers/Excel plugin](https://github.com/robotusers/cakephp-excel) - ORM wrapper for PHPExcel.
- :strawberry: [Robotusers/TableInheritance plugin](https://github.com/robotusers/cakephp-table-inheritance) - Singe Table Inheritance (STI) plugin.
- :strawberry: [RowLocker plugin](https://github.com/lorenzo/row-locker) - Exclusive locks for rows in your tables.
- [Serializeable Data Types plugin](https://github.com/burzum/cakephp-serialize-data-types) - Serialize DB content as JSON or using phps serializing functions.
- :strawberry: [Muffin/Webservices ORM plugin](https://github.com/usemuffin/webservice) - An ORM like interface for webservices.
- :strawberry: [Connehito/CakephpMasterReplica plugin](https://github.com/Connehito/cakephp-master-replica) - Switch master/replica database connections.
- :strawberry: [Itosho/EasyQuery plugin](https://github.com/itosho/easy-query) - Behavior for easily generating some complicated queries like (bulk) insert/upsert etc.
- :strawberry: [Icings/Partitionable plugin](https://github.com/icings/partitionable) - Partitionable associations allowing for basic limiting per group.

## PDF
*Plugins and software for working with PDF files.*

- :strawberry: [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## Queue
*Plugins for working with event and task queues.*

- [CakeResque plugin](https://github.com/wa0x6e/Cake-Resque) - A plugin for Resque, a library for creating background jobs.
- :strawberry: [CakeQueuesadilla plugin](https://github.com/josegonzalez/cakephp-queuesadilla) - A plugin that provides queueing integration with a variety of backends (BeanstalkD, MySQL, Redis, etc.).
- [Gearman plugin](https://github.com/cvo-technologies/cakephp-gearman) - A plugin for offloading CakePHP tasks to a Gearman Job Server.
- :strawberry: [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal and dependency-free queue solution.

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- :strawberry: [Alt3/Swagger plugin](https://github.com/alt3/cakephp-swagger) - Swagger 2.0 documentation for your CakePHP APIs using swagger-php and swagger-ui.
- [Alt3/ValidationExposer plugin](https://github.com/alt3/cakephp-validation-exposer) - Easily expose your application's validation rules.
- [ApiPagination plugin](https://github.com/bcrowe/cakephp-api-pagination) - Injects pagination information from CakePHP's Paginator into serialized JsonView and XmlView responses.
- :strawberry: [CakeDC/Api plugin](https://github.com/CakeDC/cakephp-api) - All-in-one solution to provide a complete API. It includes versioning, renderers, CRUD, authentication, extensions (paginate, filter, HATEOAS), and much more.
- [Cors plugin](https://github.com/ozee31/cakephp-cors) - Activate CORS with Middleware.
- [Cors plugin](https://github.com/snelg/cakephp-cors) - A lightweight plugin for adding CORS headers to specified endpoints.
- [CrudJsonApi plugin](https://github.com/FriendsOfCake/crud-json-api) - Crud listener for building [JSON API](https://jsonapi.org/) compliant APIs.
- :strawberry: [FractalTransformerView plugin](https://github.com/andrej-griniuk/cakephp-fractal-transformer-view) - A plugin which allows using [Fractal transformers](https://fractal.thephpleague.com/transformers/) for your API output.
- :strawberry: [MixerApi](https://mixerapi.com) - Streamline development of modern RESTful APIs for your teams CakePHP project.
- :strawberry: [SwaggerBake plugin](https://github.com/cnizzardini/cakephp-swagger-bake) - This plugin automatically builds your Swagger UI documentation from your existing models and routes. A redoc option is also available.

## Search
*Plugins and software for indexing and performing search queries on data.*

- :strawberry: [Cake/ElasticSearch plugin](https://github.com/cakephp/elastic-search) - Alternative ORM using [Elasticsearch](https://www.elastic.co/) as its backend.
- :strawberry: [PlumSearch plugin](https://github.com/skie/plum_search) - Search plugin implements custom, flexible and extendable search strategies. Implements PRG pattern.
- :strawberry: [Search plugin](https://github.com/FriendsOfCake/search) - Provides easy searching/filtering for paginated views using PRG pattern.
- [SphinxSearch plugin](https://github.com/voycey/cakephp-sphinxsearch) - Basic behaviour implementation for querying SphinxSearch indexes.
- :strawberry: [Tags plugin](https://github.com/dereuromark/cakephp-tags) - For tagging and finding tagged records.

## Security
*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

- :strawberry: [Bruteforce](https://github.com/Ali1/cakephp-bruteforce/) - Simple way to add Brute Force Protection to your installation without involving database.
- [BryanCrowe/EncryptedType](https://github.com/bcrowe/cakephp-encrypted-type) - Simple solution that enables Encrypted data types to be stored in the database.
- :strawberry: [Captcha plugin](https://github.com/dereuromark/cakephp-captcha) - Simple, unobstrusive and extendable captcha solution providing by default an image based math captcha.
- [CipherBehavior plugin](https://github.com/adayth/cakephp-cipher-behavior) - Cipher your entities data with this behavior. Encryption is done at PHP level using CakePHP Security class.
- :strawberry: [Expose plugin](https://github.com/dereuromark/cakephp-expose) - Expose entities through additional UUIDs instead of their AIID primary keys to obfuscate those IDs and data associated with these numerically ordered values.
- :strawberry: [Muffin/Obfuscate plugin](https://github.com/usemuffin/obfuscate) - Primary key obfuscation/shortening using UUIDs, HashIds, Optimus, Tiny and/or custom obfuscation strategies.
- :strawberry: [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - A plugin for rate limiting (API) requests.
- :strawberry: [Recaptcha plugin](https://github.com/ctlabvn/Recaptcha) - Simple, lightweight Google Recaptcha v2.
- [Recaptcha Mailhide plugin](https://github.com/mirko-pagliai/cakephp-recaptcha-mailhide) - A plugin that allows you to hide email addresses using reCAPTCHA.
- [StopSpam plugin](https://github.com/mirko-pagliai/cakephp-stop-spam) - A plugin that allows you to check if a username, email address or IP address has been reported as a spammer.

## SEO
*Search Engine Optimization.*

- :strawberry: [Muffin/Slug plugin](https://github.com/UseMuffin/Slug) - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.
- [Seo plugin](https://github.com/orgasmicnightmare/cakephp-seo) - Auto-creates and manages your SEO tags.
- [Sluggable plugin](https://github.com/Xety/Cake3-Sluggable) - A simple Cake3 plugin to slug fields and find records by slug.
- :strawberry: [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.

## Skeleton
*Plugins and repositories around app skeletons.*

- :strawberry: [App template](https://github.com/cakephp/app) - An empty CakePHP project for use with composer.
- :strawberry: [Crud plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.
- :strawberry: [MixerApi/Bake](https://github.com/mixerapi/bake) - Bake theme for generating RESTful controllers.
- [Plugin Skeleton](https://github.com/Xety/Cake3-PluginSkeleton) - A skeleton example to create a Cake3 plugin.

## Social
*Plugins around social features.*

- [CakeDC/Forum plugin](https://github.com/CakeDC/cakephp-forum) - Forum plugin including categories, threads and replies, reporting messages, moderators, admin interface and more.
- :strawberry: [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - Allows users to rate records and displays ratings.
- [SocialShare plugin](https://github.com/drmonkeyninja/cakephp-social-share) - Link generator for sharing content on social networks.

## Templating
*Plugins for templating and lexing.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - An address helper that outputs a marked up address.
- :strawberry: [Bake plugin](https://github.com/cakephp/bake) - Provides code generation functionality.
- [Bootstrap plugin](https://github.com/elboletaire/twbs-cake-plugin) - A Bootstrap 3 plugin with support for LESS.
- :strawberry: [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 3 integration.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel) - An Excel view to generate XLSX files.
- [Chocolate plugin](https://github.com/commercial-hippie/chocolate) - Front-End framework FormHelper extensions.
- [CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](https://commonmark.org) (markdown) support to models and views.
- :strawberry: [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view class to easily generate CSV.
- [Datalist plugin](https://github.com/rrd108/cakephp-datalist) - Support for HTML5 datalist element with the possibility to create new entries into associated models.
- :strawberry: [Feed plugin](https://github.com/dereuromark/cakephp-feed) - Containing an RssView class to easily generate (complex) RSS feeds.
- [InlineCss plugin](https://github.com/drmonkeyninja/cakephp-inline-css) - A plugin to convert HTML style blocks to inline CSS on a View template (intended for use with email templates).
- [JadeView plugin](https://github.com/clthck/cakephp-jade) - Jade template engine plugin.
- [Liquid plugin](https://github.com/gourmet/liquid) - A plugin to use the Liquid templating language for views.
- :strawberry: [Meta plugin](https://github.com/dereuromark/cakephp-meta) - Makes handling meta tags and SEO relevant HTML markup DRY and easy.
- [SocialMeta plugin](https://github.com/gourmet/social-meta) - Adds support for Facebook's OpenGraph and Twitter's Card meta tags.
- :strawberry: [TwigView plugin](https://github.com/cakephp/twig-view) - A plugin to use the Twig Templating Language for views.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - Helper for embedding YouTube, Vimeo and Dailymotion videos.

## Testing
*Plugins/Tools for testing codebases and generating test data.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - The official CakePHP integration with [Codeception](https://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- :strawberry: [CakephpFixtureFactories plugin](https://github.com/pakacuda/cakephp-fixture-factories) - Create your fixtures dynamically on a test basis, accelerate the writing and maintainance of your tests.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) support for CakePHP fixtures.
- [Fixtures plugin](https://github.com/LubosRemplik/CakePHP-Fixtures) - Fixtures plugin to read existing fixtures and create table/insert data for quick start with app.
- [FriendsOfCake/Fixturize plugin](https://github.com/FriendsOfCake/fixturize) - More efficient inserting fixtures when running test suites by decreasing amount of inserts (mysql only).
- [Gourmet/Muffin plugin](https://github.com/gourmet/muffin) - [FactoryMuffin](https://github.com/thephpleague/factory-muffin) support for CakePHP fixture records.

## Third Party APIs
*Plugins for accessing third party APIs.*

- [CakeTmdb plugin](https://github.com/drmonkeyninja/cakephp-tmdb) - The Movie Database (TMDB) API integration.
- [CloudflareDeploy Plugin](https://github.com/challgren/cakephp-cloudflare-deploy) - Useful console commands for deploying CakePHP apps using Cloudflare.
- [GitHub plugin](https://github.com/cvo-technologies/cakephp-github) - Allows access to the GitHub REST APIs using the [Webservice](https://github.com/UseMuffin/Webservice) ORM.
- [Jira plugin](https://github.com/fr3nch13/cakephp-jira) - Provides a helper to allow access to Jira's REST API using [lesstif/php-jira-rest-client](https://github.com/lesstif/php-jira-rest-client) as the Vendor. Currently read-only access.
- [Ratchet plugin](https://github.com/WyriHaximus/Ratchet) - Brings the Ratchet websocket package to CakePHP.
- [Salesforce plugin](https://github.com/voycey/cakephp-salesforce) - Allows use of CakePHP's ORM to Query and Interact with Salesforce Enterprise Instances.
- [Twitter plugin](https://github.com/cvo-technologies/cakephp-twitter) - Allows access to the Twitter REST and streaming APIs using the [Webservice](https://github.com/UseMuffin/Webservice) ORM.

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) - The .gitignore file proposals.
- :strawberry: [CakePHP Docker](https://github.com/cnizzardini/cakephp-docker) - A cakephp/app template for docker and kubernetes setup.
- [CakePHP Vagrant Setup](https://github.com/cpierce/cakephp-vagrant-setup) - Tool for spinning up multiple CakePHP 3.x Vanilla Dev Environments.
- [Devilbox](https://devilbox.readthedocs.io/en/latest/) - A docker development environment for (CakePHP) apps to be auto-setup including a lot of tools.
- [Docker](https://github.com/stefanvangastel/docker-cakephp) - CakePHP in a docker container environment.
- :strawberry: [Galley](https://gitlab.com/amayer5125/galley) - A small Docker dev environment for CakePHP development which includes a simple command line utility.
- [Mixer](https://github.com/CakeDC/mixer) - A plugin to discover and manage CakePHP plugins.
- [NetBeans](https://github.com/junichi11/cakephp3-netbeans) -  This package provides support for CakePHP in NetBeans 8.1+.
- [Oven](https://github.com/CakeDC/oven) - Setup your favorite framework with 1 file and 1 click.
- [PhpStorm plugin](https://github.com/skie/PhpStorm) -  CakePHP auto-completion support for console commands in PhpStorm IDE.
- [Puppet](https://puppetlabs.com/) - A server automation framework and application.
- [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

IDE specific compatibility information and tips can be found [here](https://github.com/dereuromark/cakephp-ide-helper/wiki#ide-support-and-tips).

## Web Applications

## CMS and applications built on CakePHP

- [CakeBlog](https://github.com/gwhitcher/CakeBlog) - Open source blog software.
- [Croogo](https://croogo.org) - CMS software
- [QuickApps-CMS](https://github.com/quickapps/cms) - Open source content management system.

## Demo
*Web-based (demo) applications and tools.*

- [BlogMVC](https://github.com/Kareylo/BlogMVC-CakePHP3) - A simple Blog example with CakePHP based on [BlogMVC Project](https://github.com/Grafikart/BlogMVC).
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) A bookmarking application built with the CRUD plugin.
- [CakeFest](http://cakefest.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".
- [Croogo 3.x](http://demo.croogo.org/3.0) - Croogo 3.x demo
- [RealWorld](https://github.com/gothinkster/cakephp-realworld-example-app) - Example CakePHP codebase containing real world examples (CRUD, auth, advanced patterns and more) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.
- [Sandbox](https://sandbox.dereuromark.de) - A sandbox CakePHP application with lots of demos and plugin showcasings.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
- [Xeta](https://github.com/XetaIO/Xeta) - A resource to help people starting with CakePHP.
- [Vue.js Demo App](https://github.com/ishanvyas22/cakephpvue-spa) - A CakePHP + VueJS single page application skeleton.

# Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help
*Where to get help.*

- [CakePHP-FR.org](http://cakephp-fr.org) - The french community website.
- [Official CakePHP Forum](https://discourse.cakephp.org/) - This is for generic questions and alike.
- [IRC Channel](https://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - Live chat/discussion with other devs and core devs.
- [stackoverflow.com/questions/tagged/cakephp](https://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.
- [dereuromark.de](https://www.dereuromark.de) - An extensive CakePHP core dev blog.
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

- [Official Blog tutorial](https://book.cakephp.org/3.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-related reading and listening materials.*

- [CakePHP Cookbook(!)](https://book.cakephp.org/) - The official CakePHP documentation.

## CakePHP Internals Reading
*Reading materials related to the CakePHP internals and decisions.*

- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - Give 'em a hand.

# Conferences

## Official
*International conference.*

- [cakefest.org](https://cakefest.org/) - Annual CakePHP Conference.

## MeetUps
*Regional meet-ups.*

- [CakePHP-DE](https://www.meetup.com/CakePHP-DE) - MeetUps in Germany.

# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits
awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/graphs/contributors), too.

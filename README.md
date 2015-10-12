# Awesome CakePHP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome CakePHP plugins, resources and shiny things.

Also see [plugins.cakephp.org/packages/categories](http://plugins.cakephp.org/packages/categories) as a categorized list.
You may also want to check out the PHP list at [awesome-php](https://github.com/dereuromark/awesome-php) as well as the generic
[awesome-awesomeness](https://github.com/dereuromark/awesome-awesomeness) list.

This list is specifically for **CakePHP 3.x** (for CakePHP 2.x please see the `cake2` branch).
It is a recommendation for good plugins and solutions for this major CakePHP version.

**Note**: ~~Strike-through~~ means, that this CakePHP 2.x plugin/resource has not yet been upgraded to 3.x.

The main advantage of this list compared to plugins.cakephp.org is, that here it can also be
a subpart of a plugin - instead of only the whole plugin/repo itself. The grouping might also be more granular.
Focus is on the specific task.

- [Awesome CakePHP](#awesome-cakephp)
	- [Skeleton](#skeleton)
	- [Environment](#environment)
	- [Debugging](#debugging)
	- [Templating](#templating)
	- [Email](#email)
	- [Files](#files)
	- [Dependency Injection](#dependency-injection)
	- [Imagery](#imagery)
	- [Testing](#testing)
	- [Security](#security)
	- [Code Analysis](#code-analysis)
	- [Navigation](#navigation)
	- [Asset Management](#asset-management)
	- [Geolocation](#geolocation)
	- [Auditing / Logging](#auditing--logging)
	- [E-commerce](#e-commerce)
	- [PDF](#pdf)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [NoSQL](#nosql)
	- [Queue](#queue)
	- [Search](#search)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Markup](#markup)
	- [Filtering and Validation](#filtering-and-validation)
	- [REST and API](#rest-and-api)
	- [Caching](#caching)
	- [Notifications](#notifications)
	- [I18n](#i18n)
	- [Social](#social)
	- [SEO](#seo)
	- [Third Party APIs](#third-party-apis)
	- [Migration](#migration)
	- [Miscellaneous](#miscellaneous)
	- [Libs](#libs)
- [Software](#software)
	- [Development Environment](#development-environment)
- [Web Applications](#web-applications)
	- [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
	- [Demo](#demo)
- [Resources](#resources)
	- [Help](#help)
	- [CakePHP Websites](#cakephp-websites)
	- [CakePHP Books](#cakephp-books)
	- [CakePHP Videos](#cakephp-videos)
	- [CakePHP Tutorials](#cakephp-tutorials)
	- [CakePHP Reading and Listening](#cakephp-reading-and-listening)
	- [CakePHP Internals Reading](#cakephp-internals-reading)
- [Conferences](#conferences)
- [Contributing](#contributing)

## Skeleton
*Plugins and repositories around app skeletons*

- [App template](https://github.com/cakephp/app) - An empty CakePHP project for use with composer.
- [Crud plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.
- [Plugin Skeleton](https://github.com/Xety/Cake3-PluginSkeleton) - A skeleton example to create a Cake3 plugin.
- ~~[Bake template "setup"](https://github.com/dereuromark/cakephp-setup/tree/2.x/Console/Templates/setup) - An example template on how customization of bake templates is possible.~~

## Environment
*Plugins for enviroment*

- [Settings plugin](https://github.com/cakemanager/cakephp-settings) - A plugin to manage your settings via your database.
- ~~[Enviroments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle enviroments.~~
- ~~[Setup plugin](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic environments.~~

## Debugging
*Plugins for debugging*

- [Airbrake plugin](https://github.com/chrisShick/AirbrakeCake) A plugin to seamlessly integrate Airbrake with CakePHP for errors and exceptions.
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing debugging and maintenance tools.
- [Whoops plugin](https://github.com/gourmet/whoops) - PHP error for cool kids with [filp/whoops](https://github.com/filp/whoops).
- ~~[ClearCache plugin](https://github.com/ceeram/clear_cache) - For easily clearing the app cache(s).~~
- ~~[GraphVizModels plugin](https://github.com/mamchenkov/CakePHP-GraphViz-Models) - Display your model relations graphically.~~

## Templating
*Plugins for templating and lexing.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - An address helper that outputs a marked up address.
- [Bootstrap plugin](https://github.com/elboletaire/twbs-cake-plugin) - A Bootstrap 3 plugin with support for LESS.
- [BootstrapUI plugin](https://github.com/friendsofcake/bootstrap-ui) - Bootstrap 3 integration.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel/tree/3.0) - An Excel view to generate XLSX files.
- [Chocolate plugin](https://github.com/commercial-hippie/chocolate) - Front-End framework FormHelper extensions.
- [CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](http://commonmark.org) (markdown) support to models and views.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view class to easily generate CSV.
- [Feed plugin](https://github.com/dereuromark/cakephp-feed) - Containing an RssView class to easily generate (complex) RSS feeds.
- [Js plugin](https://github.com/oldskool/cakephp-js) - A library containing JS helper and alike (extracted from CakePHP2.x core).
- [Liquid plugin](https://github.com/gourmet/liquid) - A plugin to use the Liquid templating language for views.
- [Meta plugin](https://github.com/dereuromark/cakephp-meta) - Makes handling meta tags and SEO relevant HTML markup DRY and easy.
- [SocialMeta plugin](https://github.com/gourmet/social-meta) - Adds support for Facebook's OpenGraph and Twitter's Card meta tags.
- [TwigView plugin](https://github.com/WyriHaximus/TwigView) - A plugin to use the Twig Templating Language for views.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - Helper for embedding YouTube, Vimeo and Dailymotion videos.
- ~~[BoostCake plugin](https://github.com/slywalker/cakephp-plugin-boost_cake) - A Twitter Bootstrap plugin.~~
- ~~[CML plugin](https://github.com/jameswatts/cake-markup-language) - Provides further abstraction of the View layer by replacing the procedural PHP code with an XML based markup.~~
- ~~[CTK plugin](https://github.com/jameswatts/cake-toolkit) - Allows views to be defined as a class.~~
- ~~[CakeFactory plugin](https://github.com/jameswatts/cake-factory) - A factory for the Cake Toolkit (CTK), which provides configurable objects.~~
- ~~[Mustache plugin](https://github.com/Dismounted/MustacheCake) - A Mustache plugin.~~
- ~~[Wysiwyg plugin](https://github.com/josegonzalez/cakephp-wysiwyg) - Support for various wysiwyg editors.~~

## Email
*Plugins for sending and parsing email.*

- [Email plugin](https://github.com/gourmet/email) - Email helper, layout and more.
- ~~[Mandrill plugin](https://github.com/a2design-company/Mandrill-CakePHP-plugin) - Sending Email using Mandrill.~~
- ~~[SendGrid plugin](https://github.com/a2design-company/sendgrid-webapi-cakephp-plugin) - Plugin for SendGrid WebAPI.~~
- ~~[EmailQueue plugin](https://github.com/nodesagency/cakephp-email-queue) - An email queue solution.~~
- ~~[Mailchimp plugin](https://github.com/dereuromark/cakephp-mailchimp) - The Mailchimp and Mandrill plugin.~~
- ~~[Postmark plugin](https://github.com/maurymmarques/postmark-cakephp) - Makes email delivery using Postmark.~~

## Files
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.
- [FlyPie plugin](https://github.com/WyriHaximus/FlyPie) - Abstract filesystem access using Flysystem.
- [Image plugin](https://github.com/josbeir/image) - Image behavior that works much like Cake's built in TranslateBehavior.
- [Proffer plugin](https://github.com/davidyell/CakePHP3-Proffer) - A customisable upload plugin with thumbnail generation.
- [Upload plugin](https://github.com/Xety/Cake3-Upload) - A little plugin to upload file.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [PipingBag plugin](https://github.com/lorenzo/piping-bag) - Dependency injection container plugin that adds the ability to configure object instances and their dependencies before they are used, and to store them into a container class for easy access.
- ~~[CakeDependency plugin](https://github.com/jameswatts/cake-dependency) - Provides a dependency injection container and service registry/locator.~~

## Imagery
*Plugins for manipulating images.*

- [ADmad/Glide plugin](https://github.com/ADmad/cakephp-glide) - A plugin for using [Glide](http://glide.thephpleague.com/1.0/) image manipulation library.
- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - An image manipulation plugin and wrapper around [Imagine](https://github.com/avalanche123/Imagine).

## Testing
*Plugins/Tools for testing codebases and generating test data.*

- [CakePHP Codeception module](https://github.com/cakephp/codeception) - The official CakePHP integration with [Codeception](http://codeception.com).
- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- [CodeSniffer plugin](https://github.com/dereuromark/cakephp-codesniffer) - Auto-find code issues/smells and auto-fix CS errors.
- [CodeSniffer plugin sniffs](https://github.com/dereuromark/codesniffer-standards) - Sniff packages/rules compatible with phpcs-fixer branch and the CodeSniffer plugin.
- [Faker plugin](https://github.com/gourmet/faker) - [Faker](https://github.com/fzaninotto/Faker) support for CakePHP fixtures.
- [Muffin plugin](https://github.com/gourmet/muffin) - [FactoryMuffin](https://github.com/thephpleague/factory-muffin) support for CakePHP fixture records.

## Security
*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

- [CipherBehavior plugin](https://github.com/adayth/cakephp-cipher-behavior) - Cipher your entities data with this behavior. Encryption is done at PHP level using CakePHP Security class.
- [Muffin/Throttle plugin](https://github.com/usemuffin/throttle) - A plugin for rate limiting (API) requests.
- ~~[Saving model data and security](http://www.dereuromark.de/2010/09/21/saving-model-data-and-security/) - Information on what to be careful about in 2.x when using CRUD forms and saving data.~~

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic/tree/cake3) - Using New Relic for analysis and monitoring.
- ~~[NewRelic plugin](https://github.com/jeremyharris/cakephp-newrelic) - Makes analyzing your CakePHP app in New Relic easier.~~

## Navigation
*Tools for building navigation structures.*

- [KnpMenu plugin](https://github.com/gourmet/knp-menu) - A menu plugin based on the [Knp Menu Library](https://github.com/KnpLabs/KnpMenu).
- ~~[MenuBuilder plugin](https://github.com/torifat/cake-menu_builder) - A menu plugin.~~

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.
- [Less plugin](https://github.com/elboletaire/less-cake-plugin) - Less parser plugin for CakePHP.
- [MinifyHtml plugin](https://github.com/WyriHaximus/MinifyHtml) - Compress HTML output.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- [Geo plugin](https://github.com/dereuromark/cakephp-geo) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMapsV3 helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).
- ~~[Geocoder plugin](https://github.com/martinbean/cakephp-geocoding-plugin) - A lightweight geocoding plugin.~~

## Auditing / Logging
*Plugins for auditing and logging.*

- [Blame plugin](https://github.com/ceeram/blame) - Plugin to update created_by and modified_by fields with logged in user id.
- [Muffin/Footprint plugin](https://github.com/UseMuffin/Footprint) - Plugin to allow passing currently logged in user to model layer.
- [Version plugin](https://github.com/josegonzalez/cakephp-version) - A plugin that facilitates versioned database entities.
- ~~[AuditLog plugin](https://github.com/jippi/cakephp-audit-log) - Records changes made to an object during CRUD operations.~~
- ~~[DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Logging to the DB instead of filesystem.~~
- ~~[Monolog plugin](https://github.com/jadb/cakephp-monolog) - Use the comprehensive logger capabilities of Monolog.~~
- ~~[Tools:WhoDidIt](https://github.com/dereuromark/cakephp-tools) - Containing WhoDidIt behavior to record changes made to an object during CRUD operations.~~

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- ~~[Cart plugin](https://github.com/burzum/cakephp-cart-plugin) - A shopping cart plugin.~~
- ~~[Payments plugin](https://github.com/burzum/cakephp-payments-plugin) - Generic Payment Interface.~~
- ~~[Paypal plugin](https://github.com/robmcvey/cakephp-paypal) - To interact with Paypal's "classic" and new REST APIs.~~
- ~~[PaypalSource plugin](https://github.com/jlkaufman/cakephp-paypal-rest-client) - A Paypal REST client plugin.~~
- ~~[Stripe plugin](https://github.com/chronon/CakePHP-StripeComponent-Plugin) - A Stripe component.~~

## PDF
*Plugins and software for working with PDF files.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## ORM and Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- [Money plugin](https://github.com/gourmet/money) - Money data type for CakePHP entities using [sebastianbergmann/money](https://github.com/sebastianbergmann/money).
- [Muffin/Trash plugin](https://github.com/usemuffin/trash) - Soft-delete behavior for CakePHP.
- [PersistRelatedData plugin](https://github.com/riesenia/persist-related-data) - Behavior for persisting selected fields of related models.
- ~~[Datasources plugin](https://github.com/cakephp/datasources) - Lots of different datasources.~~

## NoSQL
*Plugins for working with "NoSQL" backends.*

- ~~[MongoQB plugin](https://github.com/ichikaway/cakephp-mongodb/) - MongoDB database driver.~~
- ~~[NoSql](https://github.com/kamisama/CakePHP-NoSQL-Datasource) - A low-lever interface to interact with nosql datasource.~~

## Queue
*Plugins for working with event and task queues.*

- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal dependency-free CakePHP only plugin around Queue.
- ~~[CakeDjjob plugin](https://github.com/josegonzalez/cakephp-cake-djjob) - Quick and easy job queues, based on [delayed_job](https://github.com/seatgeek/djjob).~~
- [CakeResque plugin](https://github.com/kamisama/Cake-Resque) - A plugin for Resque, a library for creating background jobs.

## Search
*Plugins and software for indexing and performing search queries on data.*

- [ElasticSearch plugin](https://github.com/cakephp/elastic-search) - Alternative ORM using Elastic Search as its backend.
- [Search plugin](https://github.com/CakeDC/search) - De-facto search form standard built on PRG pattern.
- [Search plugin](https://github.com/FriendsOfCake/search) - Search provides a search module for CakePHP applications.
- [PlumSearch plugin](https://github.com/skie/plum_search) - Search plugin implements custom, flexible and extendable search strategies. Implements PRG pattern.
- [Muffin/Tags plugin](https://github.com/usemuffin/tags) - For tagging and finding tagged records
- ~~[OpenSearch plugin](https://github.com/dereuromark/cakephp-opensearch) - For creating installable search plugins for IE, Firefox and Chrome.~~
- ~~[Tags plugin](https://github.com/CakeDC/tags) - Tagging records the easy way.~~

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [Authenticate plugin](https://github.com/FriendsOfCake/Authenticate) - Authentication classes for AuthComponent.
- [CakeDC Users plugin](https://github.com/CakeDC/users/tree/3.x) - For allowing users to register and login, manage their profile and account validation. Social Login, RBAC, remember me, SuperUser authorize, forgot password, admin management, etc.
- [CookieAuth plugin](https://github.com/Xety/Cake3-CookieAuth) - A simple Cake 3 plugin to automatically authenticate users with Cookies.
- [HierAuth plugin](https://github.com/btaens/cakephp-hier-auth) - A CakePHP plugin for hierarchical, role based, simple authorization.
- [HybridAuth plugin](https://github.com/ADmad/CakePHP-HybridAuth) - A plugin which allows using the [HybridAuth](https://github.com/hybridauth/hybridauth) social sign on library with CakePHP.
- [JwtAuth plugin](https://github.com/ADmad/cakephp-jwt-auth) - A plugin for authenticating using JSON Web Tokens.
- [Muffin/OAuth2 plugin](https://github.com/usemuffin/oauth2) - OAuth2 authentication using the [`league/oauth2-client`](https://github.com/thephpleague/oauth2-client).
- [MultiTenant plugin](https://github.com/pronique/multitenant) - Easily build SaaS enabled web applications.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](https://github.com/dereuromark/cakephp-tools/blob/cake3/docs/Behavior/Passwordable.md) for a DRY approach on password hashing.
- [TinyAuth plugin](https://github.com/dereuromark/cakephp-tinyauth) - Role based (single/multi) authentication as very light-weight approach.
- [UserPermissions plugin](https://github.com/AlessandroMinoccheri/UserPermissions) -  Allow groups of users or single users to view a specific page.
- ~~[Authorize plugin](https://github.com/FriendsOfCake/Authorize) - Authorize classes for AuthComponent.~~
- ~~[GoogleAuthenticate plugin](https://github.com/ceeram/GoogleAuthenticate) - Containing Google 2 step authenticate class for AuthComponent.~~
- ~~[Sanction plugin](https://github.com/josegonzalez/cakephp-sanction) - Centralize all of those permissions in a single file.~~

## Markup
*Plugins for working with markup.*

- [CommonMark plugin](https://github.com/gourmet/common-mark) - Adds [CommonMark](http://commonmark.org/) Markdown parsing.
- [Geshi plugin](https://github.com/markstory/cakephp_geshi) - For adding GeSHI syntax highlighting.
- ~~[Decoda plugin](https://github.com/milesj/decoda) - A lightweight bbcode parser plugin.~~
- ~~[Markdown plugin](https://github.com/chronon/CakePHP-Markdown-Plugin) - A Markdown parser plugin.~~
- ~~[MarkupParsers plugin](https://github.com/CakeDC/markup_parsers) - A collection of parsers.~~

## Filtering and Validation
*Plugins for filtering and validating data.*

- [Gourmet/Filters plugin](https://github.com/gourmet/filters) - Extra dispatcher filters (maintenance, robots, ip, etc).
- [Gourmet/Validation plugin](https://github.com/gourmet/validation) - Extra validation providers (Respect, IsoCodes, etc.) and rules.
- ~~[HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier) - A standards compliant HTML filter.~~
- ~~[Tidy plugin](https://github.com/cikorka/CakePHP-HTML-Tidy-Plugin) - Validate and generate tided HTML output.~~

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- [Cors plugin](https://github.com/snelg/cakephp-cors) - A lightweight plugin for adding CORS headers to specified endpoints.
- ~~[Rest plugin](https://github.com/kvz/cakephp-rest-plugin) - a painless REST server Plugin for CakePHP.~~

## Caching
*Plugins for caching data.*

- [Cache plugin](https://github.com/dereuromark/cakephp-cache) - For caching views (HTML, CSV, JSON, XML, ...) as static cache files.
- ~~[AutoCache plugin](https://github.com/ndejong/CakephpAutocachePlugin) - A plugin that makes query caching easy.~~
- ~~[Cacher plugin](https://github.com/jeremyharris/cacher) - A plugin that caches query results.~~
- ~~[UrlCache plugin](https://github.com/dereuromark/url_cache) - Automatically cache the results of calls to Router.~~

## Notifications
*Plugins for working with notification software.*

- [Notifier plugin](https://github.com/cakemanager/cakephp-notifier) - A plugin that makes creating and reading notifications easy.
- ~~[Notification plugin](https://github.com/aschelch/cakephp-notification-plugin) - A plugin that provides an notification system.~~

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization)*

- [I18n plugin](https://github.com/ADmad/cakephp-i18n) - A plugin with I18n related tools.
- [ShadowTranslate plugin](https://github.com/AD7six/cakephp-shadow-translate) - A plugin with shadow table based replacement for core's Translate behavior.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - Managing i18n PO files and translations via Transifex API.
- ~~[Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.~~

## Social
*Plugins around social features*

- [Ratings plugin](https://github.com/dereuromark/cakephp-ratings) - Allows users to rate records.
- [SocialShare plugin](https://github.com/drmonkeyninja/cakephp-social-share) - Link generator for sharing content on social networks.
- ~~[Bookmark plugin](https://github.com/josegonzalez/cakephp-bookmark) - Creates links to popular bookmarking web-applications.~~
- ~~[Comments plugin](https://github.com/CakeDC/comments) - Allows users to comment records.~~
- ~~[Facebook plugin](https://github.com/webtechnick/CakePHP-Facebook-Plugin) - Facebook plugin.~~
- ~~[Favorite plugin](https://github.com/CakeDC/favorites) - Allows users to favor records.~~
- ~~[Feedback plugin](https://github.com/lecterror/cakephp-feedback-plugin) - Providing feedback.~~
- ~~[Like plugin](https://github.com/aschelch/cakephp-like-plugin) - Provides a feature similar to Facebook "Like".~~
- ~~[Twitter plugin](https://github.com/mishudark/CakePHP-2.x-Twitter-Plugin) - A library to interface with Twitter and its OAuth workflow.~~

## SEO
*Search Engine Optimization*

- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.
- [Muffin/Slug plugin](https://github.com/UseMuffin/Slug) - A plugin for generating slugs and finding records by slug. Uses a pluggable architecture which allows using your own slug generator class.
- [Sluggable plugin](https://github.com/Xety/Cake3-Sluggable) - A simple Cake3 plugin to slug fields and find records by slug.
- ~~[Seo plugin](https://github.com/webtechnick/CakePHP-Seo-Plugin) - SEO plugin.~~
- ~~[Sitemap plugin](http://plugins.cakephp.org/p/1681-CakePHP-Sitemap) - Generates HTML and XML sitemaps for your CakePHP application.~~

## Third Party APIs
*Plugins for accessing third party APIs.*

- [Ratchet plugin](https://github.com/WyriHaximus/Ratchet) - Brings the Ratchet websocket package to CakePHP.
- ~~[AmazonSdk plugin](https://github.com/mcallisto/cakephp-amazon-aws-sdk) - A plugin around PHP AWS SDK library.~~
- ~~[SMSFly plugin](https://github.com/imsamurai/cakephp-sms-fly-datasource) - Data source for sending SMS via sms-fly.~~
- ~~[Twitter plugin](https://github.com/mishudark/CakePHP-2.x-Twitter-Plugin) - A library to interface with Twitter and its OAuth workflow.~~

## Migration
*Plugins and resources around migration and upgrading*

- [Migrations plugin](https://github.com/cakephp/migrations) - (DB) Migration plugin.
- [Upgrade app](https://github.com/cakephp/upgrade) - Official upgrade app for 2.x=>3.x.
- [Upgrade/Migration Guide](http://book.cakephp.org/3.0/en/appendices.html) - Official migration guide.
- [Execution order](https://github.com/dereuromark/executionorder) - A 3.x test app to display the execution order of files, methods and callbacks.
- ~~[Upgrade plugin](https://github.com/dereuromark/cakephp-upgrade) - The most extensive 1.x=>2.x and partly =>3.x upgrade shells.~~

## Miscellaneous
*Misc plugins and libraries*

- [Ajax plugin](https://github.com/dereuromark/cakephp-ajax) - A plugin to ease handling AJAX requests.
- [CakeManager plugin](https://github.com/cakemanager/cakephp-cakemanager) - A user management plugin with a built-in admin area.
- [CurrencyConverter plugin](https://github.com/AlessandroMinoccheri/cakephp-currency-converter) - A plugin to convert currency into another one.
- [Dashboard plugin](https://github.com/gourmet/dashboard) - Build beautiful dashboards for your cakes!
- [Sequence plugin](https://github.com/ADmad/cakephp-sequence) - Behavior for maintaining ordered list of records.
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup/blob/cake3/docs/Maintenance/Maintenance.md) - Maintenance shell to go into maintenance mode for all requests with optional IP whitelisting.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells, ...
- [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins.
- [UserTools plugin](https://github.com/burzum/cakephp-user-tools) - User tools for login, registration, password reset and more. Works out of the box CRUD like and is highly configurable.
- [Utils plugin](https://github.com/cakemanager/cakephp-utils) - Containing useful components (Authorizer, Menu) and behaviors (WhoDidIt, Uploadable, Metas, Stateable).
- [Yaml plugin](https://github.com/chobo1210/Cake-Yaml) - For using YAML config files instead of PHP arrays.
- ~~[Dotcake](https://github.com/dotcake/dotcake) - Provides CakePHP project info for editor's cakephp plugins.~~
- ~~[Ftp plugin](https://github.com/fotografde/cakephp-ftp) - FTP/SFTP plugin.~~
- ~~[Jsonrpc plugin](https://github.com/jameswatts/cake-jsonrpc) - Provides server and client implementations of JSON-RPC.~~
- ~~[MaintenanceMode plugin](https://github.com/awebdeveloper/cakephp-maintenance-mode) - Show a custom template for all requests when in maintainance with optional IP whitelisting.~~

## Libs
*Useful libraries or tools that don't fit in the categories above.*

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library - used in CakePHP3.x core.
- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano.
- [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension - used in CakePHP3.x core (deprecated soon).
- [Chronos](https://github.com/cakephp/chronos) - A simple standalone DateTime API extension (successor of Carbon).
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
- [Rocketeer](https://github.com/Anahkiasen/rocketeer) - PHP task runner and deployment package.
- [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- [Cakebox](https://github.com/alt3/cakebox) - A Vagrant development environment powered by the CakePHP 3.x Console.
- [PuPHPet](https://puphpet.com/) - Web interface for building a Vagrant + Puppet box.
- [Puppet](http://puppetlabs.com/) - A server automation framework and application.
- [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) - The .gitignore file proposals.

## Web Applications

## CMS and applications built on CakePHP

- [CakeBlog](https://github.com/gwhitcher/CakeBlog) - Open source blog software.
- [QuickApps-CMS](https://github.com/QuickAppsCMS/QuickApps-CMS) - Open source content management system.
- ~~[Croogo](https://github.com/croogo/croogo) - Open source content management system.~~

Based on CakePHP3.x.

## Demo
*Web-based (demo) applications and tools.*
- [Bookmarkr](https://github.com/lorenzo/cakephp3-bookmarkr) A bookmarking application built with the CRUD plugin.
- [CakeFest](http://cakefest3.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".
- [CakePHP Sandbox](http://sandbox3.dereuromark.de) - A sandbox CakePHP application.
- [Query Examples](https://github.com/lorenzo/cakephp3-examples) Advanced query building examples.
- [Xeta](https://github.com/Xety/Xeta) - A resource to help people starting with CakePHP.

Based on CakePHP3.x.

# Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help
*Where to get help.*

- [CakePHP.ir](http://cakephp.ir) - discussion with other devs and generic questions for Persian community.
- [Google Group](https://groups.google.com/forum/#!forum/cake-php) - This is for generic questions and alike.
- [IRC Channel](http://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - Live chat/discussion with other devs and core devs.
- [stackoverflow.com/questions/tagged/cakephp](http://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.
- [CakePHP-FR.org](http://cakephp-fr.org) - The french community website.
- [CakePHP-BR.org](http://cakephp-br.org) - The brazilian community website.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

- [AD7six.com](http://AD7six.com) - A CakePHP core dev blog.
- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.
- [dereuromark.de](http://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [florian-kraemer.net](http://florian-kraemer.net) - A CakePHP related core dev blog.
- [jadb.io](http://jadb.io) - A CakePHP related core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
- [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.
- [waltherlalk.com](http://waltherlalk.com) - A CakePHP related core dev blog.

Very few but increasing CakePHP3.x articles.

## CakePHP Books
*Fantastic CakePHP-related (e)books.*

- ~~[CakePHP 2 Application Cookbook](http://www.packtpub.com/web-development/cakephp-2-application-cookbook) - CakePHP 2.x book by two core developers.~~
- ~~[Instant Starter](http://www.amazon.com/Instant-CakePHP-Starter-Robert-Henderson-ebook/dp/B00CITNQP2/) - CakePHP2.x book (not for total PHP beginners).~~
- ~~[Rapid Application Development with CakePHP 2](http://josediazgonzalez.com/cakephp-book/) - CakePHP 2.x book by CakePHP Core Developer @josegonzalez.~~

Written for CakePHP3.x.

## CakePHP Videos
*Fantastic CakePHP-related videos.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.


## CakePHP Tutorials
*Must-do tutorials.*

- [Official Blog tutorial](http://book.cakephp.org/3.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-releated reading and listening materials.*

- [Cookbook(!)](http://book.cakephp.org/2.0/en/index.html) - The official documentation.
- [CakePHP Podcast](http://podcast.cakephp.org/) - The official CakePHP podcasts.
- [CakePHP Reporter](http://www.scoop.it/t/cakephp-reporter) - a newspaper and collection of material about CakePHP.

## CakePHP Internals Reading
*Reading materials related to the CakePHP internals and decisions.*

- [Core Google Group](http://groups.google.com/group/cakephp-core/topics) - Discussions around the CakePHP core.
- [Top 10 (and more) core contributors](https://github.com/cakephp/cakephp/graphs/contributors) - Give 'em a hand.

# Conferences

## Official
*International conference.*

- [cakefest.org](http://cakefest.org/) - Annual CakePHP Conference.

## MeetUps
*Regional meet-ups.*

- [CakePHP-DE](http://www.meetup.com/CakePHP-DE) - MeetUps in Germany.
- [CakePHP-NewYork](http://www.meetup.com/nyc-cakephp/) - MeetUps in the New York Metropolitan Area.
- [CakePHP-NL](http://www.meetup.com/CakePHP-NL) - MeetUps in Netherlands.
- [CakePHP-France](http://www.meetup.com/CakePHP-France) - MeetUps in France.


# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits
awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/contributors), too.

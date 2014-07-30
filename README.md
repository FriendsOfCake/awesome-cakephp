# Awesome CakePHP
A curated list of amazingly awesome CakePHP plugins, resources and shiny things.

Also see http://plugins.cakephp.org/packages/categories as a categorized list
and maybe check out the PHP list at https://github.com/ziadoz/awesome-php as well.

This list is specifically for **CakePHP2.x**. For CakePHP3.x please see the *cake3* branch.
It is a recommendation for good plugins and solutions for this major CakePHP version.

The main advantage of this list compared to plugins.cakephp.org is, that here it can also be
a subpart of a plugin - instead of only the whole plugin/repo itself. The grouping might also be more granular.
Focus is on the specific task.

- [Awesome CakePHP](#awesome-cakephp)
  - [Skeleton](#skeleton)
  - [Environment](#environment)
	- [Debugging](#debugging)
	- [Templating](#templating)
	- [Dependency Injection](#dependency-injection)
	- [Imagery](#imagery)
	- [Testing](#testing)
	- [Security](#security)
	- [Code Analysis](#code-analysis)
	- [Navigation](#navigation)
	- [Asset Management](#asset-management)
	- [Geolocation](#geolocation)
	- [Logging](#logging)
	- [E-commerce](#e-commerce)
	- [PDF](#pdf)
	- [ORM and Datamapping](#orm-and-datamapping)
	- [NoSQL](#nosql)
	- [Queue](#queue)
	- [Search](#search)
	- [Authentication](#authentication)
	- [Markup](#markup)
	- [Filtering and Validation](#filtering-and-validation)
	- [REST and API](#rest-and-api)
	- [Caching](#caching)
	- [Notifications](#notifications)
	- [I18n](#i18n)
	- [Third Party APIs](#third-party-apis)
	- [SEO](#seo)
	- [Migration](#migration)
	- [Miscellaneous](#miscellaneous)
	- [Libs](#libs)
- [Software](#software)
	- [Development Environment](#development-environment)
	- [Web Applications](#web-applications)
- [Resources](#resources)
	- [CakePHP Websites](#php-websites)
	- [CakePHP Books](#php-books)
	- [CakePHP Videos](#php-videos)
	- [CakePHP Reading](#php-reading)
	- [CakePHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

## Skeleton
* Plugins and repositories around app skeletons*

* [App template](https://github.com/FriendsOfCake/app-template) - An empty CakePHP project for use with composer.
* [setup bake template](https://github.com/dereuromark/cakephp-setup/tree/master/Console/Templates/setup) - An example template on how customization of bake templates is possible.
* [CRUD](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.

## Environment
*Plugins for enviroment*

* [Enviroments](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle enviroments.
* [Setup](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic enviroments.

## Debugging
*Plugins for debugging*

* [DebugKit](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
* [Setup](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing setup tabs at the bottom.
* [GraphVizModels](https://github.com/mamchenkov/CakePHP-GraphViz-Models) - Display your model relations graphically.
* [ClearCache](https://github.com/ceeram/clear_cache) - For easily clearing the app cache(s).

## Templating
*Plugins for templating and lexing.*

* [BoostCake](https://github.com/slywalker/cakephp-plugin-boost_cake) - A Twitter Bootstrap plugin.
* [TwigView](https://github.com/predominant/TwigView) - A plugin to use the Twig Templating Language for views.
* [CsvView](https://github.com/josegonzalez/cakephp-csvview) - A view to easily generate CSV.
* [Tools:RssView](https://github.com/dereuromark/cakephp-tools) - Containing [RssView](http://www.dereuromark.de/2013/10/03/rss-feeds-in-cakephp/) to easily generate (complex) RSS.
* [CakeMarkupLanguage](https://github.com/jameswatts/cake-markup-language) -  Provides further abstraction of the View layer by replacing the procedural PHP code with an XML based markup.
* [CakeFactory](https://github.com/jameswatts/cake-factory) - A factory for the Cake Toolkit (CTK), which provides configurable objects.
* [Mustache](https://github.com/Dismounted/MustacheCake) - A Mustache plugin.

## Email
*Plugins for sending and parsing email.*

* [EmailQueue](https://github.com/nodesagency/cakephp-email-queue) - An email queue solution.
* [Postmark](https://github.com/maurymmarques/postmark-cakephp) - Makes email delivery using Postmark.
* [Mailchimp](https://github.com/dereuromark/cakephp-mailchimp) - The Mailchimp and Mandrill plugin.

## Files
*Plugins for file manipulation.*

* [FileStorage](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

* [CakeDependency](https://github.com/jameswatts/cake-dependency) - Provides a dependency injection container and service registry/locator.

## Imagery
*Plugins for manipulating images.*

* [Imagine](https://github.com/burzum/cakephp-imagine-plugin) - A plugin around Imagine.

## Testing
*Plugins for testing codebases and generating test data.*

* [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
* [CodeSniffer](https://github.com/dereuromark/cakephp-codesniffer) - A plugin to auto-find and auto-fix almost all CS errors.
* [PHPUnit](https://github.com/dereuromark/cakephp-phpunit) - An easy way to install PHPUnit if you are not using composer.

## Security
*Plugins for generating secure random numbers, encrypting data and scanning for vulnerabilities.*


## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

* [NewRelic](https://github.com/jippi/cakephp-newrelic) - Using New Relic for analysis and monitoring.

## Navigation
*Tools for building navigation structures.*

* [MenuBuilder](https://github.com/MenschDankeGmbH/cake-menu_builder) - A menu plugin.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

* [AssetCompress](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

* [Tools](https://github.com/dereuromark/cakephp-tools) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMapsV3 helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).
* [Geocoder](https://github.com/martinbean/cakephp-geocoding-plugin) - A lightweight geocoding plugin.

## Logging
*Plugins for generating and working with log files.*

* [DatabaseLog](https://github.com/webtechnick/CakePHP-DatabaseLogger-Plugin)
* [Monolog](https://github.com/Seldaek/monolog) - A comprehensive logger.

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

* [Cart](https://github.com/burzum/cakephp-cart-plugin) - A shopping cart plugin.
* [Payments](https://github.com/burzum/cakephp-payments-plugin) - Generic Payment Interface.
* [Stripe](https://github.com/chronon/CakePHP-StripeComponent-Plugin) - A Stripe component.
* [Paypal](https://github.com/robmcvey/cakephp-paypal) - To interact with Paypal's "classic" and new REST APIs.

## PDF
*Plugins and software for working with PDF files.*

* [CakePdf](https://github.com/ceeram/CakePdf) - A plugin around PDF generation.

## ORM and Datamapping
*Plugins that implement object-relational mapping or datamapping techniques.*

* [Datasources](https://github.com/cakephp/datasources) - Lots of different datasources.

## NoSQL
*Plugins for working with "NoSQL" backends.*

* [MongoQB](https://github.com/ichikaway/cakephp-mongodb/) - MongoDB database driver.
* [NoSql](https://github.com/kamisama/CakePHP-NoSQL-Datasource) - A low-lever interface to interact with nosql datasource.

## Queue
*Plugins for working with event and task queues.*

* [Queue](https://github.com/dereuromark/cakephp-queue) - A minimal dependency-free CakePHP only plugin around Queue.
* [CakeResque](https://github.com/kamisama/Cake-Resque) - A plugin for Resque, a library for creating background jobs

## Search
*Plugins and software for indexing and performing search queries on data.*

* [Tags](https://github.com/CakeDC/tags) - Tagging records the easy way.
* [Search](https://github.com/CakeDC/search) - De-facto search form standard built on RPG pattern.
* [Elastic](https://github.com/dkullmann/CakePHP-Elastic-Search-DataSource) - Connecting models to Elastic Search types.
* [OpenSearch](https://github.com/dereuromark/cakephp-opensearch) - For creating installable search plugins for IE, Firefox and Chrome.

## Authentication
*Plugins for implementing authentication and authorization.*

* [Authenticate](https://github.com/FriendsOfCake/Authenticate) - Authentication classes for AuthComponent.
* [Authorize](https://github.com/FriendsOfCake/Authorize) - Authorize classes for AuthComponent.
* [Tools:TinyAuth](https://github.com/dereuromark/tools) - Containing TinyAuth for a very lightweight (single/multi) role based access.
* [GoogleAuthenticate](https://github.com/ceeram/GoogleAuthenticate) - Containing Google 2 step authenticate class for AuthComponent.
* [Tools:Passwordable](https://github.com/dereuromark/tools) - Containing [Passwordable behavior](http://www.dereuromark.de/2011/08/25/working-with-passwords-in-cakephp/) for a DRY approach von modern password hashing.
* [Sanction](https://github.com/josegonzalez/cakephp-sanction) - Centralize all of those permissions in a single file.

## Markup
*Plugins for working with markup.*

* [MarkupParsers](https://github.com/CakeDC/markup_parsers) - A collection of parsers.
* [Decoda](https://github.com/milesj/decoda) - A lightweight bbcode parser plugin.
* [Markdown](https://github.com/chronon/CakePHP-Markdown-Plugin) - A Markdown parser plugin.
* [Geshi](https://github.com/dereuromark/cakephp_geshi) - For adding GeSHI syntax highlighting.

## Filtering and Validation
*Plugins for filtering and validating data.*

* [HtmlPurifier](https://github.com/burzum/cakephp-html-purifier) - A standards compliant HTML filter.

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

* [Rest](https://github.com/kvz/cakephp-rest-plugin) - a painless REST server Plugin for CakePHP.

## Caching
*Plugins for caching data.*

* [AutoCache](https://github.com/ndejong/CakephpAutocachePlugin) - A plugin that makes query caching easy.
* [UrlCache](https://github.com/dereuromark/url_cache) - Automatically cache the results of calls to Router.

## Notifications
*Plugins for working with notification software.*

* [Notification](https://github.com/aschelch/cakephp-notification-plugin) - A plugin that provides an notification system.

## I18n
* Plugins for I18n (Internationalization) and L10n (Localization)*

* [Localized](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.
* [Transifex](https://github.com/dereuromark/cakephp-transifex) - Imports locales via Transifex API.

## Social
* Plugins around social features*

* [Bookmark](https://github.com/josegonzalez/cakephp-bookmark) - Creates links to popular bookmarking web-applications.
* [Favorite](https://github.com/CakeDC/favorites) - Allows users to favor records.
* [Ratings](https://github.com/CakeDC/ratings) - Allows users to rate records.
* [Feedback](https://github.com/lecterror/cakephp-feedback-plugin) - Providing feedback.
* [Like](https://github.com/aschelch/cakephp-like-plugin) - Provides a feature similar to Facebook "Like".
* [Comments](https://github.com/CakeDC/comments) - Allows users to comment records.

## SEO
*Search Engine Optimization*

* [Sitemap](http://plugins.cakephp.org/p/1681-CakePHP-Sitemap) - Generates HTML and XML sitemaps for your CakePHP application.
* [Seo](https://github.com/webtechnick/CakePHP-Seo-Plugin) - SEO plugin.
* [Facebook](https://github.com/webtechnick/CakePHP-Facebook-Plugin) - Facebook plugin.

## Third Party APIs
*Plugins for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/mcallisto/cakephp-amazon-aws-sdk) - A plugin around PHP AWS SDK library.
* [Twitter](https://github.com/mishudark/CakePHP-2.x-Twitter-Plugin) - A library to interface with Twitter and its OAuth workflow.

## Migration
* Plugins and ressouces around migrationa and upgrading

* [Migrations](https://github.com/dereuromark/cakephp-migrations) - (DB) Migration plugin.
* [Upgrade](https://github.com/dereuromark/cakephp-upgrade) - The most extensive 1.x=>2.x and partly =>3.x upgrade shells.

## Miscellaneous
*Misc plugins and libraries*

* [Jsonrpc](https://github.com/jameswatts/cake-jsonrpc) - Provides server and client implementations of JSON-RPC.
* [Dotcake](https://github.com/dotcake/dotcake) - Provides CakePHP project info for editor's cakephp plugins.
* [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins.
* [AJAX](https://github.com/dereuromark/cakephp-tools/wiki/www.dereuromark.de/2014/01/09/ajax-and-cakephp/) - AJAX and CakePHP.
* [Users](https://github.com/CakeDC/users) - For allowing users to register and login manage their profile.

## Libs
*Useful libraries or tools that don't fit in the categories above.*

* [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager.
* [Composer Installers](https://github.com/composer/installers) - A  multi framework Composer library installer.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.
* [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
* [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
* [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension - used in CakePHP3.x anyway.
* [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library -  - used in CakePHP3.x anyway.

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

* [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
* [Puppet](http://puppetlabs.com/) - A server automation framework and application.

## Web Applications
*Web-based applications and tools.*

* ?

# Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

* [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.
* [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
* [dereuromark.de](http://www.dereuromark.de) - An extensive CakePHP core dev blog.
* [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.

## CakePHP Books
*Fantastic CakePHP-related books.*

* ?

## CakePHP Videos
*Fantastic CakePHP-related videos.*

* [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.

## CakePHP Reading
*Documentation and CakePHP-releated reading materials.*

* [Cookbook(!)](http://book.cakephp.org/2.0/en/index.html) - The official documentation.

## CakePHP Internals Reading
*Reading materials related to the CakePHP internals and decisions.*

* [Core Google Group](http://groups.google.com/group/cakephp-core/topics)

# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.
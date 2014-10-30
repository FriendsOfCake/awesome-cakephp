# Awesome CakePHP
A curated list of amazingly awesome CakePHP plugins, resources and shiny things.

Also see [plugins.cakephp.org/packages/categories](http://plugins.cakephp.org/packages/categories) as a categorized list.
You may also want to check out the PHP list at [awesome-php](https://github.com/dereuromark/awesome-php) as well as the generic
[awesome-awesomeness](https://github.com/dereuromark/awesome-awesomeness) list.

This list is specifically for **CakePHP2.x** (for *CakePHP3.x* please see the *cake3* branch).
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
	- [Authentication and Authorization](#authentication-and-authorization)
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

- [App template](https://github.com/FriendsOfCake/app-template) - An empty CakePHP project for use with composer.
- [Bake template "setup"](https://github.com/dereuromark/cakephp-setup/tree/master/Console/Templates/setup) - An example template on how customization of bake templates is possible.
- [Crud plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.

## Environment
*Plugins for enviroment*

- [Enviroments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle enviroments.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic enviroments.

## Debugging
*Plugins for debugging*

- [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [Airbrake plugin](https://github.com/morrislaptop/AirbrakeCake) - Integrate Airbrake for CakePHP exceptions and errors
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing setup tabs at the bottom.
- [GraphVizModels plugin](https://github.com/mamchenkov/CakePHP-GraphViz-Models) - Display your model relations graphically.
- [ClearCache plugin](https://github.com/ceeram/clear_cache) - For easily clearing the app cache(s).

## Templating
*Plugins for templating and lexing.*

- [BoostCake plugin](https://github.com/slywalker/cakephp-plugin-boost_cake) - A Twitter Bootstrap plugin.
- [TwigView plugin](https://github.com/predominant/TwigView) - A plugin to use the Twig Templating Language for views.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view to easily generate CSV.
- [Tools:RssView](https://github.com/dereuromark/cakephp-tools) - Containing [RssView](http://www.dereuromark.de/2013/10/03/rss-feeds-in-cakephp/) to easily generate (complex) RSS.
- [Mustache plugin](https://github.com/Dismounted/MustacheCake) - A Mustache plugin.
- [CTK plugin](https://github.com/jameswatts/cake-toolkit) - Allows views to be defined as a class.
- [CakeFactory plugin](https://github.com/jameswatts/cake-factory) - A factory for the Cake Toolkit (CTK), which provides configurable objects.
- [CML plugin](https://github.com/jameswatts/cake-markup-language) - Provides further abstraction of the View layer by replacing the procedural PHP code with an XML based markup.
- [Wysiwyg plugin](https://github.com/josegonzalez/cakephp-wysiwyg) - Support for various wysiwyg editors.
- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - An address helper that outputs a marked up address.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - Helper for embedding YouTube, Vimeo and Dailymotion videos.

## Email
*Plugins for sending and parsing email.*

- [EmailQueue plugin](https://github.com/nodesagency/cakephp-email-queue) - An email queue solution.
- [Postmark plugin](https://github.com/maurymmarques/postmark-cakephp) - Makes email delivery using Postmark.
- [Mailchimp plugin](https://github.com/dereuromark/cakephp-mailchimp) - The Mailchimp and Mandrill plugin.
- [Mandrill plugin](https://github.com/a2design-company/Mandrill-CakePHP-plugin) - Sending Email using Mandrill.
- [SendGrid plugin](https://github.com/a2design-company/sendgrid-webapi-cakephp-plugin) - CakePHP plugin for SendGrid WebAPI.

## Files
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [CakeDependency plugin](https://github.com/jameswatts/cake-dependency) - Provides a dependency injection container and service registry/locator.

## Imagery
*Plugins for manipulating images.*

- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - A plugin around Imagine.

## Testing
*Plugins for testing codebases and generating test data.*

- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- [CodeSniffer plugin](https://github.com/dereuromark/cakephp-codesniffer) - A plugin to auto-find and auto-fix almost all CS errors.
- [PHPUnit plugin](https://github.com/dereuromark/cakephp-phpunit) - An easy way to install PHPUnit if you are not using composer.

## Security
*Plugins for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

- ?

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic) - Using New Relic for analysis and monitoring.
- [NewRelic plugin](https://github.com/jeremyharris/cakephp-newrelic) - Makes analyzing your CakePHP app in New Relic easier.

## Navigation
*Tools for building navigation structures.*

- [MenuBuilder plugin](https://github.com/MenschDankeGmbH/cake-menu_builder) - A menu plugin.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMapsV3 helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).
- [Geocoder plugin](https://github.com/martinbean/cakephp-geocoding-plugin) - A lightweight geocoding plugin.

## Logging
*Plugins for generating and working with log files.*

- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Log into a database.
- [Monolog plugin](https://github.com/jadb/cakephp-monolog) - Use the comprehensive logger capabilities of Monolog.
- [AuditLog plugin](https://github.com/jippi/cakephp-audit-log) - Records changes made to an object during CRUD operations.
- [Tools:WhoDidIt](https://github.com/dereuromark/cakephp-tools) - Containing WhoDidIt behavior to record changes made to an object during CRUD operations.

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- [Cart plugin](https://github.com/burzum/cakephp-cart-plugin) - A shopping cart plugin.
- [Payments plugin](https://github.com/burzum/cakephp-payments-plugin) - Generic Payment Interface.
- [Stripe](https://github.com/chronon/CakePHP-StripeComponent-Plugin) - A Stripe component.
- [Paypal plugin](https://github.com/robmcvey/cakephp-paypal) - To interact with Paypal's "classic" and new REST APIs.

## PDF
*Plugins and software for working with PDF files.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## ORM and Datamapping
*Plugins that implement object-relational mapping or datamapping techniques.*

- [Datasources plugin](https://github.com/cakephp/datasources) - Lots of different datasources.

## NoSQL
*Plugins for working with "NoSQL" backends.*

- [MongoQB plugin](https://github.com/ichikaway/cakephp-mongodb/) - MongoDB database driver.
- [NoSql](https://github.com/kamisama/CakePHP-NoSQL-Datasource) - A low-lever interface to interact with nosql datasource.

## Queue
*Plugins for working with event and task queues.*

- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal dependency-free CakePHP only plugin around Queue.
- [CakeResque plugin](https://github.com/kamisama/Cake-Resque) - A plugin for Resque, a library for creating background jobs

## Search
*Plugins and software for indexing and performing search queries on data.*

- [SimpleScope](https://github.com/josegonzalez/cakephp-simple-scope) - For scoping finds.
- [Tools:NamedScope](https://github.com/dereuromark/cakephp-tools) - Containing [NamedScope behavior](http://www.dereuromark.de/2014/02/15/cakephp-and-namedscope-for-dry-conditions/) for DRY find conditions.
- [Tags plugin](https://github.com/CakeDC/tags) - Tagging records the easy way.
- [Search plugin](https://github.com/CakeDC/search) - De-facto search form standard built on RPG pattern.
- [Elastic](https://github.com/dkullmann/CakePHP-Elastic-Search-DataSource) - Connecting models to Elastic Search types.
- [OpenSearch plugin](https://github.com/dereuromark/cakephp-opensearch) - For creating installable search plugins for IE, Firefox and Chrome.

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [Authenticate plugin](https://github.com/FriendsOfCake/Authenticate) - Authentication classes for AuthComponent.
- [Authorize plugin](https://github.com/FriendsOfCake/Authorize) - Authorize classes for AuthComponent.
- [Tools:TinyAuth](https://github.com/dereuromark/cakephp-tools) - Containing TinyAuth for a very lightweight (single/multi) role based access.
- [GoogleAuthenticate plugin](https://github.com/ceeram/GoogleAuthenticate) - Containing Google 2 step authenticate class for AuthComponent.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](http://www.dereuromark.de/2011/08/25/working-with-passwords-in-cakephp/) for a DRY approach von modern password hashing.
- [Sanction plugin](https://github.com/josegonzalez/cakephp-sanction) - Centralize all of those permissions in a single file.
- [OpAuth](https://github.com/uzyn/cakephp-opauth) - Opauth provides a standardized method for PHP applications to interface with authentication providers.

## Markup
*Plugins for working with markup.*

- [MarkupParsers plugin](https://github.com/CakeDC/markup_parsers) - A collection of parsers.
- [Decoda plugin](https://github.com/milesj/decoda) - A lightweight bbcode parser plugin.
- [Markdown plugin](https://github.com/chronon/CakePHP-Markdown-Plugin) - A Markdown parser plugin.
- [Geshi plugin](https://github.com/markstory/cakephp_geshi) - For adding GeSHI syntax highlighting.

## Filtering and Validation
*Plugins for filtering and validating data.*

- [HtmlPurifier plugin](https://github.com/burzum/cakephp-html-purifier) - A standards compliant HTML filter.
- [Tidy plugin](https://github.com/cikorka/CakePHP-HTML-Tidy-Plugin) - Validate and generate tided HTML output.

## REST and API
*Plugins and web tools for developing REST-ful APIs.*

- [Rest plugin](https://github.com/kvz/cakephp-rest-plugin) - a painless REST server Plugin for CakePHP.

## Caching
*Plugins for caching data.*

- [AutoCache plugin](https://github.com/ndejong/CakephpAutocachePlugin) - A plugin that makes query caching easy.
- [Cacher plugin](https://github.com/jeremyharris/cacher) - A plugin that caches query results.
- [UrlCache plugin](https://github.com/dereuromark/url_cache) - Automatically cache the results of calls to Router.

## Notifications
*Plugins for working with notification software.*

- [Notification plugin](https://github.com/aschelch/cakephp-notification-plugin) - A plugin that provides an notification system.

## I18n
*Plugins for I18n (Internationalization) and L10n (Localization)*

- [Localized plugin](https://github.com/cakephp/localized) - Localized validation and ready-to-use translation PO files.
- [Transifex plugin](https://github.com/dereuromark/cakephp-transifex) - Imports locales via Transifex API.

## Social
*Plugins around social features*

- [Bookmark plugin](https://github.com/josegonzalez/cakephp-bookmark) - Creates links to popular bookmarking web-applications.
- [Favorite plugin](https://github.com/CakeDC/favorites) - Allows users to favor records.
- [Ratings plugin](https://github.com/CakeDC/ratings) - Allows users to rate records.
- [Feedback plugin](https://github.com/lecterror/cakephp-feedback-plugin) - Providing feedback.
- [Like plugin](https://github.com/aschelch/cakephp-like-plugin) - Provides a feature similar to Facebook "Like".
- [Comments plugin](https://github.com/CakeDC/comments) - Allows users to comment records.
- [Facebook plugin](https://github.com/webtechnick/CakePHP-Facebook-Plugin) - Facebook plugin.
- [Twitter plugin](https://github.com/mishudark/CakePHP-2.x-Twitter-Plugin) - A library to interface with Twitter and its OAuth workflow.

## SEO
*Search Engine Optimization*

- [Sitemap plugin](http://plugins.cakephp.org/p/1681-CakePHP-Sitemap) - Generates HTML and XML sitemaps for your CakePHP application.
- [Seo plugin](https://github.com/webtechnick/CakePHP-Seo-Plugin) - SEO plugin.
- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.
- [Slugger plugin](https://github.com/jeremyharris/slugger) - Automatically slugs URLs.

## Third Party APIs
*Plugins for accessing third party APIs.*

- [AmazonSdk plugin](https://github.com/mcallisto/cakephp-amazon-aws-sdk) - A plugin around PHP AWS SDK library.
- [SMSFly plugin](https://github.com/imsamurai/cakephp-sms-fly-datasource) - Data source for sending SMS via sms-fly.

## Migration
*Plugins and resources around migrationa and upgrading*

- [Migrations plugin](https://github.com/CakeDC/migrations) - (DB) Migration plugin.
- [Upgrade/Migration Guide](http://book.cakephp.org/2.0/en/appendices.html) - Official migration guide.
- [Upgrade plugin](https://github.com/dereuromark/cakephp-upgrade) - The most extensive 1.x=>2.x and partly =>3.x upgrade shells.

## Miscellaneous
*Misc plugins and libraries*

- [Jsonrpc plugin](https://github.com/jameswatts/cake-jsonrpc) - Provides server and client implementations of JSON-RPC.
- [Dotcake](https://github.com/dotcake/dotcake) - Provides CakePHP project info for editor's cakephp plugins.
- [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins.
- [AJAX](https://github.com/dereuromark/cakephp-tools/wiki/www.dereuromark.de/2014/01/09/ajax-and-cakephp/) - AJAX and CakePHP.
- [Users plugin](https://github.com/CakeDC/users) - For allowing users to register and login manage their profile.
- [MobileDetect plugin](https://github.com/chronon/CakePHP-MobileDetectComponent-Plugin) - Identifying mobile devices using the Mobile_Detect project.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells, ...

## Libs
*Useful libraries or tools that don't fit in the categories above.*

- [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager.
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.
- [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension - used in CakePHP3.x anyway.
- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library - - used in CakePHP3.x anyway.
- [Rocketeer](https://github.com/Anahkiasen/rocketeer) - Deployment
- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
- [Puppet](http://puppetlabs.com/) - A server automation framework and application.
- [PuPHPet](https://puphpet.com/) - Web interface for building a Vagrant + Puppet box.

## Web Applications

## CMS and applications built on CakePHP

- [Croogo](https://github.com/croogo/croogo) - Open source content management system.
- [QuickApps-CMS](https://github.com/QuickAppsCMS/QuickApps-CMS) - Open source content management system.
- [Infinitas CMS](https://github.com/infinitas) - Open source content management framework.

Based on CakePHP2.x.

## Demo
*Web-based (demo) applications and tools.*

- [CakePHP Sandbox](http://sandbox.dereuromark.de) - A sandbox CakePHP application.
- [CakeFest](http://cakefest.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".

Based on CakePHP2.x.

# Resources
Various resources, such as books, websites and articles, for improving your CakePHP development skills and knowledge.

## Help
*Where to get help.*

- [Google Group](https://groups.google.com/forum/#!forum/cake-php) - This is for generic questions and alike.
- [stackoverflow.com/questions/tagged/cakephp](http://stackoverflow.com/questions/tagged/cakephp) - This is for specific questions, ideally along with some example code.
- [IRC Channel](http://www.dereuromark.de/2013/01/27/irc-cakephp-channel/) - Live chat/discussion with other devs and core devs.
- [CakePHP.ir](http://cakephp.ir) - discussion with other devs and generic questions for Persian community.

## CakePHP Websites
*Useful and current CakePHP-related websites and blogs.*

- [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
- [dereuromark.de](http://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [florian-kraemer.net](http://florian-kraemer.net) - A CakePHP related core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.
- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.

## CakePHP Books
*Fantastic CakePHP-related (e)books.*

- [CakePHP 2 Application Cookbook](http://www.packtpub.com/web-development/cakephp-2-application-cookbook) - CakePHP 2.x book by two core developers.
- [Rapid Application Development with CakePHP 2](http://josediazgonzalez.com/cakephp-book/) - CakePHP 2.x book by CakePHP Core Developer @josegonzalez.
- [Instant Starter](http://www.amazon.com/Instant-CakePHP-Starter-Robert-Henderson-ebook/dp/B00CITNQP2/) - CakePHP2.x book (not for total PHP beginners).

## CakePHP Videos
*Fantastic CakePHP-related videos.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.


## CakePHP Tutorials
*Must-do tutorials.*

- [Official Blog tutorial](http://book.cakephp.org/2.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-releated reading and listening materials.*

- [Cookbook(!)](http://book.cakephp.org/2.0/en/index.html) - The official documentation.
- [CakePHP Podcast](http://podcast.cakephp.org/) - The official CakePHP podcasts.
- [Cheat Sheet](http://cakephpcheatsheet.com) - Lot of Code Snippets for the CakePHP Framework.
- [CakePHP Reporter](http://www.scoop.it/t/cakephp-reporter) - a newspaper of collection  new entries about CakePHP.

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

- [CakePHP-NL](http://www.meetup.com/CakePHP-NL) - MeetUps in Netherlands.
- [CakePHP-DE](http://www.meetup.com/CakePHP-DE) - MeetUps in Germany.
- [CakePHP-Paris](http://www.meetup.com/CakePHP-Paris/) - [CakePHP-Toulouse](http://www.meetup.com/CakePHP-Toulouse/) - MeetUps in France.

# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

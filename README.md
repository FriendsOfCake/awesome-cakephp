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
	- [Asset Management](#asset-management)
	- [Authentication and Authorization](#authentication-and-authorization)
	- [Caching](#caching)
	- [Code Analysis](#code-analysis)
	- [Debugging](#debugging)
	- [Dependency Injection](#dependency-injection)
	- [E-commerce](#e-commerce)
	- [Environment](#environment)
	- [Filtering and Validation](#filtering-and-validation)
	- [Geolocation](#geolocation)
	- [I18n](#i18n)
	- [Imagery](#imagery)
	- [Libs](#libs)
	- [Logging](#logging)
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
	- [SEO](#seo)
	- [Search](#search)
	- [Security](#security)
	- [Skeleton](#skeleton)
	- [Templating](#templating)
	- [Testing](#testing)
	- [Third Party APIs](#third-party-apis)
- [Software](#software)
	- [Development Environment](#development-environment)
- [Web Applications](#web-applications)
	- [CMS and applications built on CakePHP](#cms-and-applications-built-on-cakephp)
	- [Demo](#demo)
- [Resources](#resources)
	- [CakePHP Books](#cakephp-books)
	- [CakePHP Internals Reading](#cakephp-internals-reading)
	- [CakePHP Reading and Listening](#cakephp-reading-and-listening)
	- [CakePHP Tutorials](#cakephp-tutorials)
	- [CakePHP Videos](#cakephp-videos)
	- [CakePHP Websites](#cakephp-websites)
	- [Help](#help)
- [Conferences](#conferences)
- [Contributing](#contributing)

## Skeleton
*Plugins and repositories around app skeletons*

- [App template](https://github.com/FriendsOfCake/app-template) - An empty CakePHP project for use with composer.
- [Bake template "setup"](https://github.com/dereuromark/cakephp-setup/tree/master/Console/Templates/setup) - An example template on how customization of bake templates is possible.
- [Crud plugin](https://github.com/FriendsOfCake/crud) - CakePHP Application development on steroids - rapid prototyping / scaffolding & production ready code.

## Environment
*Plugins for enviroment*

- [Enviroments plugin](https://github.com/josegonzalez/cakephp-environments) - Plugin to handle environments.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - Plugin to handle very basic environments.

## Debugging
*Plugins for debugging*

- [Airbrake plugin](https://github.com/morrislaptop/AirbrakeCake) - Integrate Airbrake for CakePHP exceptions and errors
- [ClearCache plugin](https://github.com/ceeram/clear_cache) - For easily clearing the app cache(s).
- [DebugKit plugin](https://github.com/cakephp/debug_kit) - The de-facto standard for debugging.
- [GraphVizModels plugin](https://github.com/mamchenkov/CakePHP-GraphViz-Models) - Display your model relations graphically.
- [Setup plugin](https://github.com/dereuromark/cakephp-setup) - A lightweight setup plugin containing setup tabs at the bottom.

## Templating
*Plugins for templating and lexing.*

- [Address plugin](https://github.com/drmonkeyninja/cakephp-address) - An address helper that outputs a marked up address.
- [BoostCake plugin](https://github.com/slywalker/cakephp-plugin-boost_cake) - A Twitter Bootstrap plugin.
- [CML plugin](https://github.com/jameswatts/cake-markup-language) - Provides further abstraction of the View layer by replacing the procedural PHP code with an XML based markup.
- [CTK plugin](https://github.com/jameswatts/cake-toolkit) - Allows views to be defined as a class.
- [CakeExcel plugin](https://github.com/dakota/CakeExcel) - An Excel view to generate XLSX files.
- [CakeFactory plugin](https://github.com/jameswatts/cake-factory) - A factory for the Cake Toolkit (CTK), which provides configurable objects.
- [CsvView plugin](https://github.com/FriendsOfCake/cakephp-csvview) - A view to easily generate CSV.
- [Mustache plugin](https://github.com/Dismounted/MustacheCake) - A Mustache plugin.
- [Tools:RssView](https://github.com/dereuromark/cakephp-tools) - Containing [RssView](http://www.dereuromark.de/2013/10/03/rss-feeds-in-cakephp/) to easily generate (complex) RSS.
- [TwigView plugin](https://github.com/predominant/TwigView) - A plugin to use the Twig Templating Language for views.
- [VideoEmbed plugin](https://github.com/drmonkeyninja/cakephp-video-helper) - Helper for embedding YouTube, Vimeo and Dailymotion videos.
- [Wysiwyg plugin](https://github.com/josegonzalez/cakephp-wysiwyg) - Support for various WYSIWYG editors.

## Email
*Plugins for sending and parsing email.*

- [EmailQueue plugin](https://github.com/nodesagency/cakephp-email-queue) - An email queue solution.
- [Mailchimp plugin](https://github.com/dereuromark/cakephp-mailchimp) - The Mailchimp and Mandrill plugin.
- [Mandrill plugin](https://github.com/a2design-company/Mandrill-CakePHP-plugin) - Sending Email using Mandrill.
- [Postmark plugin](https://github.com/maurymmarques/postmark-cakephp) - Makes email delivery using Postmark.
- [SendGrid plugin](https://github.com/a2design-company/sendgrid-webapi-cakephp-plugin) - CakePHP plugin for SendGrid WebAPI.

## Files
*Plugins for file manipulation.*

- [FileStorage plugin](https://github.com/burzum/cakephp-file-storage) - Abstract file storage and upload plugin.

## Dependency Injection
*Plugins that implement the dependency injection design pattern.*

- [CakeDependency plugin](https://github.com/jameswatts/cake-dependency) - Provides a dependency injection container and service registry/locator.

## Imagery
*Plugins for manipulating images.*

- [Imagine plugin](https://github.com/burzum/cakephp-imagine-plugin) - An image manipulation plugin and wrapper around [Imagine](https://github.com/avalanche123/Imagine).

## Testing
*Plugins for testing codebases and generating test data.*

- [CakePHP CodeSniffer rules](https://github.com/cakephp/cakephp-codesniffer) - The official CakePHP CS rules.
- [CodeSniffer plugin](https://github.com/dereuromark/cakephp-codesniffer) - A plugin to auto-find and auto-fix almost all CS errors.
- [PHPUnit plugin](https://github.com/dereuromark/cakephp-phpunit) - An easy way to install PHPUnit if you are not using composer.

## Security
*Plugins and information around security, preventing vulnerabilities and protection against XSS and alike.*

- [Saving model data and security](http://www.dereuromark.de/2010/09/21/saving-model-data-and-security/) - Information on what to be careful about in 2.x when using CRUD forms and saving data.

## Code Analysis
*Plugins for analysing, parsing and manipulation codebases.*

- [NewRelic plugin](https://github.com/jeremyharris/cakephp-newrelic) - Makes analyzing your CakePHP app in New Relic easier.
- [NewRelic plugin](https://github.com/jippi/cakephp-newrelic) - Using New Relic for analysis and monitoring.

## Navigation
*Tools for building navigation structures.*

- [MenuBuilder plugin](https://github.com/torifat/cake-menu_builder) - A menu plugin.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

- [AssetCompress plugin](https://github.com/markstory/asset_compress) - A complete asset manager for CakePHP.

## Geolocation
*Plugins for geocoding addresses and working with latitudes and longitudes.*

- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing [Geocoder behavior](http://www.dereuromark.de/2012/06/12/geocoding-with-cakephp/) and [GoogleMapsV3 helper](http://www.dereuromark.de/2010/12/21/googlemapsv3-cakephp-helper/).
- [Geocoder plugin](https://github.com/martinbean/cakephp-geocoding-plugin) - A lightweight geocoding plugin.

## Logging
*Plugins for generating and working with log files.*

- [AuditLog plugin](https://github.com/jippi/cakephp-audit-log) - Records changes made to an object during CRUD operations.
- [DatabaseLog plugin](https://github.com/dereuromark/CakePHP-DatabaseLog) - Log into a database.
- [Monolog plugin](https://github.com/jadb/cakephp-monolog) - Use the comprehensive logger capabilities of Monolog.
- [Tools:WhoDidIt](https://github.com/dereuromark/cakephp-tools) - Containing WhoDidIt behavior to record changes made to an object during CRUD operations.

## E-commerce
*Plugins and applications for taking payments and building online e-commerce stores.*

- [Cart plugin](https://github.com/burzum/cakephp-cart-plugin) - A shopping cart plugin.
- [Payments plugin](https://github.com/burzum/cakephp-payments-plugin) - Generic Payment Interface.
- [Paypal plugin](https://github.com/robmcvey/cakephp-paypal) - To interact with PayPal's "classic" and new REST APIs.
- [PaypalSource plugin](https://github.com/jlkaufman/cakephp-paypal-rest-client) - A PayPal REST client plugin.
- [Stripe](https://github.com/chronon/CakePHP-StripeComponent-Plugin) - A Stripe component.

## PDF
*Plugins and software for working with PDF files.*

- [CakePdf plugin](https://github.com/FriendsOfCake/CakePdf) - A plugin around PDF generation.

## ORM and Datamapping
*Plugins that implement object-relational mapping or data-mapping techniques.*

- [Datasources plugin](https://github.com/cakephp/datasources) - Lots of different datasources.

## NoSQL
*Plugins for working with "NoSQL" backends.*

- [MongoQB plugin](https://github.com/ichikaway/cakephp-mongodb/) - MongoDB database driver.
- [NoSql](https://github.com/kamisama/CakePHP-NoSQL-Datasource) - A low-lever interface to interact with NoSQL datasource.

## Queue
*Plugins for working with event and task queues.*

- [CakeResque plugin](https://github.com/kamisama/Cake-Resque) - A plugin for Resque, a library for creating background jobs
- [Queue plugin](https://github.com/dereuromark/cakephp-queue) - A minimal dependency-free CakePHP only plugin around Queue.

## Search
*Plugins and software for indexing and performing search queries on data.*

- [Elastic](https://github.com/dkullmann/CakePHP-Elastic-Search-DataSource) - Connecting models to Elastic Search types.
- [OpenSearch plugin](https://github.com/dereuromark/cakephp-opensearch) - For creating installable search plugins for IE, Firefox and Chrome.
- [Search plugin](https://github.com/CakeDC/search) - De-facto search form standard built on RPG pattern.
- [SimpleScope](https://github.com/josegonzalez/cakephp-simple-scope) - For scoping finds.
- [Tags plugin](https://github.com/CakeDC/tags) - Tagging records the easy way.
- [Tools:NamedScope](https://github.com/dereuromark/cakephp-tools) - Containing [NamedScope behavior](http://www.dereuromark.de/2014/02/15/cakephp-and-namedscope-for-dry-conditions/) for DRY find conditions.

## Authentication and Authorization
*Plugins and libraries for implementing authentication and authorization.*

- [AnnotationControlList pluin](https://github.com/josegonzalez/cakephp-annotation-control-list) - Lightweight annotation-based ACL as plugin.
- [Authenticate plugin](https://github.com/FriendsOfCake/Authenticate) - Authentication classes for AuthComponent.
- [Authorize plugin](https://github.com/FriendsOfCake/Authorize) - Authorize classes for AuthComponent.
- [GoogleAuthenticate plugin](https://github.com/ceeram/GoogleAuthenticate) - Containing Google 2 step authenticate class for AuthComponent.
- [OpAuth](https://github.com/uzyn/cakephp-opauth) - Opauth provides a standardized method for PHP applications to interface with authentication providers.
- [Sanction plugin](https://github.com/josegonzalez/cakephp-sanction) - Centralize all of those permissions in a single file.
- [Tools:Passwordable](https://github.com/dereuromark/cakephp-tools) - Containing [Passwordable behavior](http://www.dereuromark.de/2011/08/25/working-with-passwords-in-cakephp/) for a DRY approach to modern password hashing.
- [Tools:TinyAuth](https://github.com/dereuromark/cakephp-tools) - Containing TinyAuth for a very lightweight (single/multi) role based access.

## Markup
*Plugins for working with markup.*

- [Decoda plugin](https://github.com/milesj/decoda) - A lightweight bbcode parser plugin.
- [Geshi plugin](https://github.com/markstory/cakephp_geshi) - For adding GeSHI syntax highlighting.
- [Markdown plugin](https://github.com/chronon/CakePHP-Markdown-Plugin) - A Markdown parser plugin.
- [MarkupParsers plugin](https://github.com/CakeDC/markup_parsers) - A collection of parsers.

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
- [Comments plugin](https://github.com/CakeDC/comments) - Allows users to comment records.
- [Facebook plugin](https://github.com/webtechnick/CakePHP-Facebook-Plugin) - Facebook plugin.
- [Favorite plugin](https://github.com/CakeDC/favorites) - Allows users to favor records.
- [Feedback plugin](https://github.com/lecterror/cakephp-feedback-plugin) - Providing feedback.
- [Like plugin](https://github.com/aschelch/cakephp-like-plugin) - Provides a feature similar to Facebook "Like".
- [Ratings plugin](https://github.com/CakeDC/ratings) - Allows users to rate records.
- [Twitter plugin](https://github.com/mishudark/CakePHP-2.x-Twitter-Plugin) - A library to interface with Twitter and its OAuth workflow.

## SEO
*Search Engine Optimization*

- [Seo plugin](https://github.com/webtechnick/CakePHP-Seo-Plugin) - SEO plugin.
- [Sitemap plugin](http://plugins.cakephp.org/p/1681-CakePHP-Sitemap) - Generates HTML and XML sitemaps for your CakePHP application.
- [Slugger plugin](https://github.com/jeremyharris/slugger) - Automatically slugs URLs.
- [Tools:Slugged](https://github.com/dereuromark/cakephp-tools) - Containing Slugged behavior to auto-generate URL-compatible slugs from titles.

## Third Party APIs
*Plugins for accessing third party APIs.*

- [AmazonSdk plugin](https://github.com/mcallisto/cakephp-amazon-aws-sdk) - A plugin around PHP AWS SDK library.
- [SMSFly plugin](https://github.com/imsamurai/cakephp-sms-fly-datasource) - Data source for sending SMS via sms-fly.

## Migration
*Plugins and resources around migration and upgrading*

- [Migrations plugin](https://github.com/CakeDC/migrations) - (DB) Migration plugin.
- [Upgrade plugin](https://github.com/dereuromark/cakephp-upgrade) - The most extensive 1.x=>2.x and partly =>3.x upgrade shells.
- [Upgrade/Migration Guide](http://book.cakephp.org/2.0/en/appendices.html) - Official migration guide.

## Miscellaneous
*Misc plugins and libraries*

- [AJAX](http://www.dereuromark.de/2014/01/09/ajax-and-cakephp) - AJAX and CakePHP.
- [Dotcake](https://github.com/dotcake/dotcake) - Provides CakePHP project info for editor's cakephp plugins.
- [Ftp plugin](https://github.com/fotografde/cakephp-ftp) - FTP/SFTP plugin.
- [Jsonrpc plugin](https://github.com/jameswatts/cake-jsonrpc) - Provides server and client implementations of JSON-RPC.
- [MaintenanceMode plugin](https://github.com/awebdeveloper/cakephp-maintenance-mode) - Show a custom template for all requests when in maintainance with optional IP white-listing.
- [Setup:Maintenance](https://github.com/dereuromark/cakephp-setup) - Maintenance shell to go into maintenance mode for all requests with optional IP white-listing.
- [Shim plugin](https://github.com/dereuromark/cakephp-shim) - A plugin containing useful shims and improvements as basis for your application.
- [MobileDetect plugin](https://github.com/chronon/CakePHP-MobileDetectComponent-Plugin) - Identifying mobile devices using the Mobile_Detect project.
- [Tools plugin](https://github.com/dereuromark/cakephp-tools) - Containing lots of useful libs, helpers, behaviors, components, shells, ...
- [Travis](https://github.com/FriendsOfCake/travis) - Easy travis setup for CakePHP plugins.
- [Users plugin](https://github.com/CakeDC/users) - For allowing users to register and login manage their profile.

## Libs
*Useful libraries or tools that don't fit in the categories above.*

- [Aura.Intl](https://github.com/auraphp/Aura.Intl) - A powerful I18n library - - used in CakePHP3.x anyway.
- [Capcake](https://github.com/jadb/capcake) - Deploy CakePHP applications using Capistrano
- [Carbon](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension - used in CakePHP3.x anyway.
- [Composer Installers](https://github.com/composer/installers) - A multi framework Composer library installer.
- [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager.
- [Graphviz](https://github.com/alexandresalome/graphviz) - A Graphviz library.
- [Jenkins](http://jenkins-ci.org/) - The free alternative for private (GitHub) repos.
- [Rocketeer](https://github.com/Anahkiasen/rocketeer) - Deployment
- [Travis CI](https://travis-ci.org/) - A continuous integration platform - de-facto standard for testing (GitHub) repos.

# Software
*Software for creating a development environment.*

## Development Environment
*Software and tools for creating a sandboxed development environment.*

- [PuPHPet](https://puphpet.com/) - Web interface for building a Vagrant + Puppet box.
- [Puppet](http://puppetlabs.com/) - A server automation framework and application.
- [Vagrant](http://www.vagrantup.com/) - A portable development environment utility.
- [CakePHP.gitignore](https://github.com/github/gitignore/blob/master/CakePHP.gitignore) - The .gitignore file proposals.

## Web Applications

## CMS and applications built on CakePHP

- [Croogo](https://github.com/croogo/croogo) - Open source content management system.
- [Infinitas CMS](https://github.com/infinitas) - Open source content management framework.
- [QuickApps-CMS](https://github.com/QuickAppsCMS/QuickApps-CMS) - Open source content management system.

Based on CakePHP2.x.

## Demo
*Web-based (demo) applications and tools.*

- [CakeFest](http://cakefest.dereuromark.de/) - Demo application around the annual CakePHP Conference "CakeFest".
- [CakePHP Sandbox](http://sandbox.dereuromark.de) - A sandbox CakePHP application.

Based on CakePHP2.x.

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

- [CakeDC](http://www.cakedc.com/articles) - Articles around CakePHP.
- [dereuromark.de](http://www.dereuromark.de) - An extensive CakePHP core dev blog.
- [florian-kraemer.net](http://florian-kraemer.net) - A CakePHP related core dev blog.
- [jedistirfry.co.uk](http://jedistirfry.co.uk) - A CakePHP related dev blog.
- [josediazgonzalez.com](http://josediazgonzalez.com/) - A mainly CakePHP related core dev blog.
- [mark-story.com](http://mark-story.com) - CakePHP lead dev blog.
- [waltherlalk.com](http://waltherlalk.com)- A CakePHP related core dev blog.
- [andtxr.com](http://andtxr.com) - A CakePHP related dev blog.

## CakePHP Books
*Fantastic CakePHP-related (e)books.*

- [CakePHP 2 Application Cookbook](http://www.packtpub.com/web-development/cakephp-2-application-cookbook) - CakePHP 2.x book by two core developers.
- [Instant Starter](http://www.amazon.com/Instant-CakePHP-Starter-Robert-Henderson-ebook/dp/B00CITNQP2/) - CakePHP2.x book (not for total PHP beginners).
- [Rapid Application Development with CakePHP 2](http://josediazgonzalez.com/cakephp-book/) - CakePHP 2.x book by CakePHP Core Developer @josegonzalez.

## CakePHP Videos
*Fantastic CakePHP-related videos.*

- [CakePHP](https://www.youtube.com/user/CakePHP) - Channel about CakePHP videos.


## CakePHP Tutorials
*Must-do tutorials.*

- [Official Blog tutorial](http://book.cakephp.org/2.0/en/tutorials-and-examples/blog/blog.html)

## CakePHP Reading and Listening
*Documentation and CakePHP-releated reading and listening materials.*

- [CakePHP Podcast](http://podcast.cakephp.org/) - The official CakePHP podcasts.
- [CakePHP Reporter](http://www.scoop.it/t/cakephp-reporter) - a newspaper and collection of material about CakePHP.
- [Cheat Sheet](http://cakephpcheatsheet.com) - Lot of Code Snippets for the CakePHP Framework.
- [Cookbook(!)](http://book.cakephp.org/2.0/en/index.html) - The official documentation.

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
- [CakePHP-Paris](http://www.meetup.com/CakePHP-Paris/) - [CakePHP-Toulouse](http://www.meetup.com/CakePHP-Toulouse/) - MeetUps in France.


# Contributing
Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits
awesome-cakephp has been created by [dereuromark](https://github.com/dereuromark) and is currently maintained by him and the FriendsOfCake group. Thank you to all [contributors](https://github.com/FriendsOfCake/awesome-cakephp/contributors), too.

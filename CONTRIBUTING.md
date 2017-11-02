# Contribution Guidelines
Please ensure your pull request adheres to the following guidelines:

* Please search previous suggestions before making a new one, as yours may be a duplicate.
* Code, comments and documentation need to be in English.
* Libraries that are PHP 5.4+, Composer-installable, CakePHP-PSR compliant, tested and documented are preferred.
* If possible, please publish your library under an open source license (preferably MIT).
* Please make an individual pull request for each suggestion.
* New categories, or improvements to the existing categorisation are welcome.
* Keep descriptions short and simple.
* End all descriptions with a full stop/period.
* Check your spelling and grammar.
* Make sure your text editor is set to remove trailing whitespace.
* Proposed libraries should ideally have 10+ stars.
* Please keep the lists in alphabetical order.
* Name plugins as `ExactPluginName plugin`.

Thank you for your suggestions!

## Tips for creating composer packages

Choose a semantically meaningful name for the package name. This should ideally be prefixed with the dependency, in this case "cakephp" as the framework.
The vendor name will usually be your GitHub username.
Do **not** use the CakePHP namespace (cakephp) as this is reserved to CakePHP owned plugins.
The convention is to use lowercase letters and dashes as separator.

So if you created a plugin "Logging" with your GitHub account "FooBar", a good name
would be `foo-bar/cakephp-logging`.
And the CakePHP owned "Localized" plugin can be found under `cakephp/localized` respectively.

## Tips for creating CakePHP plugins

* Make sure the README or docs contain installation and usage instructions. The more verbose, the better.
* The composer.json contains necessary dependencies including constraints (ideally using [semver](http://semver.org/) and `^` operator).
* The plugin contains basic tests (unit, ...) of the functionality provided.
* It should have Travis or some CI set up.
* You can add badges under the README h1 header to visually show your tests are green etc.

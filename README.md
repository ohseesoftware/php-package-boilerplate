# PHP Package Boilerplate

Boilerplate project to get started with a PHP package.

![Build Status Badge](https://github.com/ohseesoftware/php-package-boilerplate/workflows/Build/badge.svg)

## Usage

* Clone this project
* Change the Git upstream to your new repository
* Remove the `src/Example.php` and `tests/ExampleTest.php` example files
* Update the `psr-4` block in the `composer.json` file to have your namespace
* Update the Name, Description, Authors, and License of the `composer.json` file
* The boilerplate includes a setup for code coverage with Coveralls:
* * Login to [https://coveralls.io/](https://coveralls.io/) and import your repository
* * Grab the repo token from Coveralls, and add it as a secret into the GitHub repository with the the name `COVERALLS_REPO_TOKEN`
* Start writing your package!

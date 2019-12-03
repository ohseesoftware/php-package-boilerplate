# PHP Package Boilerplate

Boilerplate project to get started with a PHP package.

[![Current Release](https://img.shields.io/github/release/ohseesoftware/php-package-boilerplate.svg?style=flat-square)](https://github.com/ohseesoftware/php-package-boilerplate/releases)
![Build Status Badge](https://github.com/ohseesoftware/php-package-boilerplate/workflows/Build/badge.svg)
[![Coverage Status](https://coveralls.io/repos/github/ohseesoftware/php-package-boilerplate/badge.svg?branch=master)](https://coveralls.io/github/ohseesoftware/php-package-boilerplate?branch=master)
[![Maintainability Score](https://img.shields.io/codeclimate/maintainability/ohseesoftware/php-package-boilerplate.svg?style=flat-square)](https://codeclimate.com/github/ohseesoftware/php-package-boilerplate)
[![Downloads](https://img.shields.io/packagist/dt/ohseesoftware/php-package-boilerplate.svg?style=flat-square)](https://packagist.org/packages/ohseesoftware/php-package-boilerplate)
[![MIT License](https://img.shields.io/github/license/ohseesoftware/php-package-boilerplate.svg?style=flat-square)](https://github.com/ohseesoftware/php-package-boilerplate/blob/master/LICENSE)

## Usage

* Clone this project
* Change the Git upstream to your new repository
* Change the repository name through the top of the README (in the badges)
* Remove the `src/Example.php` and `tests/ExampleTest.php` example files
* Update the `psr-4` block in the `composer.json` file to have your namespace
* Update the Name, Description, Authors, and License of the `composer.json` file
* The boilerplate includes a setup for code coverage with Coveralls:
* * Login to [https://coveralls.io/](https://coveralls.io/) and import your repository
* * Grab the repo token from Coveralls, and add it as a secret into the GitHub repository with the the name `COVERALLS_REPO_TOKEN`
* The boilerplate includes a badge for maintainability score with Code Climate:
* * Login to [https://codeclimate.com](https://codeclimate.com) and import your repository
* The boilerplate includes a setup for maintainability score with Code Climate:
* * Login to [https://codeclimate.com](https://codeclimate.com) and import your repository
* Start writing your package!

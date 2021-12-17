wkhtmltopdf
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/) on arm64 system.
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.6'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _arm64_ with:

    php composer.phar require h4cc/wkhtmltopdf-arm64 "0.12.6"

The binary will then be located at:

    vendor/houseoftech/wkhtmltopdf-arm64/bin/wkhtmltopdf-arm64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-arm64

### Usage

You can use the path constant to easily locate the binary in the PHP codebase: 

``` php
$path = \houseoftech\WKHTMLToPDF\WKHTMLToPDF::PATH;
```

For realpath use following script

``` php
$realpath = realpath(\houseoftech\WKHTMLToPDF\WKHTMLToPDF::PATH);
```

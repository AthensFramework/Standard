# Standard

This `ruleset.xml` contains the University of Washington, Department of Enrollment Management Php web-application coding standard, for use with [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

# Use

To download the standard, include `uwdoem/standard` if your `composer.json` dev requirements:
```
"require-dev": {
    ...
    "uwdoem/standard": "*",
    ...
  }
```

Once you have updated your composer requirements, you'll be able to issue the following command from your project root:
```
./vendor/bin/phpcs --standard=./vendor/uwdoem/standard/ruleset.xml .
```

See the [PHP CodeSniffer docs](https://github.com/squizlabs/PHP_CodeSniffer/wiki) for more information, including excluding directories from analysis.

# Requirements

* PHP Codesniffer 2.x

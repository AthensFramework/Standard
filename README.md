[![Latest Stable Version](https://poser.pugx.org/athens/standard/v/stable)](https://packagist.org/packages/athens/standard)

# Standard

This `ruleset.xml` contains the Athens Framework code standard, for use with [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer). Projects which use the Athens Framework are welcome to use this same code standard.

# Use

To download the standard, include `athens/standard` if your `composer.json` dev requirements:
```
"require-dev": {
    ...
    "athens/standard": "1.*",
    ...
  }
```

Once you have updated your composer requirements, you'll be able to issue the following command from your project root:
```
./vendor/bin/phpcs --standard=./vendor/athens/standard/ruleset.xml .
```

See the [PHP CodeSniffer docs](https://github.com/squizlabs/PHP_CodeSniffer/wiki) for more information, including excluding directories from analysis.

# Requirements

* PHP Codesniffer 2.x

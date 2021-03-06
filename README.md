#PhpSpec extension for TeamCity CI

Formats PhpSpec output to make TeamCity display spec execution results
in real-time.

[![Build Status](https://travis-ci.org/pawel-grzona/teamcity-phpspec-extension.png)](https://travis-ci.org/pawel-grzona/teamcity-phpspec-extension)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/pawel-grzona/teamcity-phpspec-extension/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/pawel-grzona/teamcity-phpspec-extension/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/pawel-grzona/teamcity-phpspec-extension/badges/build.png?b=master)](https://scrutinizer-ci.com/g/pawel-grzona/teamcity-phpspec-extension/build-status/master)

The 2.* version has been rebuilt from scratch to work with phpspec/phpspec
rather than phpspec/phpspec2 and as such is not backward compatible.

## Installation

In your composer.json:

```json
{
    "require-dev": {
        "pawel-grzona/teamcity-phpspec-extension": "2.*"
    }
}
```

## Configuration

In your phpspec.yml:

```yml
extensions:
    - PhpSpec\TeamCity\Extension
```

## Usage

```bash
./phpspec -f teamcity
```

## Requirements

PHP 5.3+

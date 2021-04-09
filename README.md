# PHP Magneds Test
Your task is to read from the API provided by: https://www.spaceflightnewsapi.net/documentation to do the following:

1. Read the data from the https://www.spaceflightnewsapi.net/documentation API
    1. Use a library to make the request
        1. Please use a PSR-18 based library: https://packagist.org/packages/psr/http-client
    1. Refer to the Schemas at the bottom for the structure of the Entity objects.
    1. Parse the data from the API into PHP Objects that represent that schema
1. Add Symfony/Console commands to display the information in those new Entity objects.
    1. One Command to: ReadArticles
    1. One Command to: ReadBlogs
    1. Refer to the Usage part below to see the name of the commands
1. Add those Commands to the [spacenews](./spacenews) application.

How the articles and blogs are displayed is up to you.

## Nice to haves (but not required)
* Support for pagination

## Requirements
* PHP 7.4

## Usage
```./spacenews read:articles```

Read the articles from that API

```./spacenews read:blogs```

Read the blogs posts from that API


# Supported tags and respective `Dockerfile` links

  * [`latest`](https://github.com/wernight/docker-phpcs/blob/master/Dockerfile) [![](https://images.microbadger.com/badges/image/wernight/phpcs.svg)](http://microbadger.com/images/wernight/phpcs "Get your own image badge on microbadger.com")

## What is PHP_CodeSniffer

[PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) is a set of two PHP scripts; the main `phpcs` script that tokenizes PHP, JavaScript and CSS files to detect violations of a defined coding standard, and a second `phpcbf` script to automatically correct coding standard violations. PHP\_CodeSniffer is an essential development tool that ensures your code remains clean and consistent.


## Usage example

    $ docker run --rm -v $PWD:/code:ro wernight/phpcs phpcs /code


## Feedbacks

Improvement ideas and pull requests are welcome via
[Github Issue Tracker](https://github.com/wernight/docker-phpcs/issues).

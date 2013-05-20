Eleme-PHP-Coding-Standards
==========================

PHP_CodeSniffer rules (sniffs) to enforce Eleme coding conventions

## How to use this

1. install `PHP_CodeSniffer` at first:

    pear install PHP_CodeSniffer

2. then install Eleme php Coding standards:

    git clone https://github.com/thbourlove/Eleme-PHP-Coding-Standards.git $(pear config-get php_dir)/PHP/CodeSniffer/Standards/Eleme

3. set the Eleme standards as the default standard of `PHP_CodeSniffer`

    phpcs --config-set default_standard Eleme

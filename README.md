# Flexible error handling for PHP

If this package is listed as a dependency of another package, it means that the
package is designed to work with [exception-based] error handlers, such as the
one described in this [specification], but that it also supports [native] errors
that PHP produces by default.

[exception-based]: https://github.com/php-errors/exceptions
[native]: https://github.com/php-errors/native
[specification]: https://github.com/php-errors/exceptions/blob/master/doc/specification.md

## Installation

To mark a package as capable of supporting both error handling methods, simply
include this meta-package in the dependencies:

    composer require errors/any

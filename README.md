# The `errors/any` meta-package

Adding this package as a dependency indicates that the root package is designed
to work with [exception-based] error handlers, such as the one described in this
[specification], but that it also supports [native] errors that PHP produces by
default:

    composer require errors/any

[exception-based]: https://github.com/php-errors/exceptions
[native]: https://github.com/php-errors/native
[specification]: https://github.com/php-errors/exceptions/blob/master/doc/specification.md

> # No longer maintained
>
> This package is no longer maintained. See [this statement] for more info.
>
> [this statement]: https://gist.github.com/ezzatron/713a548735febe3d76f8ca831bc895c0

# The `errors/any` meta-package

Adding this package as a dependency indicates that the root package is designed
to work with [exception-based] error handlers, such as the one described in this
[specification], but that it also supports [native] errors that PHP produces by
default:

    composer require errors/any

[exception-based]: https://github.com/php-errors/exceptions
[native]: https://github.com/php-errors/native
[specification]: https://github.com/php-errors/specification/blob/master/exception-based-error-handler.md

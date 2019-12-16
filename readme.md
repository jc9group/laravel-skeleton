### Clean laravel

This is a laravel skeleton version without any frontend, unnecessary providers, middleware, facades and so on.
The main goal is to make something like lumen, but with laravel capabilities.

# Base artisan commands
If you need some unrepresented artisan commands - go to `App\Providers\BaseArtisanCommandsProvider` and uncomment them

# Providers
If you need some base providers - you can uncomment them in `config/app.php`

# Tests
Add `<directory suffix="Test.php">./{vendor}/*/tests/</directory>` to you phpunit.xml
and all tests from `{vendor}/*some_context*/tests` will be executed automatically

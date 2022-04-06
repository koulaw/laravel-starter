 # Laravel 9 starter template

## Assets

### Javascript

- Front related javascript must be in `resources/js/app.js` file
- Front related javascript must be in `resources/js/admin.js` file

### Sass

- Front related javascript must be in `resources/sass/app.scss` file
- Front related javascript must be in `resources/sass/admin.scss` file


## Routes

- Front routes are supposed to be declared in the `routes/web.php` file
- Admin routes are supposed to be declared in the `routes/admin.php` file

 ## Before commits

 ### PHP Coding Standards Fixer

 The [PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) (PHP CS Fixer) tool fixes your code to follow standards.

 - `composer sniff`: The --dry-run flag will run the fixer without making changes to your files.
 - `composer lint`

> You can find the config file at the root of the project `.php-cs-fixer.php`


### Larastan

[Larastan](https://github.com/nunomaduro/larastan) focuses on finding errors in your code. It catches whole classes of bugs even before you write tests for the code.

- `composer analyse`

> You can find the config file at the root of the project `phpstan.neon`

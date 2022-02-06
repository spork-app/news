## News

Simply add to your spork app through composer!

```
composer require spork/news
```

Publish your assets

```
php artisan vendor:publish --provider=Spork\\News\\NewsServiceProvider
```

You'll need to run `artisan migrate` to ensure your database gets the new repeating events schema

Lastly, register the Service Provider in your Spork App's `config/app.php` file. That will automatically add the News entry to the menu.

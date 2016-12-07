flukky-dev-blog powered by vuedo

Rename `.env.example` to `.env` and fill the options.

Run the following commands:

```
composer install
npm install
php artisan key:generate
php artisan migrate
php artisan db:seed
gulp
php artisan serve
```

If you are making changes to JavaScript or Styles make sure you run `gulp watch`.

You can find the technical description and a list with the libraries used in development [here](https://github.com/Vuedo/vuedo/wiki/Technical-Description).

Vuedo is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
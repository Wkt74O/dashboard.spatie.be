# 





Install this package by running cloning this repository and install like you normally install Laravel.

- Run `composer install` and `npm install yarn`
- Run `yarn` and `yarn run dev` to generate assets
- Copy `.env.example` to `.env` and fill your values (`php artisan key:generate`, database, pusher values etc)
- Run `php artisan migrate --seed`, this will seed a user based on your `BASIC_AUTH` `.env` values
- Start your queue listener and setup the Laravel scheduler.
- Open the dashboard in your browser, login and wait for the update events to fill the dashboard.

## Postcardware

If you are using our dashboard, please send us a postcard from your hometown.

Our address is: Spatie, Kruikstraat 22, 2018 Antwerp, Belgium.

All postcards are published [on our website](https://spatie.be/en/opensource/postcards).

## Support
This dashboard is tailormade to be displayed on the wall mounted tv in our office. We do not follow [semver](http://semver.org) for this project and do not provide support whatsoever. However if you're a bit familiar with Laravel and Vue you should easily find your way.

For more details on the project, read our article about the [setup and components](https://murze.be/2017/06/building-realtime-dashboard-powered-laravel-vue-2017-edition/)

## License

This project and the Laravel framework are open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

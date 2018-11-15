# Invitado

An application to make access control easy in any condo.

## Getting Started

Just clone this repo and make a copy of .env.example to .env and change the content to the right configuration.

### Installing

After you cloned the repo you have to install the dependencies via composer.

```
composer install
```

Then, the node dependecies

```
yarn install
```

After you updated the .env file with your database configuration, run the migrations.

```
php artisan migrate
```

Then, seed the database, this will create the default user.

```
php artisan db:seed
```

## Built With

* [Laravel](http://www.laravel.com) - The web framework used
* [VueJS](http://www.vuejs.org) - The javascript framework used
* [Composer](https://getcomposer.org) - Dependency Management

## Contributing

## Versioning

## Authors

* **Carlos Chávez** - *Initial work* - [cchavezflores](https://github.com/cchavezflores)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


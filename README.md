# My Laravel Starter Package
I find myself installing the same packages over and over again, so I decided to create 
this starter project to re-use in future.

I made it public so others can use it too if required.

## Packages Included

Here are the list of packages included in this starter project.
I do use other packages such as Ray but decided not to include them as most people won't utilise them.

- Laravel 10
- Livewire 3
- Laravel Breeze
- [Laravel Ide Helper](https://github.com/barryvdh/laravel-ide-helper)
- [Laravel Ignition](https://github.com/spatie/laravel-ignition)
- [Laravel Pint](https://laravel.com/docs/10.x/pint)
- [Pest & Laravel Plugin](https://pestphp.com/)
- [Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)
- TailwindCSS
- Vite

## Extra Features
Just some extra things this project includes.

### DBSeeder
I've put functionality for seeding a user into the DB in the DB Seeder class. This will look at the env file for SEED_PASSWORD.

This is not really recommended, but I just use it when starting a project and use a password like 'password'.

Obviously, don't ship something like that to prod.

### Livewire
The livewire layout is published already for full page layouts.

### Sessions
Session encryption has been enabled in the session config file.

### Redis
Cache & Session driver in the .env.example file has been configured to use Redis.

## Usage

Just download the zip file and extract it to your project folder.

You can also press 'use this template' in the top right of the repository screen.

Run the following commands to install dependencies.

```bash
composer install
npm install
```

Run the following to build vite assets
```bash
npm run build
```



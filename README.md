## Laravel Socialite (Social Login) - Login with google, facebook and github

## Clone this repo
```
git@github.com:anon1277/Laravel_Login_with_Google_and_Github.git
```

## Install composer packages
```
$ cd laravel-socialite
$ composer install
```

## Create and setup .env file
```
make a copy of .env.example and rename to .env
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
```

## Create app for google, facebook and github
```
For google app
https://console.developers.google.com/
For facebook app
https://developers.facebook.com/apps/
For gitgub app
https://github.com/settings/developers

Put all ids and secrets in .env file
```

## Migrate and insert records
```
$ php artisan migrate
```

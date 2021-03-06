# Laravel + Angular

![logo](image.png "Logo")

This is a simple application starter (boilerplate) for Laravel 5.4.x + Angular 4.

The Angular code is based on [Angular Webpack Starter](https://github.com/preboot/angular-webpack)

## Installation

- Clone the repository
- `composer install & npm install`

### Development

Run `npm run start` to start a server that'll run on `http://localhost:9045` or `npm run build-dev` to just compile the assets to public/build

### Build

You can also run `npm run build` to use webpack.config.js configuration instead of Laravel Mix.

### Laravel Mix

You can use Laravel Mix by running `npm run dev` or `npm run production`, The output will be published to public/build but it'll be incomplete and won't work with mix() functions in the layout by default.

### Usage

By default the angular code came with index.html which you can use but you can also use the Laravel blade templates as the layout file. Either one works.

If you have any questions please use the Issues tab or submit a pull request. I tried to keep this as simple as possible without all the tests, linting etc... just the basic form of a starter repository to be able to use Angualr with Laravel as the backend.

[@gabrielva](https://twitter.com/@gabrielva)

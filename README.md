# NgPolymerApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.0.
The project integrates Polymer paper-elements. The changes made:
- bower_components are installed into static assets directiory indicated by .bowerrc file (src/assets/bower_components)
- index.html loads necessary polyfills + adds imports for used elements
- main.ts bootstraps angular app on WebComponentsReady event 
- the bootstraping module (app.module.ts) uses CUSTOM_ELEMENTS_SCHEMA schema

## How to run
- clone the repo
- install npm deps (npm i)
- install bower deps (bower i) - assuming that bower was installed globally
- run the app (ng serve) - assuming that @angular/cli was installed globally

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

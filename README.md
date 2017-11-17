# angular-cli-netfx

ASP.NET Angular 5 project generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.

## Dev Workflow

Run the ASP.NET Server App with `F5` and watch for changes and in a new terminal window run the `dev` Gulp task in Task Runner Explorer to start a dev watch
aot build for compiling client assets.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `webpack-build` Gulp task to build the project. The build artifacts will be stored in the `wwwroot/` directory. Use `npm run webpack-build-prod` for a production build.

## Publish

Run `publish` Gulp task to generate a client and server production build the project. Then Right click your Host project and click `Publish` menu item
to use MS Deploy to deploy your App to IIS. 

## Running unit tests

Run `tests-run` Gulp task to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `tests-e2e` Gulp task to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

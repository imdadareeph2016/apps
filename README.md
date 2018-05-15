# Angular4 Spring Boot JWT Starter
This sub-project is cloned from https://github.com/bfwg/angular-spring-starter

This will serve as a broiler plate for token based authentication system via oauth.

## Usage
[appserver] Just start the application with the Spring Boot maven plugin (`mvn spring-boot:run`). The application is
running at [http://localhost:8080](http://localhost:8080).

[apps] Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`.

There are three user accounts present to demonstrate the different levels of access to the endpoints in
the API and the different authorization exceptions: Encryption done via Bycrypt (https://www.browserling.com/tools/bcrypt)
```
Admin/Password - imdadareeph:imdadareeph
User/Password - user:123
```



**Make sure you also have NPM 3.1, Node 6.9.5 and angular-cli@1.0.0 globally installed**


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `../server/src/main/resorces/static/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

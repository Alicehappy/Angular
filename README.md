# AngularPoto

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

1. Use Yarn create a new project(listen on port 4200): angular-poto
Cmd:
$ ng new --skip-install angular-poto && cd $_ && yarn
$ cd angular-poto
$ ng serve --open


##  Using Yarn with Angular CLI: (Angular CLI: Speed up installing dependencies with Yarn)
Yarn is an alternative package manager for NPM packages with a focus on reliability and speed.
To enable Yarn for Angular CLI you have to run the following command:
ng set --global packageManager=yarn
To later revert it back to using npm use this:

ng set --global packageManager=npm

##the command to install Yarn globally:
npm install yarn -g

##Create a new project called samleProj:
ng new sampleProj(it wilng l generate the boilerplate code of the project in the directory sampleProj with package.json and will immediately run npm install there.)
Use Yarn:
This could be done in three steps:
1. Instruct Angular CLI to not run npm install:
ng new --skip-install sampleProj
2. cd sampleProj 
3. yarn
If you use Mac or Unix-based OS, you can combine the above three steps as follows:
ng new --skip-install sampleProj && cd $_ && yarn
The bash parameter $_ refers to the last argument of the previous command, which is sampleProj in our case.
UPDATE: As of Angular CLI Beta 31 you can simply set Yarn as your default package manager so Angular CLI will use it during generation of new projects:
ng set --global packageManager=yarn
##Serve the application:
Go to the project directory and launch the server.
cd sampleProj
ng serve --openThe ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files.
Using the --open (or just -o) option will automatically open your browser on http://localhost:4200/.





























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
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

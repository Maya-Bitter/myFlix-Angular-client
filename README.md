# MyFlixAngularClient

## **Achievement 6 Project: MyFlixAngularClient**

### **Contents**

[Objective](#Objective)

[Context](#Context)

[Technical Requirements](#Technical-Requirements)

[Features and Requirements](#Features-and-Requirements)

## **Objective**

Using Angular, I built the client-side for an application called myFlix based on
its existing server-side code (REST API and database), with supporting
documentation.

[go to start](#Contents)

## Context

In this Achievement, I learned how to work with others by writing and sharing documentation with my peers, providing feedback, and making a contribution to the tech community. The ability to create detailed and straightforward handoffs for other developers is an indispensable skill that I'll need when applying for a job.

I returned to the myFlix app's server-side from Achievement 2 and build the client-side interface for a new single-page, responsive app, one that includes several interface views that will 
handle data through the previously-defined REST API endpoints.
This time I used Angular, instead of React. 


## Technical Requirements

* The application must be written in Angular (version 9 or later)
* The application requires the latest version of Node.js and npm package
* The application must contain user registration and login forms
* The application must be designed using Angular Material
* The application's codebase must contain comments using Typedoc
* The project must contain technical documentation using JSDoc
* The project must be hosted on GitHub Pages

[go to start](#Contents)

## Features and Requirements

### Key Features:

* The app should display a welcome view where users will be able to either log in or register an
  account
* Once authenticated, the user should now view all movies
* Upon clicking on a particular movie, users will be taken to a single movie view, where
additional movie details will be displayed. The single movie view will contain the following
additional features:
* A button that when clicked takes a user to the director view, where details about the
director of that particular movie will be displayed.
* A button that when clicked takes a user to the genre view, where details about that
particular genre of the movie will be displayed.

[go to start](#Contents)

### User Stories

___User story:
As a user, I want to be able to receive information on movies, directors, and genres so that I
can learn more about movies I’ve watched or am interested in.___

___User story:
As a user, I want to be able to create a profile so I can save data about my favorite movies.___

[go to start](#Contents)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

[go to start](#Contents)

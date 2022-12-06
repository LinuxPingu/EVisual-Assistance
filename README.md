# EVisual Assistance
 This project is aimed to provide services to people with visual impediments.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.1.

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

## GIT Workflow
This project follows Git Feature Workflow with Develop Branch. It allows teams to consistently merge new features, test them in (staging), and deploy to (production).

## Branches and environments
Each branch represents the code that is running on an environment. <small>For example: master branch represents the production environment.</small> So that, next table list all the branches and its corresponding environment.

| Branch | Environment |
| --- | --- |
| Master  | Production |
| Develop | Stagingn |

The master branch always reflects a production-ready state. Whenever the team wants to deploy to (production) they deploy it from the master branch.

The develop branch reflects the state with the latest delivered development changes for the next release and points to (staging).

## How to create a feature-* branch

Use follow commands to create a feature-* branch on (local) environment:

```
$ git checkout develop
$ git pull
$ git checkout -b feature-*
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

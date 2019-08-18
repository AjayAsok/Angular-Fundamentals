# AngularRouterSample

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.2.0.

This is a angular routing fundamental application. To learn basic concept of routing provided by angular.

### Steps:

1. Create a new angular application using angular CLI. Include Angular Routing also.
2. Create a Component directory inside App folder.
3. Generate 3 components inside the component directory.
4. There will be an app-routing.module.ts file inside App folder. Open that.
5. Inside const routes array provide {
    path: 'home',
    component: HomeComponent
  },
  {
    path: 'about',
    component: AboutComponent
  },
  {
    path: 'dashboard',
    component: DashboardComponent
  }

  6. Open app.component.html file.Provide routing link as below.
        <a routerLink="home" routerLinkActive="active">&nbsp;Home</a>
        <a routerLink="dashboard">&nbsp;DashBoard</a>
        <a routerLink="about">&nbsp;About</a>

Make sure that, app-routing.module should be imported in app.module.

Here we go. App is ready. Serve it :P

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

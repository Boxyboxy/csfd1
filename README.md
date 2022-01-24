# D1

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

## deploying using angular-cli-ghpages

https://github.com/angular-schule/angular-cli-ghpages

1. Install the latest version of the Angular CLI globally and create a new Angular project

   ```sh
   npm install -g @angular/cli
   ng new your-angular-project --defaults
   cd your-angular-project
   ```

2. By default the Angular CLI initializes a Git repository for you.  
   To add a new remote for GitHub, use the `git remote add` command:

   ```sh
   git remote add origin https://github.com/<username>/<repositoryname>.git
   ```

3. Add `angular-cli-ghpages` to your project.

   ```sh
   ng add angular-cli-ghpages
   ```

4. Deploy your project to GitHub pages with all default settings.
   Your project will be automatically built in production mode.

   ```sh
   ng deploy --base-href=/<repositoryname>/
   ```

   Which is the same as:

   ```sh
   ng deploy your-angular-project --base-href=/<repositoryname>/
   ```

   Please be aware of the `--base-href` option. It is necessary when your project will be deployed to a non-root folder. See more details below.

5. Your project should be available at `https://<username>.github.io/<repositoryname>`.  
   Learn more about GitHub pages on the [official website](https://pages.github.com/).

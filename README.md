# ExampleAngularPlaywrightApp

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.3.7.

```shell
➜  mrlonis ng new example-angular-playwright-app
✔ Which stylesheet format would you like to use? Sass (SCSS)     [ https://sass-lang.com/documentation/syntax#scss                ]
✔ Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? No
✔ Do you want to create a 'zoneless' application without zone.js? No
✔ Which AI tools do you want to configure with Angular best practices? https://angular.dev/ai/develop-with-ai None, Claude         [ https://docs.anthropic.com/en/docs/claude-code/memory            ], Cursor         [
https://docs.cursor.com/en/context/rules                         ], Gemini         [ https://ai.google.dev/gemini-api/docs                            ], GitHub Copilot [
https://code.visualstudio.com/docs/copilot/copilot-customization ], JetBrains AI   [ https://www.jetbrains.com/help/junie/customize-guidelines.html   ], Windsurf       [
https://docs.windsurf.com/windsurf/cascade/memories#rules        ]
CREATE example-angular-playwright-app/README.md (1490 bytes)
CREATE example-angular-playwright-app/.editorconfig (314 bytes)
CREATE example-angular-playwright-app/.gitignore (604 bytes)
CREATE example-angular-playwright-app/angular.json (2642 bytes)
CREATE example-angular-playwright-app/package.json (1153 bytes)
CREATE example-angular-playwright-app/tsconfig.json (992 bytes)
CREATE example-angular-playwright-app/tsconfig.app.json (429 bytes)
CREATE example-angular-playwright-app/tsconfig.spec.json (408 bytes)
CREATE example-angular-playwright-app/.vscode/extensions.json (130 bytes)
CREATE example-angular-playwright-app/.vscode/launch.json (470 bytes)
CREATE example-angular-playwright-app/.vscode/tasks.json (938 bytes)
CREATE example-angular-playwright-app/src/main.ts (222 bytes)
CREATE example-angular-playwright-app/src/index.html (313 bytes)
CREATE example-angular-playwright-app/src/styles.scss (80 bytes)
CREATE example-angular-playwright-app/src/app/app.scss (0 bytes)
CREATE example-angular-playwright-app/src/app/app.spec.ts (688 bytes)
CREATE example-angular-playwright-app/src/app/app.ts (313 bytes)
CREATE example-angular-playwright-app/src/app/app.html (20122 bytes)
CREATE example-angular-playwright-app/src/app/app.config.ts (400 bytes)
CREATE example-angular-playwright-app/src/app/app.routes.ts (77 bytes)
CREATE example-angular-playwright-app/public/favicon.ico (15086 bytes)
CREATE example-angular-playwright-app/.claude/CLAUDE.md (1936 bytes)
CREATE example-angular-playwright-app/.cursor/rules/cursor.mdc (1989 bytes)
CREATE example-angular-playwright-app/.gemini/GEMINI.md (1936 bytes)
CREATE example-angular-playwright-app/.github/copilot-instructions.md (1936 bytes)
CREATE example-angular-playwright-app/.junie/guidelines.md (1936 bytes)
CREATE example-angular-playwright-app/.windsurf/rules/guidelines.md (1936 bytes)
✔ Packages installed successfully.
    Successfully initialized git.
```

## Table of Contents

- [ExampleAngularPlaywrightApp](#exampleangularplaywrightapp)
  - [Table of Contents](#table-of-contents)
  - [Development server](#development-server)
  - [Code scaffolding](#code-scaffolding)
  - [Building](#building)
  - [Running unit tests](#running-unit-tests)
  - [Running end-to-end tests](#running-end-to-end-tests)
    - [Setting up Playwright for E2E Testing](#setting-up-playwright-for-e2e-testing)
  - [Additional Resources](#additional-resources)

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

### Setting up Playwright for E2E Testing

```shell
➜  example-angular-playwright-app git:(main) ✗ npm run ng -- e2e

> example-angular-playwright-app@0.0.0 ng
> ng e2e

Cannot find "e2e" target for the specified project.
You can add a package that implements these capabilities.

For example:
  Playwright: ng add playwright-ng-schematics
  Cypress: ng add @cypress/schematic
  Nightwatch: ng add @nightwatch/schematics
  WebdriverIO: ng add @wdio/schematics
  Puppeteer: ng add @puppeteer/ng-schematics

Would you like to add a package with "e2e" capabilities now? Playwright
✔ Determining Package Manager
  › Using package manager: npm
✔ Searching for compatible package version
  › Found compatible package version: playwright-ng-schematics@2.1.1.
✔ Loading package information from registry
✔ Confirming installation
✔ Installing package
✔ Install Playwright browsers (can be done manually via 'npx playwright install')? Yes
    Adding @playwright/test 1.56.1
CREATE playwright.config.ts (1933 bytes)
CREATE e2e/example.spec.ts (208 bytes)
CREATE e2e/tsconfig.json (64 bytes)
UPDATE angular.json (3074 bytes)
UPDATE package.json (1250 bytes)
UPDATE .gitignore (673 bytes)
✔ Packages installed successfully.
    Installing browsers...
```

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

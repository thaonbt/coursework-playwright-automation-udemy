"# Udemy_PlaywrightJavaScript-RahulShetty"
written by JavaScript on Visual Studio Code IDE

## Download and Install [Node.js](https://nodejs.org/en/download)

## Create a new project with Package.json

1. Create a project folder, example `"PlaywrightAutomation"`
   example: `mkdir PlaywrightAutomation`
2. Go to the created folder
   example: `cd PlaywrightAutomation`

## Install Playwright

3. Create the Playwright project by running this command
   `npm init playwright`
4. Folder `"node_modules"` is automatically created, which includes all Playwright library dependencies

## Inside the Playwright project's directory, several commands can be run

* `npx playwright test`
  Runs the end-to-end tests.
* `npx playwright test --ui`
  Starts the interactive UI mode.
* `npx playwright test --project=chromium`
  Runs the tests only on Desktop Chrome.
* `npx playwright test example`
  Runs the tests in a specific file.
* `npx playwright test --debug`
  Runs the tests in debug mode.
* `npx playwright codegen`
  Auto generate tests with Codegen.

We suggest that you begin by typing:

`npx playwright test`

And, this for open the last HTML report run:

`npx playwright show-report`

And check out the following files:

- ./tests/example.spec.js - Example end-to-end test
- ./tests-examples/demo-todo-app.spec.js - Demo Todo App end-to-end tests
- ./playwright.config.js - Playwright Test configuration

Visit https://playwright.dev/docs/intro for more information. ✨

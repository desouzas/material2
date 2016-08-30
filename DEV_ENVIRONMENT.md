# Developer guide: getting your environment set up

1. Make sure you have `node` installed with a version at _least_ 5.5.0.
2. Fork the `angular/material2` repo.
3. Clone your fork.
   Recommendation: name your git remotes `upstream` for `angular/material2`
   and `<your-username>` for your fork. Also see the [team git shortcuts](https://github.com/angular/material2/wiki/Team-git----bash-shortcuts).
4. From the root of the project, run `npm install`.

To build the project, run `npm run build`.

To bring up a local server on port 4200, run `npm run demo-app`.
This will automatically watch for changes and rebuild.

### Running unit tests

To run unit tests, run `npm test`.

### Running e2e tests

To prepare your environment, you'll need to install protractor and selenium.

```bash
# 1. Install the correct selenium version with webdriver-manager (this comes with protractor):
npm run webdriver-manager update
```

In order to run the tests:

```bash
# 1. Spin up a local server and run tests with:
npm run e2e
```

### Running benchmarks
Not yet implemented.

### Running screenshot diff tests.
Not yet implemented.

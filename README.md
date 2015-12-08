# karma-sauce-example

> An example of using the [Karma](http://karma-runner.github.io/) test runner with [Sauce Labs](https://saucelabs.com)' browser cloud to run JavaScript unit tests.

```bash
git clone https://github.com/saucelabs/karma-sauce-example.git && cd karma-sauce-example
```

Then run the following command to install the Karma command line interface globally and this repo's local node dependencies:

```bash
npm install -g karma-cli && npm install
```

## Running Karma with the [karma-sauce-launcher](https://github.com/karma-runner/karma-sauce-launcher) plugin

```bash
karma start karma.conf-ci.js
```

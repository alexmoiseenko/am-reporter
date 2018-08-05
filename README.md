# testcafe-reporter-am-reporter
[![Build Status](https://travis-ci.org/alexmoiseenko/testcafe-reporter-am-reporter.svg)](https://travis-ci.org/alexmoiseenko/testcafe-reporter-am-reporter)

This is the **am-reporter** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

## Install

```
npm install testcafe-reporter-am-reporter
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter am-reporter
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('am-reporter') // <-
    .run();
```

## Author
Alexey Moiseenko

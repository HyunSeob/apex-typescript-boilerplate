# apex-typescript-boilerplate

A boilerplate for TypeScript, Apex and AWS Lambda

## Getting Started

### Install

First, make sure that [Apex](http://apex.run) is installed.

```
$ curl https://raw.githubusercontent.com/apex/apex/master/install.sh | sh
```

Then, clone this repo.

```
$ git clone https://github.com/HyunSeob/apex-typescript-boilerplate.git
```

And then, install NPM dependencies.

```
$ npm install # or, you can also install via yarn.
```

### Set variables

To use the Apex, you have to set some variables like IAM role or function name.
Check following list for setting.

- project.dev.json
- project.prod.json
- functions/hello/function.dev.json
- functions/hello/function.prod.json

## Disclaimer

MIT Licensed.
Inspired by [Apex example for babel-webpack2](https://github.com/apex/apex/tree/master/_examples/babel-webpack2)

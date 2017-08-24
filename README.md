# sev-commissioning-app

A web application to manage sales commissions the STROMDAO Energy Blockchain.

[![Build Status](https://travis-ci.org/smuemd/sev-commissioning-app.svg?branch=master)](https://travis-ci.org/smuemd/sev-commissioning-app) (https://coveralls.io/repos/github/smuemd/sales-partner-app/badge.svg)](https://coveralls.io/github/smuemd/sales-partner-app)

## Setup

- make sure [node.js](http://nodejs.org) is at version >= `6`
- `npm i spike -g`
- clone this repo down and `cd` into the folder
- run `yarn install ` or `npm install`
- run `spike watch` or `spike compile`

## Testing
Tests are located in `test/**` and are powered by [ava](https://github.com/sindresorhus/ava)
- `yarn install ` or `npm install` to ensure devDeps are installed
- `npm test` to run test suite

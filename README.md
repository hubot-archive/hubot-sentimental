# Hubot Sentimental Adapter

## Description

This Hubot adapter uses the [Sentimental](https://github.com/thinkroth/Sentimental) 
node package to score how positive or negative the spoken words being used in your room are.

## Installation

* Add `hubot-sentimental` as a dependency in your hubot's `package.json`
* Install dependencies with `npm install`
* Run hubot with `bin/hubot`

### Note if running on Heroku

You will need to change the process type from `app` to `web` in the `Procfile`.

## Usage

You will need to set one environment variable to use this adapter.

### Heroku

    % heroku config:add REDISTOGO_URL="URL to your REDIS instance"

### Non-Heroku environment variables

    % export REDISTOGO_URL="URL to your REDIS instance"

You will have to have a REDIS server running and available already for this to work

## Contribute

Just send pull request or file an issue !

## Copyright

Copyright &copy; Jason Solis. See LICENSE for details.


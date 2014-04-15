# Hubot Sentimental Adapter

## Description

This Hubot adapter uses the [Sentimental](https://github.com/thinkroth/Sentimental) 
node package to score how positive or negative the spoken words being used in your room are.
As users speak we will analyze how positive or negative your words are using Sentimental
and keep a running average. You can then ask how everyone is doing by using one of the following commands.

```
Hubot check on jsolis
```
```
Hubot check on everyone
```

See [`src/sentimental.coffee`](src/sentimental.coffee) for full documentation.

## Data
[![NPM](https://nodei.co/npm/hubot-sentimental.png?downloads=true&stars=true)](https://nodei.co/npm/hubot-sentimental.png?downloads=true&stars=true)

## Installation

In hubot project repo, run:

`npm install hubot-sentimental --save`

Then add **hubot-sentimental** to your `external-scripts.json`:

```json
["hubot-sentimental"]
```
You will need to set one environment variable to use this adapter.

```
export REDISTOGO_URL=redis://redis-server:redis-port-number
```

## Sample Interaction

```
Hubot> Hubot check on jsolis
Hubot> jsolis has a happiness average of 0.9672131147540983
```

## Contribute

Just send pull request or file an issue !

## Copyright

Copyright &copy; Jason Solis. See LICENSE for details.



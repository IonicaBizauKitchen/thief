# Thief

Thief is a node-friendly port of [Color
Thief](http://lokeshdhakar.com/projects/color-thief/), using
[node-canvas](https://github.com/Automattic/node-canvas) under the hood.

This experimental project is no longer maintained (and has no tests). Check out [get-image-colors](https://www.npmjs.com/package/get-image-colors), which is maintained, has tests, and has no non-node dependencies.

## Install

```
npm install thief --save
```

## Usage

Cairo has a few dependencies. You'll need to run the following to develop
with thief on a Mac:

```
brew install cairo
brew install jpg
```

Check out [rainbowbot](https://github.com/zeke/rainbowbot), an open-source
Node.js web app that uses thief.

<h1 align="center">
  <br />
  <br />
  NoOp
  <br />
  <br />
  <br />
</h1>

<h5 align="center">A small package containing a NoOp and comparison function.</h5>
<p align="center">
  <a href="https://www.npmjs.com/package/@ninetynine/noop">
    <img src="https://badgen.net/npm/v/@ninetynine/noop" />
  </a>
  <a href="https://www.npmjs.com/package/@ninetynine/noop">
    <img src="https://badgen.net/npm/dt/@ninetynine/noop" />
  </a>
  <a href="https://www.npmjs.com/package/@ninetynine/noop">
    <img src="http://img.badgesize.io/https://cdn.jsdelivr.net/npm/@ninetynine/noop@latest/" />
  </a>
</p>

<br />
<br />

### Installation

`noop` can be installed with NPM or Yarn.

```
# Installing with NPM
npm i --save @ninetynine/noop
```

```
# Installing with Yarn
yarn add @ninetynine/noop
```

<hr />

### Usage

`noop` provides two different no operation functions:
 - `noop`
 - `fn`

You can also call `isNoop` to check if a function is `noop`.

```js
// Default export is a NoOp
const noop = require('@ninetynine/noop')

noop()
// > () => null
```

```js
// isNoop compares a function against noop
const { noop, isNoop } = require('@ninetynine/noop')

isNoop(noop)
// > true
```

```js
// fn can be used for less bytes
const { fn, isNoop } = require('@ninetynine/noop')

isNoop(fn)
// > true
```
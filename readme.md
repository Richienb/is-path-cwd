# is-path-cwd [![Build Status](https://travis-ci.org/sindresorhus/is-path-cwd.svg?branch=master)](https://travis-ci.org/sindresorhus/is-path-cwd)

> Check if a path is the [current working directory](https://en.wikipedia.org/wiki/Working_directory)


## Install

```
$ npm install is-path-cwd
```


## Usage

```js
const isPathCwd = require('is-path-cwd');

isPathCwd(process.cwd());
//=> true

isPathCwd('unicorn');
//=> false
```


---

<div align="center">
	<b>
		<a href="https://tidelift.com/subscription/pkg/npm-is-path-cwd?utm_source=npm-is-path-cwd&utm_medium=referral&utm_campaign=readme">Get professional support for this package with a Tidelift subscription</a>
	</b>
	<br>
	<sub>
		Tidelift helps make open source sustainable for maintainers while giving companies<br>assurances about security, maintenance, and licensing for their dependencies.
	</sub>
</div>

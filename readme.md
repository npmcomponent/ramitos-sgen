*This repository is a mirror of the [component](http://component.io) module [ramitos/sgen](http://github.com/ramitos/sgen). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-sgen`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# sgen

string generator

## installation

#### [component/component](https://github.com/component/component)

```bash
$ component install [--dev] ramitos/sgen
```

#### npm

```bash
$ npm install [--save/--save-dev] sgen
```

## example

```js
var sgen = require('sgen');

sgen.timestamp();
sgen.random();

sgen.timestamp(new Date(2012, 1, 1).getTime());
sgen.random(12);
```

## license

MIT
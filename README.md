## cypasslock

[![Build Status](https://camo.githubusercontent.com/ae5c26794bd2361513919f6e0c2bf368b5ac0ca1af9b2614d02358ccfa6f0e55/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f657870726573732e737667)](https://www.npmjs.com/package/cypasslock)

cypasslock is a library made to make password security validation easier and keep users safe from brute-force hacking

# installation

Before installing, download and install [Node.js](https://nodejs.org/). Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a package.json first with the npm init command.
```bash
npm init
```

Installation is done using the npm install command:

```bash
$ npm -i cypasslock --save
```

In Node.js:

```js
//app.js
import bluepass from 'bluepass';

bluepass.validate(12, "myPassword")
securityLevel = bluepass.securityLevel
```

## Features
* password strength checker
* field comparison

## Docs and Community
* [Documantations](https://pascall-creator.web.app/documentations)
* [Community](https://pascall-creator.web.app/community)
* Visit the [Wiki](https://github.com/pascall-de-creator/cypasslock/wiki).

# Security Issues
If you discover a security vulnerability in cypasslock, please see write a comment on the package version on github.

## License
[MIT](https://choosealicense.com/licenses/mit/)
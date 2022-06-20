# Setifi

[![Build Status](https://setifijs.netlify.app/resources/brand.png)](https://setifijs.netlify.app/src/)

[![Build Status](https://camo.githubusercontent.com/ae5c26794bd2361513919f6e0c2bf368b5ac0ca1af9b2614d02358ccfa6f0e55/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f657870726573732e737667)](https://www.npmjs.com/package/setifi)

setifi is an npm package made to make password security validation easier and keep users safe from brute-force attacks

# installation

Before installing, download and install [Node.js](https://nodejs.org/). Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a package.json first with the npm init command.
```bash
npm init
```

Installation is done using the npm install command:

```bash
npm i setifi --save
```

In Node.js:

```js
//app.js
import setifi from 'setifi';

function validate(){
    var input1 = document.getElementById("ps1").value
    setifi.validate(12, input1)
        console.log(setifi.validateErrorCode)
        console.log(setifi.securityLevel)
}

function compare(){
    var input1 = document.getElementById("ps1").value
    var input2 = document.getElementById("ps2").value
    setifi.compare(input1, input2)
        var msg = setifi.compareMessage
        console.log(msg)
}
document.getElementById("validateBtn").addEventListener("click", validate);
document.getElementById("compareBtn").addEventListener("click", compare);
```

## Features

* password strength checker
* field comparison

## Docs and Community
* [Documantations](https://setifijs.netlify.app/)

# Security Issues
If you discover a security vulnerability in setifi, please see write a comment on the package version on github.

## License
[MIT](https://choosealicense.com/licenses/mit/)

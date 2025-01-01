# Setifi

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

# Security Issues
If you discover a security vulnerability in setifi, please see write a comment on the package version on github.

## License
[MIT](https://choosealicense.com/licenses/mit/)

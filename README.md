# Special Character

[![Build Status](https://travis-ci.org/wuriyanto48/special-char.svg?branch=master)](https://travis-ci.org/wuriyanto48/special-char)

# Why ?
Sometimes you need to add **special character** to your string variable....
 **¼ µ ¿ Ȝ Φ** , hope can fix your problem

# Usage

- Install using NPM

```shell
$ npm install special-char
```

- Very simple, just add to your code

```javascript
const SC = require('special-char');

let str1 = `Its so cold, i think 10${SC.DEGREE_SIGN} now..`;
console.log(str1);
```

- you'll see the following result

```
Its so cold, i think 10° now..
```

- json

```javascript
const SC = require('special-char');

let json = {
  "id": "001",
  "name": "box a",
  "price": `${SC.POUND_SIGN} 10`
};

console.log(JSON.stringify(json));
```

- you'll see the following json result

```
{
  "id":"001",
  "name":"box a",
  "price":"£ 10"
}
```

# Task List

- [x] Basic testing
- [x] Basic example
- [x] Travis CI build
- [ ] Code finish
- [ ] Full Documentation

# How to Contribute
- Fork first
- Clone to your local machine
```shell
$ git clone https://github.com/<your-github-username>/special-char
```

- Install dependencies
```shell
$ npm install
```

- Create a new branch
```shell
$ git checkout -b feature/your-feature-branch
```

- Run test
```shell
$ npm test
```

- Push to your repository
```shell
$ git push -u origin feature/your-feature-branch
```

- Hit the Pull Request

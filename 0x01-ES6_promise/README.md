# 0x01. ES6 Promises

## Description:bulb:

One simply does not use async/await without knowing promises!

- Promises (how, why, and what)
- How to use the `then`, `resolve`, `catch` methods
- How to use every method of the Promise object
- Throw / Try
- The await operator
- How to use an `async` function

---

## Resources:books:

Read or watch:

- [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [JavaScript Promise: An introduction](https://web.dev/promises/)
- [Await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
- [Async](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [Throw / Try](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)

---

## Requirements:hammer:

- Ubuntu 18.04 LTS using NodeJS 12.22.x
- Jest Testing Framework
- ESLint

### Install NodeJS 12.22.x

```console
foo@pop-os:~$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
foo@pop-os:~$ sudo bash nodesource_setup.sh
foo@pop-os:~$ sudo apt install nodejs -y
```

### Check version

```console
foo@pop-os:~$ nodejs -v
v12.22.1
foo@pop-os:~$ npm -v
6.14.12
```

### Install Jest, Babel, and ESLint

```console
foo@pop-os:~$ npm install --save-dev jest
foo@pop-os:~$ npm install --save-dev babel-jest @babel/core @babel/preset-env
foo@pop-os:~$ npm install --save-dev eslint
```


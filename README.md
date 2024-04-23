<div align="center">
  <img src="./assets/logo.png" alt="skyterminal" height="250" />
</div>

<div align="center">
  <a href="https://www.npmjs.com/package/skyterminal">
    <img src="https://badgen.now.sh/npm/v/skyterminal" alt="version" />
  </a>
  <a href="https://www.npmjs.com/package/skyterminal">
    <img src="https://badgen.now.sh/npm/dm/skyterminal" alt="downloads" />
  </a>
  <a href="https://packagephobia.now.sh/result?p=skyterminal">
    <img src="https://packagephobia.now.sh/badge?p=skyterminal" alt="install size" />
  </a>
</div>

<div align="center">The fastest Node.js library for formatting terminal text 💖</div>

# Owner
* Discord: [! Ｄᴇᴠɪʟɪѕʜ ｃʜʀᴏɴɪᴄʟᴇѕ](https://discord.com/users/1083342294951927881)
* GitHub: [Darknessking13](https://github.com/Darknessking13)

## Features

* No dependencies
* Easy to use
* Beginner friendly

## Install
```

$ npm install skyterminal@latest 
$ yarn add skyterminal@latest 
$ pnpm add skyterminal@latest

```


## Usage

```js
//import package
const sky = require('skyterminal');

const test = '${(sky.blue().bgWhite("Hello"))}';
console.log(test);

//or
const { bold, yellow } = require('skyterminal'); //add more color as u want

const test = `${bold(yellow('Hello'))}`;
console.log(test);
```

# Note: All the same colors, backgrounds, and modifiers are available.
# API
 Colors
* sky.black()
* sky.red()
* sky.green()
* sky.yellow() 
* sky.blue()
* sky.magenta()
* sky.cyan()
* sky.white()
* sky.gray()
# Backgrounds
* sky.bgBlack()
* sky.bgRed()
* sky.bgGreen()
* sky.bgYellow()
* sky.bgBlue()
* sky.bgMagenta()
* sky.bgCyan()
* sky.bgWhite()
# Modifiers
* sky.bold()
* sky.dim()
* sky.italic()
* sky.underline()
* sky.inverse()
* sky.hidden()
* sky.strikethrough()

# Compatibility
SkyTerminal is compatible with Node.js version v12 and above.

# License
SkyTerminal is released under the MIT License.

# Conclusion
SkyTerminal is a high-performance Node.js library for formatting terminal text with ANSI colors. It is lightweight, easy to use, and compatible with other terminal libraries. By using SkyTerminal, you can improve the performance and reduce the memory usage of your terminal applications.
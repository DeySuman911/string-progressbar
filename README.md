<div align="center">
  <br />
  <p>
    <a href="https://www.npmjs.com/package/string-progressbar"><img src="https://i.ibb.co/HHXtHf3/string-progressbar.png" width="546" alt="progressbar" /></a>

  </p>
  <br />
  <p>
    <a href="https://discord.gg/tGkbpCD"><img src="https://discord.com/api/guilds/389745592232050688/embed.png" alt="Discord server" /></a> <a href="https://www.npmjs.com/package/string-progressbar"><img src="https://img.shields.io/npm/dt/string-progressbar.svg?maxAge=3600" alt="NPM downloads" /></a>

</p>
</div>

## About

**String Progressbar** is a customizable progress bar generator manily made for discord bots that are made in [Discord.js](https://discord.js.org/) and [Eris](https://abal.moe/Eris/). It generates string so its pretty much usable everywhere.

## Advantages

* Simple
* Lightweight
* Fully customizable

 ## Installation

``` sh
npm install string-progressbar
```

 ## Usage

``` js
const createBar = require('string-progressbar');
// assaign values to total and current
var total = 100;
var current = 50;
// Call the createBar method, first two arguments are mandatory
// size (length of bar) default to 40, line default to '▬' and slider default to 🔘
createBar(total, current, size, line, slider);
// There you go, now you have progress bar and percentage returned in an array as string
```

## Preview

![Progress Bar](https://i.ibb.co/LvpsrFd/fg.png "Progress Bar")

## Links

* [Discord Support](https://discord.gg/tGkbpCD)
* [Npm package](https://www.npmjs.com/package/string-progressbar)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

This project is [MIT](https://github.com/sparker-99/string-progressbar/blob/master/LICENSE) licensed.
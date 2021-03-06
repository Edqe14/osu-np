# Nui

Twitch chat bot made for osu! related stuff

[![License](https://img.shields.io/github/license/Edqe14/NuiBot?style=for-the-badge)](https://github.com/Edqe14/NuiBot/blob/main/LICENSE) [![Issues](https://img.shields.io/github/issues/Edqe14/NuiBot?style=for-the-badge)](https://github.com/Edqe14/osu-np/issues) ![Dependencies](https://img.shields.io/david/Edqe14/NuiBot?style=for-the-badge)  
[![js-semistandard-style](https://raw.githubusercontent.com/standard/semistandard/master/badge.svg)](https://github.com/standard/semistandard)

## Library/Dependencies

 1. [Stream Companion](https://github.com/Piotrekol/StreamCompanion)
 2. [StreamCompanion (node-sc)](https://npmjs.com/package/streamcompanion)
 3. [DotObj](https://github.com/Edqe14/osu-np/blob/main/src/modules/DotObj.js)
 4. [tmi.js](https://npmjs.com/package/tmi.js)
 5. [bancho.js](https://npmjs.com/package/bancho.js)

## Features

 1. Dynamic config load/store
 2. [Dot notation](https://npmjs.com/package/object-path) and common object config scheme
 3. Stream Companion implementation using its built-in WebSocket endpoints
 4. Bancho connection using IRC connection using [bancho.js](https://npmjs.com/package/bancho.js)
 5. Module/external commands
 6. Command type (chat, cli, all)
 7. Map request

## To-do

- ~~Make CONSTRUCTOR object schema to an class (OOP)~~
- Make more commands
- Fix watch config.json stop working when reloading error
- ~~Change text parser to lexure parser~~

## License

**This project is using MIT license © Edqe14**  
[Click here](https://github.com/Edqe14/osu-np/blob/main/LICENSE) to read LICENSE.

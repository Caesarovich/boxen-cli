# boxen-cli [![Build Status](https://travis-ci.org/sindresorhus/boxen-cli.svg?branch=master)](https://travis-ci.org/sindresorhus/boxen-cli)

> Create boxes in the terminal

<img src="https://github.com/sindresorhus/boxen/blob/master/screenshot.png" width="300">


## Install

```
$ npm install --global boxen-cli
```


## Usage

```
$ boxen --help

  Usage
    $ boxen <string>
    $ echo <string> | boxen

  Options
    --border-color  Color of the box border [black|red|green|yellow|blue|magenta|cyan|white|gray]
    --border-style  Style of the box border [single|double|round|single-double|double-single]
                    Can also be specified as the characters to use. See below example.
    --padding       Space between the text and box border
    --margin        Space around the box

  Examples
    $ boxen I ❤ unicorns
    ┌────────────┐
    │I ❤ unicorns│
    └────────────┘

    $ boxen --border-style=double-single …like everyone
    ╒══════════════╕
    │…like everyone│
    ╘══════════════╛

    $ boxen --border-style='1234-|' ASCII ftw!
    1----------2
    |ASCII ftw!|
    3----------4
```


## Related

- [boxen](https://github.com/sindresorhus/boxen) - API for this module


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)

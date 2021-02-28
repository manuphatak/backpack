# @manuphatak/backpack

A quick CLI tool to help hotswap your machine by backing up your local setup.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@manuphatak/backpack.svg)](https://npmjs.org/package/@manuphatak/backpack)
[![CircleCI](https://circleci.com/gh/manuphatak/backpack/tree/master.svg?style=shield)](https://circleci.com/gh/manuphatak/backpack/tree/master)
[![Codecov](https://codecov.io/gh/manuphatak/backpack/branch/master/graph/badge.svg)](https://codecov.io/gh/manuphatak/backpack)
[![Downloads/week](https://img.shields.io/npm/dw/@manuphatak/backpack.svg)](https://npmjs.org/package/@manuphatak/backpack)
[![License](https://img.shields.io/npm/l/@manuphatak/backpack.svg)](https://github.com/manuphatak/backpack/blob/master/package.json)

<!-- toc -->

- [Usage](#usage)
- [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g @manuphatak/backpack
$ backpack COMMAND
running command...
$ backpack (-v|--version|version)
@manuphatak/backpack/0.0.0 darwin-x64 node-v14.15.4
$ backpack --help [COMMAND]
USAGE
  $ backpack COMMAND
...
```

<!-- usagestop -->

# Commands

<!-- commands -->

- [`backpack hello [FILE]`](#backpack-hello-file)
- [`backpack help [COMMAND]`](#backpack-help-command)

## `backpack hello [FILE]`

describe the command here

```
USAGE
  $ backpack hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ backpack hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/manuphatak/backpack/blob/v0.0.0/src/commands/hello.ts)_

## `backpack help [COMMAND]`

display help for backpack

```
USAGE
  $ backpack help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_

<!-- commandsstop -->

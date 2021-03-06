# go-bag

A CLI tool to take your computer setup on the road.

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/go-bag.svg)](https://npmjs.org/package/go-bag)
[![build-test-release](https://github.com/manuphatak/go-bag/actions/workflows/build-test-release.yml/badge.svg)](https://github.com/manuphatak/go-bag/actions/workflows/build-test-release.yml)
[![codecov](https://codecov.io/gh/manuphatak/go-bag/branch/main/graph/badge.svg?token=A9695I83UH)](https://codecov.io/gh/manuphatak/go-bag)
[![Downloads/week](https://img.shields.io/npm/dw/go-bag.svg)](https://npmjs.org/package/go-bag)
[![License](https://img.shields.io/npm/l/go-bag.svg)](https://github.com/manuphatak/go-bag/blob/main/package.json)

<!-- toc -->

- [go-bag](#go-bag)
- [Usage](#usage)
- [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g go-bag
$ backpack COMMAND
running command...
$ backpack (-v|--version|version)
go-bag/0.0.5 darwin-x64 node-v14.15.4
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

_See code: [src/commands/hello.ts](https://github.com/manuphatak/go-bag/blob/v0.0.5/src/commands/hello.ts)_

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

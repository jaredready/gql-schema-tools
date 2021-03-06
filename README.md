gql-schema-tools
================

Tools to work with graphql schemas

![Release](https://github.com/drg-adaptive/gql-schema-tools/workflows/Release/badge.svg?branch=main)
[![Maintainability](https://api.codeclimate.com/v1/badges/ce9273e84d42cd99ae08/maintainability)](https://codeclimate.com/github/drg-adaptive/gql-schema-tools/maintainability)
[![Version](https://img.shields.io/npm/v/gql-schema-tools.svg)](https://npmjs.org/package/gql-schema-tools)
[![Downloads/week](https://img.shields.io/npm/dw/gql-schema-tools.svg)](https://npmjs.org/package/gql-schema-tools)
[![License](https://img.shields.io/npm/l/gql-schema-tools.svg)](https://github.com/drg-adaptive/gql-schema-tools/blob/master/package.json)
[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g gql-schema-tools
$ gql COMMAND
running command...
$ gql (-v|--version|version)
gql-schema-tools/0.0.0 darwin-x64 node-v12.13.1
$ gql --help [COMMAND]
USAGE
  $ gql COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`gql help [COMMAND]`](#gql-help-command)
* [`gql merge FILE`](#gql-merge-file)

## `gql help [COMMAND]`

display help for gql

```
USAGE
  $ gql help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_

## `gql merge FILE`

Merge multiple graphql schema files into a single output

```
USAGE
  $ gql merge FILE

ARGUMENTS
  FILE  Filename to save result

OPTIONS
  -h, --help         show CLI help
  -i, --input=input  [default: **/*.graphql] glob pattern of schema files
  --sort
```

_See code: [src/commands/merge.ts](https://github.com/drg-adaptive/gql-schema-tools/blob/v0.0.0/src/commands/merge.ts)_
<!-- commandsstop -->

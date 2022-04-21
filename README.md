# DVM - Deno Version Manager

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-dvm.svg?label=Release)](https://github.com/zmicro-design/plugin-dvm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-dvm/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-dvm/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-dvm.svg)](https://github.com/zmicro-design/plugin-dvm/issues)


## Installation

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zcorky/zdvm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zcorky/zdvm/master/install | bash
```

## Usage

```markdown
Deno Version Manager (v1.0.0)

Deno Version Manager is a tool for managing multiple Deno versions.

Usage:
  zdvm install <version>   - Install Deno version
  zdvm use <version>       - Use Deno version
  zdvm remove <version>    - Remove Deno version
  zdvm ls                  - List the Deno versions installed
  zdvm ls-remote           - List all Deno versions from remote
  zdvm current             - Show current Deno version
  zdvm exec                - Enter new shell with deno version for tmp
  zdvm help                - Show help

Example:
  zdvm install v1.20.6
  zdvm use v1.20.6
  zdvm remove v1.20.6
  zdvm ls
  zdvm ls-remote
  zdvm current
```

## License
ZMicro Design is released under the [MIT License](./LICENSE).
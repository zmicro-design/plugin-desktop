# DESKTOP - Virtual Machine Manager Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-desktop.svg?label=Release)](https://github.com/zmicro-design/plugin-desktop/tags)
[![Build Status](https://github.com/zmicro-design/plugin-desktop/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-desktop/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-desktop.svg)](https://github.com/zmicro-design/plugin-desktop/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install desktop
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-desktop/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-desktop/master/install | bash
```

## Usage

```markdown
desktop (v0.0.0)

Desktop Application Management Plugin

Usage:
  zmicro desktop install <name>          - Install a desktop app
  zmicro desktop create <name>           - Create a desktop app
  zmicro desktop remove <name>           - Remove a desktop app
  zmicro desktop list <name>             - List all desktop apps
  zmicro desktop info <name>             - Inspect a desktop app
  zmicro desktop help                    - Show help

Example:
  zmicro desktop install vscode
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).

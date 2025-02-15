<p align="center">
  <img src="static/app-icons/icon.png" width="256">
</p>

<div align="center">
  <h1>Multrin</h1>

[![AppVeyor](https://img.shields.io/appveyor/ci/sentialx/multrin.svg?style=flat-square)](https://ci.appveyor.com/project/sentialx/multrin)
[![Downloads](https://img.shields.io/github/downloads/sentialx/multrin/total.svg?style=flat-square)](https://github.com/sentialx/multrin/releases)

Multrin is a ~~cross-platform~~ app built on top of  `Electron`, `React`, `styled-components` and `TypeScript`, that lets you to organize apps in tabs, by just dropping them onto Multrin. It aims to greatly improve your productivity and organization.

Although Multrin long-term plan focuses mainly on integrating it with [Wexond](https://github.com/wexond/wexond) web browser, it is developed as a stand-alone application.

</div>

> NOTE: Multrin works currently only on Windows and macOS. Support for Linux coming soon.

# Features

- Dark theme
- `Ctrl + Tab` keyboard shortcut to change selected tab

### Sponsors

[![Sponsors](https://opencollective.com/multrin/tiers/sponsor.svg?avatarHeight=48)](https://opencollective.com/multrin)

### Backers

[![Backers](https://opencollective.com/multrin/tiers/backer.svg?avatarHeight=48)](https://opencollective.com/multrin)

# Screenshots

![](screenshots/screen1.gif)

# [Roadmap](https://github.com/sentialx/multrin/projects)

# Components

Multrin has some very important components:

- Tabs from [Wexond](https://github.com/wexond/wexond)
- [`node-window-manager`](https://github.com/sentialx/node-window-manager) for managing the docked windows

# Contributing

If you have found any bugs or just want to see some new features in Multrin, feel free to open an issue. I'm open to any suggestions and bug reports would be really helpful for me and appreciated very much. Multrin is in heavy development and some bugs may occur. Also, please don't hesitate to open a pull request. This is really important to me and for the further development of this project.

## Running

Before running Multrin, please ensure you have [`Node.js`](https://nodejs.org/en/) installed on your machine.

When running on Windows, make sure you have build tools installed. You can install them by running as **administrator**:

```bash
$ npm i -g windows-build-tools
```

Firstly, run this command to install all needed dependencies. If you have encountered any problems, please report it. I will try to help as much as I can.

```bash
$ yarn
```

The given command below will run Multrin in the development mode.

```bash
$ yarn dev
```

### Other commands

You can also run other commands, for other tasks like building the app or linting the code, by using the commands described below.

#### Usage:

```bash
$ npm run <command>
```

#### List of available commands:

| Command            | Description                                  |
| ------------------ | -------------------------------------------- |
| `build-production` | Bundles Multrin's source in production mode. |
| `compile-win32`    | Compiles Multrin binaries for Windows.       |
| `compile-darwin`   | Compiles Multrin binaries for macOS.         |
| `electron-rebuild` | Rebuilds all dependencies for `Electron`.    |
| `lint`             | Lints code.                                  |
| `lint-fix`         | Fixes eslint errors if any                   |
| `start`            | Starts Multrin.                              |
| `dev`              | Starts Multrin in the development mode       |

> NOTE: `compile-win32` command will produce publishing errors at the end. Just ignore them.

# Authors

[@sentialx](https://github.com/sentialx)

<a href="https://www.patreon.com/bePatron?u=12270966">
    <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>


# ![LVN UI Editor](https://github.com/ISEATO-JR/Labs-SpeedTest/blob/main/Logo.png)

> GFM  Markdown and WYSIWYG Editor - Productive and Extensible

[![github release version](https://img.shields.io/github/v/release/nhn/tui.editor.svg?include_prereleases)](https://github.com/nhn/tui.editor/releases/latest) [![npm version](https://img.shields.io/npm/v/@toast-ui/editor.svg)](https://www.npmjs.com/package/@toast-ui/editor) [![license](https://img.shields.io/github/license/nhn/tui.editor.svg)](https://github.com/nhn/tui.editor/blob/master/LICENSE) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg)](https://github.com/nhn/tui.editor/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) [![code with hearth by NHN Cloud](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-NHN_Cloud-ff1414.svg)](https://github.com/nhn)


## 📦 Intro
Hay muchas forma de como instalar neovim, en este caso vamos necesitar la version mas reciente de editor asi que tenemos que ir a su sitio oficial y seguir los paso de instalacion
[Oficial stable](https://launchpad.net/~neovim-ppa/+archive/ubuntu/stable)

## 🚩 TAbla de contenido

- [`git`](https://git-scm.com/download/linux) | Software de control de versiones |
- [`make`](https://www.gnu.org/software/make/) | GNU Make es una herramienta que controla la generación de ejecutables y otros archivos |
- [`pip`](https://pypi.org/project/pip/) |  PyPA para instalar paquetes de Python |
- [`Python`](https://www.python.org/) | Python es un lenguaje de programación |
- [`Npm`](https://www.npmjs.com/) |  Gestión de paquetes por defecto para Node.js |
- [`Nodejs`](https://github.com/nodesource/distributions/blob/master/OLD_README.md#debinstall) | Entorno de ejecución de JavaScript multiplataforma |
- [`Rust`](https://www.rust-lang.org/tools/install) | Lenguaje de programacion |

### TOAST UI Editor's Plugins

| Name | Description |
| --- | --- |
| [`@toast-ui/editor-plugin-chart`](https://github.com/nhn/tui.editor/tree/master/plugins/chart) | Plugin to render chart |
| [`@toast-ui/editor-plugin-code-syntax-highlight`](https://github.com/nhn/tui.editor/tree/master/plugins/code-syntax-highlight) | Plugin to highlight code syntax |
| [`@toast-ui/editor-plugin-color-syntax`](https://github.com/nhn/tui.editor/tree/master/plugins/color-syntax) | Plugin to color editing text |
| [`@toast-ui/editor-plugin-table-merged-cell`](https://github.com/nhn/tui.editor/tree/master/plugins/table-merged-cell) | Plugin to merge table columns |
| [`@toast-ui/editor-plugin-uml`](https://github.com/nhn/tui.editor/tree/master/plugins/uml) | Plugin to render UML |

## 🐾 Examples

* [Basic](https://nhn.github.io/tui.editor/latest/tutorial-example01-editor-basic)
* [Viewer](https://nhn.github.io/tui.editor/latest/tutorial-example04-viewer)
* [Using All Plugins](https://nhn.github.io/tui.editor/latest/tutorial-example12-editor-with-all-plugins)
* [Creating the User's Plugin](https://nhn.github.io/tui.editor/latest/tutorial-example13-creating-plugin)
* [Customizing the Toobar Buttons](https://nhn.github.io/tui.editor/latest/tutorial-example15-customizing-toolbar-buttons)
* [Internationalization (i18n)](https://nhn.github.io/tui.editor/latest/tutorial-example16-i18n)

Here are more [examples](https://nhn.github.io/tui.editor/latest/tutorial-example01-editor-basic) and play with TOAST UI Editor!


## 🌏 Browser Support

| <img src="https://user-images.githubusercontent.com/1215767/34348387-a2e64588-ea4d-11e7-8267-a43365103afe.png" alt="Chrome" width="16px" height="16px" /> Chrome | <img src="https://user-images.githubusercontent.com/1215767/34348590-250b3ca2-ea4f-11e7-9efb-da953359321f.png" alt="IE" width="16px" height="16px" /> Internet Explorer | <img src="https://user-images.githubusercontent.com/1215767/34348380-93e77ae8-ea4d-11e7-8696-9a989ddbbbf5.png" alt="Edge" width="16px" height="16px" /> Edge | <img src="https://user-images.githubusercontent.com/1215767/34348394-a981f892-ea4d-11e7-9156-d128d58386b9.png" alt="Safari" width="16px" height="16px" /> Safari | <img src="https://user-images.githubusercontent.com/1215767/34348383-9e7ed492-ea4d-11e7-910c-03b39d52f496.png" alt="Firefox" width="16px" height="16px" /> Firefox |
| :---------: | :---------: | :---------: | :---------: | :---------: |
| Yes | 11+ | Yes | Yes | Yes |


## 🔧 Pull Request Steps

TOAST UI products are open source, so you can create a pull request(PR) after you fix issues. Run npm scripts and develop yourself with the following process.

### Setup

Fork `main` branch into your personal repository. Clone it to local computer. Install node modules. Before starting development, you should check if there are any errors.

```sh
$ git clone https://github.com/{your-personal-repo}/tui.editor.git
$ npm install
$ npm run build toastmark
$ npm run test editor
```

> TOAST UI Editor uses [npm workspace](https://docs.npmjs.com/cli/v7/using-npm/workspaces/), so you need to set the environment based on [npm7](https://github.blog/2021-02-02-npm-7-is-now-generally-available/). If subversion is used, dependencies must be installed by moving direct paths per package.

### Develop

You can see your code reflected as soon as you save the code by running a server. Don't miss adding test cases and then make green rights.

#### Run snowpack-dev-server
[snowpack](https://www.snowpack.dev/) allows you to run a development server without bundling.

``` sh
$ npm run serve editor
```

#### Run webpack-dev-server
If testing of legacy browsers is required, the development server can still be run using a [webpack](https://webpack.js.org/).

``` sh
$ npm run serve:ie editor
```

#### Run test

``` sh
$ npm test editor
```

### Pull Request

Before uploading your PR, run test one last time to check if there are any errors. If it has no errors, commit and then push it!

For more information on PR's steps, please see links in the Contributing section.

## 💬 Contributing

* [Code of Conduct](https://github.com/nhn/tui.editor/blob/master/CODE_OF_CONDUCT.md)
* [Contributing Guideline](https://github.com/nhn/tui.editor/blob/master/CONTRIBUTING.md)
* [Commit Convention](https://github.com/nhn/tui.editor/blob/master/docs/COMMIT_MESSAGE_CONVENTION.md)
* [Issue Guidelines](https://github.com/nhn/tui.editor/tree/master/.github/ISSUE_TEMPLATE)


## 🍞 TOAST UI Family

- [TOAST UI Calendar](https://github.com/nhn/tui.calendar)
- [TOAST UI Chart](https://github.com/nhn/tui.chart)
- [TOAST UI Grid](https://github.com/nhn/tui.grid)
- [TOAST UI Image Editor](https://github.com/nhn/tui.image-editor)
- [TOAST UI Components](https://github.com/nhn)


## 🚀 Used By

* [NHN Dooray! - Collaboration Service (Project, Messenger, Mail, Calendar, Drive, Wiki, Contacts)](https://dooray.com)
* [UNOTES - Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=ryanmcalister.Unotes)


## 📜 License

This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) © [NHN Cloud](https://github.com/nhn).


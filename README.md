# Conqueror Helpers

Conqueror Helpers is a helper package for easier development.

> [!TIP]
> Nice addition for [Conqueror](https://github.com/Conqueror-Site-Builder/conqueror),
<!-- > [Styler](https://github.com/Conqueror-Site-Builder/styler), -->
> and [Conqueror Repo Template](https://github.com/Conqueror-Site-Builder/conqueror-repo-template)!

> [!WARNING]
> This repository contains configuration and snippets for **vscode only**,
> if you want configuration and snippet files to be added for your IDE
> or code editor please create an [**issue**](https://github.com/Conqueror-Site-Builder/conqueror-helpers/issues/new/choose)
> or **Pull Request** with the new files.

## Visual Studio Code

The following files are located in the **.vscode/** folder:

-   [`extensions.json`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/extensions.json) -
    recommended extensions for **vscode**.

-   [`settings.json`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/settings.json) -
    settings file for **vscode**, here we have emphasized
    minimalism and easy work with **git**.

-   [`json.code-snippets`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/json.code-snippets).

-   [`javascript.code-snippets`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/javascript.code-snippets).

-   [`jade.code-snippets`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/jade.code-snippets).

-   [`scss.code-snippets`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/.vscode/scss.code-snippets).

    <!-- > If you are going to use snippets of scss functions or mixins then
    > you need to install the [Styler](https://github.com/Conqueror-Site-Builder/styler) Library. -->

## Bash

In the **bash/** folder there is a [`.minttyrc`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/bash/.minttyrc)
file, it allows you to create themes for the **bash** console, the default
is the **GitHub theme**.

## Git

The following files are located in the **git** folder:

-   [`.gitconfig`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/git/.gitconfig) -
    here the emphasis is on formatting the output and convenient
    work with **submodules**.

-   [`.gitignore_global`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/git/.gitignore_global) -
    a file that contains all files and folders that should not
    be included in the project.

-   [`.gitmessage.txt`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/git/.gitmessage.txt) -
    the message that will be displayed when you commit changes.

## NPM

In the **npm/** folder is a [`.npmrc`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/npm/.npmrc)
file with the following options:

-   `fetch-retry-mintimeout=20000` and `fetch-retry-maxtimeout=120000`-
    fix for slow internet.

-   `loglevel=error` - outputs only errors.

-   `node-options=--no-deprecation` - does not show deprecation messages.

-   `save-exact=true` - saves information about the exact version of the package.

## GitHub Rulesets

There are files in the **rulesets/** folder:
-   [`Branch protections.json`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/rulesets/Branch%20protections.json)
-   [`Tag protections.json`](https://github.com/Conqueror-Site-Builder/conqueror-helpers/blob/main/helpers/rulesets/Tag%20protections.json)

## License

This project is licensed under the MIT license - see the
[LICENSE](LICENSE) for details.

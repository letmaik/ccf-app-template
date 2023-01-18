# CCF App Template [![Open in VSCode](https://img.shields.io/static/v1?label=Open+in&message=VSCode&logo=visualstudiocode&color=007ACC&logoColor=007ACC&labelColor=2C2C32)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/letmaik/ccf-app-template)

Template repository for C++ CCF applications.

Note: For complete sample apps, see https://github.com/microsoft/ccf-app-samples. 

## Quickstart

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=590635544)

[![Open in VSCode](https://img.shields.io/static/v1?label=Open+in&message=VSCode&logo=visualstudiocode&color=007ACC&logoColor=007ACC&labelColor=2C2C32)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/letmaik/ccf-app-template)

### Build C++ app

In the checkout of this repository:

```bash
$ cd cpp/
$ mkdir build && cd build
$ CC="/opt/oe_lvi/clang-10" CXX="/opt/oe_lvi/clang++-10" cmake -GNinja ..
$ ninja
```

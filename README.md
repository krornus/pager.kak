# Pager

[![IRC][IRC Badge]][IRC]

###### [Configuration](#configuration) | [Contributing](CONTRIBUTING)

> [Kakoune] extension to use the editor as a pager.

## Features

- [Pager](bin/kak-pager)
- [Manual](bin/kak-man-pager)
- [Git](bin/kak-git-pager)

## Installation

``` sh
ln --symbolic $PWD/bin/* ~/.local/bin/
```

## Configuration

Configure your shell.

``` sh
PAGER=kak-pager
```

``` sh
MANPAGER=kak-man-pager
```

``` sh
GIT_PAGER=kak-git-pager
```

[Kakoune]: http://kakoune.org
[IRC]: https://webchat.freenode.net?channels=kakoune
[IRC Badge]: https://img.shields.io/badge/IRC-%23kakoune-blue.svg

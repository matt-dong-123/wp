# wp

<!--toc:start-->
- [wp](#wp)
  - [Features](#features)
  - [Installation](#installation)
<!--toc:end-->

Improved wifi-password script for **macOS**.

Inspired (and stole some code from) [the original](https://github.com/rauchg/wifi-password).

## Features

- fzf integration
- clipboard integration

## Installation

Use my [dotfiles](https://github.com/matt-dong-123/dotfiles)

OR

Install with your favorite zsh plugin manager

e.g. [zgenom](https://github.com/jandamm/zgenom):

```
zgenom load matt-dong-123/wp
```

to your .zshrc.

OR

Paste

``` sh
curl -L https://raw.githubusercontent.com/matt-dong-123/wp/refs/headr/main/wp -o ~/bin/wp && chmod +x ~/bin/wp
```

into the terminal.

If you don't have `~/bin` in your `$PATH`, replace it with /usr/local/bin or similar.

## Usage

Get current wifi password:

```
wp
```

Get wifi password of network:

```
wp <network>
```

Copy it:

```
wp -c <network>
```

Search a network name to get password:

```
wp -f
```

Copy that:

```
wp -f -c
```

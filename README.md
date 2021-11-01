# Appiconupdate

Simple wrapper script around [fileicon](https://github.com/mklement0/fileicon) to update multiple app icons on macOS with one command.

## Setup

### Prerequisites

[fileicon](https://github.com/mklement0/fileicon) needs to be installed on your system.

```shell
$ brew install fileicon
```

### Installation

```shell
$ curl -sSL https://github.com/jonafll/appiconupdate/releases/download/v0.2.0/appiconupdate.sh > /usr/local/bin/appiconupdate && chmod 755 /usr/local/bin/appiconupdate
```

Create a directory for your app icons and place them in it. Icons work best as .icns or .png files with 512x512 pixels.

```shell
$ mkdir /path/to/icons
```

**IMPORTANT: The name of the icon files must match the application name within `/Applications`!**

```shell
$ ls /path/to/icons
Visual Studio Code.icns     Docker.icns

$ ls /Applications
Visual Studio Code.app      Docker.app
```

## Usage

```shell
$ appiconupdate /path/to/icons
```

Optionally you can set the icon path as environment variable

```shell
export ICN_PATH=/path/to/icons
```

or create an alias.

```shell
alias appiconupdate="appiconupdate /path/to/icons"
```

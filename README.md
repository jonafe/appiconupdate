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
$ curl -sSL https://github.com/jonafe/appiconupdate/releases/download/v0.1.0/appiconupdate.sh > /usr/local/bin/appiconupdate && chmod 755 /usr/local/bin/appiconupdate
```

## Usage
```shell
$ appiconupdate /path/to/icons
```

Optionally you can set the icon path as environment variable.
```shell
export ICN_PATH=/path/to/icons
```
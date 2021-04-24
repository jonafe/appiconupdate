# Appiconupdate

Simple wrapper script around [fileicon](https://github.com/mklement0/fileicon) to update multiple file icons on macOS with one command

## Setup

### Prerequisites
[fileicon](https://github.com/mklement0/fileicon) is installed on your system.

```console
brew install fileicon
```

### Install
```console
curl -sSL https://github.com/jonafe/appiconupdate/releases/download/v0.1.0/appiconupdate.sh > /usr/local/bin/appiconupdate && chmod 755 /usr/local/bin/appiconupdate
```

## Usage
```console
$ appiconupdate /path/to/icons
```

Optionally set the ICN_PATH
```console
export ICN_PATH=/path/to/icons
```
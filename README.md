# Collection of useful MacOS applications

## Prerequisite

* `$ xcode-select --install` to be prepared for Homebrew installation
* install [Homebrew](https://brew.sh/) first

## install all the apps

To automatically install Desktop apps (using either  `brew cask` or `mas` if they are available from MacOS App Store) run.

```bash
$ brew bundle install --file=Brewfile.Desktop
```

For any other area of interest just run

```bash
$ brew bundle install --file=Brewfile.${topic}
```

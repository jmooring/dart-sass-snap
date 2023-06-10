# Snap package for Dart Sass

[![dart-sass](https://snapcraft.io/dart-sass/badge.svg)](https://snapcraft.io/dart-sass)

Dart Sass is the reference implementation of Sass, written in Dart.

Sass is a style sheet language that’s compiled to CSS. It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax. Sass helps keep large style sheets well-organized and makes it easy to share design within and across projects.

Documentation: <https://sass-lang.com>

Project: <https://github.com/sass/dart-sass>

Snap package: <https://snapcraft.io/dart-sass>

## Install and remove

Use the commands below to install or remove:

```text
sudo snap install dart-sass
sudo snap remove dart-sass
```

## Update

Snap packages that you install are automatically updated when a new version is available.

## Usage

To transpile Sass to CSS:

```text
dart-sass in.scss out.css
```

To create an alias from `sass` to `dart-sass`:

```text
sudo snap alias dart-sass sass
```

To remove the alias:

```text
sudo snap unalias sass
```

# Widths-tools

Generates a suite of utility classes for sizing pieces of UI responsively.

## Dependencies

The `widths-tools` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `widths-tools` module  using Bower or npm, you will get these
dependencies at the same time. If not using Bower or npm, please be sure to
install and @import these dependencies in the relevant way.

## Installation

Yo can install `widths-tools` module via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-widths-tools --save
```

Once installed, `@import` into your project in its Tools layer:

```scss
@import "bower_components/tree-widths-tools/tools.widths";
```

### Install using npm:

```sh
$ npm install tree-widths-tools --save
```

### Install as a Git Submodule

```sh
$ git submodule add git@github.com:treeframework/tools.widths.git
```

Once installed `@import` into your project in its Tools layer:

```scss
@import "tools.widths/tools.widths";
```

### Install via file download

The least recommended option for installation is to simply download
`_tools.widths.scss` into your project and `@import` it into your project in its
Tools layer.

## Usage

Basic usage of the `widths-tools` module:

```scss
@include tree-widths(12);
```

generates a series of classes in the format `.u-7/12` to be used for sizing.

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.

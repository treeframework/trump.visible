# Visible

The `visible` module simply hides content.

## Dependencies

The `visible` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `visible` module using Bower, you will get these dependencies
at the same time. If not using Bower, please be sure to install and `@import`
these dependencies in the relevant way.

## Installation

You can install `visible` module via Bower, npm, Git Submodule, or copy and
paste.

### Install using Bower:

```sh
$ bower install tree-visible --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-visible/trump.visible";
```

### Install using npm:

```sh
$ npm install tree-visible --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/trump.visible.git
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "trump.visible/trump.visible";
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.visible.scss` into your project and `@import` it into your project
in its Trump layer.

## Usage

Basic usage of the `visible` module uses the required classes:

```html
<ul class="u-visible">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
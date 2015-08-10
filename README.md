# Visible

The `visible` module simply displays content as block.

## Dependencies

The `visible` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [settings.responsive](https://github.com/treeframework/settings.responsive)
* [tools.responsive](https://github.com/treeframework/tools.responsive)

If you install the `visible` module using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install `visible` module via Bower, npm, or copy and paste.

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

### Install via file download

The least recommended option for installation is to simply download
`_trump.visible.scss` into your project and `@import` it into your project
in its Trump layer.

## Usage

Basic usage of the `visible` module uses the required classes:

```html
<ul class="u-visible">
    <li>...</li>
    <li>...</li>
    <li>...</li>
</ul>
```

## Options

To turn responsive feature on, set switch to true (before you `@import` the file):

```scss
$tree-enable-visible--responsive:    true;
@import "bower_components/tree-visible/trump.visible";
```

For example:

```html
<ul class="u-visible@palm">
    <li>...</li>
    <li>...</li>
    <li>...</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.

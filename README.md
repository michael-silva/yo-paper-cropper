# \<yo-paper-cropper\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/michael-silva/yo-paper-cropper)

An element to wrap Cropper.js

## Example of usage ##
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="yo-paper-cropper.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<yo-paper-cropper src="https://images.pexels.com/photos/843256/pexels-photo-843256.jpeg?w=940&h=650&auto=compress&cs=tinysrgb"></yo-paper-cropper>
```

## Options ##

The **options** atrribute receive an object with all options allowed by Cropper.js.
View all options at [Cropper.js](https://github.com/fengyuanchen/cropperjs/blob/master/README.md#options) repoository

## Events ##

### image-loaded ###
Triggered when image is loaded

### cropper-ready ###
Triggered after image is loaded and when cropperjs is rendered

## For developers ##

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

### Viewing Your Element

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

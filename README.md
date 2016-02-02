# Slinky+

[jQuery sliding menu](https://github.com/alizahid/slinky/)を少し改良したver。

オプション'label'に'parent'を追加し、labelに現在の階層が表示できるよう機能を追加。

[Demo](http://konweb.github.io/slinky/)

### Installation

Download the [latest version](https://github.com/konweb/slinky/archive/master.zip). The files you need are;

- assets/js/jquery.slinky.js
- assets/css/jquery.slinky.css

### Usage

    $('.menu').slinky(options);

### Options

Option | Default value | Description
------ | ------------- | -----------
`label` | 'Back \| 'parent' | Label for the back button. Set to `true` to use the link's own label
`speed` | `300` | Animation speed in milliseconds
`resize` | `true` | Resize menu height to match content

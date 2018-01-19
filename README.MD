# Hp Button

[![Travis CI Status](https://travis-ci.org/LarissaAbreu/hp-button.svg?branch=master)](https://travis-ci.org/LarissaAbreu/hp-button)

## How to install and use:

1 - Install the element using [Bower](https://bower.io/)

```sh
$ bower install vsc-fab-button --save
```

2 -  Importing the element:

```html
<link rel="import" href="bower_components/vsc-fab-button/vsc-fab-button.html">
```

3 - Start using it:

```html
<hp-button></hp-button>
```

## Properties

Property    | Type      | Default | Description
:---        |:---       |:---     |:---
`disabled`  | *Boolean* | `false` | Allow disabled state

## Styling

The following custom properties and mixins are available for styling:

Custom property                     | Default                    | Description
:---                                |:---                        |:---
--hp-background                     | #000000                    | Button background color
--hp-margin                         | 5px                        | Button margin
--hp-color                          | #ffffff                    | Button color
--hp-fontsize                       | 20px                       | Font size button
--hp-borderradius                   | 5px                        | Border radius
--hp-boxshadow                      | 3px 3px 5px grey           | Box-shadow button
--hp-background-disabled            | rgba(112, 112, 112, 0.055) | Button disabled background color
--hp-color-disabled                 | #000000                    | Button disabled color
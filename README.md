[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/eduardosada/shop-product-card)

[Demo and API docs](https://eduardosada.github.io/shop-product-card/components/shop-product-card/)

# \<shop-product-card\>

A product item card.

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="shop-product-card.html">
    <style>
    shop-product-card {
      max-width: 200px;
      display:block;
      margin: 30px auto;
      font-family: Arial, Sans-serif;
    }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<shop-product-card
  price="2132.99"
  price-discount="10"
  name="Soft Running"
  image="demo/images/orange-portable-speaker.jpg"
></shop-product-card>
```

## How to install and use:

1 - Install the element using [Bower](http://bower.io/):

```sh
$ bower install eduardosada/shop-product-card --save
```

2 -  Import the element:

```html
<link rel="import" href="../../shop-product-card/shop-product-card.html">
```

3 - Start using it!
```html
<shop-product-card
  price="2132.99"
  price-discount="10"
  name="Soft Running"
  image="products/AF00361GND10R99_a-low_1024x1024.jpg"
></shop-product-card>
```

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Report any [issue](https://github.com/eduardosada/shop-product-card/issues/).
<br>
Want to contribute? [Follow these recommendations](https://github.com/eduardosada/shop-product-card/blob/master/CONTRIBUTING.md).

## History
See [Releases](https://github.com/eduardosada/shop-product-card/releases) for detailed changelog.

## License
[MIT License](https://github.com/eduardosada/shop-product-card/blob/master/LICENSE.md) © [Eduardo Sada](https://github.com/eduardosada/)

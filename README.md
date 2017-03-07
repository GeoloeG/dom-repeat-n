[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/GeoloeG/dom-repeat-n)

# `<dom-repeat-n>`

## Descripton

A template element that repeat `n` times its content.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install dom-repeat-n --save
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/dom-repeat-n/dom-repeat-n.html">
```

And then use it:

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="dom-repeat-n.html">
	  <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<template is="dom-repeat-n" count="3">
  <div>I am div {{index}}</div>
</template>
```

See the [Documentation](https://geoloeg.github.io/dom-repeat-n/) for more options.

## More Demos

[https://geoloeg.github.io/dom-repeat-n/](https://geoloeg.github.io/dom-repeat-n/components/dom-repeat-n/demo/)

## Discussing

If you have any questions, you can find me on the [Polymer Slack Channel](https://polymer.slack.com/), or just raise an Issue.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

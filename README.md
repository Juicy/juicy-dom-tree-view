# &lt;juicy-dom-tree-view&gt; [![Build Status](https://travis-ci.org/Juicy/juicy-dom-tree-view.svg?branch=master)](https://travis-ci.org/Juicy/juicy-dom-tree-view)

> Juicy Polymer Element, that renders a tree view of given Document Fragment

## Demo

[Check it live!](http://Juicy.github.io/juicy-dom-tree-view)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-dom-tree-view --save
```

Or [download as ZIP](https://github.com/Juicy/juicy-dom-tree-view/archive/master.zip).

## Usage

1. Import Web Components' polyfill, if needed:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-dom-tree-view/juicy-dom-tree-view.html">
    ```

3. Start using it!

    ```html
    <juicy-dom-tree-view doc="{{DocumentFragment}}"></juicy-dom-tree-view>
    ```

## Attributes/Properties

Name              | Options            | Default | Description
---               | ---                | ---     | ---
`doc`             | *DocumentFragment* |         | Document Fragment to be rendered
`multiple`        | *Boolean*          | `false` | Should multi select (with ctrl+click) be available
`fake-v1`         | *Boolean*          | `false` | Should we fake Shadow DOM v1 and render `<content>` as `<slot>`
`wrapped-content` | *Boolean*          | `false` | Should we support `<cotnent>` tags wrapped for styling with `<div content-wrapper>` and display it as single `<slot>` for simplicity.


## CSS Custom properties

Name                                         | Description
---                                          | ---
`--juicy-dom-tree-selected-background-color` | Background color of selected element

## Notes
- `juicy-dom-tree-view` is a [hybrid element](https://www.polymer-project.org/2.0/docs/devguide/hybrid-elements).

## [Contributing and Development](CONTRIBUTING.md)

## History

For detailed changelog, check [Releases](https://github.com/Juicy/juicy-dom-tree-view/releases).

## License

MIT

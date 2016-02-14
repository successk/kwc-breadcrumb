# &lt;kwc-breadcrumb&gt;

> Shows a breadcrumb

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install kwc-breadcrumb --save
```

Or [download as ZIP](https://github.com/successk/kwc-breadcrumb/archive/master.zip).

## Usage

1 – Import polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
```

2 – Import custom element:

```html
<link rel="import" href="bower_components/kwc-breadcrumb/kwc-breadcrumb.html">
```

3 – Start using it!

```html
<kwc-breadcrumb>
  <ul>
    <li><a href="...">...</a></li>
  </ul>
</kwc-breadcrumb>
```

## Options

Attribute        | Options                              | Default      | Description
---              | ---                                  | ---          | ---
`header`         | *String*                             | `null`       | The header text
`type`           | *String*, `horizontal` or `vertical` | `horizontal` | How the breadcrumb will be displayed?

## Children

Selector | Description
---      | ---
`*`      | The list of the breadcrumb, use `<ul>` list

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
None          | -            | -           | -

## Events

Event     | Detail   | Description
---       | ---      | ---
none      | -        | -

## Styles

* Both:
* --k-breadcrumb-link-styles (default {}, see --k-breadcrumb-vertical-link-styles, --k-breadcrumb-horizontal-link-styles)
* --k-breadcrumb-link-hover-styles (default {}, see --k-breadcrumb-vertical-link-hover-styles, --k-breadcrumb-horizontal-link-hover-styles)
* --k-breadcrumb-last-link-styles (default {}, see --k-breadcrumb-vertical-last-link-styles, --k-breadcrumb-horizontal-last-link-styles)
* --k-breadcrumb-last-link-hover-styles (default {}, see --k-breadcrumb-vertical-last-link-hover-styles, --k-breadcrumb-horizontal-last-link-hover-styles)

## Vertical breadcrumb only

Name                                             | Default        | Description
---                                              | ---            | --
`--k-breadcrumb-title-styles`                    | `{}`           | Styles of the title (if defined)
`--k-breadcrumb-vertical-link-styles`            | `{}`           | Styles of links
`--k-breadcrumb-vertical-link-hover-styles`      | `{}`           | Styles of link when hover
`--k-breadcrumb-vertical-last-link-styles`       | `{}`           | Styles of last link
`--k-breadcrumb-vertical-last-link-hover-styles` | `{}`           | Styles of last link when hover

## Horizontal breadcrumb only

Name                                               | Default        | Description
---                                                | ---            | --
`--k-breadcrumb-box`                               | `{}`           | Styles of the breadcrumb container
`--k-breadcrumb-separator`                         | `‣`            | Separator of breadcrumb elements
`--k-breadcrumb-horizontal-link-styles`            | `{}`           | Styles of links
`--k-breadcrumb-horizontal-link-hover-styles`      | `{}`           | Styles of link when hover
`--k-breadcrumb-horizontal-last-link-styles`       | `{}`           | Styles of last link
`--k-breadcrumb-horizontal-last-link-hover-styles` | `{}`           | Styles of last link when hover

## Both breadcrumb

Name                                    | Default        | Description
---                                     | ---            | --
`--k-breadcrumb-link-styles`            | `{}`           | Styles of links (can be used with vertical-only and horizontal-only versions)
`--k-breadcrumb-link-hover-styles`      | `{}`           | Styles of link when hover (can be used with vertical-only and horizontal-only versions)
`--k-breadcrumb-last-link-styles`       | `{}`           | Styles of last link (can be used with vertical-only and horizontal-only versions)
`--k-breadcrumb-last-link-hover-styles` | `{}`           | Styles of last link when hover (can be used with vertical-only and horizontal-only versions)

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1 – Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

```sh
$ npm install -g bower polyserve
```

2 – Install local dependencies:

```sh
$ bower install
```

3 – Start development server and open `http://localhost:8080/components/kwc-breadcrumb/`.

```sh
$ polyserve
```

## History

For detailed changelog, check [Releases](https://github.com/successk/kwc-breadcrumb/releases).

## License

MIT
# &lt;twbs-buttons&gt;

The Twitter Bootstrap Buttons Web Component.

## Demo
> [Check it live](http://ifly9.com.br/webcomponents/twbs-buttons/).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install twbs-buttons --save
```

Or [download as ZIP](https://github.com/mvaldetaro/twbs-buttons/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="bower_components/twbs-buttons/src/twbs-buttons.html">
  ```

3. Start using it!

  ```html
<twbs-buttons></twbs-buttons>
  ```

## Options

Attribute  | Options                | Default    | Description
---        | ---                    | ---        | ---
`href`     | *string*               | `#`        | The href attribute specifies the link's destination
`tag`      | `a`, `button`, `input` | `button`   | Define the tag
`type`     | `submit`, `button`     | `12`       | Define the "input" type
`value`    | *string*               | `Hello!`   | Define the "input" value
`size`     | `lg`, `sm`, `xs`       |            | Button's size
`block`    | `block`                | `block`    | Create block level buttons
`state`    | `active`, `disabled`   |            | Button will appear pressed or unclickable

## Browser Support

![IE](https://raw.github.com/paulirish/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/paulirish/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/paulirish/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/paulirish/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/paulirish/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/mvaldetaro/twbs-buttons/releases) list.

## License

[MIT License](http://mvaldetaro.mit-license.org/) © Magno Valdetaro

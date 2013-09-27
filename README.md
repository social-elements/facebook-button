# &lt;facebook-button&gt;

Web Component wrapper for [Facebook's button](https://developers.facebook.com/docs/reference/plugins/like/) using Polymer.

## Demo

![Facebook Element](http://zno.io/Quih/facebook-element.png)

> [Check it live](http://zenorocha.github.io/facebook-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/facebook-button.html">
	```

3. Start using it!

	```xml
	<facebook-button></facebook-button>
	```

## Options

Attribute     | Options             | Default        | Description
---           | ---                 | ---            | ---
`action`      | `like`, `recommend` | `like` | The verb to display in the button
`colorscheme` | `light`, `dark` | `light` | The color scheme for the like button
`font`        | `arial`, `lucida grande`, `segoe ui`, `tahoma`, `trebuchet ms`, `verdana` | `arial` | The font to display in the button
`href`        | *string* | `http://customelements.io` | The URL to like/recommend
`layout`      | `standard`, `button_count`, `box_count` | `button_count` | Determines the size and amount of social context next to the button
`showfaces`   | `true`, `false` | `false` | Specifies whether to display profile photos below the button (standard layout only)
`height`       | *int* | `20` | The height of the button
`width`       | *int* | `120` | The width of the button

> See Facebook's [official documentation](https://developers.facebook.com/docs/reference/plugins/like/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/zenorocha/facebook-button/releases/) list.

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha

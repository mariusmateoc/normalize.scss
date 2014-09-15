# Normalize.scss v3.0.4

_normalize.scss is a customisable SCSS file mixed with some styles from HTML5
boilerplate that makes browsers render all elements more consistently and in
line with modern standards.

The project relies on researching the differences between default browser
styles in order to precisely target only the styles that need or benefit from
normalizing.

You can also find style for browserhappy class which redirect the user to
upgrade his browser if it's older then IE8. Need to add this to your markup:

```html
  <!--[if lt IE 8]>
    <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
  <![endif]-->
```

[View the demo file](http://mariusmateoc.github.io/_normalize.scss/demo/index.html)


## What does it do?

* Easy customizable with variables
* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.


## How I use it?

I keep the _normalize.scss in partials folder then import it before any
other styles.

## Browser support

* Google Chrome (latest)
* Mozilla Firefox (latest)
* Mozilla Firefox 4
* Opera (latest)
* Apple Safari 6+
* Internet Explorer 8+


## Changelog

You can see the [changelog here](https://github.com/necolas/normalize.css/blob/3.0.1/CHANGELOG.md)


## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).

<div><img src="https://raw.githubusercontent.com/SlateCoding/Invisible-Ink/master/logo/so-icon.png" width="100" height="100" style="float:left;" /><h1>Invisible Ink<h1></div>

<br />
<br />

## Hide
Invisible Ink lets hide text (and elements) with just a bit of CSS.

<br />
<br />

## Demo & Playground

You can play with Balloon.css here: [https://codepen.io/slate-coding/pen/qXMNwx](https://codepen.io/slate-coding/pen/qXMNwx)

<br />
<br />

## Usage

### Documentation

**Invisible Text**
Just add the following HTML. This will make the text **white**. As soon as the user hovers over it, the text will appear.

```html
  <ink data-type="sharp-hover">My Invisible Text</ink>
```
 
Or, if you want the text to _fade_ into view, do this instead:

```html
  <ink data-type="ease-in" data-border="solid">Invisible Text That Fades Into View...</ink>
```

**Blurred Text**
Add the following. This will blur the text in all browsers **except in IE and Edge**. When the blurred text is hovered it instantly becomes readable.

```html
<ink data-type="blurred">Blurred Text!!!</ink>
```

If you want the blurred text to _fade_ into view, then:

```html
<ink data-type="blurred ease-in">Yaay I Have Blurred Text</ink>
```

**Redacted Text**
This time, instead of Invisible Text or Blurred Text, we will make the text look as if some one went over the text with a permanent marker.

```html
  <ink data-type="redacted">Permanent Markers Here</ink> 
```

Making it fade into view:

```html
  <ink data-type="redacted">Meeeeooooww Meow Meow</ink> 
```

**Adding a Border to the underside of the Text**
If you want a border under your text (see  the [demo](https://codepen.io/slate-coding/pen/qXMNwx) to see how it would look), then just add `data-border="solid"` to the `ink` element. Like this:

```html
  <ink data-border="solid" data-type="redacted">Meeeeooooww Meow Meow</ink> 
```

```html
<ink data-border="solid" data-type="blurred">Blurred Text!!!</ink>
```

```html
  <ink data-border="solid" data-type="sharp-hover">My Invisible Text</ink>
```


### Installation

**CDN version:**
Simply add this reference to your HTML:

```html
<link rel="stylesheet" href="http://slate-coding.zohosites.com/files/cdn/invisible-ink.min.css" />
```

<br />
<br />

**Manually:**
Simply download `invisible-ink.min.css` from this repository and add it to your HTML. e.g.

```html
<link rel="stylesheet" href="path/to/invisible-ink.min.css">
```

<br />
<br />


### Contributing
To contribute to this project, you must:

1. Fork this repo.
2. Make your changes.
3. Submit a pull request.


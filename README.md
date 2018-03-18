![Logo](https://raw.githubusercontent.com/eligeorgios/InvisiText/master/logo/logo-128.png)
---

InvisiText lets you hide text (and elements) with just a bit of CSS.

## Playground

You can play around with Invisible Ink here: [https://codepen.io/desperate-coding/pen/qXMNwx](https://codepen.io/slate-coding/pen/qXMNwx)

## Usage

### Documentation

**Invisible Text**  
Just add the following HTML. This will make the text **white**. As soon as the user hovers over it, the text will appear.

      <ink data-type="sharp-hover">My Invisible Text</ink>

Or, if you want the text to _fade_ into view, do this instead:

      <ink data-type="ease-in" data-border="solid">Invisible Text That Fades Into View...</ink>

**Blurred Text**  
Add the following. This will blur the text in all browsers **except in IE and Edge**. When the blurred text is hovered it instantly becomes readable.

    <ink data-type="blurred">Blurred Text!!!</ink>

If you want the blurred text to _fade_ into view, then:

    <ink data-type="blurred ease-in">Yaay I Have Blurred Text</ink>

**Redacted Text**  
This time, instead of Invisible Text or Blurred Text, we will make the text look as if some one went over the text with a permanent marker.

      <ink data-type="redacted">Permanent Markers Here</ink> 

Making it fade into view:

      <ink data-type="redacted">Meeeeooooww Meow Meow</ink> 

**Adding a Border to the underside of the Text**  
If you want a border under your text (see the [demo](https://codepen.io/slate-coding/pen/qXMNwx) to see how it would look), then just add `data-border="solid"` to the `ink` element. Like this:

    <ink data-border="solid" data-type="redacted">Meeeeooooww Meow Meow</ink> 


    <ink data-border="solid" data-type="blurred">Blurred Text!!!</ink>


    <ink data-border="solid" data-type="sharp-hover">My Invisible Text</ink>

## Installation

**CDN version:**  
Simply add this reference to your HTML:

    <CDN-COMING-SOON-ON-JSDELIVR/>

**Manually:**  
Simply download `invisible-ink.min.css` from this repository and add it to your HTML. e.g.

    <link rel="stylesheet" href="path/to/invisible-ink.min.css">

## Contributing

To contribute to this project, you must:

1.  Clone this repo.
2.  Make your changes.
3.  Carefully test out your changes in all major browsers (eg. IE, Edge, Chrome, Opera, Firefox, Tor, etc.)
4.  Submit a pull request.


## Notes

Note 1. InvisiText `blurred` does not work on IE or Edge yet.

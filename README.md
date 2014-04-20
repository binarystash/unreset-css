# Unreset.css
Unreset.css restores default element styles which are reset by [Eric Meyer's Reset.css](http://meyerweb.com/eric/tools/css/reset/). Simply add the class `unreset` to the page element whose styles must be restored. Although unreset.css is specifically targeted to undo Eric Meyer's reset styles, it may also be used to undo styles by other reset stylesheets.

Unreset.css is based on [Default style sheet for HTML 4](http://www.w3.org/TR/CSS21/sample.html) and the [official Webkit UA stylesheet](http://trac.webkit.org/browser/trunk/Source/WebCore/css/html.css).

## Installation

Include unreset.css in your page

```html
<link rel="stylesheet" type="text/css" href="css/unreset.css">
```

## Usage

Add the class `unreset` to the elements needing to be unreset.

```html
<div id="content" class="unreset">
  <p>I use the default paragraph style.</p>
  <ul>
    <li>I will have a bullet point.</li>
    <li>I will have a bullet point.</li>
  </ul>
</div>
```

## Compatibility 

Tested on IE8-11, latest versions of Firefox, Chrome and Safari

## Support

Report bugs at https://github.com/binarystash/unreset-css/issues.

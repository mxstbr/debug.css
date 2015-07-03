# `debug.css`

`debug.css` is a tiny stylesheet to help visually identify CSS positioning and sizing issues during development.

## Usage

Simply include a link to the stylesheet in the head of your document, like so:

    <link href="https://rawgithub.com/mxstbr/debug.css/master/debug.css" media="all" rel="stylesheet" type="text/css" />

**Don't forget to remove the link to debug.css once you've finished debugging.**

Alternatively, create a bookmark and copy the following code into the URL field to create a bookmarklet for quick debugging:

    javascript:(function(){var e=document.createElement("link");e.setAttribute("href","https://rawgithub.com/mxstbr/debug.css/master/debug.css");e.setAttribute("rel","stylesheet");e.setAttribute("type","text/css");e.setAttribute("media","all");document.head.appendChild(e)})();
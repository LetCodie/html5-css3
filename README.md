# html5-css3 : 30/May/2017

caniuse.com
html5please.com

## Content models

internationalization attribute : lang
  http://webpageworkshop.co.uk/main/language_codes

Metadata for search engine
  not allow for indexing by search engine clawer
  <meta name="robots" content="noindex,nofollow">

  can be specify, it's not hurt
  <meta name="robots" content="index,follow">

  <meta name="keywords" content="...">
  <meta name="description" content="...">

  <link rel="stylesheet" href="" type="text/css">
  <link rel="icon" src="" type="image/ico">

media attribute

  <link rel="stylesheet" href="..." media="screen">
  <link rel="stylesheet" href="..." media="print">

  <link rel="stylesheet" href="..." media="screen,projection,tv">

  values of media attribute:
    . all: all devices( default )
    . braille: 
    . embrossed: 
    . handheld
    . print:
    . projection:
    . screen:
    . speech :
    . tty: 
    . tv:

    requires attributes : rel, href
    optional attributes : title, type, media, hreflang, sizes

https://github.com/afarkas/html5shiv

Shorthand for font
  body {
    font: 14px/1.5 "Trebuchet MT", sans, Arial;
  }

  -- font-style, font-variant, font-weight, font-size/line-height, font-family;
  h5 {
    font: small-caps italic bold 100% Arial, sans-serif;
  }

shorthand for background

.intro {
  background: #fff url(image.png) 94% 20px no-repeat;
}


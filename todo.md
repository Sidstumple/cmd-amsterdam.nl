# TODO

## Miscellaneous

*   Tip: Apart Profiel / gebruiker in Chrome zonder plugins
*   [Use gzip compression on assets](http://softstribe.com/wordpress/enable-gzip-compression-in-wordpress/)

## HTTP optimisation

### HTTP/1

*   Concatenate
*   Icon fonts
*   Domain Sharding

### HTTP/2

*   Don’t concatenate
*   No icon fonts
*   No Domain Sharding

## Audits

*   [PageSpeed](https://developers.google.com/speed/pagespeed/insights/)
*   [WebPageTest](https://www.webpagetest.org)
*   [Chrome Dev Tools](https://developer.chrome.com/devtools)
*   [Chrome Audits](https://developer.chrome.com/extensions/experimental_devtools_audits)

## Image performance

*   [client hints](http://httpwg.org/http-extensions/client-hints.html)
*   [`srcset`](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) and [`sizes`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#Example_4_Using_the_srcset_and_sizes_attributes)
*   [`<picture>` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)

## Caching

*   [gulp-rev](https://github.com/sindresorhus/gulp-rev)
    — Static asset revisioning by appending content hash to filenames

## Minify

### CSS

*   [clean-css](https://github.com/jakubpawlowicz/clean-css)
    — Fast and efficient CSS optimizer for node.js and the Web

### HTML

*   [html-minifier](https://github.com/kangax/html-minifier)
    — Javascript-based HTML compressor/minifier

### JavaScript

*   [Uglify](https://github.com/mishoo/UglifyJS2)
    — JavaScript parser / mangler / compressor / beautifier toolkit

### Fonts

### Images

*   Downsize images with Adobe PhotoShop, by saving for web
*   SVG images are smaller, although Wordpress does not support this because of security issues. (https://www.bjornjohansen.no/svg-in-wordpress)

# metalsmith-mathjax
Prerender mathjax in metalsmith

## Usage

Just add `mathjax: true` in the gray matter and this plugin will prerender your MathJax as SVG. This cuts down on the Javascript overhead and eliminates the delay one typically sees where the raw TeX renders for a second before MathJax loads.

Of course, you also need to add the plugin to `metalsmith.json`.

This repository was originally created by [Chris Wilson](wilson428) for use on [MechanicalScribe.com](http://mechanicalscribe.com).

## License
[MIT](LICENSE.md)
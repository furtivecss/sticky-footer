# Furtive Sticky Footer

A CSS module for sticky footers using `display: flex;`. Used in [furtive.css](http://furtive.co).

<http://caniuse.com/#search=flex>

## Installation

It's recommended to use [rework-npm](https://github.com/reworkcss/rework-npm):

```
npm install --save furtive-sticky-footer
```

```javascript
var rework = require('rework'),
    reworkNPM = require('rework-npm');

var output = rework('@import "furtive-sticky-footer";', { source: 'my-file.css' })
    .use(reworkNPM());
```

## Usage

Detailed documentation and examples can be found at [furtive.co](http://furtive.co).

## License

MIT

## Acknowledgements

Based off of <http://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/>.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com) ([@4lpine](https://twitter.com/4lpine)).

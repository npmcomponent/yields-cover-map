*This repository is a mirror of the [component](http://component.io) module [yields/cover-map](http://github.com/yields/cover-map). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-cover-map`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# cover-map

  map coverage data from yields/instrument

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/cover-map

## Example

```js
var cov = instrument('my-component');
var obj = map(cov);
// =>
{
  sloc: N,
  hits: N,
  misses: N,
  percent: N,
  mods: [
    {
      instrumented: '...',
      ranges: [...],
      covered: {...},
      uncovered: {...},
      name: 'my-component',
      key: 'my-component/index.js',
      ast: {...},
      hits: N,
      misses: N,
      sloc: N,
      percent: N
    }
  ],
}
```

## License

  MIT

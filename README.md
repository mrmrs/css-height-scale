# css-height-scale 0.0.7

Css module of single purpose classes for height scale

#### Stats

279 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-height-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-height-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-height-scale";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-height-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   HEIGHT SCALE
*/
.ht1 { height: 1rem; }
.ht2 { height: 2rem; }
.ht3 { height: 4rem; }
.ht4 { height: 8rem; }
.ht5 { height: 16rem; }
.ht6 { height: 32rem; }
.ht7 { height: 48rem; }
.ht8 { height: 64rem; }
.ht9 { height: 96rem; }
.ht10 { height: 128rem; }
@media screen and (min-width: 48em) {
 .ht1-ns { height: 1rem; }
 .ht2-ns { height: 2rem; }
 .ht3-ns { height: 4rem; }
 .ht4-ns { height: 8rem; }
 .ht5-ns { height: 16rem; }
 .ht6-ns { height: 32rem; }
 .ht7-ns { height: 48rem; }
 .ht8-ns { height: 64rem; }
 .ht9-ns { height: 96rem; }
 .ht10-ns { height: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ht1-m { height: 1rem; }
 .ht2-m { height: 2rem; }
 .ht3-m { height: 4rem; }
 .ht4-m { height: 8rem; }
 .ht5-m { height: 16rem; }
 .ht6-m { height: 32rem; }
 .ht7-m { height: 48rem; }
 .ht8-m { height: 64rem; }
 .ht9-m { height: 96rem; }
 .ht10-m { height: 128rem; }
}
@media screen and (min-width: 64em) {
 .ht1-l { height: 1rem; }
 .ht2-l { height: 2rem; }
 .ht3-l { height: 4rem; }
 .ht4-l { height: 8rem; }
 .ht5-l { height: 16rem; }
 .ht6-l { height: 32rem; }
 .ht7-l { height: 48rem; }
 .ht8-l { height: 64rem; }
 .ht9-l { height: 96rem; }
 .ht10-l { height: 128rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

# CSS HEIGHT SCALE

  Mobile-first classes for css-height-scale.
  Set the desired css-height-scale on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-height-scale
```
View on [npm](https://www.npmjs.org/package/css-height-scale)


## File Size

1.3K height-scale.css
916B height-scale.min.css

## The Code
```
.ht1   { height: 1rem; }
.ht2   { height: 2rem; }
.ht3   { height: 4rem; }
.ht4   { height: 8rem; }
.ht5   { height: 16rem; }
.ht6   { height: 32rem; }
.ht7   { height: 48rem; }
.ht8   { height: 64rem; }
.ht9   { height: 96rem; }
.ht10  { height: 128rem; }

@media screen and (min-width: 48em) {
  .ht1-ns   { height: 1rem; }
  .ht2-ns   { height: 2rem; }
  .ht3-ns   { height: 4rem; }
  .ht4-ns   { height: 8rem; }
  .ht5-ns   { height: 16rem; }
  .ht6-ns   { height: 32rem; }
  .ht7-ns   { height: 48rem; }
  .ht8-ns   { height: 64rem; }
  .ht9-ns   { height: 96rem; }
  .ht10-ns  { height: 128rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ht1-m   { height: 1rem; }
  .ht2-m   { height: 2rem; }
  .ht3-m   { height: 4rem; }
  .ht4-m   { height: 8rem; }
  .ht5-m   { height: 16rem; }
  .ht6-m   { height: 32rem; }
  .ht7-m   { height: 48rem; }
  .ht8-m   { height: 64rem; }
  .ht9-m   { height: 96rem; }
  .ht10-m  { height: 128rem; }
}

@media screen and (min-width: 64em)  {
  .ht1-l   { height: 1rem; }
  .ht2-l   { height: 2rem; }
  .ht3-l   { height: 4rem; }
  .ht4-l   { height: 8rem; }
  .ht5-l   { height: 16rem; }
  .ht6-l   { height: 32rem; }
  .ht7-l   { height: 48rem; }
  .ht8-l   { height: 64rem; }
  .ht9-l   { height: 96rem; }
  .ht10-l  { height: 128rem; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


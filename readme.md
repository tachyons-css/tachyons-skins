# tachyons-skins 3.1.6

Performance based css module.

#### Stats

884 | 107 | 107
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-skins
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-skins
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-skins";
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
<link rel="stylesheet" href="path/to/module/css/tachyons-skins">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   COLOR VARIABLES

   Variables to set colors for
   color, background-color, and border-color

*/
/* variables */
/*

   SKINS

*/
/* Text colors */
.black-90 { color: rgba( 0, 0, 0, .9 ); }
.black-80 { color: rgba( 0, 0, 0, .8 ); }
.black-70 { color: rgba( 0, 0, 0, .7 ); }
.black-60 { color: rgba( 0, 0, 0, .6 ); }
.black-50 { color: rgba( 0, 0, 0, .5 ); }
.black-40 { color: rgba( 0, 0, 0, .4 ); }
.black-30 { color: rgba( 0, 0, 0, .3 ); }
.black-20 { color: rgba( 0, 0, 0, .2 ); }
.black-10 { color: rgba( 0, 0, 0, .1 ); }
.black-05 { color: rgba( 0, 0, 0, .05 ); }
.bg-black-90 { background-color: rgba( 0, 0, 0, .9 ); }
.bg-black-80 { background-color: rgba( 0, 0, 0, .8 ); }
.bg-black-70 { background-color: rgba( 0, 0, 0, .7 ); }
.bg-black-60 { background-color: rgba( 0, 0, 0, .6 ); }
.bg-black-50 { background-color: rgba( 0, 0, 0, .5 ); }
.bg-black-40 { background-color: rgba( 0, 0, 0, .4 ); }
.bg-black-30 { background-color: rgba( 0, 0, 0, .3 ); }
.bg-black-20 { background-color: rgba( 0, 0, 0, .2 ); }
.bg-black-10 { background-color: rgba( 0, 0, 0, .1 ); }
.bg-black-05 { background-color: rgba( 0, 0, 0, .05 ); }
.white-90 { color: rgba( 255, 255, 255, .9 ); }
.white-80 { color: rgba( 255, 255, 255, .8 ); }
.white-70 { color: rgba( 255, 255, 255, .7 ); }
.white-60 { color: rgba( 255, 255, 255, .6 ); }
.white-50 { color: rgba( 255, 255, 255, .5 ); }
.white-40 { color: rgba( 255, 255, 255, .4 ); }
.white-30 { color: rgba( 255, 255, 255, .3 ); }
.white-20 { color: rgba( 255, 255, 255, .2 ); }
.white-10 { color: rgba( 255, 255, 255, .1 ); }
.bg-white-90 { background-color: rgba( 255, 255, 255, .9 ); }
.bg-white-80 { background-color: rgba( 255, 255, 255, .8 ); }
.bg-white-70 { background-color: rgba( 255, 255, 255, .7 ); }
.bg-white-60 { background-color: rgba( 255, 255, 255, .6 ); }
.bg-white-50 { background-color: rgba( 255, 255, 255, .5 ); }
.bg-white-40 { background-color: rgba( 255, 255, 255, .4 ); }
.bg-white-30 { background-color: rgba( 255, 255, 255, .3 ); }
.bg-white-20 { background-color: rgba( 255, 255, 255, .2 ); }
.bg-white-10 { background-color: rgba( 255, 255, 255, .1 ); }
.black { color: #000; }
.near-black { color: #111; }
.dark-gray { color: #333; }
.mid-gray { color: #555; }
.gray { color: #777; }
.silver { color: #999; }
.light-silver { color: #aaa; }
.moon-gray { color: #ccc; }
.light-gray { color: #eee; }
.near-white { color: #f4f4f4; }
.white { color: #fff; }
/* Background colors */
.bg-black { background-color: #000; }
.bg-near-black { background-color: #111; }
.bg-dark-gray { background-color: #333; }
.bg-mid-gray { background-color: #555; }
.bg-gray { background-color: #777; }
.bg-silver { background-color: #999; }
.bg-light-silver { background-color: #aaa; }
.bg-moon-gray { background-color: #ccc; }
.bg-light-gray { background-color: #eee; }
.bg-near-white { background-color: #f4f4f4; }
.bg-white { background-color: #fff; }
.bg-transparent { background-color: transparent; }
/* Skins for specific pseudoclasses */
.focus-black:focus { color: #000; }
.focus-near-black:focus { color: #111; }
.focus-dark-gray:focus { color: #333; }
.focus-mid-gray:focus { color: #555; }
.focus-gray:focus { color: #777; }
.focus-silver:focus { color: #999; }
.focus-light-silver:focus { color: #aaa; }
.focus-moon-gray:focus { color: #ccc; }
.focus-light-gray:focus { color: #eee; }
.focus-near-white:focus { color: #f4f4f4; }
.focus-white:focus { color: #fff; }
.bg-focus-black:focus { background-color: #000; }
.bg-focus-near-black:focus { background-color: #111; }
.bg-focus-dark-gray:focus { background-color: #333; }
.bg-focus-mid-gray:focus { background-color: #555; }
.bg-focus-gray:focus { background-color: #777; }
.bg-focus-silver:focus { background-color: #999; }
.bg-focus-light-silver:focus { background-color: #aaa; }
.bg-focus-moon-gray:focus { background-color: #ccc; }
.bg-focus-light-gray:focus { background-color: #eee; }
.bg-focus-near-white:focus { background-color: #f4f4f4; }
.bg-focus-white:focus { background-color: #fff; }
.bg-focus-transparent:focus { background-color: transparent; }
.hover-black:hover { color: #000; }
.hover-near-black:hover { color: #111; }
.hover-dark-gray:hover { color: #333; }
.hover-mid-gray:hover { color: #555; }
.hover-gray:hover { color: #777; }
.hover-silver:hover { color: #999; }
.hover-light-silver:hover { color: #aaa; }
.hover-moon-gray:hover { color: #ccc; }
.hover-light-gray:hover { color: #eee; }
.hover-near-white:hover { color: #f4f4f4; }
.hover-white:hover { color: #fff; }
.bg-hover-black:hover { background-color: #000; }
.bg-hover-near-black:hover { background-color: #111; }
.bg-hover-dark-gray:hover { background-color: #333; }
.bg-hover-mid-gray:hover { background-color: #555; }
.bg-hover-gray:hover { background-color: #777; }
.bg-hover-silver:hover { background-color: #999; }
.bg-hover-light-silver:hover { background-color: #aaa; }
.bg-hover-moon-gray:hover { background-color: #ccc; }
.bg-hover-light-gray:hover { background-color: #eee; }
.bg-hover-near-white:hover { background-color: #f4f4f4; }
.bg-hover-white:hover { background-color: #fff; }
.bg-hover-transparent:hover { background-color: transparent; }
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

MIT


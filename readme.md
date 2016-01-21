# tachyons-skins 1.1.0

Performance based css module.

#### Stats

2369 | 344 | 344
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
.black-100 { color: rgba( 0, 0, 0, 1 ); }
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
.bg-black-100 { background-color: rgba( 0, 0, 0, 1 ); }
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
.white-100 { color: rgba( 255, 255, 255, 1 ); }
.white-90 { color: rgba( 255, 255, 255, .9 ); }
.white-80 { color: rgba( 255, 255, 255, .8 ); }
.white-70 { color: rgba( 255, 255, 255, .7 ); }
.white-60 { color: rgba( 255, 255, 255, .6 ); }
.white-50 { color: rgba( 255, 255, 255, .5 ); }
.white-40 { color: rgba( 255, 255, 255, .4 ); }
.white-30 { color: rgba( 255, 255, 255, .3 ); }
.white-20 { color: rgba( 255, 255, 255, .2 ); }
.white-10 { color: rgba( 255, 255, 255, .1 ); }
.bg-white-100 { background-color: rgba( 255, 255, 255, 1 ); }
.bg-white-90 { background-color: rgba( 255, 255, 255, .9 ); }
.bg-white-80 { background-color: rgba( 255, 255, 255, .8 ); }
.bg-white-70 { background-color: rgba( 255, 255, 255, .7 ); }
.bg-white-60 { background-color: rgba( 255, 255, 255, .6 ); }
.bg-white-50 { background-color: rgba( 255, 255, 255, .5 ); }
.bg-white-40 { background-color: rgba( 255, 255, 255, .4 ); }
.bg-white-30 { background-color: rgba( 255, 255, 255, .3 ); }
.bg-white-20 { background-color: rgba( 255, 255, 255, .2 ); }
.bg-white-10 { background-color: rgba( 255, 255, 255, .1 ); }
.black { color: #111; }
.dark-gray { color: #333; }
.mid-gray { color: #555; }
.gray { color: #777; }
.silver { color: #999; }
.light-silver { color: #aaa; }
.light-gray { color: #eee; }
.near-white { color: #f4f4f4; }
.white { color: #fff; }
.blue { color: #0074D9; }
.light-blue { color: #64a8ff; }
.lightest-blue { color: #a2dfff; }
.dark-blue { color: #0045a1; }
.darkest-blue { color: #002f86; }
.yellow { color: #fff93c; }
.light-yellow { color: #fffa60; }
.lightest-yellow { color: #fffca6; }
.dark-yellow { color: #e2c100; }
.darkest-yellow { color: #c4a600; }
.orange { color: #FF851B; }
.light-orange { color: #ffa942; }
.lightest-orange { color: #ffc55d; }
.dark-orange { color: #d05e00; }
.darkest-orange { color: #b14400; }
.red { color: #d82c2c; }
.light-red { color: #f94f44; }
.lightest-red { color: #ff6c5c; }
.dark-red { color: #bd001a; }
.darkest-red { color: #9d0003; }
.teal { color: #27bfa8; }
.light-teal { color: #4eddc5; }
.lightest-teal { color: #6ffae0; }
.dark-teal { color: #25a28f; }
.darkest-teal { color: #008876; }
.green { color: #3D9970; }
.light-green { color: #5ab48a; }
.lightest-green { color: #75d0a4; }
.dark-green { color: #1e7f58; }
.darkest-green { color: #006540; }
.pink { color: #F012BE; }
.light-pink { color: #ff57e8; }
.lightest-pink { color: #ff81ff; }
.dark-pink { color: #d100a3; }
.darkest-pink { color: #b20088; }
.purple { color: #980bc6; }
.light-purple { color: #b536e2; }
.lightest-purple { color: #d355ff; }
.dark-purple { color: #7b00a9; }
.darkest-purple { color: #5f008e; }
/* Background colors */
.bg-black { background-color: #111; }
.bg-dark-gray { background-color: #333; }
.bg-mid-gray { background-color: #555; }
.bg-gray { background-color: #777; }
.bg-silver { background-color: #999; }
.bg-light-silver { background-color: #aaa; }
.bg-light-gray { background-color: #eee; }
.bg-near-white { background-color: #f4f4f4; }
.bg-white { background-color: #fff; }
.bg-blue { background-color: #0074D9; }
.bg-light-blue { background-color: #64a8ff; }
.bg-lightest-blue { background-color: #a2dfff; }
.bg-dark-blue { background-color: #0045a1; }
.bg-darkest-blue { background-color: #002f86; }
.bg-yellow { background-color: #fff93c; }
.bg-light-yellow { background-color: #fffa60; }
.bg-lightest-yellow { background-color: #fffca6; }
.bg-dark-yellow { background-color: #e2c100; }
.bg-darkest-yellow { background-color: #c4a600; }
.bg-orange { background-color: #FF851B; }
.bg-light-orange { background-color: #ffa942; }
.bg-lightest-orange { background-color: #ffc55d; }
.bg-dark-orange { background-color: #d05e00; }
.bg-darkest-orange { background-color: #b14400; }
.bg-red { background-color: #d82c2c; }
.bg-light-red { background-color: #f94f44; }
.bg-lightest-red { background-color: #ff6c5c; }
.bg-dark-red { background-color: #bd001a; }
.bg-darkest-red { background-color: #9d0003; }
.bg-teal { background-color: #27bfa8; }
.bg-light-teal { background-color: #4eddc5; }
.bg-lightest-teal { background-color: #6ffae0; }
.bg-dark-teal { background-color: #25a28f; }
.bg-darkest-teal { background-color: #008876; }
.bg-green { background-color: #3D9970; }
.bg-light-green { background-color: #5ab48a; }
.bg-lightest-green { background-color: #75d0a4; }
.bg-dark-green { background-color: #1e7f58; }
.bg-darkest-green { background-color: #006540; }
.bg-pink { background-color: #F012BE; }
.bg-light-pink { background-color: #ff57e8; }
.bg-lightest-pink { background-color: #ff81ff; }
.bg-dark-pink { background-color: #d100a3; }
.bg-darkest-pink { background-color: #b20088; }
.bg-purple { background-color: #980bc6; }
.bg-light-purple { background-color: #b536e2; }
.bg-lightest-purple { background-color: #d355ff; }
.bg-dark-purple { background-color: #7b00a9; }
.bg-darkest-purple { background-color: #5f008e; }
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
.focus-blue:focus { color: #0074D9; }
.focus-light-blue:focus { color: #64a8ff; }
.focus-lightest-blue:focus { color: #a2dfff; }
.focus-dark-blue:focus { color: #0045a1; }
.focus-darkest-blue:focus { color: #002f86; }
.focus-yellow:focus { color: #fff93c; }
.focus-light-yellow:focus { color: #fffa60; }
.focus-lightest-yellow:focus { color: #fffca6; }
.focus-dark-yellow:focus { color: #e2c100; }
.focus-darkest-yellow:focus { color: #c4a600; }
.focus-orange:focus { color: #FF851B; }
.focus-light-orange:focus { color: #ffa942; }
.focus-lightest-orange:focus { color: #ffc55d; }
.focus-dark-orange:focus { color: #d05e00; }
.focus-darkest-orange:focus { color: #b14400; }
.focus-red:focus { color: #d82c2c; }
.focus-light-red:focus { color: #f94f44; }
.focus-lightest-red:focus { color: #ff6c5c; }
.focus-dark-red:focus { color: #bd001a; }
.focus-darkest-red:focus { color: #9d0003; }
.focus-teal:focus { color: #27bfa8; }
.focus-light-teal:focus { color: #4eddc5; }
.focus-lightest-teal:focus { color: #6ffae0; }
.focus-dark-teal:focus { color: #25a28f; }
.focus-darkest-teal:focus { color: #008876; }
.focus-green:focus { color: #3D9970; }
.focus-light-green:focus { color: #5ab48a; }
.focus-lightest-green:focus { color: #75d0a4; }
.focus-dark-green:focus { color: #1e7f58; }
.focus-darkest-green:focus { color: #006540; }
.focus-pink:focus { color: #F012BE; }
.focus-light-pink:focus { color: #ff57e8; }
.focus-lightest-pink:focus { color: #ff81ff; }
.focus-dark-pink:focus { color: #d100a3; }
.focus-darkest-pink:focus { color: #b20088; }
.focus-purple:focus { color: #980bc6; }
.focus-light-purple:focus { color: #b536e2; }
.focus-lightest-purple:focus { color: #d355ff; }
.focus-dark-purple:focus { color: #7b00a9; }
.focus-darkest-purple:focus { color: #5f008e; }
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
.bg-focus-blue:focus { background-color: #0074D9; }
.bg-focus-light-blue:focus { background-color: #64a8ff; }
.bg-focus-lightest-blue:focus { background-color: #a2dfff; }
.bg-focus-dark-blue:focus { background-color: #0045a1; }
.bg-focus-darkest-blue:focus { background-color: #002f86; }
.bg-focus-yellow:focus { background-color: #fff93c; }
.bg-focus-light-yellow:focus { background-color: #fffa60; }
.bg-focus-lightest-yellow:focus { background-color: #fffca6; }
.bg-focus-dark-yellow:focus { background-color: #e2c100; }
.bg-focus-darkest-yellow:focus { background-color: #c4a600; }
.bg-focus-orange:focus { background-color: #FF851B; }
.bg-focus-light-orange:focus { background-color: #ffa942; }
.bg-focus-lightest-orange:focus { background-color: #ffc55d; }
.bg-focus-dark-orange:focus { background-color: #d05e00; }
.bg-focus-darkest-orange:focus { background-color: #b14400; }
.bg-focus-red:focus { background-color: #d82c2c; }
.bg-focus-light-red:focus { background-color: #f94f44; }
.bg-focus-lightest-red:focus { background-color: #ff6c5c; }
.bg-focus-dark-red:focus { background-color: #bd001a; }
.bg-focus-darkest-red:focus { background-color: #9d0003; }
.bg-focus-teal:focus { background-color: #27bfa8; }
.bg-focus-light-teal:focus { background-color: #4eddc5; }
.bg-focus-lightest-teal:focus { background-color: #6ffae0; }
.bg-focus-dark-teal:focus { background-color: #25a28f; }
.bg-focus-darkest-teal:focus { background-color: #008876; }
.bg-focus-green:focus { background-color: #3D9970; }
.bg-focus-light-green:focus { background-color: #5ab48a; }
.bg-focus-lightest-green:focus { background-color: #75d0a4; }
.bg-focus-dark-green:focus { background-color: #1e7f58; }
.bg-focus-darkest-green:focus { background-color: #006540; }
.bg-focus-pink:focus { background-color: #F012BE; }
.bg-focus-light-pink:focus { background-color: #ff57e8; }
.bg-focus-lightest-pink:focus { background-color: #ff81ff; }
.bg-focus-dark-pink:focus { background-color: #d100a3; }
.bg-focus-darkest-pink:focus { background-color: #b20088; }
.bg-focus-purple:focus { background-color: #980bc6; }
.bg-focus-light-purple:focus { background-color: #b536e2; }
.bg-focus-lightest-purple:focus { background-color: #d355ff; }
.bg-focus-dark-purple:focus { background-color: #7b00a9; }
.bg-focus-darkest-purple:focus { background-color: #5f008e; }
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
.hover-blue:hover { color: #0074D9; }
.hover-light-blue:hover { color: #64a8ff; }
.hover-lightest-blue:hover { color: #a2dfff; }
.hover-dark-blue:hover { color: #0045a1; }
.hover-darkest-blue:hover { color: #002f86; }
.hover-yellow:hover { color: #fff93c; }
.hover-light-yellow:hover { color: #fffa60; }
.hover-lightest-yellow:hover { color: #fffca6; }
.hover-dark-yellow:hover { color: #e2c100; }
.hover-darkest-yellow:hover { color: #c4a600; }
.hover-orange:hover { color: #FF851B; }
.hover-light-orange:hover { color: #ffa942; }
.hover-lightest-orange:hover { color: #ffc55d; }
.hover-dark-orange:hover { color: #d05e00; }
.hover-darkest-orange:hover { color: #b14400; }
.hover-red:hover { color: #d82c2c; }
.hover-light-red:hover { color: #f94f44; }
.hover-lightest-red:hover { color: #ff6c5c; }
.hover-dark-red:hover { color: #bd001a; }
.hover-darkest-red:hover { color: #9d0003; }
.hover-teal:hover { color: #27bfa8; }
.hover-light-teal:hover { color: #4eddc5; }
.hover-lightest-teal:hover { color: #6ffae0; }
.hover-dark-teal:hover { color: #25a28f; }
.hover-darkest-teal:hover { color: #008876; }
.hover-green:hover { color: #3D9970; }
.hover-light-green:hover { color: #5ab48a; }
.hover-lightest-green:hover { color: #75d0a4; }
.hover-dark-green:hover { color: #1e7f58; }
.hover-darkest-green:hover { color: #006540; }
.hover-pink:hover { color: #F012BE; }
.hover-light-pink:hover { color: #ff57e8; }
.hover-lightest-pink:hover { color: #ff81ff; }
.hover-dark-pink:hover { color: #d100a3; }
.hover-darkest-pink:hover { color: #b20088; }
.hover-purple:hover { color: #980bc6; }
.hover-light-purple:hover { color: #b536e2; }
.hover-lightest-purple:hover { color: #d355ff; }
.hover-dark-purple:hover { color: #7b00a9; }
.hover-darkest-purple:hover { color: #5f008e; }
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
.bg-hover-blue:hover { background-color: #0074D9; }
.bg-hover-light-blue:hover { background-color: #64a8ff; }
.bg-hover-lightest-blue:hover { background-color: #a2dfff; }
.bg-hover-dark-blue:hover { background-color: #0045a1; }
.bg-hover-darkest-blue:hover { background-color: #002f86; }
.bg-hover-yellow:hover { background-color: #fff93c; }
.bg-hover-light-yellow:hover { background-color: #fffa60; }
.bg-hover-lightest-yellow:hover { background-color: #fffca6; }
.bg-hover-dark-yellow:hover { background-color: #e2c100; }
.bg-hover-darkest-yellow:hover { background-color: #c4a600; }
.bg-hover-orange:hover { background-color: #FF851B; }
.bg-hover-light-orange:hover { background-color: #ffa942; }
.bg-hover-lightest-orange:hover { background-color: #ffc55d; }
.bg-hover-dark-orange:hover { background-color: #d05e00; }
.bg-hover-darkest-orange:hover { background-color: #b14400; }
.bg-hover-red:hover { background-color: #d82c2c; }
.bg-hover-light-red:hover { background-color: #f94f44; }
.bg-hover-lightest-red:hover { background-color: #ff6c5c; }
.bg-hover-dark-red:hover { background-color: #bd001a; }
.bg-hover-darkest-red:hover { background-color: #9d0003; }
.bg-hover-teal:hover { background-color: #27bfa8; }
.bg-hover-light-teal:hover { background-color: #4eddc5; }
.bg-hover-lightest-teal:hover { background-color: #6ffae0; }
.bg-hover-dark-teal:hover { background-color: #25a28f; }
.bg-hover-darkest-teal:hover { background-color: #008876; }
.bg-hover-green:hover { background-color: #3D9970; }
.bg-hover-light-green:hover { background-color: #5ab48a; }
.bg-hover-lightest-green:hover { background-color: #75d0a4; }
.bg-hover-dark-green:hover { background-color: #1e7f58; }
.bg-hover-darkest-green:hover { background-color: #006540; }
.bg-hover-pink:hover { background-color: #F012BE; }
.bg-hover-light-pink:hover { background-color: #ff57e8; }
.bg-hover-lightest-pink:hover { background-color: #ff81ff; }
.bg-hover-dark-pink:hover { background-color: #d100a3; }
.bg-hover-darkest-pink:hover { background-color: #b20088; }
.bg-hover-purple:hover { background-color: #980bc6; }
.bg-hover-light-purple:hover { background-color: #b536e2; }
.bg-hover-lightest-purple:hover { background-color: #d355ff; }
.bg-hover-dark-purple:hover { background-color: #7b00a9; }
.bg-hover-darkest-purple:hover { background-color: #5f008e; }
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


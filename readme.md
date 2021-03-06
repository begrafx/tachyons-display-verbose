# tachyons-display-verbose 1.0.3

Performance based css module.

### Stats

426 | 36 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-display-verbose
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-display-verbose
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-display-verbose.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-display-verbose";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-display-verbose@1.0.3/css/tachyons-display-verbose.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-display-verbose">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   DISPLAY

   Base:
    d = display

   Modifiers:
    n     = none
    b     = block
    ib    = inline-block
    it    = inline-table
    t     = table
    tc    = table-cell
    tr    = table-row
    tcol  = table-column
    tcolg = table-column-group

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
.display-none { display: none; }
.display-inline { display: inline; }
.display-block { display: block; }
.display-inline-block { display: inline-block; }
.display-inline-table { display: inline-table; }
.display-table { display: table; }
.display-table-cell { display: table-cell; }
.display-table-column { display: table-column; }
.display-table-column-group { display: table-column-group; }
@media screen and (min-width: 48em) {
 .display-none-ns { display: none; }
 .display-inline-ns { display: inline; }
 .display-block-ns { display: block; }
 .display-inline-block-ns { display: inline-block; }
 .display-inline-table-ns { display: inline-table; }
 .display-table-ns { display: table; }
 .display-table-cell-ns { display: table-cell; }
 .display-table-column-ns { display: table-column; }
 .display-table-column-group-ns { display: table-column-group; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .display-none-m { display: none; }
 .display-inline-m { display: inline; }
 .display-block-m { display: block; }
 .display-inline-block-m { display: inline-block; }
 .display-inline-table-m { display: inline-table; }
 .display-table-m { display: table; }
 .display-table-cell-m { display: table-cell; }
 .display-table-column-m { display: table-column; }
 .display-table-column-group-m { display: table-column-group; }
}
@media screen and (min-width: 64em) {
 .display-none-l { display: none; }
 .display-inline-l { display: inline; }
 .display-block-l { display: block; }
 .display-inline-block-l { display: inline-block; }
 .display-inline-table-l { display: inline-table; }
 .display-table-l { display: table; }
 .display-table-cell-l { display: table-cell; }
 .display-table-column-l { display: table-column; }
 .display-table-column-group-l { display: table-column-group; }
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


angular2-IE9-shims
==================

Shims to make angular2 RC1 app work on IE9(+)

**Note:** It has been pulled from (i.e., angular2 version `2.0.0-beta.17`): 

- the cdn:

`https://npmcdn.com/angular2@2.0.0-beta.17/es6/dev/src/testing/shims_for_IE.js`

- or the package:

`node_modules/angular2/es6/dev/src/testing/shims_for_IE.js`

^It can be used as a temporary workaround for now in app (for angular2 RC1 module only), until the underlying libraries are fixed to include this polyfill(s).


## Install

You can install this package with `npm` or can manually [download as zip](https://github.com/narainsagar/angular2-ie9-shims/archive/master.zip).

```
$ npm install angular2-IE9-shims
```

## Use

Add a `<script>` to your `index.html`:

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE.dev.js"></script>
```
OR

```html
  <script src="/path/to/angular2-ie9-shims/shims_for_IE.prod.js"></script>
```

## License

MIT in [LICENSE](/LICENSE) file.

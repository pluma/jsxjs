# Synopsis

Convert JSX files to JS, while remaining your sanity.

[![license - MIT](http://b.repl.ca/v1/license-MIT-blue.png)](http://pluma.mit-license.org) [![Flattr this](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=pluma&url=https://github.com/pluma/jsxjs)

[![NPM status](https://nodei.co/npm/jsxjs.png?compact=true)](https://npmjs.org/package/jsxjs)

[![Dependencies](https://david-dm.org/pluma/jsxjs.png?theme=shields.io)](https://david-dm.org/pluma/jsxjs)

# Usage

`jsxjs [source path...] [output folder]`

Converts JSX source files to JavaScript. Unlike the `jsx` CLI provided by `react-tools` this command optionally takes multiple sources (entire directories or individual files) and converts *all* `.js` and `.jsx` files in the source paths.

# Options

* `--no-magic`: By default, `jsxjs` will add missing `@jsx` pragmas in files with the extension `.jsx` and not convert other files if they do not contain the pragma (they will be copied instead). This option forces `jsxjs` to convert all matching files and not fix missing pragmas.
* `-a`, `--all`: By default, `jsxjs` will only convert files with the extensions `.js` or `.jsx`. This option will make `jsxjs` convert *all* files regardless of their extensions.
* `-v`, `--verbose`: Logs source and output file paths for each file that is converted.

# License

The MIT/Expat license. For more information, see http://pluma.mit-license.org/ or the accompanying [LICENSE](https://github.com/pluma/jsxjs/blob/master/LICENSE) file.
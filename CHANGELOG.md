# Changelog

## 1.1.3 (February 21, 2018)

IMPROVEMENTS:

- Add package keywords

## 1.1.2 (February 21, 2018)

IMPROVEMENTS:

- Detection of regex values (although not an official data type) to avoid weird highlighting

## 1.1.1 (November 25, 2017)

IMPROVEMENTS:

- Add installation instructions and screenshot

## 1.1.0 (November 25, 2017)

NEW FEATURES:

- Support folding markers for directives like `<source>...</source>`
- Support toggling comments
- Support escape sequenes like `foo\nbar` in single, double and unquoted strings
- Support array and hash (using JSON source) value types like `["foo","bar"]`
- Support integer, time and size value types (e.g. `property 100`, `bufsize 5M` or `finterval 5s`)
- Support highlighting `${variables}` (used by e.g. [record_transformer plugin](https://docs.fluentd.org/v0.12/articles/filter_record_transformer))
- Support (double quoted) string interpolations like `#{Time.new.to_i + 1}` (using Ruby source)

IMPROVEMENTS:

- Add example fluent.conf file using as many Fluentd features as possible (even if this package does not highlight it correctly)

## 1.0.0 (November 22, 2017)

NEW FEATURES:

- Initial release of the [Sublime Text and TextMate package](https://github.com/adamchainz/fluentd.tmLanguage) as package for Atom

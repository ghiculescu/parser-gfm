## HEAD

### Minor Enhancements

* Allow rendering emoji amidst GFM ([#30](https://github.com/kramdown/parser-gfm/pull/30))

### Bug Fixes

* Do not cast Symbols into strings to be re-casted in the options hash ([#20](https://github.com/kramdown/parser-gfm/pull/20))
* Respect `:transliterated_header_ids` kramdown option ([#22](https://github.com/kramdown/parser-gfm/pull/22))


## 1.1.0 / 2019-05-29

### Minor Enhancements

* GFM Parser refactored and optimized to improve memory usage and maintainability
  ([#11](https://github.com/kramdown/parser-gfm/pull/11), [#13](https://github.com/kramdown/parser-gfm/pull/13))

### Bug Fixes

* Define test methods with a shorter name ([#7](https://github.com/kramdown/parser-gfm/pull/7))
* Load the main file in the gem ([#10](https://github.com/kramdown/parser-gfm/pull/10))
* Fix strikethrough a single character ([#9](https://github.com/kramdown/parser-gfm/pull/9))


## 1.0.1 / 2019-01-13

### Bug Fixes

* Add missing loader file


## 1.0.0 / 2019-01-11

* Initial version based on kramdown 1.17.0

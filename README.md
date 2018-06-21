## Rutie

“The tie between Ruby and Rust.”
[![Build Status](https://travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)

*Breaking changes coming with rewrite underway.*


## Migrating from Ruru to Rutie

For using Rutie versions less than 0.1 the change is simple.  Replace all occurences
of the string `ruru` with `rutie` in your program.  And if you would like to use
`ruby-sys` code from Rutie rather than requiring `ruby-sys` you can change all existing
references to `ruby_sys` to `rutie::rubysys`.

After 0.1 you will have additional considerations to change like `Error` being removed.  For that; change instances of type `ruru::result::Error` to `rutie::AnyException`.


## LICENSE

MIT LICENSE — see [LICENSE](LICENSE)

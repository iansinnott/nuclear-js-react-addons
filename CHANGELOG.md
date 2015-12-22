## 0.3.0 (December 22, 2015)

 - BREAKING CHANGE: `provideReactor` is deprecated in favor of a `Provider` component
 - BREAKING CHANGE: `nuclearComponent` renamed to `connect`, now a higher order function that returns a Higher Order Component.  Usage as a decorator remains the same.

## 0.2.0 (September 14, 2015)

 - BREAKING CHANGE: nuclearComponent API matches nuclearMixin API for getDataBindings

 now the nuclearComponent will always take a function that receives props (to avoid `this` bindings ambiguity and to match the constructor signature if using es6)

## 0.1.1 (August 10, 2015)

 - Fix documentation
 - Improve README.md
 - UMD build


## 0.1.0 (July 22, 2015)

 - Initial release
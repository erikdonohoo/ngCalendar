## Goals of project

#### i18n support
Use angular's [i18n](https://code.angularjs.org/1.3.14/i18n/) configurations for handling month, day, and various time differences.

#### responsive
Components should base appearance on the size of the container they are placed in, but this should also be configurable.

#### configuration
Easy to use api, with smart configuration defaults.

#### polyfill for input[type="date"]
should treat date inputs like angular wants to as a javascript date object, but configure it to allow treating the actual model value however you want (ie long, datestring, UTF, etc)

#### customizable UI
Should be able to swap a new theme in easily

#### mobile friendly
Components should work well on touch devices and on various screen sizes

#### performant
Should be fast and optimize manipulations to the DOM as well as other expensive operations

#### angular 2.0 support
Should anticipate angular2.0 and support it early

#### support latest toolchain
Use gulp instead of grunt to be better prepared for the future, written in es6

---
*More to come*

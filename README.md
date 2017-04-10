# html-text

A Polymer Element that builds and runs an elasticsearch query.

### Example
```html
<build-and-run-query
  client="[[client]]"
  fields='"myField"'
  values='"myValue"'
  index-name="myIndexName"
  index-types='["myIndexType"]'
  error="{{error}}"
  loading="{{loading}}"
  results="{{results}}">
</build-and-run-query>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve


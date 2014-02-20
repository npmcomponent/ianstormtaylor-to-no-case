*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-no-case](http://github.com/ianstormtaylor/to-no-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-no-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-no-case

  Remove an existing case from a string.

## Installation

    $ component install ianstormtaylor/to-no-case
    $ npm install to-no-case

## Example

```js
var clean = require('to-no-case');

clean('camelCase');       // "camel case"
clean('snake_case');      // "snake case"
clean('slug-case');       // "slug case"
clean('Title of Case');   // "title of case"
clean('Sentence case.');  // "sentence case."
```

## API

### toNoCase(string)
  
  Returns the `string` with an existing case removed.

## License

  MIT

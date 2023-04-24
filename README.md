# @7sean68/jacoco-parse

forked from https://github.com/vokal/jacoco-parse

Parse jacoco results file and return JSON

The output is based on, and intended to be compatible with, https://github.com/davglass/lcov-parse
as well as https://github.com/vokal/cobertura-parse

## Use

```js
var jacoco = require( "jacoco-parse" );

// parse by file path
jacoco.parseFile( "filepath.xml", function( err, result ) { ... } );

// or parse file contents
jacoco.parseContent( "<?xml version="1.0" ?><report>...</report>",
    function( err, result ) { ... } );
```

# jsonprint
A small, simple module to output properly formatted pretty JSON with syntax highlighting to your terminal

## Usage

jsonprint can be used as follows:

```
const jsonp = require('jsonprint');
const object = {
    key1: 'value1',
    key2: [1,2,3],
    key4: null,
    key5: {
        key6: 10
    }
};

console.log(jsonp(object));
```


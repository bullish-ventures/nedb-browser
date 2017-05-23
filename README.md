# nedb-node

> NeDB for the browser

**This is a experimental work in progress. Not ready for use.**

## Installation

```
npm install nedb-browser --save
```

## Documentation

TODO

## Complete Example

```js
const Datastore = require('nedb-node');

const db = new Datastore('file://users.db');

db.find({}, function(error, users) {

});
```

## License

Copyright (c) 2016

Licensed under the [MIT license](LICENSE).

## When you want to access get query parameters from browser.

### Installation

```sh
npm install get-query --save
```

### Example

Suppose we have link with query parameters:
`http://localhost/home?name=Joe&subs=1,2,3`


```js

import getQuery from 'get-query';

const urlGetParams = getQuery();  // { name: "Joe", subs: [1,2,3] }

```


### License

The MIT License (MIT)

Copyright (c) 2016 Sabbir Ahmed

### nearley
---
https://github.com/kach/nearley
https://nearley.js.org/

```
npm install --save nearley
npm install -g nearley
nearleyc grammar.ne -o grammar.js
```

```js
const nearley = require("nearley");
const grammar = require("./grammar.js");
const parser = new nearley.Parser(nearley.Grammar.fromCompiled(grammar));
parser.feed("foo\n");
console.log(parser.results);
```

```

```



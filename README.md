# pushdata-rpgcoin

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

Encode/decode value as rpgcoin `OP_PUSHDATA` integer


## Example

``` javascript
var pushdata = require('pushdata-rpgcoin')

var i = 120
var buffer = new Buffer(pushdata.encodingLength(i))

pushdata.encode(buffer, i)
```

## LICENSE [MIT](LICENSE)

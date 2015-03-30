# Danish postal codes

JSON data of all danish postal codes.

```js
var codes = require('postal-codes-denmark');

codes === codes.denmark;	// true

codes[codes.length - 1];
// { code: "9990", city: "Skagen", street: "", company: "" }

codes[codes.denmark.length - 1];
// { code: "9990", city: "Skagen", street: "", company: "" }

codes.greeland[0];
// { code: "3900", city: "Nuuk", street: "", company:"" }
```

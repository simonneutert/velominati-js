# velominati-js

**Please bear in mind, that I intentionally added the source to every rule object!**

_The authors of the http://www.velominati.com were not reachable to ask for permission._ :fearful:

Please, **always** add the source to their website when using the quotes!

#### I do 100 % respect what they put out for all us cyclists around the world.

If you like their work and/or use this repo, at least buy a copy of their [book on amazon](https://amzn.to/3bX6IQg).

## npm 

``` javascript
const Velominati = require('velominati-js');

const v = new Velominati

console.log(v.rules) // [{rule: {index: Integer, title: String, text: String, source: 'https://www.velominati.com/#the-rules'}}, ...]

const rule1 = v.rules[0]
const rule95 = v.rules[94]

console.log(v.rule95)

// structure of a rule object
//
// rule: {
//   index: Integer,
//   title: String,
//   text: String,
//   source: 'https://www.velominati.com/#the-rules'
// }
```
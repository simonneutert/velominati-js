# velominati-js

**Please bear in mind, that I intentionally added the source to every rule object.**

The authors of the http://velominati.com were not reachable to ask permission. 

Please, add the source to their website when using the quotes.

I do 100 % respect what they put out for the cyclists around the world.

If you like their work and use this repo, at least buy a copy of their [book on amazon](https://amzn.to/3bX6IQg).

## npm 

``` javascript
const Velominati = require('velominati-js');

const v = new Velominati

console.log(v.rules)

const rule1 = v.rules[0]
// rule: {
//   index: Integer,
//   title: String,
//   text: String,
//   source: 'https://www.velominati.com/#the-rules'
// }
```
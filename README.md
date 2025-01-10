# velominati-js

**Please bear in mind, that I intentionally added the source to every rule
object!**

_The authors of the http://www.velominati.com have not replied to my request,
giving their permission to publish this package. I advise you to contact the
keepers of the cog, when using this code and let them know. I am very sure they
are happy to know!_

Please, **always** add the source to their website when using the quotes!

#### I do 100 % respect what they put out for all us cyclists around the world.

If you like their work and/or use this repo, at least buy a copy of their
[book on amazon](https://amzn.to/3bX6IQg).

## npm

```javascript
const Velominati = require("velominati-js");

const v = new Velominati();

const rule1 = v.rules[1];
// rule1.title => String
// rule2.text => String
const rule95 = v.rules[95];

// access rules 1 to 95
console.log(v.rule(33));
// => {
//   index: Integer,
//   title: String,
//   text: String,
//   source: 'https://www.velominati.com/#the-rules'
// }
```

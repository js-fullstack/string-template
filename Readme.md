# string-template

[![build status][1]][2] [![dependency status][3]][4] [![coverage report][9]][10] [![stability index][15]][16]

[![npm stats][13]][14]

[![browser support][5]][6]

  Fork from https://www.npmjs.com/package/string-template

  only add functionality:

  ```
  var compile = require('./compile.js');

  var template = compile('hello {name} where is {age}');

  console.log(template.parameters); // ['name', 'age'] will return

```
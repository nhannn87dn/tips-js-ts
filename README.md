**Trả về full dường dẫn thư mục hiện tại**
```js
var path = require('path');

const pathOject = path.parse(__dirname);
console.log(pathOject)

//output

{
  root: 'C:\\',
  dir: 'C:\\xampp\\htdocs\\learning',
  base: 'nodeapp',
  ext: '',
  name: 'nodeapp'
}

```

# nodeverse-db

## Usage

```js
const setupDatabase = require('nodeverse-db');

setupDabase(config).then(db =>{
    const {Agent, Metric} = db

}).catch(err => console.log(err))
```
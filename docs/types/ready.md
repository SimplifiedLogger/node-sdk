# Ready
Type for handling READY based Console Logs.

---

## Case Layout
```js
case "ready": {
  return console.log(``);
}
```

---

## Case Parameters
| Params      | Description                      |
| ----------- | -------------------------------- |
| content     | Title                            |
| type        | The log type (error, log etc)    |

---

## Example Usage (Discord.js)
```js
const SimpleLogs = require('simplified-logger');

module.exports = async (client) => {
    
    SimpleLogs.log(`Client is ready!`, 'ready')
}
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: ready
Message: Client is ready!
```

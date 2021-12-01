# Warn
Type for handling WARNING based Console Logs.

---

## Case Layout
```js
case "warn": {
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
    
    SimpleLogs.log(`Something is happening!`, 'warn')
}
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: log
Message: Something is happening!
```

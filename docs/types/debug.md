# Debug
Type for handling DEBUG based Console Logs.

---

## Case Layout
```js
case "debug": {
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

SimpleLogs.log(`Something is happening!`, 'debug')
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: debug
Message: Something is happening!
```

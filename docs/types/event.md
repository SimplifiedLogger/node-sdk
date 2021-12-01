# Event
Type for handling EVENT based Console Logs.

---

## Case Layout
```js
case "event": {
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
    
    SimpleLogs.log(`Something is happening!`, 'event')
}
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: event
Message: Something is happening!
```

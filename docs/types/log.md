# Log
Type for handling the base Console Logs.

---

## Case Layout
```js
case "log": {
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

## Example Usage (Discord.js Ready Event)
```js
const SimpleLogs = require('simplified-logger');

module.exports = async (client) => {
    
    SimpleLogs.log(`Signed in as ${client.user.username}`, 'ready')
}
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: log
Message: Something cool happened!
```

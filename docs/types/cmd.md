# CMD
Type for handling CMD based Console Logs.

---

## Case Layout
```js
case "cmd": {
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

SimpleLogs.log(`Loaded all Bot Commands`, 'cmd')
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: cmd
Message: Loaded all Bot Commands
```

# Error
Type for handling ERROR based Console Logs.

---

## Case Layout
```js
case "error": {
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

.catch((err) => {
  
  SimpleLogs.log(err, 'error')
});
```

---

## Example Response
```terminal
[Logger] - Date: 11-30-2021
Type: log
Message: Error Occured!
```

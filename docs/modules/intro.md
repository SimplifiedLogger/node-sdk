![npm](https://nodei.co/npm/simplified-logger.png?downloads=true&stars=true)

---

# Installation
- NPM: `npm i simplified-logger@latest`
- Package: append `"simplified-logger": "^1.0.3"` to your `Package.json`

---

# The Basics
```js
const SimpleLogs = require('simplified-logger');

SimpleLogs.log('Wow look at me', 'log')
```

---

## Example (Discord.js)
```
const SimpleLogs = require('simplified-logger');

module.exports = async (client) => {
    
    SimpleLogs.log(`Client is ready!`, 'ready')
}
```

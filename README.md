# roip
A fast way to check if a request is from Roblox

## Example
```javascript
const roip = require("roip");
const ip = "127.0.0.1";

roip.check(ip)
.then(() => {
    console.log("Request is from roblox!");
})
.catch(err => {
    console.error(err);
})
```

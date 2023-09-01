# betterlogs.js
Upgrade your terminal logs with betterlogs.js

# Install
```
npm install betterlogs.js
yarn add betterlogs.js
pnpm add betterlogs.js
```

# Import
```
const betterlogs = require("betterlogs.js");
import betterlogs from "betterlogs.js";
```

# Configuration
> Options available you can use (`1` & `2`)

```yml
1 - Display console logs with barrier
2 - Display console logs without barrier
```

# Example
## Using type (`1`)
```js
betterlogs.debug("1", "Hello World!");
betterlogs.error("1", "Hello World!");
betterlogs.info("1", "Hello World!");
betterlogs.warn("1", "Hello World!");
betterlogs.trace("1", "Hello World!");
betterlogs.verbose("1", "Hello World!");
betterlogs.success("1", "Hello World!");
betterlogs.notice("1", "Hello World!");
betterlogs.critical("1", "Hello World!");
betterlogs.alert("1", "Hello World!");
betterlogs.emergency("1", "Hello World!");
betterlogs.progress("1", "Hello World!");
betterlogs.update("1", "Hello World!");
betterlogs.query("1", "Hello World!");
betterlogs.performance("1", "Hello World!");
betterlogs.activity("1", "Hello World!");
betterlogs.authorization("1", "Hello World!");
betterlogs.network("1", "Hello World!");
betterlogs.security("1", "Hello World!");
betterlogs.database("1", "Hello World!");
betterlogs.audit("1", "Hello World!");
betterlogs.danger("1", "Hello World!");
betterlogs.ready("1", "Hello World!");
betterlogs.event("1", "Hello World!");
betterlogs.heartbeat("1", "Hello World!");
betterlogs.shard("1", "Hello World!");
betterlogs.cluster("1", "Hello World!");
betterlogs.command("1", "Hello World!");
betterlogs.message("1", "Hello World!");
```
## Preview
![Preview](https://telegra.ph/file/93b8b4ffa14b37cde11e1.png)

## Using type (`2`)
```js
betterlogs.debug("2", "Hello World!");
betterlogs.error("2", "Hello World!");
betterlogs.info("2", "Hello World!");
betterlogs.warn("2", "Hello World!");
betterlogs.trace("2", "Hello World!");
betterlogs.verbose("2", "Hello World!");
betterlogs.success("2", "Hello World!");
betterlogs.notice("2", "Hello World!");
betterlogs.critical("2", "Hello World!");
betterlogs.alert("2", "Hello World!");
betterlogs.emergency("2", "Hello World!");
betterlogs.progress("2", "Hello World!");
betterlogs.update("2", "Hello World!");
betterlogs.query("2", "Hello World!");
betterlogs.performance("2", "Hello World!");
betterlogs.activity("2", "Hello World!");
betterlogs.authorization("2", "Hello World!");
betterlogs.network("2", "Hello World!");
betterlogs.security("2", "Hello World!");
betterlogs.database("2", "Hello World!");
betterlogs.audit("2", "Hello World!");
betterlogs.danger("2", "Hello World!");
betterlogs.ready("2", "Hello World!");
betterlogs.event("2", "Hello World!");
betterlogs.heartbeat("2", "Hello World!");
betterlogs.shard("2", "Hello World!");
betterlogs.cluster("2", "Hello World!");
betterlogs.command("2", "Hello World!");
betterlogs.message("2", "Hello World!");
```
## Preview
![Preview](https://telegra.ph/file/0e542be6b3694e5878163.png)
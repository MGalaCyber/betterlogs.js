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
import betterlogs from "betterlogs.js"
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
betterlogs.warn("1", "Hello Word");
betterlogs.danger("1", "Hello Word");
betterlogs.info("1", "Hello Word");
betterlogs.error("1", "Hello Word");
betterlogs.debug("1", "Hello Word");
betterlogs.ready("1", "Hello Word");
betterlogs.database("1", "Hello Word");
betterlogs.event("1", "Hello Word");
betterlogs.heartbeat("1", "Hello Word");
betterlogs.shard("1", "Hello Word");
betterlogs.cluster("1", "Hello Word");
betterlogs.command("1", "Hello Word");
betterlogs.notice("1", "Hello Word");
betterlogs.critical("1", "Hello Word");
betterlogs.trace("1", "Hello Word");
```
## Preview
![Preview](https://telegra.ph/file/b76a455d6bccb7d1640a3.png)

## Using type (`2`)
```js
betterlogs.warn("2", "Hello Word");
betterlogs.danger("2", "Hello Word");
betterlogs.info("2", "Hello Word");
betterlogs.error("2", "Hello Word");
betterlogs.debug("2", "Hello Word");
betterlogs.ready("2", "Hello Word");
betterlogs.database("2", "Hello Word");
betterlogs.event("2", "Hello Word");
betterlogs.heartbeat("2", "Hello Word");
betterlogs.shard("2", "Hello Word");
betterlogs.cluster("2", "Hello Word");
betterlogs.command("2", "Hello Word");
betterlogs.notice("2", "Hello Word");
betterlogs.critical("2", "Hello Word");
betterlogs.trace("2", "Hello Word");
```
## Preview
![Preview](https://telegra.ph/file/7db8ae4b9ee60e1302e93.png)
## koa-starter

### What includes:

* Multipy Koa-Routers using.
* Flowtype.
* Eslint.
* Backpack.

### Usage

### Clone:

```bash
git clone https://github.com/vamosgs/koa-starter.git
```

### Environment:

    Change .envEXAMPLE to .env for starting develompent.

### Routing:

Create your router in src/routes file
then import it in src/routes/index.js

example:

```js
const newRouter = require("./newRouter");

const routes = combineRouters([root, newRouter]);
```

### Commands:

* Build:
  ```bash
  yarn build
  ```
* Dev server:

  ```bash
  yarn dev
  ```

* Start on your server:

  ```bash
  yarn start
  ```

### Its still in progress...
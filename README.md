# cross-worker-pear

Cross-runtime worker abstractions for Pear.

```
npm i cross-worker-pear
```

## Usage

```js
const { spawn } = require('cross-worker-pear')

const pipe = spawn('./worker', ['arg1', 'arg2'])
```

## License

Apache-2.0

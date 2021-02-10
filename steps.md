# Install ShellJS with npm
```
    npm install shelljs
```
## OR with Yarn
```
    yarn add shelljs
```

# Require the 'exec' function of shelljs
```js
    const { exec } = require('shelljs');
```

# Execute the command
```js
    exec("echo # That Works!! > COMMAND.md",{ silent: true })
```

# See the result in COMMAND.md
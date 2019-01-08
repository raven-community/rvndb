# Rvndb

Rvndb client

# Install

```
npm install
```

# Usage

- There's only one api: `rvndb.read()`.
- Simply pass a base64 encoded JSON query that follows the Rvndb Query Language spec at https://rvndb.network/#bql

# Example

```
const rvndb = require('rvndb')
rvndb.read({ ... }, function(err, response) {
 res.json(response)
})
```

Also see [examples/app.js](examples/app.js) for an actual example

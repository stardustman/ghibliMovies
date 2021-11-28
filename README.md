## asynchronous code
The asynchronous code will be written in three ways: 
1. callbacks, 
2. promises, 
3. and with the async/await keywords.

## core
1. envent loop
2. call stack
3. message queue

##  asynchronous operation
 (`operation`, the `condition` for it to be completed,  the `function` to be called when it’s completed)

### callback

```javascript
function asynchronousFunction([ Function Arguments ], [ Callback Function ]) {
    [ Action ]
}
```

### promise

```javascript
promiseFunction()
    .then([ Callback Function for Fulfilled Promise ])
    .catch([ Callback Function for Rejected Promise ])
```

### async/await

```javascript
async function() {
    await [Asynchronous Action]
}
```

## References
1. [Studio Ghibli API](https://ghibliapi.herokuapp.com/)
2. [how-to-write-asynchronous-code-in-node-js](https://www.digitalocean.com/community/tutorials/how-to-write-asynchronous-code-in-node-js)
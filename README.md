## Observable Event Listeners

### What is Observable?

**Observable is a useful node.js plugin to add event listeners that can be called upon later.**

## Setting up:
```console
npm i observable-eventlisteners --save
```

## Importing:
```js
const { Observable } = require('observable-eventlisteners')
```

## Preparation:
```js
var observable = new Observable();
```

## Commands:
Listening for Events:
```js
observable.on('your event', (data) => {console.log(data})
```
Firing Events:
```js
observable.fire('your event', {message: 'hello'})
```
```console
> {message: 'hello'}
```
observable.fireEvent('your event', {message: 'hello world'})
observable.send('your event', {message: 'hello'})
```

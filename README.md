# random-choice

>Get a random item from an array with a weighted probablility

## Install
```
$ npm install random-choice
```

## Usage
```js
const randomChoice = require('random-choice');

//Give relative wqeights for the items in your array
randomChoice(['apple', 'orange', 'banana'], [.50, .25, .25]);
//=> 'apple'

//Integer ratios work too
randomChoice(['apple', 'orange', 'banana'], [2, 1, 1]);
//=> 'apple'
```

## License
MIT

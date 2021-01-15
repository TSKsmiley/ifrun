IF Run
=======================================

When making something that can take a CallBack, you can use ifrun to only run if defined.

the entirety of ifrun is 70 characters
***

## List of features

*   Runs a function with args if it is not null

## Download & Installation

There are 2 ways to use if run Option 1 using the npm package and Option 2 without it

## Using npm (Option 1)
install
```shell 
$ npm i ifrun
```

import
```js
const ifRun = require("ifRun");
```
## Without using npm (Option 2)
define
```js
const ifRun = (func, args)=>{if(!func) return; func(args)};
```

# Example usage
```js
function test(hello){
    console.log(hello);
}

ifRun(test,"sup");
```





## Authors or Acknowledgments

*   Arnar Freyr Ástvaldsson

## License

    This project is licensed under the MIT License
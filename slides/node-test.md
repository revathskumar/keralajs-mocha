##  node-test

```js
// calculator.js
Calculator = {
  add: function(a, b) {
    return a + b;
  }
}

module.exports = Calculator
```


```js
// test.js
var Calc = require("./calculator");
var assert = require("chai").assert

suite("add", function(){
  test("two positive", function(){
    assert(Calc.add(1,3), 4);
  });

  test("positive and negaive", function(){
    assert(Calc.add(-5,4), 1);
  })
});
```

##  browser-test

```js
Calc = {
  add: function(a, b){
    return a + b;
  }
}
```


```js
mocha.setup('tdd');
var assert = chai.assert;

suite("add", function(){
  test("two positive", function(){
    assert(Calc.add(1,3), 4);
  });

  test("positive and negaive", function(){
    assert(Calc.add(-5,4), 1);
  })
});

mocha.run();
```

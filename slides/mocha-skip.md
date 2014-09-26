##  skip tests

```js
suite("add", function(){
  test.skip("two positive", function(){
    assert(Calc.add(1,3), 4);
  });

  test("positive and negaive", function(done){
    assert(Calc.add(-5, 4), -1);
  })
});
```

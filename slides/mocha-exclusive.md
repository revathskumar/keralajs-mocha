##  exclusive tests

* Run only specific test/suite
* similar to grep

```js
suite("add", function(){
  test.only("two positive", function(){
    assert(Calc.add(1,3), 4);
  });

  test("positive and negaive", function(done){
    assert(Calc.add(-5, 4), -1);
  })
});
```

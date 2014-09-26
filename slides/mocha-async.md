##  Asynchronous

```js
Calc = {
  add: function(a, b, fn){
    fn(a + b);
  }
}


suite("add", function(){
  test("two positive", function(done){
    Calc.add(1,3, function(result){
      assert(result, 4);
      done();
    })

  });
});
```

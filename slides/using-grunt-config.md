##  grunt config

```js
module.exports = function(grunt) {
    grunt.loadNpmTasks('grunt-mocha');

    grunt.initConfig({
        mocha: {
          test: {
            src: ['tests/**/*.html'],
          },
        }
    });
}
```

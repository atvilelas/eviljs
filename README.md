# eviljs

## Usage:
```javascript

evil((() => {
    function test() {
        console.log('this function does a bunch of things');
    }

    test();

})());

evil(`
    function test() {
        console.log('this function does a bunch of other things');
    }

    test();
`
)
```
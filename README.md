## Rest Operator

 #### Rest Operator: 
* Rest operator consists of three dots.
* The rest parameter packs elements into an array.

```javascript

const printNumbers = (a,b,c, ...args) => {
console.log(args[2]);//5
}
printNumbers(1,2,3,4,5);

```


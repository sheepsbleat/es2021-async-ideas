# es2021-async-ideas
new ideas for es2021 async javascript

# ideas:


## description
a new type of async coding

## name
name ideas: waypoint

## syntax
every waypoint method will be a starter point for the code to run when the function is called

## examples

```javascript 
async function foo() {
waypoint() /*method can be anonymous or named*/ {
// will be called on function invocation
console.log("called");
}

waypoint namedwaypoint() {
// will also be called on invocation asynchronously with other waypoint
console.log(" I am named ");
}
}


```

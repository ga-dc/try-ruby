# Try Ruby

Please complete the first 3 levels of Try Ruby - http://tryruby.org/

## Deliverables

Please open an issue on this repository, and choose one programming concept to discuss,
including but not limited to:

- conditionals
- truthy/falsey
- for loops
- functions/methods
- complex data types

and compare and contrast their JavaScript and Ruby implementations.


In JavaScript, functions and ruby do the same thing, encapsulate data. But in Ruby,
functions are methods and are created using def.

hashes, and symbols are new data types that exist within Ruby, but not within JavaScript.
They are the same in aspects such as strings, booleans, arrays, and integers.

in JavaScript for loops are written like this:

for(var i = 0; i<something.length; i++){}

  in Ruby it is written like:

  FOR:
fruits = ["apple", "banana", "cherry"]
  for fruit in fruits
    puts fruit
end

A few examples in differences.

For example:

### Truthy/Falsey

In JavaScript, 0 is a falsey value, but 0 is a truthy value in Ruby.

```rb
# ruby
number = 0
if number
  puts "0 is truthy"
end
```

```js
// javascript
var number = 0;
if(!number){
  console.log("0 is falsey");
}
```

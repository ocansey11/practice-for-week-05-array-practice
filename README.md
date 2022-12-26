# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(1)
Space complexity: O(1)
Justification: arr.push() works by putting a value at the end of an arr, all it needs is the arr.length.

[push on MDN][push]


## `arr.pop()`

Time complexity: O(1)
Space complexity: O(1)
Justification:  arr.pop() works by removing a value at the end of an arr, all it needs is the arr.length.

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(1)
Space complexity: O(1)
Justification:  arr.shift() removes the value at the begging of an arr, a very simple task, no matter the size of the array
[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(1)
Space complexity: O(1)
Justification:  arr.shift() places a value at the begging of an arr, a very simple task, no matter the size of the array

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(n)
Space complexity: O(1)
Justification: you can add or remove a certain number of values to the array hence time complexity varies. However, it does not create a new array hence the results for space complexity

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: since it returns a shallow of an arr, space and time complexity depend on the size of the copy.

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(1)
Space complexity: O(1)
Justification: returns the value of of a target index

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(n)
Space complexity: O(n)
Justification: map executes a callback that results in mirroring the size of the input arr hence varying sizes produces varying results. A new array is created and will need n slots in memory

[map on MDN][map]

## `arr.filter()`

Time complexity: O(n)
Space complexity: O(n)
Justification: since it returns a shallow copy, time and space complexity depend on the size of the filtered values

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(n)
Space complexity: O(1)
Justification: time complexity depends on the callback and size of arr.

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(n)
Space complexity: O(1)
Justification: time complexity will depend on the total number of values in the array. However since no shallow copy is produced memory space is not needed

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(n)
Space complexity: O(n)
Justification: time complexity will depend on the total number of values being provided array. Since an array is being populated n slots in memory is required

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax

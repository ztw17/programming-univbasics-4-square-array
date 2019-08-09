# Square Array

## Learning Goals

- Apply `while` to iterate over an `Array`

## Introduction

In this lab we will be building a method, `square_array`, that
[squares](https://en.wikipedia.org/wiki/Square_(algebra)) each element in an
`Array` of numbers and returns a new `Array` of these squared numbers.

**Hint:** There is more than one way to square numbers! Google Ruby's exponent
operator or refer back to the earlier lesson on simple math.

## Apply `while` to Iterate Over an Array

To build this method, use the iterator `while` and implement your own logic. Use
only `while`, `Array`s, and any other previously discussed methods for the
solution. Don't use the Ruby docs or the internet to find built-in methods or
code you may not understand yet.

Example:

```ruby
numbers = [1,2,3]

squared_results = square_array(numbers)
# => [1,4,9]

bigger_numbers = [9,10,16,25]

big_results = square_array(bigger_numbers)
# => [81,100,256,625]
big_results
# => [81,100,256,625]
```
Once you have the tests passing, you can optionally test out implementing this
with a higher level iterator.

## Conclusion

As demonstrated, Ruby gives us a number of shortcuts to complete iterative
tasks with ease. Instead of manually writing loops, you can achieve the same
results with fewer lines of code.

## Resources
* [Ruby Docs](http://www.ruby-doc.org/core-2.6.3/)

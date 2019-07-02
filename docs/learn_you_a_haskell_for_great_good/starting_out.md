## ready

```
:set prompt "ghci> "
```

True False || && not == /=

infix function
prefix function

In Haskell, functions are called by writing the function name, a space and then the parameters, separated by spaces.

succ min max div

function application has the highest precedence of them all.

If a function takes two parameters, we can also call it as an infix function by surrounding it with backticks.

## Baby's first function

Making basic functions that are obviously correct and then combining them into more complex functions.

Functions in Haskell don't have to be in any particular order.

the else part is mandatory in Haskell.
the if statement in Haskell is an expression. an expression is basically a piece of code that returns a value.

the apostrophe `'` is a valid character.

function can't begin with uppercase letters.

when a function doesn't take any parameters, we usually say it's a definition.

## An intro to lists

lists are homogenous data structure. It stores several elements of the same type.
string are just lists of characters.

++ : !!

lists can also contain lists.

when using <, <=, > and >= to compare lists, they are compared in lexicographical order.

head tail last init length null reverse take drop maximum minimum sum product elem

## Texas ranges

.. cycle repeat

## List comprehension

```
[x*2 | x <- [1..10]]
```

the weeding out lists by predicates is also called filtering,

_

## Tuples

a tuple can contain a combination of several types.

fst snd zip

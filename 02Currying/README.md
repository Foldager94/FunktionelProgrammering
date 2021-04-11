## The principle of currying

> The Principle of currying is to make functions that takes multiple arguments when called, to a series of functions that takes a single argument
> Not curried:`f : (a,b) -> c ` <br>
> Curried:` f : a -> b -> c` <br>
> Curried functions allows us to take advantage of lazy evalutation and partial application

## How to implement and use currying in Elm and Haskell

> #### Elm <br>
>
> `add : Int -> Int -> Int <br> ` >`add x y = x + y` >`add5 = add 5` >`result = add5 10 ` >`result = 15 // true `
>
> #### Haskell <br>

## Typical currying use cases

> Partial application

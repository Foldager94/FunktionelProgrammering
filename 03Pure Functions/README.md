## When can a function be defined as pure

> If the functions does not have any side effect
> Given the same input the function must return the same output
> The function needs consisten behavier

## What is a side effect

> A side effect is any change in the system that is observable to the outside world
> Like printing a result to the screen
> function is said to have a side effect if it modifies some state variable values outside its local environment

### when to avoid

> When creating functions. This is a way to keep the functions pure, and easy to test and refactor

### when to embrace

> When you need to show something to the user
> If you need to write to a file or a database

## How to handle polymorphism using union types

> Union types allowes us to store different data in the same memory spot
> In elm and haskell we can use the 'Maybe' tag.
>
> ```
> type Maybe x
>   = just x
>   | Nothing
> ```
>
> ```
> data Maybe x
>   = Nothing
>   | just x
> ```

## How to handle errors using union types

> We would be useing maybe or nothing

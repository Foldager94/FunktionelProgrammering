## How to use pattern matching to destruct various data structures as:

Pattern matching is the act of checking one or more inputs against a pre-defined pattern and seeing if they match.

### lists

In this example we see a a function using pattern matching. In this case the function will take a list and see if the list is empty.

```elm
--Elm

isEmpty : List a -> Bool
isEmpty xs =
    case xs of
        [] ->
            True

        _ ->
            False
```

### tuples

### records

### union types

This was the original `workflows/deploy` and `workflows/test` files.
I decided to make a main workflow referencing these files where the `workflows/deploy` will only start after the `workflows/test` has finished and passed.

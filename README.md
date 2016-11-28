# typelevel-fizzbuzz

You have your series you know and love: 
1, 2, Fizz, 4, Buzz, ...

Now let's ask the compiler to build it for us in the form of the type of a shapeless `HList`, so we have:

_1 :: _2 :: Fizz :: _4 :: Buzz :: Fizz :: _7 ....

Credit to Miles (who else?) for implementing it as an example in shapeless. This is a variation that uses a typelevel range which is then mapped with a poly function to the desired series. Particular focus was put into making the typelevel code as expressive as possible. As with anything of this ilk, don't do this at home! This is just for entertainment purposes.

Enjoy.

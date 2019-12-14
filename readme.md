### Mandelbrot
## whta's going on inside  [-1 and 1]


Well, let’s take 2 and see the sequence.

2, 4, 16, 256… and so on. It quickly gets larger and larger, approaching infinity.

Let’s start with 0.5:

0.5, 0.25, 0.0625, 0.00390625… It is quickly approaching zero.

How about 1?

1, 1, 1, 1… Boring.

And negative numbers immediately turn positive and follow the same sequences.

So, we can see that any number between -1 and 1 (inclusive) will not go to infinity, and any number greater than 1 or smaller than -1 will. The closer it is to 1 when it starts, the slower it will move away from 1.

Now, imagine we are talking about 2D numbers. Technically we are not talking about vectors, but for now don’t worry about how they work, just see them as x and y pairs.

A 2D version of the above gives us a circle with radius 1, within which the 2D numbers decay to zero, and outside numbers shoot off to the infinite borders.

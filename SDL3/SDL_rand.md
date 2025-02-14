###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_rand

Generate a pseudo-random number less than n for positive n

## Header File

Defined in [<SDL3/SDL_stdinc.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_stdinc.h)

## Syntax

```c
Sint32 SDL_rand(Sint32 n);
```

## Function Parameters

|        |       |                                                      |
| ------ | ----- | ---------------------------------------------------- |
| Sint32 | **n** | the number of possible outcomes. n must be positive. |

## Return Value

(Sint32) Returns a random value in the range of [0 .. n-1].

## Remarks

The method used is faster and of better quality than `rand() % n`. Odds are
roughly 99.9% even for n = 1 million. Evenness is better for smaller n, and
much worse as n gets bigger.

Example: to simulate a d6 use `SDL_rand(6) + 1` The +1 converts 0..5 to
1..6

If you want to generate a pseudo-random number in the full range of Sint32,
you should use: (Sint32)[SDL_rand_bits](SDL_rand_bits)()

If you want reproducible output, be sure to initialize with
[SDL_srand](SDL_srand)() first.

There are no guarantees as to the quality of the random sequence produced,
and this should not be used for security (cryptography, passwords) or where
money is on the line (loot-boxes, casinos). There are many random number
libraries available with different characteristics and you should pick one
of those to meet any serious needs.

## Thread Safety

All calls should be made from a single thread

## Version

This function is available since SDL 3.1.3.

## See Also

- [SDL_srand](SDL_srand)
- [SDL_randf](SDL_randf)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryStdinc](CategoryStdinc)


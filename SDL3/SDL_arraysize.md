###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_arraysize

The number of elements in an array.

## Header File

Defined in [<SDL3/SDL_stdinc.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_stdinc.h)

## Syntax

```c
#define SDL_arraysize(array) (sizeof(array)/sizeof(array[0]))
```

## Remarks

This macro looks like it double-evaluates the argument, but it does so
inside of `sizeof`, so there are no side-effects here, as expressions do
not actually run any code in these cases.

## Version

This macro is available since SDL 3.1.3.

----
[CategoryAPI](CategoryAPI), [CategoryAPIMacro](CategoryAPIMacro), [CategoryStdinc](CategoryStdinc)


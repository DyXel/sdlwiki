###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_MouseWheelDirection

Scroll direction types for the Scroll event

## Header File

Defined in [<SDL3/SDL_mouse.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_mouse.h)

## Syntax

```c
typedef enum SDL_MouseWheelDirection
{
    SDL_MOUSEWHEEL_NORMAL,    /**< The scroll direction is normal */
    SDL_MOUSEWHEEL_FLIPPED    /**< The scroll direction is flipped / natural */
} SDL_MouseWheelDirection;
```

## Version

This enum is available since SDL 3.1.3.

----
[CategoryAPI](CategoryAPI), [CategoryAPIEnum](CategoryAPIEnum), [CategoryMouse](CategoryMouse)


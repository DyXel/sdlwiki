###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_HINT_JOYSTICK_HIDAPI

A variable controlling whether the HIDAPI joystick drivers should be used.

## Header File

Defined in [<SDL3/SDL_hints.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_hints.h)

## Syntax

```c
#define SDL_HINT_JOYSTICK_HIDAPI "SDL_JOYSTICK_HIDAPI"
```

## Remarks

The variable can be set to the following values:

- "0": HIDAPI drivers are not used.
- "1": HIDAPI drivers are used. (default)

This variable is the default for all drivers, but can be overridden by the
hints for specific drivers below.

This hint should be set before enumerating controllers.

## Version

This hint is available since SDL 3.1.3.

----
[CategoryAPI](CategoryAPI), [CategoryAPIMacro](CategoryAPIMacro), [CategoryHints](CategoryHints)


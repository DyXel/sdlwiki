###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_GetGamepadStringForAxis

Convert from an [SDL_GamepadAxis](SDL_GamepadAxis) enum to a string.

## Header File

Defined in [<SDL3/SDL_gamepad.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_gamepad.h)

## Syntax

```c
const char * SDL_GetGamepadStringForAxis(SDL_GamepadAxis axis);
```

## Function Parameters

|                                    |          |                                                               |
| ---------------------------------- | -------- | ------------------------------------------------------------- |
| [SDL_GamepadAxis](SDL_GamepadAxis) | **axis** | an enum value for a given [SDL_GamepadAxis](SDL_GamepadAxis). |

## Return Value

(const char *) Returns a string for the given axis, or NULL if an invalid
axis is specified. The string returned is of the format used by
[SDL_Gamepad](SDL_Gamepad) mapping strings.

## Version

This function is available since SDL 3.1.3.

## See Also

- [SDL_GetGamepadAxisFromString](SDL_GetGamepadAxisFromString)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryGamepad](CategoryGamepad)


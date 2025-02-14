###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_GetWindowFlags

Get the window flags.

## Header File

Defined in [<SDL3/SDL_video.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_video.h)

## Syntax

```c
SDL_WindowFlags SDL_GetWindowFlags(SDL_Window *window);
```

## Function Parameters

|                            |            |                      |
| -------------------------- | ---------- | -------------------- |
| [SDL_Window](SDL_Window) * | **window** | the window to query. |

## Return Value

([SDL_WindowFlags](SDL_WindowFlags)) Returns a mask of the
[SDL_WindowFlags](SDL_WindowFlags) associated with `window`.

## Version

This function is available since SDL 3.1.3.

## See Also

- [SDL_CreateWindow](SDL_CreateWindow)
- [SDL_HideWindow](SDL_HideWindow)
- [SDL_MaximizeWindow](SDL_MaximizeWindow)
- [SDL_MinimizeWindow](SDL_MinimizeWindow)
- [SDL_SetWindowFullscreen](SDL_SetWindowFullscreen)
- [SDL_SetWindowMouseGrab](SDL_SetWindowMouseGrab)
- [SDL_ShowWindow](SDL_ShowWindow)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryVideo](CategoryVideo)


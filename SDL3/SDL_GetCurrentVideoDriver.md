###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_GetCurrentVideoDriver

Get the name of the currently initialized video driver.

## Header File

Defined in [<SDL3/SDL_video.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_video.h)

## Syntax

```c
const char * SDL_GetCurrentVideoDriver(void);
```

## Return Value

(const char *) Returns the name of the current video driver or NULL if no
driver has been initialized.

## Remarks

The names of drivers are all simple, low-ASCII identifiers, like "cocoa",
"x11" or "windows". These never have Unicode characters, and are not meant
to be proper names.

## Version

This function is available since SDL 3.1.3.

## See Also

- [SDL_GetNumVideoDrivers](SDL_GetNumVideoDrivers)
- [SDL_GetVideoDriver](SDL_GetVideoDriver)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryVideo](CategoryVideo)


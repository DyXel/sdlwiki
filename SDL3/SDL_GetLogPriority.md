###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_GetLogPriority

Get the priority of a particular log category.

## Header File

Defined in [<SDL3/SDL_log.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_log.h)

## Syntax

```c
SDL_LogPriority SDL_GetLogPriority(int category);
```

## Function Parameters

|     |              |                        |
| --- | ------------ | ---------------------- |
| int | **category** | the category to query. |

## Return Value

([SDL_LogPriority](SDL_LogPriority)) Returns the
[SDL_LogPriority](SDL_LogPriority) for the requested category.

## Thread Safety

It is safe to call this function from any thread.

## Version

This function is available since SDL 3.1.3.

## See Also

- [SDL_SetLogPriority](SDL_SetLogPriority)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryLog](CategoryLog)


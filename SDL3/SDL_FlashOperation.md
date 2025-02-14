###### (This is the documentation for SDL3, which is the current stable version. [SDL2](https://wiki.libsdl.org/SDL2/) was the previous version!)
# SDL_FlashOperation

Window flash operation.

## Header File

Defined in [<SDL3/SDL_video.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_video.h)

## Syntax

```c
typedef enum SDL_FlashOperation
{
    SDL_FLASH_CANCEL,                   /**< Cancel any window flash state */
    SDL_FLASH_BRIEFLY,                  /**< Flash the window briefly to get attention */
    SDL_FLASH_UNTIL_FOCUSED             /**< Flash the window until it gets focus */
} SDL_FlashOperation;
```

## Version

This enum is available since SDL 3.1.3.

----
[CategoryAPI](CategoryAPI), [CategoryAPIEnum](CategoryAPIEnum), [CategoryVideo](CategoryVideo)


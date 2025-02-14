###### (This function is part of SDL_ttf, a separate library from SDL.)
# TTF_Text

Text created with [TTF_CreateText](TTF_CreateText)()

## Header File

Defined in [<SDL3_ttf/SDL_ttf.h>](https://github.com/libsdl-org/SDL_ttf/blob/main/include/SDL3_ttf/SDL_ttf.h)

## Syntax

```c
typedef struct TTF_Text
{
    char *text;             /**< A copy of the text used to create this text object, useful for layout and debugging. This will be freed automatically when the object is destroyed. */
    int num_lines;          /**< The number of lines in the text, 0 if it's empty */

    int refcount;           /**< Application reference count, used when freeing surface */

    TTF_TextData *internal; /**< Private */

} TTF_Text;
```

## Version

This struct is available since SDL_ttf 3.0.0.

## See Also

- [TTF_CreateText](TTF_CreateText)
- [TTF_GetTextProperties](TTF_GetTextProperties)
- [TTF_DestroyText](TTF_DestroyText)

----
[CategoryAPI](CategoryAPI), [CategoryAPIStruct](CategoryAPIStruct)


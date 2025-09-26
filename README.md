# renpy-help

# Japanese text not rendering
1. Download a japanese font. [Example](https://fonts.google.com/noto/specimen/Noto+Sans+JP) (You'll probably have to use one of the fonts provided inside of the `static` folder).
2. Add the font file (.ttf) to the `game` folder.
3. on `options.rpy` add the following:
```py
## Fonts and Font Sizes ########################################################

define gui.text_font = "fonts/font.ttf" # Example for general text
define gui.name_text_font = "fonts/font.ttf" # Example for character names
define gui.interface_text_font = "fonts/font.ttf" # Example for interface text
```

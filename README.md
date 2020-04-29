# Affinity Macro Library

## Sprite Sheets

[Download](https://github.com/narranoid/Affinity-Macro-Library/raw/master/SpriteSheets.afmacros)  
[Tutorial]()

The sprite sheet macros feature a variety of tricks for quickly generating sprite sheets out of your layer stack.
I made a tutorial on how to use them including various other tricks for creating sprite sheets.
Check it out [here]().

### Tile Bounding Box

Creates a bounding box for your tile. This helps by spreading the sprites using alignment tools, because every sprite layer will have the same boundaries. The bounding box box covers the dimensions of the document/artboard and can be scaled afterwards.

### Scaled Tile Bounding Box

Tile bounding box feature including a scale factor to immediately shrink sprite layers, so they all fit on the sheet.

### Tile Line

Aligns sprites in a horizontal line. Layers including the tile bounding box will be distributed with proper spacing for a sprite sheet containing animation.

### Tile Line Shift

Used to shift tile lines down and to the right. If the tile line doesn't fit the document along the width, but there is space along the height of the document, this macro can be used to quickly duplicate and move the lines so all sprites are visible on the document.

### Plain Bounding Box

Just creates an invisible bounding box of the document bounds.

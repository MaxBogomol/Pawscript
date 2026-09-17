# Pawscript

Pawscript is a pixel font that was originally created for [Paw Paint DS](https://github.com/MaxBogomol/PawPaintDS).

# Files

`/sprites` - font sprites.  
`/chars/chars.md` - characters used in sprites.  
`/chars/unicode.md` - unicode codes for characters used in sprites.  
`/chars/length.md` - characters whose length differs from 6 pixels.  

# Font display

This font is created as pixel sprites, so if you want to use it in your project, you'll likely need to create your own rendering implementation. Example implementation in [Paw Paint DS](https://github.com/MaxBogomol/PawPaintDS).  
Each sprite contains a row of 8 characters.  
The characters in a standard sprite are 8 by 8 pixels.   
The characters in an extended sprite are 9 by 12 pixels, with a 3-pixel padding at the top. This size is needed for diacritics and other large characters.  
The length of each character is the length of the character sprite itself plus one pixel of padding.  
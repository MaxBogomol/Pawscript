[![License](https://img.shields.io/badge/%20-LICENSE-blue?style=for-the-badge&color=blue&logo=github&logoColor=000000&labelColor=FFFFFF)](https://github.com/MaxBogomol/Pawscript/blob/main/LICENSE.md)
[![Release](https://img.shields.io/github/v/release/MaxBogomol/Pawscript?style=for-the-badge&color=6aa84f&logo=github&label=PAWSCRIPT)](https://github.com/MaxBogomol/Pawscript/releases)
[![Github](https://img.shields.io/github/stars/MaxBogomol/Pawscript?style=for-the-badge&color=6aa84f&logo=github&label=PAWSCRIPT)](https://github.com/MaxBogomol/Pawscript)
[![TheFluffyVillage](https://img.shields.io/badge/%20-PAWSCRIPT-5800ff?style=for-the-badge&color=d77787&logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMTAiIGhlaWdodD0iMTAiIHZpZXdCb3g9IjAgMCAxMCAxMCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTYuNTAxODkgMEg4LjQ5ODAzVjIuOTQ4NzlMNi41MDE4OSAxLjc1MTEzVjBaIiBmaWxsPSJjdXJyZW50Q29sb3IiLz4KPHBhdGggZD0iTTEuNDAwMSA1LjNDMS40MDAxIDUgMC4xNTA2NTIgNC41IDAuMTUwNjUyIDYuM0MwLjY1MDY1IDUuOCAxLjE1MDY1IDUuOCAxLjQwMDEgNi4zVjUuM1oiIGZpbGw9ImN1cnJlbnRDb2xvciIvPgo8cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTUuNTAwMTQgNy4wMDAwMVYxMEgxLjUwMDY1QzAuNzcyMjIyIDEwIDAgOS4zMjg0MyAwIDguNTAwMDFDMCA3LjY3MTU4IDAuNjcxNTcgNy4wMDAwMSAxLjM5OTk5IDcuMDAwMDFWNy43NTAwMUMxLjA4NTc4IDcuNzUwMDEgMC43NDk5OTcgOC4xMDQ0NCAwLjc0OTk5NyA4LjUwMDAxQzAuNzQ5OTk3IDguODk1NTggMS4xODU4NCA5LjI1IDEuNTAwMDUgOS4yNUwxLjUwMDE2IDMuOTk5ODNMMC4wMDAxNjQ1MDEgMy45OTk4NUwxLjY2MDg3IDMuMDAzMzhDMS42NjA4NyAxLjk5OTgyIDEuNjYwODcgMS41MzI5OCAyLjI1MDE1IDAuOTk5ODVDMi4yNTAxNSAxLjM5OTgyIDIuMjUwMTUgMS44NDAyNiAyLjYwMDE1IDEuOTk5ODJDMi42MDAxNSAxLjMyMjg3IDIuODU0OTQgMC45OTk4NSAzLjQ1ODY2IDAuNTYyNTY0QzMuNTAwMTUgMS4wOTk4MiAzLjUwMDE1IDEuNDk5ODIgNC4wMTI5NiAxLjU5MjA2TDQuOTk5OTIgMC45OTk4NUwxMCAzLjk5OTg1TDguNDk4MDMgNC4wMDAwMUw4LjQ5Nzk4IDYuNzUwMTZDOC45OTQxMiA2Ljc1MDE2IDkuMzQ4MTQgNi43NTAxNiA5LjQ5ODAyIDYuMjUwMTZDOS40OTgwMiA2LjI3ODggOS40OTggNy4wNDIgOC45OTQxMiA3LjY4NDkxQzkuMDk1NjggNy44MDA3OCA5LjI0NDEyIDcuOCA5LjQ4NjMxIDcuNjg0OTFDOS4zMDI3MSA4LjQgOC45OTQxMiA4LjUgOC40OTgwMyA4LjVWMTBINy41MDAxM1Y3LjAwMDAxSDUuNTAwMTRaTTIuNTAwMDMgOC40OTk4NFY1Ljk5OTg1SDQuNTAwMDNWOC40OTk4NEgyLjUwMDAzWiIgZmlsbD0iY3VycmVudENvbG9yIi8+Cjwvc3ZnPg==&logoColor=000000&labelColor=FFFFFF)](https://fluffy-village.dev/pages/eng/creations/pawscript.html)
[![Discord](https://img.shields.io/discord/1155188824360624148?style=for-the-badge&color=6aa84f&logo=discord&label=THE%20FLUFFY%20VILLAGE)](https://discord.fluffy-village.dev/)

# Pawscript

Pawscript is a pixel font that was originally created for [Paw Paint DS](https://github.com/MaxBogomol/PawPaintDS).

![](https://fluffy-village.dev/assets/creations/pawscript/pawscript.png)

# Writing systems

- Latin
- Greek
- Cyrillic
- Hebrew

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
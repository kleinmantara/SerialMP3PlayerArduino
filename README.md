# Useful hints for the serial mp3 player (YX5300 chip)
- Directories **must be** consecutively numbered `##`
  - There must be **always** a `01` directory
  - No gaps in the numbering
  - No sub directorys
  - No files in the SD card root directory
  - No other files than wav or mp3 in the directorys
- The files **must be** consecutively numbered `###${NAME}`
  - Also **across** directory boundaries
  - No gaps in the numbering
- On a Mac:
  - remove all hidden mac files
    - see https://www.techwalla.com/articles/how-to-show-and-hide-hidden-files-on-mac-os-x

Example:
```
/-+- `01`
  |   + `001_Happy_Dance.mp3`
  |   + `002-O_Sole_Mio.mp3`
  |
  +- `02`
  |   + `003Humpty_Dumpty.mp3`
  |   + `004-Incy_Wincy_Spider.mp3`
  |   + `005-Grand_Duke.mp3`
  | 
  +- `03`
      + `006-Fernando.mp3`
      + `007-Mamma_Mia.mp3`
```

## Arduino Librarys
- https://github.com/MajicDesigns/MD_YX5300
- https://github.com/salvadorrueda/SerialMP3Player

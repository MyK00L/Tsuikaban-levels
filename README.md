# Tsuikaban-levels
M's Tsuikaban's levels

## Attribution

The levels hereby provided are designed by:
- [MyK00L](https://github.com/myk00l)

## Level file specification
```
6 10
##########
#.....##D#
#........#
#.....####
#.....####
##########
1 1
9
2 2 255 0 0 1
3 2 255 0 0 2
4 2 255 0 0 3
4 3 0 255 255 3
3 3 0 255 255 2
2 3 0 255 255 1
6 2 0 255 255 -2
7 2 255 0 0 -4
8 2 0 255 255 -4
```
- The first line contains two integers: the `height` and the `width` of the board
- The second to the `height + 1` lines contain the map:
  - A `#` is used to represent a wall
  - A `.` is used to represent a free block
  - A `D` is used to represent a door
- The next line contains the initial position (`y`, `x`) of the player
- The following line contains the number of coloured blocks in the board
- Each following line contains:
  - `y x` coordinates of the block
  - `r g b` components of the block
  - `n`, the value of the block

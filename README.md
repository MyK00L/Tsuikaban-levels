# Tsuikaban-levels
M's Tsuikaban's levels

## Attribution

The levels hereby provided are designed by:
- [MyK00L](https://github.com/myk00l) (0-16)

## Level file specification
```
4 12
############
#..........#
######...#D#
############
1 1
2
3 1 255 0 0 1
5 1 0 0 255 1
```
- The first line contains two integers: the `height` and the `width` of the board
- The second to the `height + 1` lines contain the map:
  - A `#` is used to represent a wall
  - A `.` is used to represent a free block
  - A `D` is used to represent a door
- The next line contains the initial position (`x`, `y`) of the player
- The following line contains the number of coloured blocks in the board
- Each following line contains:
  - `x y` coordinates of the block
  - `r g b` components of the block
  - `n`, the value of the block

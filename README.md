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
3 1 255 95 75 1
5 1 30 142 184 1
```
- The first line contains two integers: the `height` and the `width` of the board
- The next `height` lines contain the map:
  - `#` is used to represent a wall tile
  - `.` is used to represent a floor tile
  - `D` is used to represent a door tile
- The next line contains the initial position (`x`, `y`) of the player
- The following line contains the number of coloured `Cubes` in the board
- Each following line contains:
  - `x y` coordinates of the cube
  - `r g b` components of the cube
  - `n`, the value of the cube

## Color scheme

* ![#CF7ADB](https://www.colorbook.io/imagecreator.php?hex=CF7ADB&width=100&height=50) `rgb(207, 122, 219)`
* ![#FF5F4B](https://www.colorbook.io/imagecreator.php?hex=FF5F4B&width=100&height=50) `rgb(255, 95, 75)`
* ![#FFDB66](https://www.colorbook.io/imagecreator.php?hex=FFDB66&width=100&height=50) `rgb(255, 219, 102)`
* ![#1E8EB8](https://www.colorbook.io/imagecreator.php?hex=1E8EB8&width=100&height=50) `rgb(30, 142, 184)`
* ![#8ABDFF](https://www.colorbook.io/imagecreator.php?hex=8ABDFF&width=100&height=50) `rgb(138, 189, 255)`
* ![#FF954A](https://www.colorbook.io/imagecreator.php?hex=FF954A&width=100&height=50) `rgb(255, 149, 74)`
* ![#8F2B62](https://www.colorbook.io/imagecreator.php?hex=8F2B62&width=100&height=50) `rgb(143, 43, 98)`
* ![#CAFF42](https://www.colorbook.io/imagecreator.php?hex=CAFF42&width=100&height=50) `rgb(202, 255, 66)`
* ![#4C4DEB](https://www.colorbook.io/imagecreator.php?hex=4C4DEB&width=100&height=50) `rgb(76, 77, 235)`
* ![#70C88C](https://www.colorbook.io/imagecreator.php?hex=70C88C&width=100&height=50) `rgb(112, 200, 140)`
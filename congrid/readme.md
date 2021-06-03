# Congrid Information
## Example
```py
import congrid as c
grid = c.newGrid(5, 5)
grid.plot(4, 4, "1")
grid.plot(3, 4, "purple_1b")
grid.plot(2, 4, "green")
grid.plot(1, 4, "73")
grid.plot(0, 4, "6")
grid.show()
```
## Documentation
### `newGrid()`
Returns a Grid.
### `Grid` Object
#### `Show`
Prints grid to the console.
#### `Plot`
Plot a grid.

`grid.plot(x, y, color)`

`x` - int
`y` - int
`color` - string, defaults to the default color set in `newGrid()`
## Colors
![List Of Colors](https://congridimgs.ucyt5040.repl.co/g.png)
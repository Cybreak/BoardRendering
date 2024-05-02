## How to install

1, Run ``pip install BoardRendering`` in Console

2, Your done

## Examples
```
from BoardRendering import Board

board = Board(size=3, default="0")
board.set((2, 1), "1")

print(board.display)

# Result:
 # 000
 # 001
 # 000

```

# Problem
## By [HackerRank](www.hackerrank.com)

> Given an integer, <a href="https://www.codecogs.com/eqnedit.php?latex=n" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n" title="n" /></a>, print its first <a href="https://www.codecogs.com/eqnedit.php?latex=10" target="_blank"><img src="https://latex.codecogs.com/gif.latex?10" title="10" /></a> multiples. Each multiple <a href="https://www.codecogs.com/eqnedit.php?latex=n&space;\times&space;i" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n&space;\times&space;i" title="n \times i" /></a> (where <a href="https://www.codecogs.com/eqnedit.php?latex=1&space;\le&space;i&space;\le&space;10" target="_blank"><img src="https://latex.codecogs.com/gif.latex?1&space;\le&space;i&space;\le&space;10" title="1 \le i \le 10" /></a>) should be printed on a new line in the form: n x i = result.

## Thought Process

* 10 multiples (for loop with range())
* print (f string)

## Code

```
# n, as int, is given from hackerrank.
# range(x, y) where x is inclusive and default is 0 and where y is exclusive and no default.
for i in range(1, 11):
  print(f'{n} x {i} = {n*i}')
```

## Final Code

```
#!/bin/python3

import math
import os
import random
import re
import sys

if __name__ == '__main__':
    n = int(input())
    
    for i in range(1,11):
      print(f'{n} x {i} = {n*i}')
```

# Conclusion
Finally figured out that I was supposed to be creating all of my code under the `if __name__ == '__main__':` part. How silly :)

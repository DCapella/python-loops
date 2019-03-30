# Problem
## By [HackerRank](www.hackerrank.com)

> Given an integer, %n%, print its first %10% multiples. Each multiple %n x i% (where 1 %\lte i \lte 10%) should be printed on a new line in the form: n x i = result.

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

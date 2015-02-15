# pytsort
Topological Sorting in Python. Works on both Python >=2.6 and >=3.2.

# Example
```
from tsort import tsort
from pprint import pprint

data = {
    2: {11},
    9: {11, 8},
    10: {11, 3},
    11: {7, 5},
    8: {7, 3},
}

out = tsort(data, smallest_first=True)
pprint(out)
```

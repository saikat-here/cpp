# Vector

1. Dynamic array. Its will resize when the allocated memory gets full
2. The new allocation will be 2x of the current size. It starts with allocating size for 1 element (int, flow, pointer etc) and gets double (2x) upon used the allocated space.

## Syntax

```
#include <vector> 
vector<int> MyVector
```

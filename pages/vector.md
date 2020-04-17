# Vector

1. Dynamic array. Its will resize when the allocated memory gets full
2. The new allocation will be 2x of the current size. It starts with allocating size for 1 element (int, flow, pointer etc) and gets double (2x) upon used the allocated space.
3. The existing elements will be copied to to newly allocated memory. So, resizing is a costly operation. It's better to set the size if the size is known using vector::reserve(size_type n).

### Syntax

```
#include <vector> 
vector<int> MyVector
```
### Methods and more details
[Click Here](http://www.cplusplus.com/reference/vector/vector/)

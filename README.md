Tom Forsyth's [Linear-Speed Vertex Cache Optimisation](http://home.comcast.net/~tom_forsyth/papers/fast_vert_cache_opt.html) algorithm implementation by [Martin Storsjo](http://www.martin.st/thesis/) in header file single-file library.

Add `#define FORSYTH_IMPLEMENTATION` before `#include "forsyth.h"` in **one** .c or .cpp file to create the implementation.

Usage:
```c
forsythReorderIndices(outIndices, indices, numTriangles, numVertices);
```

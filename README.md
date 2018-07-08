```c
#include "macro_add.h"
#define N1 3
#define N2 5
#define NX MACRO_ADD(N1, N2)
/* NX is 8 */
#define STR(s) #s
#define NXSTR STR(NX)
/* NXSTR is "8" */
```

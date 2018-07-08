```c
#include "macro_add.h"

#define N MACRO_ADD(1, 2)
/* N is 3 */

#define X 4
#define ADD_2X MACRO_ADD(2, X)
/* ADD_2X is 6 */

#define Y 7
#define ADD(n1, n2) MACRO_ADD(n1, n2)
#define ADD_XY ADD(X, Y)
/* ADD_XY is 11 */

```

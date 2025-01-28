# C9-libs
 
This repo contains libraries for the C9 language. Development of these helper libraries is done here, not in the language spec repo.
All libraries are implemented as implementation only, ie no header files. The libraries are not self contained, so make sure you copy all #included files to your project.

## Libraries

- `arena.c`: Simple growing arena allocator
- `array.c`: Dynamic array type and array functions
- `random.c`: Fast pseudo random number generator
- `status.c`: Status code struct type
- `string.c`: String type and string functions
- `types.c`: Basic int and float types
- `types_print.c`: Print functions for basic types

## Usage

The libraries are implemented for direct inclusion in your source files. To use them, copy the `.c` files to your tree and include them where you need them:

```c
#include "array.c"
```

All `.c` files have include guards, so you can include them in multiple places without issues.

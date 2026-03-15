# DZ (DZecko) / DZ++ (DZépépé)

The eastern slovak library for C (and C++). Why? Because we could, of course!

## Using

This project resides solely in a single header file, aptly named `easternslovak.h`.
Download that file alone, or along this whole repository, and then, after
including it in your source files like you would with any other header, you
will be fully set up! (Just make sure you use relatively modern compiler)

## Integrated transpiler
For testing, we also provide C to DZ and reverse transpiler in the file
`translate.py`. Launch it with `./translate.py to easternslovak.h path/to/your/C/file.c path/to/new/DZ/file.dz`

## Obligatory "Hello World" example

```c
#include "easternslovak.h"
#include <stdio.h>

cifra perša( praznota ) {
    vycišnif( "PanBohpozdrav švet, ta ňe?\n" );
    vracšezos 0;
}
```

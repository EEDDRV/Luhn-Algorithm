# Luhn-algorithm
A simple checksum formula used to validate a variety of identification numbers, such as credit card numbers, IMEI numbers, etc.

# Usage
```c
#include "Luhn_algorithm.h"
```
```c
char * number = "4263982640269299";
bool IsTrue = checkLuhn(number);
```
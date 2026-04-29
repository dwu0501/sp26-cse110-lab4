1. The bug was that variables num1 and num2 were treated as strings, which made the sum become string concatenation instead of an actual numeric sum.
2. The solution is to call the Number() on both variables so we have the sum we want.

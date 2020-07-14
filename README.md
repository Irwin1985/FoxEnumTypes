# FoxEnumTypes
A `built-in` function that emulates the enum data types

## Examples
```xBase
// declare the FoxProperty Prg
Set Procedure to "FoxEnumTypes" Additive

// Creating an enumerable type
loColor = Enum("RED, BLUE, GREEN")
?loColor.RED && 1

// You may also provide a default value.
loColor = Enum("RED = 5, BLUE, GREEN")
?loColor.GREEN && 7
```

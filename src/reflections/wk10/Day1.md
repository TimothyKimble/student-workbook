# C# Data Types (Day 1)

## What are the three categories of data types? How are they different?
The three categories of data types are value types, reference types, and pointer types. A value type holds it's own data value within it's own memory space. The variables of these data types directly contain values. A reference type doesn't store its value directly. Instead, it stores the address where the value is being stored. Pointer types do not inherit from objects and no conversions exist between pointer types and objects.
## What are the Value-type data types? What differences do you notice from JavaScript?
The value-type data types consist of the following: bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort. One big difference I've noticed is that in Javascript, we don't need to really call out if a number is a decimal, but in C# there are tons of different types for number values. 

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
Reference types are stored in memory by their location rather than their actual value. The difference between reference types and value types is that reference types are stored by locations in memory, meanwhile value types are stored by their actual value. 

## Afternoon Challenge Rock Paper Scissors in C#
https://github.com/TimothyKimble/Rock_Paper_Scissors_C_Sharp
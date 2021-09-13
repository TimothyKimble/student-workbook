# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The purpose of a namespace in C# is to arrange classes, structs, interfaces, enums and delegates.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types meanwhile classes are reference types. Structs are stored on the stack while classes are stored on the heap. 
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
It is set to public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string is the indication of the type of return that should come from the function. 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The abstract is preventing other classes from inheriting the class car that were previously marked as virtual. 
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The override keyword is used to extend or modify a virtual/abstract method, property, indexer, or event of base class into a derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Four differenct access modifiers that you can use are as follows: private, which makes an object only accessible inside it's own class or structure. Public, which are accessible from everywhere in your project. Protected which implies that the object is accessible inside the class and in all classes that derive from that class. The fourth would be Internal, which specifies that the object is accessible only inside it's own assembly but not in other assemblies. 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The only thing that can access that private class or method would be it's own class that it was created in. 
```
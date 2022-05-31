# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a class that holds methods and variables that can be called across a workspace.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are like class-lyte. They can be used to build objects that behave like class objects.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
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
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
string is an indication of the return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract means that its meant to be instantiated as part of a base class and not on its own. It sort of narrows the scope.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual means its able to overwritten.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, private, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
It can only be accessed from wihtin the file.
```
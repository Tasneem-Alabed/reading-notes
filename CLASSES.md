# Classes and memory management 

## What is the difference between a static and an instance constructor?
     Static constructors allow you to initialize static variables in a class, or do other things needed to do in a class after it's first referenced in your code. They are called only once each time your program runs.
Static constructors are declared with this syntax, and can't be overloaded or have any parameters because they run when your class is referenced by its name


Instance constructors are the ones that are called whenever you create new objects (instances of classes). They're also the ones you normally use in Java and most other object-oriented languages.
 You use these to give your new objects their initial state. These can be overloaded, and can take parameters

## How does the use of a static constructor differ from setting properties/values?

### Stack and Heap

A constructor is a method whose name is the same as the name of its type. Its method signature includes only an optional access modifier, the method name and its parameter list; it does not include a return type

Property accessors often consist of single-line statements that just assign or return the result of an expression. You can implement these properties as expression-bodied members. Expression body definitions consist of the  symbol followed by the expression to assign to or retrieve from the property

### Compare “Garbage Collection” in C# with the lifecycle of normal household items

In the common language runtime  the garbage collector (GC) serves as an automatic memory manager. The garbage collector manages the allocation and release of memory for an application. Therefore, developers working with managed code don't have to write code to perform memory management tasks. Automatic memory management can eliminate common problems such as forgetting to free an object and causing a memory leak or attempting to access freed memory for an object that's already been freed.

benefits:

1-Frees developers from having to manually release memory.

2-Allocates objects on the managed heap efficiently.

3-Reclaims objects that are no longer being used, clears their memory, and keeps the memory available for future allocations. Managed objects automatically get clean content to start with, so their constructors don't have to initialize every data field.

4-Provides memory safety by making sure that an object can't use for itself the memory allocated for another object.

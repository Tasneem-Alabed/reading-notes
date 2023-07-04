## Collections (C#)

it is a class another way to manage collection of objects it more flexible way to work with groups of objects

## Using a Simple Collection
it is enables to work with a strongly typed list of objects.

## Kinds of Collections
Some of the common collection classes are described in this section:

System.Collections.Generic classes

A generic collection is useful when every item in the collection has the same data type. A generic collection enforces strong typing by allowing only the desired data type to be added.



System.Collections.Concurrent classes

In .NET Framework 4 and later versions, the collections in the System.Collections.Concurrent namespace provide efficient thread-safe operations for accessing collection items from multiple threads.

The classes in the System.Collections.Concurrent namespace should be used instead of the corresponding types in the System.Collections.Generic and System.Collections namespaces whenever multiple threads are accessing the collection concurrently. For more information, see Thread-Safe Collections and System.Collections.Concurrent.


System.Collections classes

The classes in the System.Collections namespace do not store elements as specifically typed objects, but as objects of type Object.

Whenever possible, you should use the generic collections in the System.Collections.Generic namespace or the System.Collections.Concurrent namespace instead of the legacy types in the System.Collections namespace.

# Enumeration types (C# reference)

An enumeration type (or enum type) is a value type defined by a set of named constants of the underlying integral numeric type. To define an enumeration type, use the enum keyword and specify the names of enum members.By default, the associated constant values of enum members are of type int; they start with zero and increase by one following the definition text order. You can explicitly specify any other integral numeric type as an underlying type of an enumeration type. You can also explicitly specify the associated constant values,



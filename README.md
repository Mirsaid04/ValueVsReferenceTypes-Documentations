# Overview 

Hello everyone , Welcome to my Documentaion which is about `Value and Reference Type` , are you ready to get full information about both types , and stay with me , Thank you

![](./ValueVsReferenceTypes%20Documentations/Assets/Difference-Between-Value-Type-and-Reference-Type.webp)

1. What is the **Value Type** ? 

**Answers** =>

    1.1 Value types directly store the data value itself, which means they hold the actual data.

    1.2 They are typically stored on the stack (though there are exceptions like when they are part of a class).

    1.3 Value types are value semantics, meaning when you assign a value type to another variable or pass it as a method argument, a copy of the value is made.
    
    Common examples of value types in C# include:
    * Integral types: int, char, byte, short, long, bool, etc.
    * Floating-point types: float, double, decimal
    * Enums
    * Structs
    * Nullable value types (int?, double?) which can represent null values.

2. What is the **Reference Type** ?

**Answers** =>

    2.1 Reference types store a reference (or memory address) to the data, rather than the actual data itself.

    2.2 They are typically stored on the managed heap.

    2.3 Reference types are reference semantics, which means when you assign a reference type to another variable or pass it as a method argument, you are working with a reference to the same underlying object in memory.
    * Common examples of reference types in C# include:

    * Classes: User-defined types that can have methods, properties, and fields.
    * Strings: A sequence of characters.
    * Delegates: Function pointers that allow you to define methods to be executed.
    * Interfaces: Define a contract that classes can implement.
    * Arrays: A collection of elements that can be of any type (including other reference types or value types).

    

    ![](./ValueVsReferenceTypes%20Documentations/Assets/1_CrAxZeJZsgUiEUrby6BHow.jpg)
    

    

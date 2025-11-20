### What is C# ?
- C# is type-safe object-oriented language
- Enables developers to build a variety of secure and robust applications
- It was developed by Microsoft within the.NET Framework

### Design Goals of C# ?
- You can use C# to create traditional Windows Windows client applications, XML Web services, distributed components, client-server applications, database applications, WPF, MVC, .NET CORE etc...
- The language provides support for software engineering principles such as strong type checking, array bounds checking, automatic garbage collection etc

### Features of C# :
- C# fully supports OOP concepts,
- Its syntax is similar to C, C++, and Java, so it's easy for beginners and developers transitioning from other languages.
- No need to manually free memory. The .NET garbage collector automatically cleans unused objects.
- Key features: nullable value type, enumerations, delegates, lambda expressions, and direct memory access

### Advantages of c# ?
- Interoperability - "Interop" process enables C# programs to do almost anything that a native C++ application can do.
- Ease of Use - Syntax allows for users familiar with C, C++, or Java to easily Start coding in C# very effortlessly.

### What is boxing and unboxing concept in c# ?
- Boxing = Converting a Value Type → Reference Type (object)
- Unboxing = Converting Reference Type (object) → Value Type

- Boxing is the process of converting a value type into an object type.
- Unboxing is the process of extracting the value type from the object.

### What is implicit and explicit conversionn in c# ?
- Implicit conversion happens automatically when no data is lost.
The compiler converts the data type on its own.
- Explicit conversion happens when you forcefully convert one type to another.
You must write the cast manually

| Conversion Type | Safety          | Syntax          | Example        |
| --------------- | --------------- | --------------- | -------------- |
| **Implicit**    | Safe, automatic | No extra syntax | `int → double` |
| **Explicit**    | Risky, manual   | Use `(type)`    | `double → int` |


# C# and .NET Roadmap for Beginners

This document contains a simplified list of concepts to guide new developers through learning the basics of the C# programming language, and a brief introduction to the .NET ecosystem.

## Diagram

![C# and .NET Roadmap Diagram](https://raw.githubusercontent.com/gridlocdev/csharp-learning-roadmap/main/csharp-roadmap.drawio.svg)

## C#

- Learn the Fundamentals
  - [Basic Syntax](https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/tutorials/hello-world)
  - [Variables](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/variables) and [Data Types](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types)
    - [String](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types)
    - [Int](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)
    - [Boolean](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/bool)
    - [Float/Double/Decimal](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)
    - [Var](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/anonymous-types)
  - [Conditionals](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/selection-statements)
  - [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/methods)
  - [Collections](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)
    - [List](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1)
    - [Dictionary](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.dictionary-2)
    - [Array](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/)
  - [Loops](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/iteration-statements)
  - [Namespaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/namespaces)
  - [Using directives](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-directive)
  - [String Interpolation](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/tokens/interpolated)
- Object-Oriented Programming
  - Three Pillars
    - [Encapsulation](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/)
      - [Classes](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/classes)
      - [Structs](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/struct)
      - [Records](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/records)
    - [Inheritance](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/inheritance)
      - [Interfaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/interfaces)
      - [Abstract classes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/abstract)
    - [Polymorphism](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/polymorphism)
      - [Virtual](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/virtual)
      - [Override](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/override)
      - [Using Base Classes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/base)
  - [Access Modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
    - [Public](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/public)
    - [Private](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/private)
    - [Internal](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/internal)
    - [Protected](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/protected)
- Going Deeper
  - [Enums](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/enum)
  - [Object and Collection initializers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/object-and-collection-initializers)
  - [Lambdas](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
    - ["=>" Operator](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-operator)
    - [Arrow Functions](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
  - [Asynchronous Programming](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Threads](https://docs.microsoft.com/en-us/dotnet/standard/threading/using-threads-and-threading)
    - [Tasks](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Async](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/async)
    - [Await](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/await)
  - [Exception Handling](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/exceptions/exception-handling)
  - [Linq](https://docs.microsoft.com/en-us/dotnet/csharp/linq/)
  - [Generics](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/generics)
  - Immutability
    - [Readonly](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/readonly)
    - [Const](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/const)
  - [Static](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/static)
  - [Serialization](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/)

## .NET

With a solid understanding of the language features of C#, the .NET ecosystem has many options for your next path:

- Web Developer (.NET Core) : [Nick Chapsas - My .NET backend developer roadmap for 2022](https://www.youtube.com/watch?v=gw-6lKrKlp0)
- Desktop/Mobile Developer (Xamarin / .NET Maui) : [James Montemagno - Xamarin Tutorial for Beginners - Build iOS & Android Apps with C#, Visual Studio, and Xamarin.Forms](https://www.youtube.com/watch?v=zvp7wvbyceo)
- Data Engineer (Machine Learning with ML.NET) : [ML.NET Home](https://dotnet.microsoft.com/en-us/apps/machinelearning-ai/ml-dotnet)
- Game Developer (Unity) : [freeCodeCamp.org - Learn Unity - Beginner's Game Development Tutorial](https://www.youtube.com/watch?v=gB1F9G0JXOo)

| Web Developer (.NET Core) | Desktop/Mobile Developer (Xamarin / .NET Maui) |
|:---:|:---:|
| <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/.NET_Core_Logo.svg" width="100px" alt=".NET Core Logo"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Xamarin_logo_and_wordmark.png" width="225px" alt="Xamarin Logo"/> | 
| [Nick Chapsas - My .NET backend developer roadmap for 2022](https://www.youtube.com/watch?v=gw-6lKrKlp0) | [James Montemagno - Xamarin Tutorial for Beginners - Build iOS & Android Apps with C#, Visual Studio, and Xamarin.Forms](https://www.youtube.com/watch?v=zvp7wvbyceo) |

| Data Engineer (Machine Learning with ML.NET) | Game Developer (Unity) |
|:---:|:---:|
| <img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Mldotnet.svg" width="100px" alt="ML.NET Logo"/> | <img src="https://unity3d.com/profiles/unity3d/themes/unity/images/ui/ui/unity-logo-darkmode.min.svg" width="175px" alt="Unity Game Engine Logo"/> |
| [Microsoft - ML.NET Home](https://dotnet.microsoft.com/en-us/apps/machinelearning-ai/ml-dotnet) | [freeCodeCamp.org - Learn Unity - Beginner's Game Development Tutorial](https://www.youtube.com/watch?v=gB1F9G0JXOo) |

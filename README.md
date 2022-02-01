# C# and .NET Roadmap for Beginners

This document contains a simplified list of concepts to guide new developers through learning the basics of the C# and .NET ecosystem.

## Diagram

![C# and .NET Roadmap Diagram](https://raw.githubusercontent.com/gridlocdev/dotnet-learning-roadmap/main/csharp-roadmap.drawio.svg)

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

## .NET (Web Developer)

> This portion is still in progress! Feel free to suggest any items to add here if I haven't created a roadmap diagram for the below yet.

- Understanding the Ecosystem
  - .NET Framework
  - .NET Standard
  - .NET (Core)
- Tooling
  - [.NET CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/)
  - NuGet
- .NET (Core) Web Projects
  - Blazor WebAssembly
  - Minimal Web API
  - Web API
  - Razor Pages
  - Blazor Server
  - MVC
- Libraries
  - ORM
    - Entity Framework, Dapper
  - Testing
    - Unit Testing
      - xUnit, NUnit, MSTest
    - [Performance Testing](https://docs.microsoft.com/en-us/aspnet/core/test/load-tests?view=aspnetcore-6.0)
    - E2E Testing
      - Selenium
  - Logging
    - NLog, Serilog
  - Other
    - AutoMapper
    - Swashbuckle / Swagger

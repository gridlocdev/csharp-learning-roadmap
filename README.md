# C# and .NET Roadmap for Beginners

This document contains a simplified list of concepts to guide new developers through learning the basics of the C# and .NET ecosystem.

## Diagram

![C# and .NET Roadmap Diagram](https://raw.githubusercontent.com/gridlocdev/dotnet-learning-roadmap/main/dotnet-developer-roadmap.drawio.svg)

## C#

- Learn the Fundamentals
  - Basic Syntax
  - Variables and Data Types
    - String
    - Int
    - Double/Float/Decimal
    - Boolean
    - Var
  - [Conditionals](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/selection-statements)
  - [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/methods)
  - [Collections](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)
    - Array
    - List
    - Dictionary
  - [Iterators](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/iterators)
  - [Namespaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/namespaces) and [Using directives](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-directive)
  - [String Interpolation](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/tokens/interpolated)
  - [Exception Handling](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/exceptions/exception-handling)
- Object-Oriented Programming
  - Three Pillars
    - [Encapsulation](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/)
      - Classes
      - Structs
      - Records
    - [Inheritance](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/inheritance)
      - Interfaces
      - Abstract classes
    - [Polymorphism](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/polymorphism)
      - Virtual
      - Override
      - Base Constructor
  - [Access Levels](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
    - Public
    - Private
    - Internal
    - Protected
- Going Deeper
  - [Linq](https://docs.microsoft.com/en-us/dotnet/csharp/linq/)
  - [Object and Collection initializers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/object-and-collection-initializers)
  - [Lambdas](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
    - Lambda operator expressions
    - Arrow functions
  - [Asynchronous Programming](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - Async/await
    - Tasks and Threads
  - [Serialization](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/)
  - [Reflection](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/reflection)
  - (Optional) Functional Techniques
    - [Pattern Matching](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/pattern-matching)
    - [Discards](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/discards)
    - [Deconstructing Tuples](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/deconstruct)

## .NET (Web Developer)

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

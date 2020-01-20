# Module 2 - Generics

## A bit of history

First things first we should go back to **.NET Framework 1.0** where generics were not implemented yet - people used something like ***ArrayList*** to store data of different type in one place. This approach highly utilized *boxing/unboxing* feature of **.NET Framework** and therefore everyone had performance issues in some cases. Also potentially there could be an issue related ***type-safety*** - when we expecting one type, but instead receiving another and because of that all of our application could stop working.

So in order to eliminate such issues in **.NET Framework** Microsoft had implemented in **.NET Framework 2.0** so called *Generics*, below will be a basic definition of it from Microsoft:
* *Generics* let you tailor a method, class, structure, or interface to the precise data type it acts upon. For example, instead of using the Hashtable class, which allows keys and values to be of any type, you can use the ***Dictionary<TKey,TValue>*** generic class and specify the type allowed for the key and the type allowed for the value. Among the benefits of generics are increased code reusability and type safety.

## Links to internet resources

* [Generics in .NET](https://docs.microsoft.com/en-us/dotnet/standard/generics/) - here you can find information how **Generics** works in .NET (both .NET Core and .NET Framework), advantages and disadvantages and many more interesting information; **(EN/RU)**
* [Generics in C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/) - here you can find information how you can use **Generics** within your **C#** code; **(EN/RU)**
* [Generics in C# #2][https://professorweb.ru/my/csharp/charp_theory/level11/11_1.php] - here also you can find information how you can use **Generics** within your **C#** code; **(RU)**

## Links to books
* [CLR via C#](https://www.amazon.com/CLR-via-4th-Developer-Reference/dp/0735667454) - this book covers almost all information you may need to accomplish your tasks using **Generics**, see chapter with ***Chapter 12 - Generics***; **(EN/RU)**
* [C# in Depth](https://www.manning.com/books/c-sharp-in-depth-fourth-edition) - this book goes right from 1st version of **C#** to latest ones and explains how **C#** were evolving during the time and why **Generics** were implemented eventually; **(EN/RU)**
* [Pro .NET Performance: Optimize Your C# Applications](https://www.amazon.com/Pro-NET-Performance-Optimize-Applications/dp/1430244585) - this book mostly focused on optimization of **.NET** platform in general and you may found interesting about some feature with **Generics** in particular, see ***Chapter 5 - Collections and Generics***; **(EN/RU)**
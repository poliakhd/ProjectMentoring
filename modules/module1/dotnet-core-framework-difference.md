# Module 1 - .NET Core vs .NET Framework differences

The big and main difference is platform where we can use each of it:
* **.NET Core** is cross-platform and applications written on it can be run against most common operating systems, e.g.:
    * **Windows-based** - Windows 7, 10, etc. (full list of supported OS can be found [here](https://docs.microsoft.com/en-us/dotnet/core/install/dependencies?tabs=netcore22&pivots=os-windows));
    * **Linux-based** - Ubuntu, CentOS, Debian, etc. (full list of supported OS can be found [here](https://docs.microsoft.com/en-us/dotnet/core/install/dependencies?tabs=netcore22&pivots=os-linux))
    * **macOS-based** - Sierra, High Sierra, etc. (full list of supported OS can be found [here](https://docs.microsoft.com/en-us/dotnet/core/install/dependencies?tabs=netcore22&pivots=os-macos));
* **.NET Framewrok** is platform-dependent and apllication written on it can be run against Windows-based operating systems;

However this is not as simple as it could be seen, so in order to understand and select right one for your application, you must consider a lot of things, e.g. if you have following **.NET Core** would be a better choice:
* You have cross-platform needs;
* You are targeting microservices;
* You are using Docker containers;
* You need high-performance and scalable systems;
* You need side-by-side .NET versions per application;

As for **.NET Framework**:
* Your app currently uses .NET Framework (recommendation is to extend instead of migrating);
* Your app uses third-party .NET libraries or NuGet packages not available for .NET Core;
* Your app uses .NET technologies that aren't available for .NET Core;
* Your app uses a platform that doesn’t support .NET Core. Windows, macOS, and Linux support .NET Core;

## Links to internet resources

* [Choosing between .NET Core and .NET Framework](https://docs.microsoft.com/en-us/dotnet/standard/choosing-core-framework-server) - here you can find information about what to choose for your application as a framework; **(EN/RU)**

**\*** Microsoft eventually came to unification of **.NET platform** and if future there will no any of **.NET Core 4.x** or **.NET Framework 5.x** versions, but instead will be simple **.NET 5.x** - read this [article](https://devblogs.microsoft.com/dotnet/introducing-net-5/) if you are interested in future of .NET in general.
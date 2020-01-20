# Module 8 - Clean Architecture

**CQRS** separates reads and writes into different models, using commands to update data, and queries to read data.

Commands should be task based, rather than data centric. ("Book hotel room", not "set ReservationStatus to Reserved").
Commands may be placed on a queue for asynchronous processing, rather than being processed synchronously.
Queries never modify the database. A query returns a Dto that does not encapsulate any domain knowledge.

You should focus on such themes:
* **Clean Architecture** overview;
* **Clean Architecture** examples;
* **Clean Architecture** usage;

### Links to internet resources

* [NorthwindTraders Clean Architecture](https://github.com/JasonGT/NorthwindTraders/blob/master/Docs/Slides.pdf) - here you can find information about **Clean Architecture**; **(EN/RU)**
* [ NorthwindTraders Clean Architecture Repository](https://github.com/JasonGT/NorthwindTraders/tree/master/Src) - here you can find repository with examples of **NorthwindTraders Clean Architecture**; **(EN)**
* [Clean architecture](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#clean-architecture) - here you can find information about **Clean Architecture**; **(RU)**
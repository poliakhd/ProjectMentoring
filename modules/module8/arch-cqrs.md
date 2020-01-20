# Module 8 - CQRS

**CQRS** separates reads and writes into different models, using commands to update data, and queries to read data.

Commands should be task based, rather than data centric. ("Book hotel room", not "set ReservationStatus to Reserved").
Commands may be placed on a queue for asynchronous processing, rather than being processed synchronously.
Queries never modify the database. A query returns a Dto that does not encapsulate any domain knowledge.

You should focus on such themes:
* **CQRS** overview;
* **CQRS** usage;

### Links to internet resources

* [Command and Query Responsibility Segregation (CQRS)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs) - here you can find information about **CQRS** pattern; **(EN/RU)**
* [Pattern: Command Query Responsibility Segregation (CQRS)](https://microservices.io/patterns/data/cqrs.html) - here you can find information about **CQRS** pattern; **(EN)**
* [Command and Query Responsibility Segregation (CQRS) in practice](https://blog.byndyu.ru/2014/07/command-and-query-responsibility.html) - here you can find information about **CQRS** pattern with examples; **(RU)**
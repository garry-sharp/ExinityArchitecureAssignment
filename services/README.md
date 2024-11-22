In this code base each of the services is a sub package and then would be run by targeting that service with a CLI. As I need to show a structure for the whole system I've done it like this.

In reality, however, I would prefer for common code to live in a separate repo in a publicly exported [/pkg/](/pkg/) folder and for each service to exist in its own repo. It keeps the code cleaner, makes tests/logs easier to parse and prevents merge hell.
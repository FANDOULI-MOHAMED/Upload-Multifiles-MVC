to upload multi files in the same controller just follow the steps below:

declares the attributes as String in the entity

create entityRepository

create the serviceRepository with it's interface and inject the repository

create the controllermethod GetMapping and PostMapping and inject the serviceinterface to respect the IOC (Low coupling)

here is the exemple:

change the name of the file just let the name of each class and interface as they are

PS: here you'll not find the service interface just the methods in the implementationClass
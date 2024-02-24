Attendance-System-John-Cole
model package: contains entity classes

repository package: Contains classes responsible for interacting with your data store (e.g., MySQL).
These classes handle database operations related to your entities.

service package: Contains service classes that encapsulate your business logic.
These classes interact with repositories and provide a higher-level API to your controllers or other parts of the system.

resources directory: Holds configuration files, such as your database configuration, quiz banks, etc.

test: contains test classes for services
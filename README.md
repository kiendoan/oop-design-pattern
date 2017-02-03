# oop-design-pattern
OOP design pattern example in node js

- **Open close**: drawShape example (Rectangle and Circle extends Shape)
- **Dependency Inversion**: High level not depend on low level
- **Interface Segregation**: robot is a worker but not eating

---

- **Singleton**: single DB connection pool, single express object, single data in multi thread
- **Factory**: create objects of the same base type (multi level base - abstract factory)
- **Builder**: creator delegate (object)
- **Prototype**: same as javascript prototype
- **Chain of Responsibility**: return this in each function (in javascript)
- **Object Pool**: Limited number of resources (ex: DB connection poll)
- **Command**: callback, ex Remote with light on command ((new Remote()).setCommand(new LightOnCommand(lightObj)).buttonPressed())
- **Observer**: redis pub-sub, node event emitter
- **Strategy**: objects that same method name but difference strategy, delegate, Families of related algorithms (ex change strategy (Agressive, Defensive) of chess or robot before moving)
- **Template method**: hook, delegate, the methods from subclass are called in the template method from superclass (ex CRUD class in backend cms)
- **Adapter**: adapter of 3rd libraries (ex topup money, IAP ...)
- **Bridge**: ex DAO object that implements storage both mysql and mongo (Persistence Frameworks), look and feel in GUI app (GUI frameworks)
- **Composition**: tree data structure (ex menu as tree, file system as tree ...)
- **Decorator**: ex DecoratedScrollableWindow, EspressoWithMochaAndWhip
- **Flyweight**: use when a large number of objects that have some shared state among them (ex game war - solider shared the GraphicalRepresentation, text editor - characters in block has the same style)
- **Proxy**: The Proxy design pattern is applicable when there is a need to control access to an Object, as well as when there is a need for a sophisticated reference to an Object
- **Facade**: The Facade Pattern provides a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that makes the subsystem easier to use.
(ex HomeTheaterFacade, Form dialog contains many components)

---

- **Lazy**: overwrite method after first execution (in the method scope)
- **Nullify**: assign variable to null to improve GC
- **Try-finally**: code in finally block can be executed even after return in try block



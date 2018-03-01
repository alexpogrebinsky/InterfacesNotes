# InterfacesNotes

Interfaces

What are they?

- They are a contract.  They contain declared members: properties, methods, indexers, and events.  They are only declared, they are never defined in the Interface.

-  Once they are inherited in the Derived Class or Struct ( Class: Interface) it is up to the Derived Class or Struct to define the members.  

- If a Derived Class or Struct implements an Interface, it must also implement and define all of its members.

- Interfaces are public by DEFAULT


What's so good about them?

- They offer consistancey across classes.

- Interfaces CAN inherit other Interfaces!

- You can use an Interface to simulate (or act like) an inheritance for a struct because structs cannot inherit classes or other structs.

- They are like abstract classes except  you can use as many Interfaces as you like on a derived Class or Struct, unlike classes (you can only inherit classes once).

- If a base class (Car: Interface) implements an interface, any class that's derived from that base class inherits that implmentation (Car: Interface: DerivedClass).


What can't you do w/ an Interface?

- An interface members CANNOT be constants, fields, operators, insance constructors, finalizers, or tpes. 

- Members cannot be static.

- An Inteface CANNOT be instantiated (or constructed) directly.  Instantiation is an instance of a class, which makes an object, and is made by constructors.

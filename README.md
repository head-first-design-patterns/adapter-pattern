## Adapter Pattern

Adapter pattern converts the interface of a class into another interface `clients` expect. Adapters enable classes to work together that couldn't have happened otherwise because of incompatible interfaces

Use case of adapters: Compatibility between new and old code. For example, in Java Enumerators are old and Iterators are new.
We can have adapters of Iterator for old code and adapters of Enumerators for new code.

### Key principles:

- An adapter can implement multiple interfaces (for being usable to multiple clients)
- An adapter can encapsulate multiple adaptees (for combining functionality)
- There are 2 types of adapters: object and class
- Object adapters utilize composition
- Class adapters utilize inheritance

### Understanding the code

- This is a simulation of a Duck and a turkey adapting to be a duck
- The TurkeyAdapter implements

### Running the code

```
cd src/
javac DuckTestDrive.java


```
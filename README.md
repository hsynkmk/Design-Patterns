# Design Patterns

A collection of design patterns implemented in C# with clean examples and detailed explanations.

## 📚 Patterns Catalog

### Creational Patterns
1. **[Singleton Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Singleton.md)**: Ensures a class has only one instance while providing global access. Ideal for configuration managers and logging systems.
2. **[Factory Method Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Factory_Method.md)**: Defers object creation to subclasses while maintaining a common interface. Enables flexible object generation.
3. **[Abstract Factory Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Abstract_Factory.md)**: Creates families of related objects without specifying concrete classes. Perfect for cross-platform UI toolkits.
4. **[Builder Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Builder.md)**: Constructs complex objects step-by-step. Useful for creating objects with many optional components.
5. **[Prototype Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Prototype.md)**: Creates new objects by cloning prototypes. Efficient for expensive object initialization.

### Structural Patterns
6. **[Adapter Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Adapter.md)**: Bridges incompatible interfaces. Commonly used in legacy system integration.
7. **[Decorator Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Decorator.md)**: Adds responsibilities to objects dynamically. Alternative to subclassing for extending functionality.
8. **[Facade Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Facade.md)**: Provides simplified interface to complex subsystems. Reduces subsystem dependencies.
9. **[Composite Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Composite.md)**: Treats individual objects and compositions uniformly. Ideal for tree-structured hierarchies.
10. **[Proxy Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Proxy.md)**: Controls access to another object. Used in lazy loading and access control.
11. **[Flyweight Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Flyweight.md)**: Minimizes memory usage through object sharing. Effective for large quantities of similar objects.
12. **[Bridge Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Bridge.md)**: Decouples abstraction from implementation. Enables independent variation of both.

### Behavioral Patterns
13. **[Memento Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Memento.md)**: Captures and restores object state. Essential for undo/redo functionality.
14. **[State Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/State.md)**: Encapsulates state-specific behavior. Manages object behavior changes during runtime.
15. **[Iterator Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Iterator.md)**: Provides sequential access to collection elements. Abstracts traversal logic.
16. **[Strategy Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Strategy.md)**: Encapsulates interchangeable algorithms. Enables runtime algorithm selection.
17. **[Template Method Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Template_Method.md)**: Defines algorithm skeleton with customizable steps. Promotes code reuse.
18. **[Command Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Command.md)**: Encapsulates requests as objects. Enables queuing and undo operations.
19. **[Observer Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Observer.md)**: Implements publish-subscribe mechanism. Maintains consistency between related objects.
20. **[Mediator Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Mediator.md)**: Centralizes complex communication between objects. Reduces direct dependencies.
21. **[Chain of Responsibility](https://github.com/hsynkmk/Design-Patterns/blob/main/Chain_of_Responsibility.md)**: Passes requests through handler chain. Achieves loose coupling in request processing.
22. **[Visitor Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Visitor.md)**:  Separates algorithms from object structures. Enables adding new operations without changing classes.
23. **[Composite Pattern](https://github.com/hsynkmk/Design-Patterns/blob/main/Composite.md)**: (Note: Composite appears in both Structural and Behavioral categories based on usage context)

## 🛠 Usage

Each pattern includes:
- Problem statement
- Pattern solution
- C# implementation
- Usage examples
- Mermaid class diagrams
- Key benefits and considerations

```bash
# Clone repository
git clone https://github.com/hsynkmk/Design-Patterns.git
```

📖 Prerequisites
- Basic understanding of object-oriented programming
- Familiarity with C# syntax
- Visual Studio or VS Code (recommended)

🤝 Contributing
Contributions welcome! Please:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

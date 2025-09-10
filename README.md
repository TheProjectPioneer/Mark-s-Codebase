# Design Patterns Lab (and Beyond)

This repository is my **engineering knowledgebase**, a place where I explore, document, and demonstrate **software design patterns**, architectural practices, and other development concepts across different stacks (currently .NET and Angular).

The goal is not just to re-implement patterns blindly, but to:
- **Show the intent** of each pattern (the "why").
- **Demonstrate the implementation** in different technologies (.NET / Angular).
- **Contrast naive vs. pattern-based approaches**, so the trade-offs are clear.
- **Keep everything small and runnable**, with per-pattern demos and tests.
- **Build a personal playground** where I can expand beyond design patterns later.

---

## Structure
test
- `/net` → .NET implementations (C#, xUnit, console demos).  
- `/angular` → Angular workspace (one demo app + one lib per pattern).  
- `/docs` → Explanations, UML diagrams (PlantUML / Mermaid), notes.  

Each pattern is isolated as a **subproject** (per language)

---

## The 23 GoF Design Patterns

The **Gang of Four** design patterns fall into three categories: **Creational**, **Structural**, and **Behavioral**.  
Below is the list I’ll be going through and demonstrating in this repo.

## Creational Patterns
1. Factory Method [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Creational.FactoryMethod)  
2. Abstract Factory [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Creational.AbstractFactory)  
3. Builder [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Creational.Builder)  
4. Prototype [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Creational.Prototype)  
5. Singleton [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Creational.Singleton)  

## Structural Patterns
6. Adapter [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Adapter)  
7. Bridge [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Bridge)  
8. Composite [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Composite)  
9. Decorator [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Decorator)  
10. Facade [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Facade)  
11. Flyweight [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Flyweight)  
12. Proxy [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Structural.Proxy)  

## Behavioral Patterns
13. Chain of Responsibility [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.ChainOfResponsibility)  
14. Command [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Command)  
15. Interpreter [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Interpreter)  
16. Iterator [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Iterator)  
17. Mediator [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Mediator)  
18. Memento [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Memento)  
19. Observer [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Observer)  
20. State [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.State)  
21. Strategy [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Strategy)  
22. Template Method [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.TemplateMethod)  
23. Visitor [(.NET)](dotnet/DesignPatterns/src/DesignPatterns.Behavioral.Visitor)  


---

## How to Use This Repo


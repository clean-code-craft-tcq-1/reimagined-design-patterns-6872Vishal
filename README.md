# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.
> 

Adapter Design Pattern:

The Adapter design pattern allows incompatible classes to interact with each other by converting the interface of one class into an interface excepted by other.

Example :
Now consider you are travelling to Europe with laptop, the standard power cable doesn't fit in european socket. So what do we do? , buy a adapter which acts as a interface between the socket and power cable.Now the same can be applicable in coding. Instead of making changes to existing code, we add new interface which acts as a adapter.

Advantage:
Improve's the reusability of older functionality.

Disadvantage:
The overall complexity of the code increases because you need to introduce a set of new interfaces and classes. Sometimes it’s simpler just to change the service class so that it matches the rest of your code.


Observer Pattern:

Observer pattern is used when there is one-to-many relationship between objects such as if one object is modified, its depenedent objects are to be notified automatically. Observer pattern falls under behavioral pattern category.

Example:
Now consider we subscribed to a OTT platform, if there is a new movie release in the platform we get a notification to watch the movie. Here we are the Observer and the OTT becomes oberservable.Similarly in code a publisher class is created which is connected to a subscriber classes, publisher notifies theses  subscriber's when there is information which need to be notify. 

Advantages:
You can introduce new subscriber without changing the publisher code.

Disadvantages:
Subscribers are notified in random order


State Pattern:

In State pattern, we create objects which represent various states and a context object whose behavior varies as its state object changes.

Example:
In our mobile phones we have three modes for incoming calls, Ring, Vibrate and Silent Mode. Each option provides us the different outputs. Similar in code based on internal state machine cycle, we will set the code perform different operations.

Advantage:
Organize the code related to particular states into separate classes and simpliflying the code.

Disadvantage:
When there are only couple of state machine or code changes rarely, this pattern is not recommended.  




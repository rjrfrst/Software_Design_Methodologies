-- Introduction
There is no single correct way to approach a software engineering problem. Designing a product which satisfies a customer's needs while leveraging a team's skillset (and delivering on time and on budget) isn't something with a one-size-fits-all solution. There is, however, usually one option which is a better fit for a given situation than others. In this exercise we will find out about some of the different ways in which we could go about designing a system.

-- Design Strategies
There are three principle design strategies used in software engineering:

Structured design
Function oriented design
Object oriented design

None of these are compulsory when designing a product but following one will greatly aid the process. Each has its benefits and each has its drawbacks. Unlike many other aspects of software engineering they generally exist in isolation as the principles of each sit in direct opposition to each other in some scenarios.

There is no scenario where one of these strategies can't be used, but we may be making our lives harder by choosing one over another. Likewise the majority of programming languages can be used with any strategy, but some are better fits for one strategy than another. For example Java is an excellent choice for an object oriented design while Scala would be a better choice for a functional design. Some languages such as Python can be used effectively with either, but have to sacrifice some features to achieve that flexibility.

Within each methodology there are various design patterns which provide further structure for us. In general though these are much more easily transferred across methodologies, although the precise implementation will vary by language. In practice the language used for a project will likely be the last thing to be chosen, determined by a combination of methodology and design pattern.

--Task

In this exercise you will be required to research the design strategies listed above and answer some questions about them. Your answers should be in a markdown (.md) file and uploaded to GitHub, then the link submitted using the lab submission form. There is no MVP/extension split for this task - you should attempt to answer every question. You can collaborate with others in the cohort on the research part of the task but everyone should submit their own answers.

1. What do we mean by coupling and cohesion when discussing structured design?

Coupling is how strongly modules and classes are connected to one another. Normally this refers to how two components - e.g. classes - interact with one another. 
It measures how closely the modules are connected & how much they rely on each other.
Low Coupling promotes independence, modularity, and flexibility of the code.
The lower the degree of coupling, better the quality of the software

Cohesion is how strongly modules and classes are internally related to themselves. Normally, this refers to a component - e.g. class - are re,ated to one another and belong together.  
It can be separated into High and Low, High cohesion indicates that the elements in a component (class) have elements that all share a common purpose.
Low cohesion suggests that the elements are less focused and may serve multiple UNRELATED purposes. 



2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

The top-down approach, involves designing the overall of a project and then breaking it own into smaller components. 
The bottom-up approach, involves the design of the very basic level and building up as it goes. 

I think that function oriented design and bottom-up approach goes hand in hand.
Since the bottom-up approach starts by creating the most basic small step to grow. This model is better suited as it ensures less errors and when things are created they will have to be tested.
The bottom-up design is normally based on composition, which can be very difficult at the early stages but it will be more scalable in larger projects. 


3. In which design methodology would a class diagram be most useful?
Object orientated design 


4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

4.1 Abstraction -   
To abstract something away, when you call the function you don't have to understand exactly what it is doing.
To create a reusable and simple to understand code that can be extended to other classes. 
It is like creating coffee is the concrete and the abstract are the steps.

4.2 Encapsulation -
Encapsulation means that each object in your code should control its own state.
Removing access to parts of your code and making things private is exactly what Encapsulation is all about.

4.3 Inheritance -
Inheritance lets one object INHERIT the properties and methods of another object.

4.4 Polymorphism -
Polymorphism means "the condition of occurring in several different forms.". This also takes in inheritance since its the implementation of the interface. 


5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

The way the Strategy Design Pattern operates is by isolating an object's behaviour from the thing itself. 
The behaviour is broken down into several strategies, each of which carries out the behaviour in a unique way.


6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I would recommend an Agile Design Methodology since it is adaptable and flexible. 
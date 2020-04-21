
# Software Design: an Agile Approach

### Designing Software
Keywords	Agile, code, design, maintenance
Writing code is easy, creating maintainable software, not so much. In this presentation we discuss some of the core concerns, issues, impediments, and solutions

#### notes
* I liked the Strategic vs Tactical design part - Strategic design is draft and Tactical design might change the Strategic or evolve it. I also like the part where he discusses Evolutionary vs Accdential design. And the cheese analogy for software maintenance.
* This video is how do you choose stories based on value & impact. Other key points are simple design, balancing between up front and JIT design.

### Strategic Design vs. Tactical Design Tweet
Keywords	UML, architecture, design, strategic, tactical, tdd
Big up front design is bad. Not thinking about design until just in time is equally bad. Having two levels of design is better. Let's discuss why and how.

### Design Constructs: Part I Tweet
Keywords	OO, abstraction, design, encapsulation, inheritance, object-oriented programming, polymorphism
We discuss the different design constructs that we use in general and focus on OO

### Design Constructs: Part II Tweet
Keywords	OO, design, functional, object-oriented programming, patterns, principles
We take our discussions on design constructs further, diving into functional constructs, and discuss principles and patterns

### Thinking about Abstraction Tweet
Keywords	abstraction, bounded, context, design, domain, modeling
Abstractions are fundamental in life and in applications we create. We discuss about how to create better abstractions in this presentation
#### notes
* what is a good abstraction
* domain
* context 
* bounded context
* Domain Driven Design
* Great explanation about how to create abstractions in software for real-world objects. And How you may model what is necessary within a context.


### Design Principles: Part I
Keywords: cohesion, coupling, design, law of demeter, metrics, quality, tell dont ask
We discuss some fundamental metrics to measure the quality of design in this part.


### Design Principles: Part II
Keywords: complexity, design, fragility, immobility, opacity, repetition, rigidity, viscosity
We discuss the perils of bad design in this part of the presentation -


### Design Principles: Part III
Keywords: DRY, Dont Repeat Yourself, SRP, YAGNI, design, single responsibility
In this part, we focus on three fundamental principles, YAGNI, DRY, and SRP.


### Design Principles: Part IV
Keywords: OCP, design, open closed principle
Using an example that impacts extensibility we explore the open closed principle.


### Design Principles: Part V
Keywords: OCP, design, open closed principle
We discuss further about the application of the Open Closed principle.


### Design Principles: Part VI
Keywords: LSP, Liskovs Substitution Principle, design
We take up issues with inheritance and how Liskov's substitution principle helps deal with those issues.


### Design Principles: Part VII
Keywords: LSP, Liskovs Substitution Principle, design
We continue discussions on LSP, but look at specific examples of compliance and violations.


### Design Principles: Part VIII
Keywords: DIP, Dependency Inversion Principles, design
We learn about the Dependency Inversion Principle and how it helps create extensible design

### Design Principles: Part IX 
Keywords: DIP, Dependency Inversion Principles, design
We build an example using the dependency inversion principle and discover some surprises along the way.

### Design Principles: Part X
Keywords: Acyclic Dependency Principle, design
We discuss the perils of cyclic dependencies and ways to eliminate cycles


### Design Principles: Part XI
Keywords: Stable Abstraction Principle, Stable Dependency Principle, design
We dive into stable dependency principle and stable abstraction principle in this part of the presentation.

### Design Principles: Part XII
Keywords: Quantitative Measure, design
We bring two principles together to qualitatively measure the quality of design


### Design Principles: Part XIII
Keywords: JDepend, Quantitative Measure, design
Starting with a code example, we measure the quality of design, both through calculation and using JDepend.



### How to Approach Refactoring: Part I
Keywords: Refactor, code, design, quality, refactoring, software development
Why should we consider refactoring code?


```

```

```
Lowering the quality of the code lengthens the software development time" - 

First law of programming

```

#### Why refactor?
* to be agile
* to make the code easier to understand
* to make it easier to maintain
* to make change affordable
* to be agile -> to embrace change

```
Change is only constant -

```
#### Benefits
* Evolve it - Make it work first, then make it better real soon (in next few mins for hours - not in days)
* Refactor reduces risk - can lead to lightweight pragmatic design


### How to Approach Refactoring: Part 2 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We revisit the question as to what refactoring is and how to alleviate some impediments

#### notes

```
A refactor a day keeps the rewrite away -@saleandro

Refactoring is not a story or a backlog item or not even a scheduled task. It is immediate and continuous like washing your hands in the bathroom everyday. You always do it. It should never appear in a schedule. -@unclebobmartin
```


### How to Approach Refactoring: Part 3 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We discuss the zeroth principle for refactoring - zeroth principle



### How to Approach Refactoring: Part 4 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
The inspiration to refactor code surprisingly comes from a non-technical bestseller

#### notes
* book: on writing well by William Zinser
* Simplicity
* Clarity
* Brevity
* Humanity


### How to Approach Refactoring: Part 5 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We discuss the first principle of refactoring and the reasons, to reduce code - first principle


### How to Approach Refactoring: Part 6 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
Prefer clear instead of clever code - second principle



### How to Approach Refactoring: Part 7 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We discuss why we should refactor to keep the code small and cohesive - 3rd principle

#### notes

* cohesion and coupling 

##### Cohesion

```
	degree to which things come and work to together 
	like things are together and different things are apart	

	where the code is narrow, focused, does one thing, and that one thing well.
```


### How to Approach Refactoring: Part 8
Keywords	Refactor, code, design, quality, refactoring, software development
We discuss the reasons to keep it DRY and how to approach that - 


### How to Approach Refactoring: Part 9 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
Dependency Inversion is valuable, but there's more benefit to eliminate or move dependency where possible



How to Approach Refactoring: Part 10 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
Use comments to detail why and not what

How to Approach Refactoring: Part 11 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
If a code takes time to learn, it's a good candidate to refactor

How to Approach Refactoring: Part 12 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We look into the next principle, to avoid primitive obsession

How to Approach Refactoring: Part 13 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
Checking in code frequently has many benefits and not doing so has significant drawbacks


How to Approach Refactoring: Part 14 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
Long methods are a peril in software development, but the multiple levels of abstraction is the main culprit


How to Approach Refactoring: Part 15 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
To refactor or not to refactor is the question


How to Approach Refactoring: Part 16 Tweet
Keywords	Refactor, code, design, quality, refactoring, software development
We end this series with a discussion of the flow, the steps for productive refactoring









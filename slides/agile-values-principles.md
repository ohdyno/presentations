## Agile Software Development
### Values and Principles

---

## The Value of Software

![software logo](/slides/software.jpg) <!-- .element class="fragment inline-image"  -->
![business value](/slides/money.jpg) <!-- .element class="fragment inline-image" width="40%"  -->

note:
- software does not have value by itself
- every line of code is liability (financial, legal, etc.)
- from the business standpoint, it's only valuable when it provides business value
- usually, lowering cost or increasing profit


## The Ideal

![triangle of project management](/slides/project-triangle.png) <!-- .element width="50%" -->

note:
- the ideal outcome for a business is that they can get valuable software that is
	- on time
	- on budget
	- with all the features


## The Reality

![sad face becuase of software development failure](/slides/sad-face.jpg)

note:
- reality:
	- schedules slip
	- budgets grow
	- poor quality (lacking features or more bugs)
- customers are unhappy, the developers are unhappy, and the business is unhappy


## The Solution!

![waterfall model](/slides/waterfall-model.svg) <!-- .element width="70%" -->

note: 
- inspired from manufaturing and applied it to software engineering.
- does reflect activites done during software development
- each step is meant to prevent re-work at the later steps

issues:
- improbably to prevent re-work upfront
- process becomes heavy due to failures
- heavy process slows down software delivery, which
	- increases budget
	- misses deadline
	- building incorrect features
- results in vicious cycle ("runaway-process")

---

## February 2001. Snowbird, Utah

![image for original agile signatures](/slides/agile-background.jpg) <!-- .element width="70%" -->

note:
- seasoned developers
- felt the pain of run-away process that causes people pain
- Agile Alliance
- met to outline the values and principles tha twould allow software teams to work quickly and respond to change

notable names:
- Kent Beck (XP)
- Bob Martin (Clean Code, C++)
- Martin Fowler (Refactoring)
- Ken Schwaber and Jeff Sutherland (SCRUM)
- Alistar Cockburn (Hexgonal / Ports and Adapters Architecture)
- Ward Cunningham (Wiki, Technical Debt)
- Ron Jeffries
- Andrew Hunt and Dave Thomas (Pragmatic Programmer)
- James Grenning (Embedded)


## Manifesto for Agile Software Development

**Individuals and interactions** over processes and tools

**Working software** over comprehensive documentation

**Customer collaboration** over contract negotiation

**Responding to change** over following a plan


### Individuals and interactions over processes and tools
![individuals and interactions](/slides/individuals-interactions.png) <!-- .element width="60%" -->
![process and tools](/slides/process-tools.jpg) <!-- .element width="25%" -->

note:
- people are the most important ingredient of success
- good process won't save project if no strong people
- bad process will make strongest people effective
- taylor the process toward the people
- A strong player may be an average programmer, but someone who works well with others
- similarly, let the team control the environment


### Working software over comprehensive documentation
![working software](/slides/working-software.jpg) <!-- .element width="60%" -->
![documentation](/slides/documentation.jpg) <!-- .element width="25%" -->

"Produce no document unless its need is immediate and significant." - Martin's first law of documentation <!-- .element class="fragment" style="font-size: 16pt" -->

note:
- this means software documentation is bad right?
- "code is not the ideal medium for communicating the rationale and structure of a system"
- best ways to transfer information
	- the code (does not lie about what it does)
	- the team (rationale, structure of the system, road map)
- Martin's first law of documentation


### Customer collaboration over contract negotiation
![customer collaboration](/slides/collaboration.jpg) <!-- .element width="60%" -->
![contract](/slides/contract.jpg) <!-- .element width="25%" -->

note:
- successful projects involve customer feedback on a regular and frequent basis.
- what's the value of the contract?
- contract is still valuable, since that affects the collaboration
- not "requirements, schedule, and cost"
- best contract is one that governs the way the development team and the customer will work together


### Responding to change over following a plan
![respond to change](/slides/feedback.png) <!-- .element width="60%" -->
![gantt chart](/slides/plan.png) <!-- .element width="25%" -->

note:
- the traditional success criteria is "how close were we to the plan"
- in this case, we treat the plan as immutable, especially if we have put a lot of effort in creating the plan
- our plans should be flexible and be ready to adapt to changes in the business and technology
- how do we need to achieve this?

---

## 12 Principles
Characteristics that differentiate a set of agile practices from a heavyweight process.


Our highest priority is to satisfy the customer through **early and continuous delivery of valuable software**.


Welcome changing requirements, even late in development. Agile processes **harness change for the customer's competitive advantage**.


**Delivery working software frequently**, from a couple of weeks to a couple of months, with a preference ot the shorter time scale.


Business people and developers must **work together** daily throughout the project. 


Build projects around **motivated individuals**. Give them the **environment and support** they need, and **trust** them to get the job done.


The most efficient and effective method of conveying information to and within a development team is **face-to-face conversation**.


**Working software** is the primary measure of progress.


Agile processes promote **sustainable development**. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.


Continuous attention to **technical excellence** and **good design** enhances **agility**.


**Simplicity** - the art of maximizing the amount of work not done - is essential.


The best architectures, requirements, and designs emerge from **self-organizing teams**.


At regular intervals, the team reflects on **how to become more effective**, then tunes and adjusts its behavior accordingly.

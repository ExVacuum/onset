# Module 1: Intro to Requirements

### [PROG1350 - Software Engineering Fundamentals](/PROG1350)

## Associated Reading

  - Code Complete, 2nd Edition (ISBN 9788178530857):
    - Chapter 3
    
    <details>
    <summary>Some key ideas:</summary>
    
      - Emphasizing construction practices emphasizes quality during the middle of the project.
      - The goal of preparation is to reduce large amounts of **risk**, and prerequisites help with this.
      - Oftentimes, it isn't practical to specify all of a project's requirements up front, but getting most of the critical ones idetified early on will save you a lot of grief. 
      Some strategies for this include:
        - Plan 80% of requirements up front, and plan time to identify the rest in the development process.
        - Plan the most important 20% of requirements up front, and then specify the rest in small intervals as you go. Oftentimes this is easier to do.
      - A good problem definition helps to lay the foundation for the requirements, and in turn the rest of the development process.
      - Problem definitions should be in user language, **not** over-complicated computer talk, as programming may not always be the best solution.
      - If a problem is ill-defined, you may waste time solving the wrong problem.
      - Requirements help to minimize the changes necessary in the middle of development. Consider:
        - A *coding* error may mean you need to rework a small portion of the code.
        - A *requirements* error, on the other hand, may mean you need to rework large portions if not all of the code.
      - A requirements checklist is included in this chapter in order to help assess the quality of your requirements. A DOCX version is available [here](https://stuconestogacon-my.sharepoint.com/:w:/g/personal/sbartha6300_conestogac_on_ca/EfZalsKclVdIpzb_cO7cgU8B-aINI9LN-j5rgjkuBAdJYA?e=KaworF).
        please save a copy, rather than editing this one directly.
      - It is vital to ensure that everyone is aware of the costs of changes to the requirements. In order to help mitigate these cahnges:
        - Establish a system for handling requested changes to the requirements
        - Use short, incremental development stages in order to accomodate changes more easily as you go.
      - The quality of high-level program architecture determines a system's conceptual integrity, and in turn its final quality.
      - Good architecture makes construction easy, bad architecture makes construction impossible.
        
      </details>
      
## Module Content

### Requirements

#### What are they?

> Requirements are like a set of instructions that tell us what needs to be done. They must be concise and complete, without room for interpretation, or unanswered questions.

#### What do they tell us?

> Requirements describe:
>
> 1. The system itself
> 2. What the system is capable of doing
> 3. Interactions with the system
>
> and more.

#### Why do we need them?

> Requirements are necessary for all parties to have an equal understanding of the system and its capabilities. Requirements focus everyone's attention on creating the same system.

Having precise and accurate requirements is the **most important** part of the development process, as having them early into the SDLC means less time is wasted having to deal with potential do-overs of large portions of the system.

Gathering requirements reduces the amount of *surprises*, which can be costly in terms of time, money, and frustration.

Requirements should emphasize *what* need to be done, not *how* it should be done. This would be jumping the gun straight to the design phase.

**Requirements Reduce Risk**

### The Traditional Phases of System Development

#### Iterative Design Process

Iterative design processes follow a set of phases, backtracking whenever necessary:

1. Planning Phase
    *  Scoping out the project, scheduling, and other planning activities
2. Analysis Phase
    * Requirements are gathered, analyzed and refined
3. Design Phase
    * The system architecture is designed in order to fulfill the requirements
4. Implementation Phase
    * System is programmed, most of the testing is conducted
5. Maintenance/Support Phase
    * Changes or bug fixes after release

These stages form the basis of the System Development Life Cycle (SDLC).

### Other Approaches

There are approaches apart from the traditional one, some of them more agile. Regardless of the chosen approach, requirements are still vital to the project's success.

### Why Requirements are Often Overlooked

Sometimes, the requirements-gathering process is overlooked. This could be due to:
- Lack of expertise on the part of those responsible
- Haste to begin coding
- Those in charge of those responsible lacking patience for requirements
- The project being small enough that everyone knows what to do

### Reasoning for Official Requirements

Using an official documentation of requirements offers many benefit, including:

1. Allowing the user to drive the functionality
2. Avoiding arguments or interpretations later on
3. Elimination of errors and inconsistencies early on, while it is easier
4. It can form the basis of an agreement or contract if signed off on

### Gathering Requirements

In order to gather requirements, one must:

- Determine what needs to be done at a high, uncomplicated level
- Interact with customers or clients
- Match customers' needs with the capabilities of the product

#### Customers

In this case, *customer* can mean any person or organization with a vested interest in the priduct ot project's outcome (stakeholders). It is necessary to know and prioritize your customers and their needs.

Sometimes customers don't know what they need, and may suggest an inferior solution, rather than stating their problem. This means it is important to talk to the customer and ensure that you understand the problem, in order to  produce an effective product.
It's a good idea to:
- Get feedback from previous users
- Have customer feedback groups
- Conducting surveys
- Taking trips to the customer site

### (Un)Stable Requirements

It is important to remember that requirements are **not** stable, and are subject to change. The average project's requirements will change by 25%. *However*, you can certainly help keep your requirements as stable
as possible by *documenting* them.

#### Dealing with changes

Some ways you can deal with the inevitability of changes to your requirements include:
- Assessing your requirements with a checklist (see the associated reading at the top of this page)
- Ensure an understanding of the cost of changes
- Set up a procedure for controlling changes
- Accomodate changes through your development process
- Know when to dump the project
- Keep an eye on the business case for the project

### Documenting Requirements

In order to document requirements, many projects use a document called a Software Requirements Specification (SRS). The SRS contains a set of precise properties and constraints that the system must satisfy.

Characteristics of a good SRS include:
- Understandability by end users (limit technical jargon)
- Non-prescriptive nature (with exceptions for implementation constraints)
- Accuracy (representative of user needs)
- Concision (get to the point)
- Clarity
- Precision (no room for interpretation)
- Consistency (no contradictions)
- Traceability (origins of requirements must be clear)
- Malleability (changes can be made easily, completely, and consistently)
- Verifiability (must be able to check if requirement is met)
- Usability during the operation and maintenance phase (needs of this phase must be addressed)

An SRS must include the following to be complete:
- All significant requirements
- Definition of the responses of the software to all realizable classes of input
- Conformity to all applicable standards
- Full labeling and referencing of all tables and diagrams and the definition of all terms

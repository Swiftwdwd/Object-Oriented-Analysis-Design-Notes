# Unified Modeling Language ("Union of all Modeling Languages")
## Waterfall Model
- Requirements Engineering
  - Requests for change in requirements at any stage
- Design
- Implementation (To Design)
  - Lacking feedback loops for problems
- Testing/Verification (To Implementation)
- Maintenance (To Verification/Implementation)
  - Verifying patches
  - Forking updates to next version
## UML
- "Union of all Modeling Languages"
  - Enormous language
  - Many loosely related styles under one roof
- But
  - Provides a common, simple, graphical representation of software design and implementation
  - Allows developers, architects, and users to discuss the workings of the software
## Modeling Guidelines
- Nearly everything in UML is optional
- Models are rarely complete
- UML is "open to interpretation"
- UML is designed to be extended
## Static Modeling in UML
captures the fixed, code-level relationships in the system
- Class diagrams (widely used)
- Package diagrams
- Component diagrams
- Composite structure diagrams
- Deployment diagrams
## Behavioral Modeling with UML
captures the dynamic execution of a system
- Use case diagrams (widely used)
- Interaction diagrams
- Sequence diagrams (widely used)
- Collaboration diagrams
- State diagrams (widely used)
- Activity diagrams (widely used)
## Use Case Diagrams
capture the requirements of a system from teh user's perspective

![image](https://github.com/Swiftwdwd/Object-Oriented-Analysis-Design-Notes/blob/master/QQ截图20200102112234.png)
- Inclusion (e.g., push button include in ride)
- Generalization/specialization (e.g., push train button and push station button are specializations of push button)
- Extension expresses an exceptional variation of a use case (e.g., derail is an exceptional ride)
## Statechart Diagrams
- Another way of specifying behavioral requirements (Built on state machines)
- Show the various stages of an entity during its lifetime
- Can be used to show the state transitions of methods, objects, components
  - Behavioral state machines show the behavior of a particular element in a system
  - Protocol state machines show the behavior of a protocol
- Components
  - state
  - action
  - activity
  - transition
  
![image1](https://github.com/Swiftwdwd/Object-Oriented-Analysis-Design-Notes/blob/master/statechart.png)
## Class Diagram
Models the static relationships between the components of a system
- The multiplicity of a class is specified by a number in the upper right corner of the component
  - Usually omitted and assumed to be more than 1
  - Specifying a multiplicity of 1 indicates the class should be a singleton
- Visibility
  - Public +
  - Private -
  - Protected #
  - Package ~
- Parameter list
  - Name
  - Type

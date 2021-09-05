## Component-Based Architecture

Component-based architecture focuses on the decomposition of the design into individual functional or logical components that represent well-defined communication interfaces containing methods, events, and properties. It provides a higher level of abstraction and divides the problem into sub-problems, each associated with component partitions.

The primary objective of component-based architecture is to ensure component reusability. A component encapsulates functionality and behaviors of a software element into a reusable and self-deployable binary unit. There are many standard component frameworks such as COM/DCOM, JavaBean, EJB, CORBA, .NET, web services, and grid services. These technologies are widely used in local desktop GUI application design such as graphic JavaBean components, MS ActiveX components, and COM components which can be reused by simply drag and drop operation.

**A component** is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.
![](https://www.tutorialspoint.com/software_architecture_design/images/principles_of_component_based_design.jpg)
## Characteristics of Components
Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.
Conducting Component-Level Design
Recognizes all design classes that correspond to the problem domain as defined in the analysis model and architectural model.

Recognizes all design classes that correspond to the infrastructure domain.

Describes all design classes that are not acquired as reusable components, and specifies message details.

Identifies appropriate interfaces for each component and elaborates attributes and defines data types and data structures required to implement them.

Describes processing flow within each operation in detail by means of pseudo code or UML activity diagrams.

Describes persistent data sources (databases and files) and identifies the classes required to manage them.

Develop and elaborates behavioral representations for a class or component. This can be done by elaborating the UML state diagrams created for the analysis model and by examining all use cases that are relevant to the design class.

Elaborates deployment diagrams to provide additional implementation detail.

Demonstrates the location of key packages or classes of components in a system by using class instances and designating specific hardware and operating system environment.

The final decision can be made by using established design principles and guidelines. Experienced designers consider all (or most) of the alternative design solutions before settling on the final design model.

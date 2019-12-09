# Project: Beagle

### Table of Contents
- [Introduction](PHILOSOPHY.md)
- [Environment](ENVIRONMENT.md):
    + [Build System](ENVIRONMENT.md#Build-System)
    + [Deployment System](ENVIRONMENT.md#Deployment-System)
    + [Version Control Integration System](ENVIRONMENT.md#VCS-Integration-System)
    + [Embedded Interpreter](ENVIRONMENT.md#Embedded-Interpreter)
- [Flow Control](FLOW_CONTROL.md):
    + [Conditional Branching](FLOW_CONTROL.md#Conditional-Branching)
        * [Fundamental Branching with If-Else-If-Else](FLOW_CONTROL.md#If-Else-If-Else-Branching)
        * [Complex Branching with When](FLOW_CONTROL.md#When-Statements)
        * [Expression Based Branching](FLOW_CONTROL.md#Expression-Based-Branching)
    + [Fundamental Looping](FLOW_CONTROL.md#Fundamental-Looping)
        * [Fundamental For-Loops](FLOW_CONTROL.md#Fundamental-For-Loops)
        * [Fundamental While-Loops](FLOW_CONTROL.md#Fundamental-While-Loops)
        * [Expression Based Looping](FLOW_CONTROL.md#Expression-Based-Looping)
- [Definitions](DEFINITIONS.md)
    + [Definitions as Expressions](DEFINITIONS.md#Definitions-As-Expressions)
    + [Defining a Property](DEFINITIONS.md#Defining-A-Property)
    + [Defining a Function](DEFINITIONS.md#Defining-A-Function)
    + [Defining a Class](DEFINITIONS.md#Defining-A-Class)
    + [Defining a Struct](DEFINITIONS.md#Defining-A-Struct)
    + [Defining a Constant](DEFINITIONS.md#Defining-A-Constant)
    + [Defining an Enum](DEFINITIONS.md#Defining-An-Enum)
    + [Defining a Trait](DEFINITIONS.md#Defining-A-Trait)
    + [Defining an Interface](DEFINITIONS.md#Defining-An-Interface)
    + [Defining a Module](DEFINITIONS.md#Defining-A-Module)
    + [Defining a Reference](DEFINITIONS.md#Defining-A-Reference)
    + [Defining a Rule](DEFINITIONS.md#Defining-A-Rule)
    + [Defining a Macro](DEFINITIONS.md#Defining-A-Rule)
    + [Defining a Thread](DEFINITIONS.md#Defining-A-Thread)
    + [Defining a Task](DEFINITIONS.md#Defining-A-Task)
    + [Defining a Rule](DEFINITIONS.md#Defining-A-Rule)
- [Properties](PROPERTIES.md)
    + [Basic Properties](PROPERTIES.md#Basic-Properties)
    + [Property Setters](PROPERTIES.md#Property-Setters)
    + [Property Getters](PROPERTIES.md#Property-Getters)
    + [Backing Fields](PROPERTIES.md#Backing-Fields)
    + [Object Member Properties](PROPERTIES.md#Object-Member-Properties)
        * [Class Member Properties](PROPERTIES.md#Class-Member-Properties)
        * [Constructor Member Properties](PROPERTIES.md#Constructor-Member-Properties)
        * [Data Structure Member Properties](PROPERTIES.md#Data-Structure-Member-Properties)
        * [Extension Properties](PROPERTIES.md#Extension-Properties)
- [Variables](VARIABLES.md)
    + [Basic Variables](VARIABLES.md#Basic-Variables)
    + [Let vs Def](VARIABLES.md#Let-Vs-Def)
- [Functions](FUNCTIONS.md)
    + [Basic Functions](FUNCTIONS.md#Basic-Functions)
    + [Function References](FUNCTIONS.md#Function-References)
    + [Function Types](FUNCTIONS.md#Function-Types)
    + [Higher-Order Functions and Lambdas](FUNCTIONS.md#Higher-Order-Functions)
    + [Extension Functions](FUNCTIONS.md#Extension-Functions)
    + [Local Functions](FUNCTIONS.md#Local-Functions)
    + [Member Functions](FUNCTIONS.md#Member-Funcions)
    + [Pass By Reference](FUNCTIONS.md#Pass-By-Reference)
- [Classes](CLASSES.md)
    + [Basic Classes](CLASSES.md#Classes)
    + [Class Constructors](CLASSES.md#Constructors)
        * [Non-Primary Constructors](CLASSES.md#Non-Primary-Constructors)
    + [Class Droppers](CLASSES.md#Droppers)
        * [Non-Primary Droppers](CLASSES.md#Non-Primary-Droppers)
    + [Class Members](CLASSES.md#Class-Members)
        * [Class Member Properties](CLASSES.md#Class-Member-Properties)
        * [Class Member Functions](CLASSES.md#Class-Member-Functions)
    + [Encapsulaton](CLASSES.md#Encapsulation)
        * [Private Members](CLASSES.md#Private-Members)
        * [Internal Members](CLASSES.md#Internal-Members)
        * [Protected Members](CLASSES.md#Protected-Members)
        * [Encapsulated Constructors](CLASSES.md#Encapsulated-Constructors)
    + [Inheritance](CLASSES.md#Inheritance)
    + [Companion Objects](CLASSES.md#Companion-Objects)
    + [Open Classes](CLASSES.md#Open-Classes)
    + [Abstract Classes](CLASSES.md#Abstract-Classes)
    + [Inner Classes](CLASSES.md#Inner-Classes)
- [Interfaces](INTERFACES.md)
    + [Basic Interfaces](INTERFACES.md#Basic-Interfaces)
    + [Abstract Members](INTERFACES.md#Abstract-Members)
        * [Interface Properties](INTERFACE.md#Interface-Properties)
        * [Interface Functions](INTERFACE.md#Interface-Functions)
    + [Default Members](INTERFACES.md#Default-Members)
        * [Default Properties](INTERFACES.md#Default-Properties)
        * [Default Functions](INTERFACES.md#Default-Functions)
    + [Interface Constructors](INTERFACES.md#Interface-Constructors)
- [Enums](ENUMS.md)
    + [Basic Enums](ENUMS.md#Basic-Enums)
    + [Enum Constructors](ENUMS.md#Enum-Constructors)
    + [Enum Members](ENUMS.md#Enum-Members)
        * [Enum Member Properties](ENUMS.md#Enum-Member-Properties)
        * [Enum Member Functions](ENUMS.md#Enum-Member-Functions)
        * [Enum Constructor Member Properties](ENUMS.md#Enum-Constructor-Member-Properties)
    + [Abstract Enum Members](ENUMS.md#Abstract-Enum-Members)
        * [Abstract Member Properties](ENUMS.md#Abstract-Enum-Member-Properties)
        * [Abstract Member Functions](ENUMS.md#Abstract-Enum-Member-Functions)
    + [Enum Companion Objects](ENUMS.md#Enum-Companion-Objects)
    + [Enum Operator Overloading](ENUMS.md#Enum-Operator-Overloading)
- [References](REFERENCES.md)
    + [Basic References](REFERENCES.md#Basic-References)
    + [Immediate Referencing](REFERENCES.md#Immediate-Referencing)
    + [`ref` Keyword](REFERENCES.md#Ref-Keyword)
    + [Pass-by-Reference](REFERENCES.md#Pass-By-Reference)
- [Memory Management](MEMORY_MANAGEMENT.md)
    + [How Memory Management Works](MEMORY_MANAGEMENT.md#How-Memory-Management-Works)
    + [Memory Reservations](MEMORY_MANAGEMENT.md#Memory-Reservation)
    + [Memory Deletion](MEMORY_MANAGEMENT.md#Memory-Deletion)
    + [Object Memory Management](MEMORY_MANAGEMENT.md#Object-Memory-Management)
        * [Object Constructors and Droppers](MEMORY_MANAGEMENT.md#Object-Constructors-And-Droppers)
    + [Heap Vs Stack Allocations (Def vs Let)](MEMORY_MANAGEMENT.md#Heap-Vs-Stack-Allocations)
- [Structs](STRUCTS.md)
    + [Basic Structs](STRUCTS.md#Basic-Structs)
    + [Data Structure Members](STRUCTS.md#Data-Structure-Members)
        * [Data Structure Member Properties](STRUCTS.md#Data-Structure-Member-Properties)
        * [Data Structure Member Functions](STRUCTS.md#Data-Structure-Member-Functions)
    + [With Clause](STRUCTS.md#With-Clause)
        * [Implementing Traits and Abstract Types](STRUCTS.md#Implementing-Traits-And-Abstract-Types)
    + [Data Structure Constructors](STRUCTS.md#Data-Structure-Constructors)
        * [Non-Primary Constructors](STRUCTS.md#Non-Primary-Constructors)
    + [Data Structure Droppers](STRUCTS.md#Data-Structure-Droppers)
        * [Non-Primary Droppers](STRUCTS.md#Non-Primary-Droppers)
- [Traits](TRAITS.md)
    + [Basic Traits](TRAITS.md#Basic-Traits)
    + [Trait Members](TRAITS.md#Trait-Members)
        * [Trait Member Properties](TRAITS.md#Trait-Member-Properties)
        * [Trait Member Functions](TRAITS.md#Trait-Member-Function)
    + [Traits With Traits](TRAITS.md#Traits-With-Traits)
    + [Trait Constructors](TRAITS.md#Trait-Constructors)
    + [Trait Droppers](TRAITS.md#Trait-Droppers)
    + [Traits As Pseudotypes](TRAITS.md#Trait-Psuedotyping)
    + [Anonymous Trait Implementations](TRAITS.md#Anonymous-Trait-Implementations)
- [Abstract Types](ABSTRACT_TYPES.md)
    + [Basic Abstract Types](ABSTRACT_TYPES.md#Basic-Abstract-Types)
    + [Abstract Type Members](ABSTRACT_TYPES.md#Abstract-Type-Members)
    + [Abstract Type Functions](ABSTRACT_TYPES.md#Abstract-Type-Functions)
    + [Abstract Type Constructors](ABSTRACT_TYPES.md#Abstract-Type-Constructors)
        * [Non-Primary Constructors](ABSTRACT_TYPES.md#Non-Primary-Constructors)
    + [Abstract Type Droppers](ABSTRACT_TYPES.md#Abstract-Type-Constructors)
        * [Non-Primary Droppers](ABSTRACT_TYPES.md#Non-Primary-Droppers)
    + [Implementing Abstract Types](ABSTRACT_TYPES.md#Implementing-Abstract-Types)
        * [Class Implementation](ABSTRACT_TYPES.md#Class-Implementation)
        * [Data Structure Implementation](ABSTRACT_TYPES.md#Structs-Implementation)
    + [Abstract Type Inclusions](ABSTRACT_TYPES.md#Abstract-Inclusions)
        * [Abstract Type Inclusion: With Clause](ABSTRACT_TYPE.md#Abstract-Type-Inclusion-Using-With-Clauses)
        * [Interface Inclusion](ABSTRACT_TYPES.md#Interface-Inclusion)
        * [Abstract Class Inclusion](ABSTRACT_TYPES.md#Abstract-Class-Inclusion)
- [Polymorphic Programming with `?`](POLYMORPHISM.md)
    + [Nullable Types](POLYMORPHISM.md#Null-Safety-And-Nullible-Types)
    + [Duck Typing](POLYMORPHISM.md#Duck-Typing)
        * [Use `?` For Dynamic Typing](POLYMORPHISM.md#Using-?-For-Dynamic-Typing)
        * [Dynamic Type Restrictions](POLYMORPHISM.md#Dynamic-Type-Restrictions)
            - [Class Only Dynamic Typing](POLYMORPHISM.md#Class-Only-Dynamic-Typing)
            - [Data Structure Only Dynamic Typing](POLYMORPHISM.md#Data-Structure-Only-Dynamic-Typing)
        * [Trait Binding](POLYMORPHISM.md#Trait-Binding)
    + [Type Casting](POLYMORPHISM.md#Type-Casting)
    + [Generics (A Form Of Polymorphism But Deserves Its Own Document)](GENERICS.md)
- [Generic Programming](GENERICS.md)
    + [Basic-Generics](GENERICS.md#Basic-Generics)
    + [Variance](GENERICS.md#Variance)
        * [Covariance and Declaration-site Variance](GENERICS.md#Covariance-And-Declaration-site-Variance)
        * [Contravariance and Use-site Variance](GENERICS.md#Contravariance-And-Use-site-Variance)
    + [Type Projection](GENERICS.md#Type-Projection)
    + [Star Projection](GENERICS.md#Star-Projection)
    + [Generic Functions](GENERICS.md#Generic-Functions)
    + [Generic Constraints](GENERICS.md#Generic-Constraints)
        * [Binding With Where Clause](GENERICS.md#Binding-With-Where-Clause)
    + [Type Erasure](GENERICS.md#Type-Erasure)
- [Modules](MODULES.md)
    + [Basic Modules](MODULES.md#Basic-Modules)
    + [Directory Based Modules](MODULES.md#Directory-Based-Modules)
    + [Submodules](MODULES.md#Submodules)
    + [Module Dependencies](MODULES.md#Module-Dependencies)
- [Concurrency](Concurrency.md)
    + [Threads and Multithreading](Concurrency.md#Multithreading)
        * [Defining a Thread](Concurrency.md#Defining-A-Thread)
        * [Thread Handlers](Concurrency.md#Thread-Handlers)
    + [Coroutines and Multitasking](Concurrency.md#Multitasking)
        * [Defining a Task (Coroutine)](Concurrency.md#Defining-A-Task)
        * [Task Scopes and Handlers](Concurrency.md#Task-Scopes-And-Handlers)
    + [Suspending Functions and Properties](Concurrency.md#Suspending-Functions-And-Properties)
        * [Async/Await Functions](Concurrency.md#Async-Await-Functions-In-Threads)
        * [Async/Await Properties](Concurrency.md#Async-Await-Properties)
- [Data Validation Rules](RULES.md)
    + [Defining a Rule](RULES.md)
    + [Rule Dependencies/Chaining](RULES.md)

# Automation Test Training

**Software Testing** is the process of identifying the *correctness* and *quality* of software program. In other words, testing is executing a system or application in order to find software *bugs*, *defects* or *errors*. The purpose is to check whether the software satisfies the specific requirements, needs and expectations of the customer.

## Ways of Testing
**[Software Testing](docs/software-testing.md)**: Process to find out bugs and issues in the system/application. 

**[Manual Testing](docs/manual-testing.md)**: Test Cases executed manually.

**[Automation Testing]()**: Testing performed with the help of automation tools.

## Test Artifacts
**[Test Basis]()**: It is the information needed in order to start the test analysis and create our Test Cases. 

**[Test Case Specification]()**: A document described detailed summary of what scenarios will be tested, how they will be tested, how often they will be tested. 

**[Test Scenario]()**: It is also called Test Condition or Test Possibility means any functionality that can be tested.

**[Test Case]()**: What is Test Case and Strategy to Write Good Test Case a documentation which specifies input, pre-conditions, set of execution steps and expected result. 

## Testing Process
**[Software Testing Principles]()**: Seven Important Software Testing Principle to Improve Testing Quality. 

**[Testing Process]()**: Testing is a process rather than a single activity. It includes Planning & Controlling, Analysis & Design, Implementation & Execution, Evaluating Exit Criteria & Reporting and Test Closure Activities.

**[Software Testing Life Cycle]()**: Software Testing Life Cycle (STLC) is defined as a sequence of activities conducted to perform Software Testing. It consists of series of activities carried out methodologically to help certify your software product. 

## [Software Development Life Cycle](docs/001-software-development-life-cycle.html)

## Level of Testing
- **Functional Testing**: Functional testing involves testing the application against the business requirements. The goal of functional testing is to verify that the application is behaving the way it was designed to. 
  - **Unit Testing**: Individually and independently testing of smallest testable parts of an application. 
  - **Integration Testing**: When individual software modules are combined together and tested as a group than it is known as Integration Testing. 
  - **Smoke Testing**: Preliminary testing to reveal simple failures severe enough to (for example) reject a prospective software release or build. 
  - **Sanity Testing**: Very brief run-through of the functionalities to assure that part of the system or methodology works roughly as expected. 
  - **System Testing**: Testing conducted on a complete, integrated system to evaluate the system’s compliance with its specified requirements. 
  - **Regression Testing**: Retesting of a software system to confirm that changes made to few parts of the codes has not any side affects on existing system functionalities. 
  - **Acceptance Testing**: Formal testing with respect to user needs, requirements, and business processes conducted to determine whether a system satisfies the acceptance criteria. 
  - **Alpha & Beta Testing**: Alpha Testing is conducted by a team of highly skilled testers at development site whereas Beta Testing is always conducted in Real Time environment by customers or end users at their own site. 
  - **End to End Testing**: End to End Testing is usually executed after functional and system testing. It uses actual production like data and test environment to simulate real-time settings. End-to-End testing is also called Chain Testing. 
- **Non-Functional Testing**: Non-Functional testing is designed to figure out if your product will provide a good user experience.
  - **Performance Testing**: To evaluate the performance of components of a particular system under a particular workload. 
  - **Load Testing**: Testing the behaviour of the system under a specific load or to get the breakeven point where system starts downgrading it’s performance. 
  - **Stress Testing**: It is performed to find the upper limit capacity of the system and also to determine how the system performs if the current load goes well above the expected maximum. 
  - **Usability Testing**: Testing to determine the extent to which the software product is understood, easy to learn, easy to operate and attractive to the users under specified conditions. 
  - **Security Testing**: This intends to uncover vulnerabilities of the system and determine that its data and resources are protected from possible intruders. 
  - **Portability Testing**: Software reliability is the probability that software will work properly in a specified environment and for a given amount of time. 

## Methods of Testing
- **[Black Box Testing]()**: Method in which the internal structure/ design/ implementation of the item being tested is NOT known to the tester. 
- **[White Box Testing]()**: Method in which the internal structure/ design/ implementation of the item being tested is known to the tester. 
- **[Gray Box Testing]()**: Method in which tester has knowledge of some parts of internal structure. 

## Techniques of Dynamic Testing
**[Dynamic Testing]()**: Testing conducting while the program is executed. 

- Structured Based
  - Statement
  - Decision
  - Condition
  - Multiple Condition
- Experienced Based
  - Error Guessing
  - Exploratory Testing
- Specification Based
  - Boundary Value Analysis
  - Equivalence Partitioning 
  - Decision Table Testing
  - Orthogonal Array Testing 
  - State Transition Diagrams
  - Use Case Testing

## Techniques of Static Testing
**[Static Testing]()**: Testing of a software without executing the code. 

- **Review** – Typically used to find and eliminate errors or ambiguities in documents such as requirements, design, test cases, etc.
  - Informal Review
  - WalkThrough
  - Technical Review
  - Inspection
- **Static Analysis** – The code written by developers are analysed (usually by tools) for structural defects that may lead to defects.
  - Static Analysis
  - Data Flow
  - Control Flow

## Test Management
- **Bug Life Cycle**: Defect life cycle is the journey of a defect cycle, which a defect goes through during its lifetime.
- **Continuous Integration CI**: It is a software engineering practice in which isolated changes are immediately tested and reported on when they are added to a larger code base. 
- **Configuration Management CM**: A complete Configuration Management program includes provisions for the storing, tracking, and updating of all system information on a component, subsystem, and system basis. 
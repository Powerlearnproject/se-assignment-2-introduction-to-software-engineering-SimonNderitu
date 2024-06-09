[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244327&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?
At the first conference on software engineering in 1968, Fritz Bauer defined software engineering as "The establishment and use of sound engineering principles in order to obtain economically developed software that is reliable and works efficiently on real machines". Stephen Schach defined the same as "A discipline whose aim is the production of quality software, software that is delivered on time, within budget, and that satisfies its requirements".
While traditional programming focuses on coding and immediate problem-solving, software engineering encompasses the entire software development lifecycle, emphasizing quality, maintainability, and adherence to engineering principles. 

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
SDLC involves phases which include:
Requirements- this includes gathering and documenting user needs and system requirements
Design. This is the creation of high-level detailed design of the software architecture and interfaces
Implementation- this involves writing the code and building the software as per the specifications
Testing. Testing involves conducting test to ensure that software meets the requirements, both functional requirements and quality standards
Deployment. This is the releasing of the software to the users after it has been developed.
Maintenance. This entails provision of updates and enhancement of the software after it has been deployed.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Waterfall is a linear and sequential approach where each phase must be completed before the next one begins. It follows a strict order: requirements, design, implementation, testing, deployment, and maintenance while Agile is an iterative and incremental approach that breaks the project into small cycles called sprints. Each sprint involves all phases of development and results in a potentially shippable product increment.

Waterfall is best suited for short time project while Agile is best suited for long term project.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:
Requirements describe the "what" of a system. Requirements engineering is the disciplined application of proven principles, methods, tools, and notations to describe a proposed system's intended behaviour and its associated constraints
The quality of a software product is only as good as the process that creates it. Requirements engineering is one of the most crucial activities in this creation process. This process consists of four steps which are:
1.	Requirements Elicitation: This is also known as gathering of requirements. Here, requirements are identified with the help of customer and existing systems proc- esses, if available.
2.	Requirements Analysis: Analysis of requirements starts with requirement elicitation. The requirements are analysed in order to identify inconsistencies, defects, omissions etc. 
3.	Requirements Documentation: This is the end product of requirements elicitation and analysis. The documentation is very important as it will be the foundation for the design of the software. The document is known as software requirements specification (SRS).
4.	Requirements Review: The review process is carried out to improve the quality of the SRS. It may also be called as requirements verification. For maximum benefits, review and verification should not be treated as a discrete activity to be done only at the end of the preparation of SRS. It should be treated as continuous activity that is incorporated into the elicitation, analysis, and documentation.


Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity refers to the practice of dividing a software system into distinct, self-contained components or modules, each responsible for a specific aspect of the system's functionality. These modules interact with one another through well-defined interfaces, allowing them to be developed, tested, and maintained independently.
It provides a good way to ensure scalability by:
Ensuring that Teams can work on different modules concurrently without interfering with each other's work, speeding up development, modules can be reused across different parts of the system or in other projects, reducing redundancy and effort, and modules can be scaled independently based on the specific needs of their functionality, allowing more efficient use of resources.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Unit testing- This involves testing of individual components or modules of a software
Integration testing- Testing for interaction between different components or subsystems
System testing- Testing the entire software system as a whole.
Acceptance testing- Testing of software against user requirements thus ensuring that it meets user needs.
Testing helps ensure that the software meets the desired quality standards and is free from defects that could affect its performance or usability, Testing verifies that the software behaves as expected (verification) and meets user needs and requirements (validation) and also provides documentation and insights into the software's behavior, making future maintenance and enhancements easier and less error-prone.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
These are software tools used for tracking changes to source code and coordinating quality. They include:
Git. Features: Distributed version control, Branching and merging capabilities, support for multiple workflows such as Git Flows and Popular hosting services like GitHub, GitLab, and Bitbucket
Mercurial. Features: Distributed version control, Simplicity and ease of use, Robust branching and merging, and extensible with plugins
Perforce Helix Core. Features: Centralized version control, fine-grained access controls, Strong support for large binary files, Advanced merging and branching capabilities and high performance for large codebases

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Project manager roles include: To oversees the planning, execution and delivery of software. It is the responsibility of a manager to manage, motivate, encourage, guide and control the people of his/her team.
Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Maintenance is an essential part of the software lifecycle for several reasons:
Correcting bugs and defects- Software is rarely perfect upon release. Users often encounter bugs that need to be fixed to ensure proper functionality.
Improving performance- Optimization: As software is used, opportunities for optimization become apparent. Maintenance allows for performance improvements to make the software run more efficiently.
Adding new features - User Requirements: Users’ needs and expectations change over time. Maintenance allows the addition of new features to meet these evolving requirements.
Enhancing security - As new security threats emerge, maintenance is essential for patching vulnerabilities to protect against cyberattacks.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Privacy Violations- This entails Collecting excessive user data without consent, and failing to adequately protect user data from breaches.
To address this, the software engineer should prioritize User Privacy and Data Protection by Implement data minimization principles, collecting only what is necessary and using strong encryption and security practices to protect user data.
Security Flaws. This occurs through Releasing software with known vulnerabilities as well as insufficient testing leading to exploitable bugs. 
 A solution to this can be by implementing rigorous testing protocols to identify and fix security vulnerabilities and ensuring comprehensive quality assurance processes are in place.
Conflict of Interest - Making decisions influenced by personal gain rather than user welfare.
To avoid this a developer must avoid the disclosure any potential conflicts to relevant stakeholders and ensure that decisions are made based on the best interest of the project and users, not personal gain.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].

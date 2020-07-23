# Week 8

## [Types of Software Testing](https://www.softwaretestinghelp.com/types-of-software-testing)

**software testing**: a process of analyzing a software item to detect the differences between existing and required conditions (i.e., defects) and to evaluate the features of the software item

*Testing shows the presence of defects - goal is to make software fail.*

Testing approaches include:

* **white box**: based on applications internal code structure (glass box, clear box, structural testing)
  * Done at unit level
  * Internal perspective of the system and programming skills
* **black box**: evaluate the functionality of the software without looking at internal code (behavioral, specification-based, input-output)
* **grey box**: combination of white and black testing
  * Tester has access to design documents
  * Helps create better test cases

**unit testing**: checks individual modules of the source code to make sure properly working

* Typically done by programmers
* Requires detailed knowledge

**integration testing**: testing the connectivity or data transfer between a couple of unit tested modules

* Top-down approach, bottom-up approach, sandwich approach

### Software Testing Types

**alpha testing**: objective is to identify all possible issues or defects before releasing it to the market or to the user

* Most common type of testing in the software industry
* Carried out at the end of software development but before Beta Testing

**acceptance testing**: performed by the client and verifies whether the end to end the flow of the system is as per the business requirements or not and if it is as per the needs of the end-user

* Client accepts the software only when all the features and functionalities work as expected.
* Generally the last phase, also known as UAT

**ad-hoc testing**: objective is to find the defects and break the application by executing any flow of the application or any random functionality

* Informal and can be performed by anyone in the project

**accessibility testing**: determines whether the software or application is accessible for disabled people

**beta testing**: testing done by end-users or others in the *real environment*, the final testing done before releasing an application for commercial purpose

* End-user actually uses the software and shares the feedback to the company

**back-end testing**: testing of the database to validate data through queries

* Testing of table structure, schema, stored procedure, data structure and so on

**browser compatibility testing**: validates how web applications/sites perform on different browsers and operating systems

**backward compatibility testing**:  a type of testing that validates whether the newly developed or updated software works well with the older version of the environment

**boundary value testing**: checks the behavior of the application at the boundary level

* If an input takes a range of numbers from 1 to 500, one would perform tests for 0,1,2,499,500,501.

**branch testing**: code is tested thoroughly by traversing at every branch

**comparison testing**: comparison of a product's strength and weaknesses with its previous versions or other similar products

**compatibility testing**: validates how software behaves and run in a different environment, servers, hardware, and network environment

**component testing**: involves testing of multiple functionalities as a single code and its objective is to identify if any defect exists after connecting those multiple functionalities with each other

**end-to-end testing**: involves testing of a complete application environment in a situation that mimics real-world use

**equivalence partitioning**: testing technique that is a type of black box testing, that involves selecting a set of the group, picking a few values for testing with the understanding that all values from that group generate the same output

* Input accepts -10 to +10, so one would choose a negative value, zero, and a positive value

**example testing**: real-time scenarios based on the experience of the testers

**exploratory testing**: informal testing used to explore the application and look for defects that exist in the application

* Advisable to keep track of what flow you have tested and the activity you did before the start of the specific flow.

**functional testing**: Ignores the internal internal parts of a system and focuses only on the output to check if it is as per the requirement or not

**GUI testing**: validating the GUI as per the business requirement

* Can include the size of the buttons and input fields, alignment of all text, tables, and content in the tables, menu

**gorilla testing**: where one module or the functionality in the module is tested throughly and heavily to check the robustness of the application

**happy path testing**: the objective is to test an application successfully on a positive flow, ignoring negative or error conditions, to validate it generates expected product

**install/uninstall testing**: testing done on full, partial, or upgrade install/uninstall processes on different operating systems under different hardware or software environment

**load testing**: objective is to check how much load or maximum workload a system can handle without any performance degradation

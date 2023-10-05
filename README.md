# Task 4. Salary Emulator
 
Implement Spring app and Junit tests for it. This application will be an internal company salary application with Object Model: Employee, Position, Salary and a few services
 
- EmployeeService: hire/fire new Employees for the specific position
- PositionService: CRUD over the list of available positions in company
- SalaryService: bind salary to position based on yearly salary changes, inflation, $ course and another company events (by your choice)

  	Emulate a few years of company life via console output and duplicate it to log file.

1.	Configure beans using Java-based approach
2.	Implement 3 services using different types of autowiring and scopes
3.	Use factory-method (singleton) and factory-bean (service locator), use FactoryBean with ConfigurationSupport
4.	Pass bean references, string constants and primitive types as constructor parameters
5.	Use setter approach for passing another bean parameter
6.	Divide complex Java configuration into a few simple Java configs
7.	Implement bean that sends message to log at initialization and destroy phases
8.	Use SpEL to inject values (inline lists or math operations) with custom parser configuration
9.	Use correct validation for fields (for example: size of salary, age of Employee) based on JSR-303 Bean Validation API
10.  Provide tests for invalid data
11.  Use field-formatting API when it has a meaning

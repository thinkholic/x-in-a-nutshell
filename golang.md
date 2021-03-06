# Go Programming

## Overview
<todo>

## Audience
Students new to the Go programming language who have experience with other programming languages.

## Prerequisites
This course is specially designed for individuals with prior programming background. Also it assumes a working knowledge of basic Object Oriented Programming concepts. If you have no prior programming experience or not familiar with Object Oriented Programming, you should consider our "Programming Basics for Non-Programmers with Python" course.

## Course Outline
### 1: Variables and Operators
#### Introduction
#### What Does Go Look Like?
#### Using Variables, Packages, and Functions to Print Stars
  - Defining and Printing
#### Declaring Variables
  - Declaring a Variable Using `var`
  - Declaring Multiple Variables at Once with `var`
  - Skipping the Type or Value When Declaring Variables
  - Type Inference Gone Wrong
  - Short Variable Declaration
  - Declaring Multiple Variables with a Short Variable Declaration
  - Declaring Multiple Variables from a Function
  - Using `var` to Declare Multiple Variables in One Line
  - Non-English Variable Names
  - Changing the Value of a Variable
  - Changing Multiple Values at Once
#### Operators
  - Using Operators with Numbers
  - Shorthand Operators
  - Comparing Values
  - Zero Values
#### Pointers
  - Value versus Pointer
  - Getting a Pointer
  - Getting a Value from a Pointer
  - Function Design with Pointers
  - Pointer Value Swap
#### Constants
  - Enums
#### Scope

### 2: Logic and Loops
#### Introduction
#### Logic
  - `if` Statements
  - `if else` Statements
  - `else if` Statements
  - The Initial `if` Statement
  - Expression `switch` Statements
    - Using a `switch` Statement
    - `switch` Statements and Multiple `case` Values
    - Expressionless `switch` Statements
#### Loops
  - The `for i` Loop
    - Looping Over Arrays and Slices
  - The `range` Loop
    - Looping Over a Map
    - Looping Over Map Data Using `range`
  - `break` and `continue`
    - Using `break` and `continue` to Control Loops
  - Bubble Sort

### 3: Core Types
#### Introduction
#### True and False
#### Numbers
  - Integer
  - Floating Point
    - Floating-Point Number Accuracy
  - Overflow and Wraparound
    - Triggering Number Wraparound
  - Big Numbers
#### Byte
#### Text
  - Rune
  - Safely Looping over a String
#### The nil Value

### 4: Complex Types
- Introduction
- Collection Types
#### Arrays
- Defining an Array
- Comparing Arrays
- Initializing Arrays Using Keys
- Reading from an Array
- Writing to an Array
- Looping an Array
  - Looping Over an Array Using a `for i` Loop
  - Modifying the Contents of an Array in a Loop
- Filling an Array
#### Slice
- Working with Slices
  - Printing a User's Name Based on User Input
  - Appending Multiple Items to a Slice
  - Creating a Locale Checker
  - Creating Slices from Slices and Arrays
    - Creating Slices from a Slice
- Understanding Slice Internals
  - Using make to Control the Capacity of a Slice
  - Background Behavior of Slices
  - Controlling Internal Slice Behavior
#### Map Fundamentals
- Creating, Reading, and Writing a Map
  - Reading from Maps
  - Slicing the Week
  - Deleting Elements from a Map
  - Removing an Element from a Slice
#### Simple Custom Types
  - Creating a Simple Custom Type
#### Structs
- Creating Struct Types and Values
- Comparing Structs to Each Other
- Struct Composition Using Embedding
- Type Conversions
- Type Assertions and `interface{}`
- Type Switch

### 5: Functions
#### Introduction
#### Functions
- Parts of a function
#### fizzBuzz
- Creating a simple Function
- Expectation Ratings from the Number of Items Sold
#### Parameters
  - The Difference between an Argument and a Parameter
  - Function Variable Scope
  - Return Values
#### Naked Returns
- Variadic Function
- Anonymous Functions
#### Closures
  - Function Types
#### `defer`

### 6: Errors
Introduction
What Are Errors?
Syntax Errors
Runtime Errors
Exercise 6.01: Runtime Errors While Adding Numbers
Semantic Errors
Exercise 6.02: Logic Error with Walking Distance
Error Handling Using Other Programming Languages
Error Interface Type
Creating Error Values
Exercise 6.03: Creating an Application to Calculate Pay for the Week
Panic
Exercise 6.04: Crashing the Program on Errors Using panic
Recover
Exercise 6.05: Recovering from a Panic
Guidelines when working with Errors and Panic
Activity 6.01: Creating a Custom Error Message
for a Banking Application
Activity 6.02: Validating a Bank Customer's
Direct Deposit Submission
Activity 6.03: Panic on Invalid Data Submission
Activity 6.04: Preventing a Panic from Crashing the App
Summary

### 7: Interfaces
Introduction
Interface
Defining an Interface
Implementing an Interface
Advantages of Implementing Interfaces Implicitly
Exercise 7.01: Implementing an Interface
Duck Typing
Polymorphism
Exercise 7.02: Calculating the Area of Different Shapes
Using Polymorphism
Accepting Interfaces and Returning Structs
Empty interface{}
Type Assertion and Switches
Exercise 7.03: Analyzing Empty interface{} Data
Activity 7.01: Calculating Pay and Performance Review
Summary

### 8: Packages
Introduction
Maintainable
Reusable
Modular
What Is a Package?
Package Structure
Package Naming
Package Declarations
Exported and Unexported Code
GOROOT and GOPATH
Package Alias
Main Package
Exercise 8.01: Creating a Package to Calculate Areas of Various Shapes
The init() Function
Exercise 8.02: Loading Budget Categories
Executing Multiple init() Functions
Exercise 8.03: Assigning Payees to Budget Categories
Activity 8.01: Creating a Function to Calculate Payroll and Performance
Review
Summary

### 9: Basic Debugging
Introduction
Methods for Bug-Free Code
Code Incrementally and Test Often
Writing Unit Tests
Handling All Errors
Performing Logging
Formatting Using fmt
Exercise 9.01: Working with fmt.Println
Formatting Using fmt.Printf()
Additional Options for Formatting
Exercise 9.02: Printing Decimal, Binary, and Hex Values
Basic Debugging
Printing Go Variable Types
Exercise 9.03 Printing the Go Representation of a Variable
Logging
Log Fatal Errors
Activity 9.01: Building a Program to Validate Social
Security Numbers
Summary

### 10: About Time
Introduction
Making Time
Exercise 10.1: Creating a Function to Return a timestamp
Comparing Time
Duration Calculation
Managing Time
Exercise 10.2: Duration of Execution
Formatting Time
Exercise 10.03: What Is the Time in Your Zone?
Activity 10.01: Formatting a Date According to User Requirements
Activity 10.02: Enforcing a Specific Format of Date and Time
Activity 10.03: Measuring Elapsed Time
Activity 10.04: Calculating the Future Date and Time
Activity 10.05: Printing the Local Time in Different Time Zones

### 11: Encoding and Decoding (JSON)
Introduction
JSON
Decoding JSON
Struct Tags
Exercise 11.01: Unmarshaling Student Courses
Encoding JSON
Exercise 11.02: Marshaling Student Courses
Unknown JSON Structures
Exercise 11.03: Analyzing College Class JSON
GOB: Go's Own Encoding
Exercise 11.04: Using gob to Encode Data
Activity 11.01: Mimicking a Customer Order Using JSON
Summary

### 12: Files and Systems
Introduction
Filesystem
File Permissions
Flags and Arguments
Signals
Exercise 12.01: Simulating Cleanup
Creating and Writing to Files
Reading the Whole File at Once
Exercise 12.02: Backing Up Files
CSV
Activity 12.01: Parsing Bank Transaction Files459
Summary

### 13: SQL and Databases
- Introduction
- The Database
- Database API and Drivers
- Connecting to Databases
- Creating Tables
- Inserting Data
Exercise 13.01: Creating a Table with Numbers 477
Retrieving Data
Updating Existing Data
Deleting Data
Exercise 13.02: Holding Prime Numbers in a Database485
Truncating and Deleting Table
Activity 13.01: Holding User Data in a Table
Activity 13.02: Finding Messages of Specific Users490
Summary

### 14: Using the Go HTTP Client
Introduction
The Go HTTP Client and Its Uses
Sending a Request to a Server
Exercise 14.01: Sending a Get Request to a Web Server
Using the Go HTTP Client
Structured Data
Exercise 14.02: Using the HTTP Client with Structured Data499
Activity 14.01: Requesting Data from a Web Server
and Processing the Response
Sending Data to a Server
Exercise 14.03: Sending a Post Request to a Web Server
Using the Go HTTP Client
Uploading Files in a Post Request
Exercise 14.04: Uploading a File to a Web Server via a Post Request506
Custom Request Headers
Exercise 14.05: Using Custom Headers and Options
with the Go HTTP Client
509
Activity 14.02: Sending Data to a Web Server and Checking
Whether the Data Was Received Using POST and GET 512
Summary

### 15: HTTP Servers
Introduction
How to Build a Basic Server
HTTP Handler
Exercise 15.01: Creating a Hello World Server518
Simple Routing
Exercise 15.02: Routing Our Server
Handler versus Handler Function
Activity 15.01: Adding a Page Counter to an HTML Page524
Returning Complex Structures
Activity 15.02: Serving a Request with a JSON Payload527
Dynamic Content
Exercise 15.03: Personalized Welcome
Templating
Exercise 15.04: Templating Our Pages
Static Resources
Exercise 15.05: Creating a Hello World Server Using a Static File
Getting Some Style
Exercise 15.06: A Stylish Welcome
Getting Dynamic
Activity 15.03: External Template
HTTP Methods
Exercise 15.07: Completing a Questionnaire
JSON loads
Exercise 15.08: Building a Server That Accepts JSON Requests
Summary

### 16: Concurrent Work
Introduction
Goroutines
Exercise 16.01: Using Concurrent Routines
WaitGroup
Exercise 16.02: Experimenting with WaitGroup
Race Conditions
Atomic Operations
Exercise 16.03: An Atomic Change
Invisible Concurrency
Activity 16.01: Listing Numbers
Channels
Exercise 16.04: Exchange Greeting Messages via Channels
Exercise 16.05: Two-Way Message Exchange with Channels
Exercise 16.06: Sum Numbers from Everywhere
Exercise 16.07: Request to Goroutines
The Importance of Concurrency
Exercise 16.08: Equally Splitting the Work between Routines
Concurrency Patterns
Activity 16.02: Source Files
Buffers
Exercise 16.09: Notifying When Computation Has Finished
Some More Common Practices
HTTP Servers
Methods as Routines
Exercise 16.10: A Structured Work
Go Context Package
Exercise 16.11: Managing Routines with Context
Summary

### 17: Using Go Tools
Introduction
The go build Tool
Exercise 17.01: Using the go build Tool
The go run Tool
Exercise 17.02: Using the go run Tool
The gofmt Tool
Exercise 17.03: Using the gofmt Tool
The goimports Tool
Exercise 17.04: Using the goimports Tool
The go vet Tool
Exercise 17.05: Using the go vet Tool
The Go Race Detector
Exercise 17.06: Using the Go Race Detector
The go doc Tool
Exercise 17.07: Implementing the go doc Tool
The go get Tool
Exercise 17.08: Implementing the go get Tool
Activity 17.01: Using gofmt, goimport, go vet, and go get to Correct a File
Summary

### 18: Security
Introduction
Application Security
SQL Injection
Command Injection
Exercise 18.01: Handling SQL Injection
Cross-Site Scripting
Exercise 18.02: Handling XSS Attacks
Cryptography
Hashing Libraries
Exercise 18.03: Using Different Hashing Libraries
Encryption
Symmetric Encryption
Exercise 18.04: Symmetric Encryption and Decryption
Asymmetric Encryption
Exercise 18.05: Asymmetric Encryption and Decryption
Random Generators
Exercise 18.06: Random Generator
HTTPS/TLS
Exercise 18.07: Generating a Certificate and Private Key
Exercise 18.08: Running an HTTPS Server
Password Management
Activity 18.01: Authenticating Users on the Application
Using Hashed Passwords
Activity 18.02: Creating CA Signed Certificates Using Crypto Libraries

### 19: Special Features
Introduction
Build Constraints
Build Tags
Filenames
Reflection
TypeOf and ValueOf
Exercise 19.01: Using Reflection
Activity 19.01: Defining Build Constraints Using Filenames
DeepEqual
Wildcard Pattern
The unsafe Package
Exercise 19.02: Using cgo with unsafe
Activity 19.02: Using Wildcard with Go Test

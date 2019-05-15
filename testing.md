# Developer Testing 

## Types of Tests 
- Unit Test: Execution of a complete class, routine, or small program that has been written by a single programmer or team, which is testing in isolation from complete team. 
- Integration Test: Combined execution of two or more classes, packages, componenets, or subsystems that have been created by multiple programmers. 
- Component Test: Execution of a class, package, or small program that involved work of multiple programmers, which is tested in isolation from complete system
System 
- System Test: Execution of software in its final configuration, including integration wtih other software and hardware systems. Tests for security, performance, timing probrlmes, and other issues that can't be tested at lower levels of integration. 
- Regression : Repetition of previously executed test cases for the purpose of finding bugs that previously passed the same set of tests. 
-  Basis Testing: Test each statement in code at least once. All possible paths. 

## Equivalence Partitioning 
- Good test case covers large part of possible input data
- If two test cases flush out same errors, just save one 
- Ultimately reduce number of test cases required

## Error Guessing 
- Creating test cases based on guesses about where program might have errors
- Requires certain amount of sophistication in guessing 
- Base guesses on intuition and past experiences

## Boundary Analysis 
- Off-by-one error 
- num instead of num-1
- `>` instead of `>=`

## Bag o' Tricks 


## Good Data vs. Bad Data


## Keeping Records 
- Full description of problem 
- Time it took to fix 
- Suggested workaround 
- Steps to repeat problem 
- Related defects 
- Severity 

- Origin 
- Subclassification 



## Common Errors 
- Structural 
- Data 
- Functionality as implemented
- Construction 
- Integratoin 
- Functional Requirements 
- Test Defs or execution 
- System, software architecture 
- Unspecified 

### Tips 
- About 8-25% of project time should be spent testing
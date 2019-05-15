# Conquering Complexity 
The complexity in your code can affect **program runtime**, **structure**, **readability** and **error number**. 

## Techniques to Reduce Complexity 
1. **Divide system into subsystems at the architecture level** so your brain can focus on a smaller amount at a time. 
2. **Carefully define class interfaces** so you can ignore the internal workings of the class 
3. **Preserve the abstraction** represented by class interface so your brain doesn't have to remember arbitrary details. 
4. **Avoid global data**, it vastly increases the percentage of code you need to juggle in your brain at any one time. 
5. **Avoid deep inheritance heirarchies** because they are intellectually demanding  
6. **Avoid deep nesting** of loops and conditionals because they can be replaces by simpler control structures that burn up fewer grey cells
7. **Carefully define your approach to error handling** rather than using an arbitrary proliferation of different error-handling techniques 
8. **Keep functions short** and use clear, self-explanatory variable names 
9. **Minimize number of parameters passed in**
10. **Use conventions** to spare brain the challenge of remembering arbitaray accidental differences between sections of code
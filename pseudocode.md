# What is Pseudocode? 
Pseudocode is an informal, english-like notation for describing how an algorithm, routine, class, or program will work. 

## Why is it important?
- Ease of idiation and iteration
- A way for non-technical stakeholders to understand work 
- Great for quickly discussing ideas with a team 

## The Steps 
1. **Break the Problem Up** </br>
&nbsp;&nbsp;&nbsp;- Don't start pseudocoding right away</br>
&nbsp;&nbsp;&nbsp;- Deconstruct into smaller problems</br>
2. **Create a General Design** </br>
&nbsp;&nbsp;&nbsp;- Start at highest level </br>
&nbsp;&nbsp;&nbsp;- What is goal of function/ feauture/ class?</br>
3. **Drill Down into Design**  </br>
&nbsp;&nbsp;&nbsp;- Start writing nuts and bolts of pseudocode</br>
&nbsp;&nbsp;&nbsp;- What do pseudocode innards look like?</br>
4. **Review**</br>
&nbsp;&nbsp;&nbsp;- Reflect, make sure you've solved given problem </br>
&nbsp;&nbsp;&nbsp;- Walk thru pseudo code, have someone else try</br>

## Pseudocode Checklist 
- Writtin in plain english 
- No code notation! No funcs, operators, etc
- Anyone can understand it, regarldess of tech experience 
- High level architecture, not *how* code will be written 

## Pseudocode Example
### Bad
```
total = 0
For i = 0, while i is less than ageList.length, i++
total = total plus ageList(i) 
Average = total divided by ageList length
return average

```
### Good
```
Set total to zero
For each age in the list
Add the age into the total
Set average to the quotient of the total and the length of the list
Print the average

```
1. Concept in my own words:
Switch-statement is another way to make decisions in my program. similar to if-statement, but cleaner when I have many possible choices. Imagine that instead of
using "else if" for many conditions, a switch lets me check one value against several cases.When the program runs, it looks at the value inside the switch, finds
the matching case, and runs the code inside that case. Switch‑statements are useful when you want to compare one variable to many fixed options, like menu choices 
or grades.Switch‑statements also appear in loops, functions,or arrays.

2. Key C# Syntax:
- Include one "switch" and many "case"
- Each one ends with "break"

3. Eureka Exercise/ Moment
The exercise that helped me understand switch‑statements was when I recreated a simple Bhive Menu. At first, I kept forgetting to add break, which caused the program to run multiple cases at once. 
I also didn’t understand why switch was better than writing a bunch of if‑statements. It finally made sense when I saw how clean and organized the
switch‑statement looked compared to several else if lines. After that, I understood how switch connects to if‑statements, loops, and even functions that 
return values used inside the switch.

4. Common beginners mistake:
A common mistake I made was forgetting the break statement. Without it, the program “falls through” and runs the next case even if it doesn’t match. 
This happened because I didn’t realize that switch‑statements don’t automatically stop after a case. Once I learned the purpose of break,
my switch‑statements worked the way I expected.


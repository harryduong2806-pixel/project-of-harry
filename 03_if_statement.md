1. Concept in my own words:
If-statement lets my program make decisions between mutiple options. It will check the condition first, if the condition is satisfied, it will execute something I tell the
computer to do, if no, it will skip to the next options. They also connect to other concepts like loops, and switch-statement. It will help you understand the flow of your code
more easily.

2. Key C# Syntax:
- It will execute the body if the condition is satisfied.
- Other parts of if-statement are "else" and "else if".

For instance:
int age = 17;

if (age >= 18) 
{
    Console.WriteLine("Adult");  (the condition is age greater and equal than 18, if the condition is satisfied, execute Write "Adult")
} 
else 
{
    Console.WriteLine("Minor"); (if age is not greater and equal than 18, execute Write "Minor")
}

3. Eureka Exercise/Moment
The exercise that helped me understand if‑statements was when we wrote a program that checked whether a number was prime or not.At first, I kept writing conditions incorrectly, 
like using = instead of ==, or forgetting parentheses. It finally clicked when I saw how the program chose different paths depending on the condition. 

4. Common beginners mistake:
A common mistake I made was writing conditions that always evaluated to true or false without realizing it. For example, I wrote if (x = 5) instead of if
(x == 5), which actually changed the value of x instead of checking it. This happened because I didn’t fully understand the difference between assignment
and comparison. Once I learned how operators work inside conditions, my if‑statements became much more accurate.

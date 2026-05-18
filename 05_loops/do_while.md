1. Concept in my own words:
A do-while loop is a loop that always run at least once before checking the condition. So, it is very useful for things like validation, like asking the user
for input, after that, computer will check input with condition, if it is satisfied, it will stop and execute the next part, if no, it will repeat.The condition 
is put after "while" and the code will be put in "do".

2. Key C# Syntax:
- Do first, check after
- After "do", it will be followed by a couple of curly bracket, the code will be put in that
- After code part will be while and follow by a semicolon

-For instance:
int number;

do {
    Console.Write("Enter a positive number: ");
    number = int.Parse(Console.ReadLine());
} while (number <= 0);

3. Eureka Exercise/Moment:
The moment do-while really made sense was when i redid the Bhive exercise using do-while loop to validate something in the code. At first, I really have difficulties
figuring out why the code did not execute as I expected. Then, I did some research and found out that It is due to missing operators.

4. Common beginner mistake:
One mistake I made early on was forgetting the semicolon after the while (condition) line. Without it, the program wouldn’t compile, and I had no idea why
. Another mistake was creating an infinite loop because I forgot to update the variable inside the loop. Both issues came from not fully understanding how
the condition and operators worked together. Once I slowed down and traced the loop step by step, it became much easier to control.
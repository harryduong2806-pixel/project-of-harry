WHILE LOOP:
1. Concept in my own words:
A while loop repeats a block of code as long as its condition stays true. It is different from do-while loop in the first time that they execute.
While loops connect to other concepts like arrays (looping through elements), functions (repeating actions), and even switch‑statements when building menus.

2. Key C# Syntax:
- Check condition first
- End when condition becomes false

- Basic example:
int count = 5;

while (count > 0) {
    Console.WriteLine(count);
    count--;
}

3. Eureka Exercise/Moment:
The while loop clicked for me when I did some extra exercise at home. It was about printing numbers until I said "stop". At first, I forgot to update
the variable inside the loop, which caused an infinite loop. I also didn’t fully understand that the condition is checked before the loop runs.
Once I traced the code step by step, I realized how important it is to change the variable inside the loop so the condition eventually becomes false.
After that, while loops felt much more predictable and easier to use.

4. Common beginner mistake:
A mistake I made early on was writing a condition that never changed, which caused the loop to run forever. I also sometimes used = instead of comparison 
operators like == or >. These mistakes happened because I didn’t fully understand how the condition controlled the loop.

FOR LOOP:
  
1. Concept in my own words:
For loop is a loop that runs a specific number of times. It has three parts: a starting value, a condition (range), and an update (+,-,..). This loop keeps running 
until it reaches its range. They rely on operators for the condition and the update, and they connect to other concepts like arrays, nested loops, and 
functions that return values you want to loop through. Once you understand for loops, you can write cleaner and more organized code for repeated tasks.

2. Key C# Syntax:
- Has an initializer, condition and update
- Run as long as the condition is true
- For instance:
for (int i = 0; i < 5; i++) {
    Console.WriteLine(i);
}

3. Eureka Exercise/Moment:
The for loop made sense to me when we used it to loop through an array and print each element. At first, I kept messing up the index or forgetting that
arrays start at index 0.Once I understood how the initializer, condition, and update worked together, for loops became one of the easiest tools to use.

4. Common Beginners mistake:
A common mistake I made was writing the wrong condition, like using <= instead of <, which caused an “index out of range” error when looping through arrays. 
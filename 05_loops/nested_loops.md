1. Concepts in my own words:
Nested loops are when you put one loop inside another. The outer loop runs first, and for each time it runs, the inner loop runs completely. 
This is useful when you need to work with rows and columns, patterns, or 2D arrays. Nested loops rely on the same operators and conditions as regular loops
, but they let you repeat actions in multiple layers.

2. Key C# Syntax:
- Inner loop repeats fully for every steps of the outer loops
- When the inner loop finish its whole turn, the outer loop will execute the next turn.
 For instance:
 for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 2; j++) {
        Console.WriteLine($"i={i}, j={j}");
    }
}

3. Eureka Exercise/Moment:
Nested loops clicked for me when I did an exercise of tracing. At first, I was struggeling with the code and the condition. Then, I did some research and 
understood more about this concept.

4. Common Beginner Mistake:
A mistake I made was using the same variable name for both loops, which broke the logic. Another mistake was forgetting to reset the inner loop variable.
These happened because I didn’t fully understand how each loop controls its own counter.
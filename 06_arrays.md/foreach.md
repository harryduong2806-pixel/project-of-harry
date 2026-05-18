1. Concept in my own words:
Foreach Loop is used to go through every item in total of things, like an array or list, one by one. You can connect to each element directly, this thing 
can make your code easier and cleaner to read. Like these concepts before, this concept can connect to other concepts.

2. Key C# Syntax:
- Read each elements in order.
- No index needed:
int[] numbers = { 1, 2, 3, 4 };

foreach (int num in numbers) {
    Console.WriteLine(num);
}

3. Eureka Exercise/Moment:
- Foreach finally made sense to me when I used it to print every value in an array. I kept trying to use an index at first because I was used to for 
loops. Once I realized foreach automatically gives you each item, I understood why it’s so simple and useful. After that, looping through arrays felt
much easier.

4. Common Beginners Mistake:
A mistake I made was trying to change the values inside a foreach loop. I didn’t know that foreach is meant for reading, not modifying. Another mistake
was thinking I could use an index inside foreach, which doesn’t work.


1. Concept in my own words:
2D array is a table made of rows and columns. 2D stores data in a grid. We will have two indexes: one for the row and one for the column. This is useful for 
things like game boards, seating charts, or something like that.

2. Key C# Syntax:
- First index is row
- Second index is column
- Or you can relate to (x;y) x will be the vertical and y will be the horizontal one.
- For instance:
int[,] grid = {
    {1, 2, 3},
    {4, 5, 6}
};

Console.WriteLine(grid[0, 1]); // prints 2

3. Eureka Exercise/ Moment:
At first time, I was confused about the order of indexex in 2D array, but after few exercises, I finally figured out and this concept really made sense to
me.

4. Common Beginners Mistake:
I think It was about the order of the indexes in grid, some people will have difficuties distinguishing 2 indexes like [row,column] and [column,row].


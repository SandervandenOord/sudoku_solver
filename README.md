# Sudoku solver
Solving sudoku's brute force (but fast)

I use a simple brute force method:  
1. Find all coordinates without a number (a zero instead of a number 1 to 9).
2. Try for the first coordinate the number 1.
3. Check if number is possible: no nr 1 in row, column or sector present already.
4. If number already present, try higher number for that coordinate.
5. If number is possible in current coordinate, go to next coordinate. 
6. If no number is possible at all in a coordinate, it means we have filled an earlier coordinate with the wrong number. So we backtrack one coordinate and try for that coordinate a different, higher number.

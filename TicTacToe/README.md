#Calculate winner function() <br>
1) lines array is initialized with all possible winning conditions <br>
2) function iterates through each winning combination<br>
3) Each iteration are destructured into variables 'a', 'b', 'c' <br>
4) Function checks if the cells in the current winning combination have the same value.<br>
- squares[a] ensures that the cell at index 'a' is not empty<br>
- squares[a] === squares[b] checks if the cells at indicies 'a' and 'c' have the same player symbol <br>
5) if the condition is true, there's a winner and the function returns the player symbol at index 'a' (either 'X' or 'O') <br>
6) If the loop iterates through all the winning combinations and none of them satisfy the winning condition, the function returns 'null, indicating that there's no winner yet.


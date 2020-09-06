# CodeHS Chess

CodeHS Chess AI Using a Minimax Algorithm

[Code on CodeHS](https://codehs.com/sandbox/phillipcutter/Working_Chess)

[App on CodeHS](https://codehs.com/sandbox/phillipcutter/Working_Chess/run)

This project was during my 10th grade in high school because I had too much free time in my various CTE classes.

The AI in this program simply uses the minimax algorithm to calculate the best possible position to move to. It does this by testing each possible move on a board, generating an output "score" from each possible move, and choosing the most favorable score. The advantage of this AI is that it can simulate the user's move and pretend the user will play the best move too. This can repeat to a predefined depth allowing the AI to "see forward more turns". This means that as the depth increases, so does how good the AI is at picking moves.

Development for this project only took place during school and eventually I ran out of time to work on it. To see the most recent version (which seems to be broken), check out the [latest branch](https://github.com/mrfleap/codehs-chess/tree/latest).

# Features

There aren't a lot of fancy features, but these are some honorable mentions for this small project:

- AI vs AI or player vs player with `blackAI` and `whiteAI` variables
- Variable screen height and width rendering
- Custom number of columns and rows for board rendering
- Customizable weights for pieces
- Customizable colors

Download Link: https://assignmentchef.com/product/solved-cs160-assignment-10-tic-tac-toe
<br>
<strong> Program Implementation                                     </strong>

You will write a program that plays the game <strong>Tic-Tac-Toe</strong>.

First, prompt the user to find out if they want to play with one or two players.  If the user wants to play with only one player, then the computer must be the other player.  You can choose whatever algorithm you want for the computer, i.e. picking random places to put the piece or intelligently selecting your move based on player 1’s selection.  However, you must not select a position that has already been selected at any time!!!

After you determine how many players are playing the game, then you can determine what character each player wants to choose.  You must make sure that Player 2 or the computer doesn’t choose the same character as Player 1.  Print the empty board, and then prompt the player(s) for their position on the board, printing the board after each turn.  Make sure that the player(s) chooses valid positions on the board!!!

<strong>Example Tic-Tac-Toe: </strong>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/273-1.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/273-1.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/492.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/492.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Congratulations Player 1, you are a winner!!!

<strong>Program Input:</strong>

<ul>

 <li>Determine whether the user wants to play 1 or 2 players for Tic-Tac-Toe</li>

 <li>The character/game piece each player wants.</li>

 <li>Player’s choice of position on the board.</li>

</ul>

<strong> </strong>

<strong>Program Output:</strong>

<ul>

 <li>The view of the board after each player’s turn, along with an initial empty board.</li>

 <li>A prompt asking for the player’s selection on the board.</li>

</ul>

<strong> </strong>

<strong>Tic-Tac-Toe Error Handling: </strong>

<ul>

 <li>Player’s choice is not appropriate, such as a non-positive int for row/column</li>

 <li>Player chooses a position that is not on the board, i.e. row 5, column 2.</li>

 <li>Player chooses a position that is already occupied.</li>

 <li>Player 2 chooses Player 1’s character.</li>

</ul>

Some functions you might want to include are an <strong>initialize_board()</strong>, which initializes the board to spaces, a <strong>get_player_piece() </strong>that allows players to pick their pieces, i.e. ‘X’ or ‘O’,  <strong>choose_next_move()</strong>, which fills the board with the player’s choice, a <strong>print_board()</strong> that prints the board to the screen after each user’s turn, <strong>is_full()</strong> to check if the board is full, a <strong>is_winner()</strong>, which checks to see if there is a winner, and a <strong>print_winner_results()</strong> that prints the results of the game to the screen.

<strong> Program Design </strong>

Begin by designing you program using these steps, and write steps 1, 2, and 4 on paper or in a text editor.  Then, implement the program using Python.

<ul>

 <li><strong>Step 1:</strong> <strong>Problem Analysis</strong>. (10 pts)</li>

</ul>

Do you understand everything in the problem? List anything you do not fully understand, and make sure to ask a TA or instructor about anything you do not understand.

<ul>

 <li>What are the user inputs/requirements, program outputs, etc.?</li>

 <li>What assumptions are you are making?</li>

 <li>What are the functional requirements of this problem?</li>

 <li>What are all the tasks and subtasks in this problem?</li>

 <li><strong>Step 2:</strong> <strong>Program Design</strong>. (20 pts) List the specific steps needed to play the game of</li>

</ul>

TicTacToe.  What does the overall big picture of this program look like? (flowchart or pseudocode) o What are all the higher-level tasks to accomplish in this program, and where will you call each task?

<ul>

 <li>What are the decisions that need to be made to determine which high-level tasks to complete?</li>

 <li>Based on all the tasks you identified, what does the algorithm details in each task look like?</li>

</ul>

(flowchart or pseudocode)

&#x25aa; What are the decisions you’ll make within each task?

<ul>

 <li>How and where are you going to handle bad input?</li>

</ul>

Based on your answers above, list the <strong>specific steps or provide a flowchart </strong>of what is needed to program Tic-Tac-Toe. Be very explicit!!!




<ul>

 <li><strong>Step 3:</strong> <strong>Program Implementation</strong>.</li>

</ul>

This is the Python code that plays TicTacToe.




<ul>

 <li><strong>Step 4:</strong> <strong>Program Testing</strong>. (10 pts)</li>

</ul>

Create a Test Plan with several test cases including good and bad cases.






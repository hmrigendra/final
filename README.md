In this I have make a GitHub Action file that plays tic tac toe with you whenever you push into the repo.

Pre-Requisites
You have to first initialise the board to have 10 spaces for it to work. You have to change the main branch to master. You have to give GitHub Actions Workflow persission as Read and Write.

Note
Each character in board.txt represents a space in tic-tac-toe grid. The first blankspace represents nothing.
 123456789 represents 9 | 8 | 7
                      4 | 5 | 6
                      1 | 2 | 3

Working
You have to pull after initial push to see the changes made to board.txt. You will have to push again after editing the board.txt file by removing a blankspace and adding X. This will go on till anyone of you win.

Apologies. I couldn't fine tune this due to lack of time. One problem occuring is GitHub actions is taking first two moves without our intervention. It also doesn't display whether you won or lost. The tictactoe1.py code is also not visually appealing.

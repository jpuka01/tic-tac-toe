# CS20 HW5 Tic Tac Toe Deliverables

1. Worksheet uploaded in a Word document on Canvas
2. All files (ttt1 through ttt4) are compressed in zip and uploaded to Canvas

- ttt1.html:
- ttt2.html:
- ttt3.html:
- ttt4.html:

## Answered Questions

1. The most challenging part of this assignment is accounting for the many 
different logics that make up the game as a whole. I also found working with 
the provided code from ttt2.html initially confusing, but eventually figured 
out how to work with the code among other various challenges I faced.

2. There are a couple code sections that I really enjoyed implementing. One
section of code that I'm proud of is this:

// Create an array of current board values (X, O, -)
            for (let i = 0; i < NUM_SQUARES; i++) {
                let square = document.getElementById("sq" + i);
                // If square is empty, -, else, maintain current square value
                moves[i] = square.innerText === "" ? "-" : square.innerText;
            }

I particularly liked this section because given the context of checking every
square per turn, I found this implementation pretty nifty as the code snippet 
handles the current state of each square as the game progresses inside an array.
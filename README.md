# Rock-paper-scissors-lizard-Spock
### Mark Addinall
### ASSET-IQ Dealer Network

The object of this coding task is to write a small geek game,
Rock-Paper-Scissors-Lizard-Spock. It is suitable for both
our front-end candidates where we expect the code delivered
in Javascript (and or some library, React, Angular, Vue) and
our server side candidates where we expect the solution to be
delivered in Python. You may use Flask if you are familiar with
this library.

The Javascript solution will obviouly be executed in a browser.

Code, both front end and back end should use object oriented or 
functional programming techniques. We will be paying attention
to:
- program structure
- algorithm design
- code readability
- documentation

Rock, Paper, Scissors, Lizard, Spock is a game of chance. 
It is first used to settle a dispute about what to watch on TV between 
Sheldon and Raj in "The Lizard-Spock Expansion - BIG BANG THEORY".

The game was originally created by Sam Kass with Karen Bryla.

## Rules:

The game is an expansion on the game Rock, Paper, Scissors. 
Each player picks a variable and reveals it at the same time. 
The winner is the one who defeats the others. 
In a tie, the process is repeated until a winner is found.

- Scissors cuts Paper
- Paper covers Rock
- Rock crushes Lizard
- Lizard poisons Spock
- Spock smashes Scissors
- Scissors decapitates Lizard
- Lizard eats Paper
- Paper disproves Spock
- Spock vaporizes Rock
- (and as it always has) Rock crushes Scissors


There are many ways to solve this game.  The one we
would like delivered is to equate the strings
"rock", "paper", "scissors", "lizard", "Spock" to numbers
as follows:

- 0 - rock
- 1 - Spock
- 2 - paper
- 3 - lizard
- 4 - scissors

and deduce an algorith to determine the winner, you or the computer!
(**BIG HINT** modulo arithmatic)

Build a method nameToNumber(name) that converts the string name into a 
number between 0 and 4 as described above. This function should use a sequence of 
process controls of your choice. You can use conditions of the form name == 'paper', etc. to 
distinguish the cases, switch/case constructs or positional arithmatic. your choice. 

Your code should also include a final clause that catches cases when name does not 
match any of the five correct input strings and prints an appropriate error message. 

Next, you should build a second method, numberToName(number) that converts 
a number in the range 0 to 4 into its corresponding name as a string. Again, we suggest 
including a final clause that catches cases when number is not in the correct range. 

Implement the first part of the main function rpsls(playerChoice).
Design an intereactive session with the user of your computer game.
It is ENTIRELY up to you how this is done.  If you are a candidate for
our front end position, you may want to start giving use some visual
**WOW!** starting about now!  The Python should be at least neat!

Implement the second part of rockPaperSpock that generates the computer's guess and shows 
an appropriate message for that guess. In particular, compute a random number compNumber 
between 0 and 4 that corresponds to the computer's guess using an appropriate method.

You should make sure that you do not accidently generate numbers in the wrong range. 

Then compute the name compChoice corresponding to the computer's number using the function 
numberToName() and display an appropriate message with the computer's choice to the console.

Implement the last part of rockPaperSpock that determines and presents the winner. 
Specifically, compute the difference between compNumber and playerNumber using the algorithm
you designed.

Then write a closing method whose conditions test the various possible values of 
this difference and then prints an appropriate message concerning the winner.

Again, if you are a front end candidate, show us some **bells-and-whistles!**

What to do?  Follow the button into our Git repository, clone it, start a new branch with your name in
the branch name and code away!

Have fun.


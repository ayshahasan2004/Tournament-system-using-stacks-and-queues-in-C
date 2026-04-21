This project simulates a tournament system using stacks and queues in C.
It is developed by Aysha Mohammad under the supervision of Dr. Radi Jarrar.
The system manages multiple teams competing in elimination rounds.
Each match determines a winner based on round rules (odd or even).
Odd rounds: the smaller team ID wins.
Even rounds: the larger team ID wins.
A queue is used to manage teams in each round.
A stack is used to track losing teams.
The tournament continues until a single champion remains.
The program also determines the runner-up team.
Runner-up is calculated based on teams that lost to the champion.
Dynamic memory allocation is used for storing team IDs.
The program validates user input for number of teams and IDs.
Invalid inputs are rejected and re-entered by the user.
The system supports automatic advancement if a team has no opponent.
Each round's results are printed clearly on the screen.
The final output shows the champion and runner-up teams.
The implementation demonstrates queue and stack operations.
It also shows practical use of linked structures in C.
This project is part of a Data Structures course assignment.

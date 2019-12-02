# project1 pseudocode

1) single player mode

2) pick a category and its associated point value

Categories:

     . Category needs a few clickable elements beneath them that are worth a variety of points.
- These elements need to be:

     . Clickable
     . Store a value (the points it’s worth)
     . Disappear or disable themselves after they’ve been selected.
      

3) answer question in alotted time period

    . when category is clicked, 10 second timer begins
    . if question is answered before 10 second timer ends, points are awarded
    . if question is not answered before 10 second timer ends, no points are awarded

- timer needs to do 3 things 
    . Start.
    . Countdown 
    . Check if the correct answer was chosen, and if not display something.

- Timer task:
    . onClick that listens for when a user clicks a category.
    . startTimer() function to start the countdown.
    . if/else statement you check if an answer was chosen before time runs out.


4) If correct, say "Correct" and award associated points

5) if incorrect, say "Incorrect" and follow up with correct answer response.

6) Game continues until all questions have been answered and/or points recieved.

7) If player earns more than 2000, points, they win the game.

8) if player earns less than 2000 points, player loses the game.

# Football Shots Dataset for xG models
 A primitive dataset to store information about shots taken in football matches. Meant for creating xG models (personal use, not commercial).

The data was collected from [Understat]{https://understat.com} using the [understat]{https://github.com/amosbastian/understat} package.

It includes information about:

1. 'minute' - Minute of the match in which the shot was taken.
2. 'X', 'Y' - X & Y coordinates from where the shot was taken.
3. 'h_a' - Binary value to indicate whether it was a home game or an away game.
4. 'situation' - Integer labels to indicate the situation in which shot was taken. For example, open play, set piece, etc.
5. 'shotType' - Integer label to indicate whether the shot was right footed, left footed, a header, or with another body part.
6. 'h_goals' - number of goals the home team had scored at the point of time of the shot.
7. 'a_goals' - number of goals the away team had scored at the point of time of the shot.
8. 'lastAction' - Integer label to indicate the last action that had been performed before the shot was taken.
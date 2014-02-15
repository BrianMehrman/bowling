bowling
=======

figure out and print the score of each frame for an array of rolls during a bowling match

A bowling match consists of ten frames. Each frame except for the tenth consists of one or two balls, or attempts to knock down the ten pins at the end of the alley. Doing so on the first ball of the frame is called a strike, and the second ball of the frame is not rolled. Knocking down all ten pins with both balls (having left some up with the first ball) is called a spare. If both attempts to knock down the pins leave some standing, the frame is called an open frame. A spare in the tenth frame gives the bowler one extra ball; a strike in the tenth gives him or her two extra balls. A bowling score is computed as follows. A strike counts as 10 points plus the sum of the next two balls. A spare counts as 10 points plus the next ball. Any other balls merely count as themselves, as do any bonus balls rolled as a result of a strike or a spare in the tenth frame. Suppose for example that the sequence of balls was

[9,1,   0,10,   10,   10,   6,2,   7,3,   8,2,   10,   9,0,   9,1,   10]

spacing is not important but it may make the example easier to understand

The output from the console or UI show be as follows:
Frame   score
-----   ----- 
 1       10 
 2       30 
 3       56 
 4       74 
 5       82 
 6      100 
 7      120 
 8      139 
 9      148 
 10     168

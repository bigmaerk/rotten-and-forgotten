-- movement patterns --

=================
Entrance........0 [1]
Arcade..........1 [2,0]
Diner...........2 [4,1]
Hallway 1.......3 [10,5,2]
Hallway 2.......4 [9,4]
Office..........5 [5]
Ancillary.......6 [6,5,3]
Kitchen.........7 [9]
Electrical......8 [7,9]
Backstage.......9 [8,6]
Supply Closet...10 [7]
=================

FREDBEAR:
- starts at backstage
- 75% (3/4) chance of making decision
- 2000ms per decision
- 3/4 chance of avoiding office
- at next move, add 1 to number of visits in that room
- go to room with lower amount of visits
- if rooms are same amount, choose random room

# Java_Rubiks_Cube
A virtual Rubik's cube written in java with multiple functions to manipulate a rubiks cube.

## ---functions included (and syntax)--- 

1. **demo( int scrams )** - 
                         
2. **negate( String move )** - Move(String) takes given move and returns the oposite move.

3. **rowRight( int row )** - int row(row number 0-2 to be rotated right)

4. **rowLeft( int row )** - int row(row number 0-2 to be rotated to the left)

5. **columnDown( int column )** - int column ( column 0-2 to be rotated down)

6. **columnUp( int column )** - int column (column 0 -2 to be rotated up)
                                          
7. **calcSim( Cube cube2 )** - Compares each cell of given cube and object cube, returns % similarity
                             
8. **printCube()** - Prints cube with each face labeled to console
                      
9. **scramble( int scrams )** - Randomly makes int scrams amount of random moves to the cube.
                                 
10. **interpretMove( String move )** - String move (move abbreviation to be completed) executes
                                       move abbreviation.

# How the cube is ordered

- [0] Front Face
- [1] Top Face
- [2] Back Face
- [3] Bottom Face
- [4] Left Face
- [5] Right Face
  
# How the cube face's are ordered

   [0]   [1]  [2]
[0]  R    R   R

[1]  R    R   R

[2]  R    R   R

# Move Abreviations

- U# - rotate column # up
- D# - rotate column # down
- L# - rotate row # to the left
- R# - rotate row # to the right




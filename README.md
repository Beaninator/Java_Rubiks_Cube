# Java_Rubiks_Cube
A virtual Rubik's cube written in java with multiple functions to manipulate a rubiks cube.

## ---functions included (and syntax)--- 

1. demo( cube, scrams) - cube(3D arraylist) int scrams(amount of random moves that will be taken)
                         This function takes a PRE-INITIALIZED CUBE and randomizes it then, negates
                         all moves taken which gives the illusion of the cube being solved
                         
2. negate(move) - move(String) takes given move and returns the oposite move.

3. rowRight( cube, row ) - cube(3D arraylist) int row(row number 0-2 to be rotated right)

4. rowLeft( cube, row ) - cube(3D arraylist) int row(row number 0-2 to be rotated to the left)

5. columnDown( cube, column ) - cube(3D arraylist) int column ( column 0-2 to be rotated down)

6. columnUp( cube, column ) - cube(3D arraylist) int column (column 0 -2 to be rotated up)

7. rotateClockwise( cube, face ) - cube(3D arraylist) int face (face 0-5 to be rotated clockwise)

8. rotateCounterClockwise( cube, face ) - cube(3D arraylist) int face(face 0-5 to be rotated counter
                                          clockwise)
                                          
9. calcSim( cube1, cube2 ) - cube1(3D arraylist) cube2(3D arraylist) each cell of the two given cubes
                             and returns a double similarity percentage
                             
10. genCube( cube ) - cube(3D arraylist) takes blank 3d arraylist of size 3 X 3 X 3 and populates it 
                      with the given colors of a rubiks cube (R - red, W - white, B, - blue ...etc)

11. printCube( cube ) - cube (3D arraylist) as an argument and prints it out "face by face" to
                        console
                      
12. scramble( cube, scrams ) - cube (3D arraylist) as an argument and randomly makes int scrams 
                               amount of random moves to the cube.
                               
13. copyCube( original, copy ) - original (3D arraylist "cube") copy (3d arraylist "cube") copies 
                                 cube "original" to cube "copy"
                                 
14. interpretMove( cube, move ) - cube(3D arraylist) String move(move abreviation to be completed)
                                  interprets given move abreviation, and executes it on given cube
                                  
15. interpretMoveSet( cube, moveSet ) - cube(3D arraylist) String List moveSet( set of move abreviations
                                        to be executed on given cube)

# How the cube is ordered
  [0]         [1]       [2]        [3]          [4]        [5]
  Front Face, Top Face, Back Face, Bottom Face, Left Face, Right Face
  
# How the cube face's are ordered

    [0]  [1]  [2]
[0]  R    R   R

[1]  R    R   R

[2]  R    R   R

# Move Abreviations

U# - rotate column # up
D# - rotate column # down
L# - rotate row # to the left
R# - rotate row # to the right




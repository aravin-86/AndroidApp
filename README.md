## This is a sample Android App that displays Hello to Android World!!! :)

Develop the below game in Android !!

## GAME OF LIFE
 
The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbours, which are the cells that are directly horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
 
1. Any live cell with fewer than two live neighbours dies, as if by loneliness.<br/>
2. Any live cell with more than three live neighbours dies, as if by overcrowding.<br/>
3. Any live cell with two or three live neighbours lives, unchanged, to the next generation.<br/>
4. Any dead cell with exactly three live neighbours comes to life.<br/>
 
The initial pattern constitutes the 'seed' of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed - births and deaths happen simultaneously, and the discrete moment at which this happens is sometimes called a tick. (In other words, each generation is a pure function of the one before.) The rules continue to be applied repeatedly to create further generations.
 
### Problem

The inputs below represent the cells in the universe as X or - . X is a alive cell. - is a dead cell or no cell. The below inputs provide the provide pattern or initial cells in the universe . The output is the state of the system in the next tick (one run of the application of all the rules) , represented in the same format.

------------------------------------------------------------------------------------------------------------------
Input A:<br/>
(Block pattern - Still life)<br/>
1, 1<br/>
1, 2<br/>
2, 1<br/>
2, 2<br/>
Output A:<br/>
1, 1<br/>
1, 2<br/>
2, 1<br/>
2, 2<br/>

------------------------------------------------------------------------------------------------------------------
Input B<br/>
(Boat pattern - Still life)<br/>
0, 1<br/>
1, 0<br/>
2, 1<br/>
0, 2<br/>
1, 2<br/>

Output B<br/>
0, 1<br/>
1, 0<br/>
2, 1<br/>
0, 2<br/>
1, 2<br/>
 ------------------------------------------------------------------------------------------------------------------
Input C<br/>
(Blinker pattern - oscillator)<br/>
1, 1<br/>
1, 0<br/>
1, 2<br/>
 
Output C<br/>
1, 1<br/>
0, 1<br/>
2, 1<br/>

 ------------------------------------------------------------------------------------------------------------------

Input D<br/>
(Toad pattern - two phase oscillator)<br/>
1, 1<br/>
1, 2<br/>
1, 3<br/>
2, 2<br/>
2, 3<br/>
2, 4<br/>

Output D<br/>
0, 2<br/>
1, 1<br/>
1, 4<br/>
2, 1<br/>
2, 4<br/>
3, 3<br/>

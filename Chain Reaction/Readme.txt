Chain Reaction

Create a JavaFX application for a multiplayer game - "Chain Reaction". It's a strategy game for 2 to 8
players. The objective of this game is to take control of the board by eliminating your opponents.

Rules of the game is mentioned below (given for 2 but can be generalised to any number of players):
*  The gameplay takes place in a m x n board.
*  For each cell in the board, we define a critical mass. The critical mass is equal to the number of
   orthogonally adjacent cells. That would be 4 for usual cells, 3 for cells in the edge and 2 for cells
   in the corner.
*  All cells are initially empty. The Red and the Green player take turns to place "orbs" of their corresponding
   colours. The Red player can only place a Red orb in an empty cell or a cell which already contains one
   or more red orbs. When two or more orbs are placed in the same cell, they stack up.
*  When a cell is located

# penguin-trap

## description of the game

is a board game consiting of a isometric-hexagonal-grid board and a penguin figure.
Players will take turn to remove an existing hexagonal block of "ice" on the board.
Removing a block may cause surrounding block to collaspse.
The penguin figure will stand on one of the blocks.
The winner must not causes the falling of the block under the figure.

## goal of project

* Starter: find the maximum move in any n*n suqare-grid penguin-trap board
* Final: find the maximum move in any hexagonal-grid penguin-trap board
  * Define hexagoal grid and its size

Each one use method of random play (Play random move until the game is ended).

* Special: improve runtime of "update_board" funtion.
* Ultimate: explaining the answer using game amd graph theory.

## functions
* initial_board(n, position_penguin = None)
* penguin_position(board) 
* penguin_die(board)
* remove_position(board,x,y)
* block_fail(board)
* update_board(board)
* pretty_print(board)
* random_play_stop(board)
* random_play(board)

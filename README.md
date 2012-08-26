Tic Tac Toe
===========

A simple implementation of Tic Tac Toe, written in solely in Javascript. It uses some [Underscore.js](http://underscorejs.org) helper functions, and [jQuery](http://jquery.com) to update the view.

This implementation features perfect AI; it will always choose the move that will lead to a win, if possible. Perfect AI comes at a cost, however: the computer computes every possible move, a process that has a recursion within an iteration. I've hard coded in the first and second symbol on the board, and you'll notice a substantial thinking time when placing the 3rd/4th symbol, roughly 10 seconds.

As it's an html page, you can visit the [Github Pages version of this repo](http://perspectivezoom.github.com/tictactoe) to see it in action.
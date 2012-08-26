Tic Tac Toe
===========

A simple implementation of Tic Tac Toe, written in Javascript. It uses some [Underscore.js](http://underscorejs.org) helper functions, and [jQuery](http://jquery.com) to update the view.

This implementation features perfect AI; it will always choose a move that will lead to a win, if possible. Perfect AI comes at a cost, however: it recomputes the game tree on every move, an expensive process that has a recursion within an iteration. I've hard coded in the AI's first move, but you'll notice a substantial thinking time on its second move, roughly 10 seconds.

As it's an html page, you can visit the [Github Pages version of this repo](http://perspectivezoom.github.com/tictactoe) to see it in action.
# Chess-cheater

Uses Vue.js for front-end and php for back-end
A Wordle like website where user can log in every day to play a chess game against a bot, which changes its strategy (cheats) every day. User has only 1 chance to beat the bot by outplaying its trickery.

Files:

Chessboard manager - keeps track of every tile and which piece occupies it.
Piece base class - Defines basic methods which will be inherited by different pieces to fulfil their function.
Piece sub class - Will use methods and overrides to create every piece.
UI manager - Handles the visual aspects of the program.
UserStats - Handles everything user related such as their, username, password, score, etc.
Player - Controls what kind of actions can user perform during game run time.
Opponent - Controls what kind of actions can opponent perform during run time.
Chess engine script - The script that calculates the best moves available.
Cheat randomizer - Chooses a cheat that the opponent will use on that day and passes its properties.
Game manager - Manages a lot of other stuff that is not covered by previous scripts.

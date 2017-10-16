# Tennis in JavaScript

## How to run tests
Tests are available to be run both with node.js and in the browser.
For node, simply call
  node TennisTest.js
(Only failures will be shown on the console)

For the browser, open TennisTest.html and refresh after change.

## Description
A game consists of a sequence of points played with the same player serving, and is won by the first side to have won at least four points with a margin of two points or more over their opponent. Normally the server's score is always called first and the opponent's score second. Score calling in tennis is unusual in that each point has a corresponding call that is different from its point value.

| Number of points won |	Corresponding call |
|---|-------:|
| 0	| "love" |
| 1 | "15"   |
| 2	| "30"   |
| 3	| "40"   |
| 4	| Game= winner |

For instance if the server has won three points so far in the game, and the non-server has won one, the score is "40-15".

When both sides have won the same number of points then: when each side has won one, or two, points, the score is described as "15-all" and "30-all", respectively.

## TODO Deuce Scoring
If each player has won three points, the score is called as "deuce", not "40–all".

From that point on in the game, whenever the score is tied, it is described as "deuce", regardless of how many points have been played.

Scoring beyond a "deuce" score, in which both players have scored three points each, requires that one player must get two points ahead in order to win the game.

The side which wins the next point after deuce is said to have the advantage.  If they lose the next point, the score is again deuce, since the score is tied.  The players' names are used:  in this format (e.g. "advantage Player 1" or "advantage Player 2").

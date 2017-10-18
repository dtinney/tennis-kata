# Tennis in JavaScript

## How to run tests
Tests are available to be run both with node.js and in the browser.
For node, simply call
  node TennisTest.js
(Only failures will be shown on the console)

For the browser, open TennisTest.html and refresh after change.

## Description
A game consists of a sequence of points played with the same player serving, and is won by the first side to have won at least four points with a margin of two points or more over their opponent.


| Number of points won |	Corresponding call |
|---|-------:|
| 0	| "love" |
| 1 | "15"   |
| 2	| "30"   |
| 3	| "40"   |
| 4	| Game= winner |

For instance if the server has won three points so far in the game, and the non-server has won one, the score is "40-15".

When both sides have won the same number of points then: when each side has won one, or two, points, the score is described as "15-all" and "30-all", respectively.

When each side have won the same number of points past 4 the score is described as "deuce"

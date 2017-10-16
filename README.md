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

When both sides have won the same number of points then: when each side has won one, or two, points, the score is described as "15-all" and "30-all" (or "15-up" and "30-up"), respectively.

However, if each player has won three points, the score is called as "deuce", not "40–all".

From that point on in the game, whenever the score is tied, it is described as "deuce", regardless of how many points have been played.

In standard play, scoring beyond a "deuce" score, in which both players have scored three points each, requires that one player must get two points ahead in order to win the game. This type of tennis scoring is known as "advantage scoring" (or "ads"). The side which wins the next point after deuce is said to have the advantage. If they lose the next point, the score is again deuce, since the score is tied. If the side with the advantage wins the next point, that side has won the game, since they have a lead of two points. When the server is the player with the advantage, the score may be called as "advantage in". When the server's opponent has the advantage, the score may be called as "advantage out". These phrases are sometimes shortened to "ad in" or "van in" (or "my ad") and "ad out" (or "your ad"). Alternatively, the players' names are used: in professional tournaments the umpire announces the score in this format (e.g. "advantage Federer" or "advantage Murray").

In the USTA rule book (but not the ITF rules) there is the comment: ‘"Zero," "one," "two," and "three," may be substituted for "Love," "15," "30," and "40." This is particularly appropriate for matches with an inexperienced player or in which one player does not understand English.’[2]

For tie-breaks the calls are simply the number of points won by each player.

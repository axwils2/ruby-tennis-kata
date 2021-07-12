## Kata Goal
The goal of this kata is to practice refactorig skills. You can start with Game 1 and continue to Games 2 and 3 once you are satisfied. It helps to give reasons as to why a bit of code should be refactored. To that end, you can use https://en.wikipedia.org/wiki/Code_smell to help give names to potential refactors you see.

Remember, the purpose of refactoring is to make code easier to understand and cheaper to modify.

A test suite has been provided. Ensure the test suite is 'all green' after your refactorings. To run the test suite, run `ruby tennis_test.rb`. Feel free to modify any of this repo locally to suite your needs in your refactoring endeavors.

## Kata Description

Tennis has a rather quirky scoring system, and to newcomers it can be a little difficult to keep track of. The tennis society has contracted you to build a scoreboard to display the current score during tennis games.

You can read more about Tennis scores on wikipedia which is summarized below:

* A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
* The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as “Love”, “Fifteen”, “Thirty”, and “Forty” respectively.
* If at least three points have been scored by each player, and the scores are equal, the score is “Deuce”.
* If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is “Advantage” for the player in the lead.
You need only report the score for the current game. Sets and Matches are out of scope.


Welcome to the Lambda-Man course.

It was the year 2014, and many members of our community worked hard to control Lambda-Man. Now, ten years later, this wonderful event is still memorized by holding a small Lambda-Man competition.

This course will teach you how to optimally control Lambda-Man to eat all pills. There is no fruit involved (neither low-hanging nor high-hanging), and even better: no ghosts! The input to each problem is a simple rectangular grid such as the following:

```
###.#...
...L..##
.#######
```

The grid contains exactly one `L` character, which is the starting position of Lambda-Man. There will be one or more `.` characters indicating the locations of pills to be eaten, and `#` characters are walls. The outside boundary of the grid is considered to consist of walls as well.

A solution should be a string of `U`, `R`, `D` and `L` characters (up, right, down, left, respectively) indicating the path to take. For example, a possible solution to the above example grid is the following path:
```
LLLDURRRUDRRURR
```
When Lambda-Man is instructed to move into a square containing a wall, nothing happens and the instruction is skipped. Your solution may consist of at most `1,000,000` characters.

The following levels are available:
* [lambdaman1] Your score: 33. Best score: 33.
* [lambdaman2] Your score: 44. Best score: 44.
* [lambdaman3] Your score: 76. Best score: 58.
* [lambdaman4] Your score: 412. Best score: 151.
* [lambdaman5] Your score: 215. Best score: 142.
* [lambdaman6] Your score: 217. Best score: 73.
* [lambdaman7] Your score: 495. Best score: 139.
* [lambdaman8] Your score: 4917. Best score: 113.
* [lambdaman9] Your score: 3525. Best score: 112.
* [lambdaman10] Your score: 3349. Best score: 143.
* [lambdaman11] Your score: 10003. Best score: 1524.
* [lambdaman12] Your score: 10011. Best score: 1588.
* [lambdaman13] Your score: 10003. Best score: 1578.
* [lambdaman14] Your score: 10011. Best score: 1565.
* [lambdaman15] Your score: 10003. Best score: 1581.
* [lambdaman16] Your score: 8209. Best score: 287.
* [lambdaman17] Your score: 3092. Best score: 231.
* [lambdaman18] Your score: 16067. Best score: 3521.
* [lambdaman19] Your score: 16364. Best score: 1442.
* [lambdaman20] Your score: 23665. Best score: 5264.
* [lambdaman21] Your score: 47438. Best score: 9194.

To submit a solution, send an ICFP expression that evaluates to:

```
solve lambdamanX path
```

Your score is number of bytes that the ICFP expressions consists of (i.e. the size of the POST body), so a lower score is better.


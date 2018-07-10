---
title: "Tetris Bot"
excerpt: "Created a invincible bot which can play tetris without losing."
header:
  teaser: /assets/images/projects/tetris-th.jpg
sidebar:
  - title: "<i class=\"fab fa-github\" aria-hidden=\"true\"></i> <a href=\"https://github.com/yashketkar/B551-Elements-Of-Artificial-Intelligence/tree/master/iyerg-yketkar-mpanchol-a2\">GitHub Repo</a>"
    image: /assets/images/projects/tetris-sb.jpg
    image_alt: "thumbnail"
  - title: "Responsibilities"
    text: "See part 2 of the above repo."
---
This bot was created as a part of an assignment, where we were provided a skeleton code for the tetris game. I had to create the algorithm and logic to determine the next move of the bot. This was done using search algorithms and using a probabilistic approach. The heuristic for this algorithm was determined using a Genetic algorithm.

The heuristic or scoring function gave a particular configuration of the game state a score taking into account various factors like average height, max height, holes, bumpiness and complete lines.

The parameters to be considered and weights of each parameter were referenced from [here](https://codemyroad.wordpress.com/2013/04/14/tetris-ai-the-near-perfect-player/).

Briefly, the algorithm worked as follows:

1. For each piece and the upcoming piece generate all possible successor configurations of the game.
2. Choose the next position from the successors with best score using the above scoring function and make the moves to reach that configuration of the board.

Once the best successor configuration was found, then move the piece accordingly to reach that state. Thus we could get an impossible to beat bot given the probability distribution of the incoming pieces. If the probability distribution of the incoming pieces were changed dynamically, it would require us to run the genetic algorithm to learn the weights used in the scoring function for the given new probability distribution. Thus making it difficult to have a set of weights which could be perfect for dynamically updating distribution of pieces.

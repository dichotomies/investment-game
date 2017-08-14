# Managing Risks of Investments

## Game Basics:

The Game consists of rounds. In each round, a predefined, fixed amount is invested.

The amount invested in is taken from the current amount. On the beginning of the game,
the current amount is equal to the starting amount, e.g. 100 CX (currency x).

The return on investment (ROI) is also fixed, e.g. 10% of invested amount.

The probability of winning and losing is equal in each round, i.e. 50%.

## Goal of the Game:

Assuming that you could play as many rounds of this game as you want and that 
the ROI equals 0.1, choose an (optimal) amount that you invest in per each round 
w.r.t. the start amount such that:

- the risk of losing (all) the money is minimized 
- and the exptected ROI is maximized

## Examples of played Games

General paramter set: `nb_rounds_per_game = 1000`.

Choosing `invest_ratio` of `0.2` results (naturally) in high volatility, higher 
ROI but low amount of rounds played. In average, in 482 games out of 1000 games
no total loss occured.)

Choosing `invest_ratio` of `0.05` results (naturally) in low volatility, lower 
ROI and high amount of rounds played. In average, in 934 games out of 1000 games
no total loss occured.

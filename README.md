# Darts: a Monte-Carlo simulation
Today I was playing darts with some friends. While playing, I noticed something: I suck at darts.
With my skillset, aiming is not a realistic concept. Rather, my darts launch in the general direction of the board. If they hit anything inside the big coloured circle, I call that a success throw. 

However, the rules of darts are quite strict. Depending on the rule set, one starts with 301 or 501 points, every thrown dart's score being subtracted from that number, eventually reaching 0. One must reach _exactly_ 0, and end with a dart landing in the 'double score' ring. Quite a specific throw is thus needed to close a game off.

This made me wonder: if it were not for my opponents that _can_ aim, and thus close a darts game with some skill, just _how long_ would I be stuck in a darts-game-limbo before finally reaching sweet sweet victory?

Instead of playing and finding out, I had a better idea. What if I simulate this from the comfort of my own desk?
In this repository, I simulate the time needed for closing off a darts game using a [Monte Carlo simulation](https://en.wikipedia.org/wiki/Monte_Carlo_method).

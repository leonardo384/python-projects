mancala
=======
Excerpt from Coursera's "Principles of computing":

In Solitaire Mancala, the player has six houses and a store. At the start of a game, a variable number of seeds are placed in each house (as opposed to the three seeds per house in two-player Mancala). As in two-player Mancala, the player may select a house and gather all of the seeds in that house. The player then places the seeds one at time in the houses to the right of the selected house. In Solitaire Mancala, the last seed must be placed in the store. Other moves that either don't place a seed in store or end up with seeds left over are not allowed and are illegal. Note that the restriction that the last seed in a move must always be placed in the store substantially limits the choice of legal moves available to the player. If we index the store and houses from right to left starting at zero for the store, moving the seeds from a particular house is legal exactly when the number of seeds in the house matches the house's index.
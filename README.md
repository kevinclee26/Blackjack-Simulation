# Blackjack-Simulation
## Practical Python and Data Science Learning by buliding a Blackjack simulator

### Ever wondered how much advantage the House has in Blackjack? This project creates a simulator and illustrates the results. Here's what the results say: 
- Player wins  41%  of the time
- Push 9%  of the time
- Dealer wins 49%  of the time

### Below are some interesting findings: 
-  On average: 
    -  a Player is dealt 20 ~10% of the time, roughly the same as getting a 12 or 13. 20 has ~70% chance of winning and is the best hand to be dealt besides a Blackjack, which shows up ~5% of the time. 
    -  a Player only has a ~50% chance of winning if dealt a 10 or 11. of course the chances of winning is higher if the Dealer is showing a 5 through 8, but drop significantly if the Player doubles down (gets only one card). 
    -  a Player has <1% chance of pushing with the Dealer if dealt a 21. 
    
![Image](https://github.com/kevinclee26/Blackjack-Simulation/blob/master/image.png)

### As it turns out, the Dealer has an advantage when both sides play with the same exact strategy (hit soft 16)
Of course there are ways to lower the advance of the house. In future edits of this project - we'll modify the strategy. I'd love to try to simulate random player actions and train a Machine Learning model to learn the best strategy

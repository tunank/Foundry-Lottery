# Random Raffle contract

## About
This code is to create a random raffle lottery

1. User can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After a X amount of time, the lottery gonna draw a winner
   1. This gonna be done programatically
3. Using Chainlink VRF & Chainlink automation
   1. Chainlink VRF => Randomness
   2. Chainlink Automation -> time based trigger
   
## Test
1. Write some deploy scripts
2. Write our tests
   1. Work on local chain
   2. Forked testnet
   3. Forked mainnet
# dBet365 :large_orange_diamond:

I would like to create a dApp where users can bet against other users about which coins (or tokens) will perform better in a period of time compared to other coins.

E.g. Alice thinks that Ethereum will perform better than Cardano in the next month (i.e. from the 1st to the 31st of October). She opens a new "Bet" and plays 1ETH.
Bob looks at the list of open Bets and sees the one from Alice. He has the logo of Cardano tattooed on his arm so he is willing to take the other side of the bet and accepts the challenge, adding another 1ETH. At the end of October, one of them will receive 2ETH (minus protocol fees).

Users will only have two options:
  - Create a new Bet
  - Accept an open Bet

In order to create a Bet, a user will have to:
  - Choose a pair (among a list of supported coins/tokens) and the winner.
  - Choose a time period (could be hourly, daily, weekly or monthly).
  - Set an amount (in ETH or WETH I don't know yet)

In order to accept an open Bet a user will have to simply add the required amount to play. Once a bet is closed, nobody else can join neither can't be opened again.

Considerations:
- For creating a new Bet, I'd like to do it via signature (if it is technically possible) to avoid paying gas.
- In order to know the prices at the beginning and the end of a period I will need to use an oracle.




_Note: This file is just a first brainstorming, nothing is set in stone and I will keep adding ideas and updating this file as the bootcamp advances._ 

# Bowling-Kata

The goal of this kata is to implement a program that is capable of scoring a game of ten pin bowling:
https://en.wikipedia.org/wiki/Ten-pin_bowling#Scoring

The tests to be written are as follows:

1. A game of 20 rolls that hit no pins scores zero.
2. A game of 20 rolls that hit 1 pin each scores 20.
3. A game with a spare in the first frame, should score the next roll. (5,5,3,0,0... should score 16) 
4. A game with a strike in the first frame, should score the next two rolls. (10,3,4,0,0... should score 24)
5. A perfect game of all strikes should score 300.

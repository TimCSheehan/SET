## SET

This project will encompass the rules of the card game SET (see setgame.com). This is mostly a chance for me to fool around with writing algorithms using pythons native environment. The first goal is to generate a set game (dealing a deck of set cards) and write a robust algorithm to identify 'sets' and remove them from play. It may prove useful at this point to explore visualizing cards - and ideally visuallizing entire games- through both the jupyter environment but also as a stand alone window. Once this is set up, it would be interesting to explore what strategies might outperform the route search in finding sets and comparing them. Final stages may involve running simulations comparing the outcomes of various strategies, observing if any strategies affect the rate of 'no set' states, building a model from scratch using reinforcement learning, and possibly using machine vision to take this algorithm out into the real world of set.

# Proposed architecture
generate_deck.py
    -this will generate a (or multiple) shuffled decks of SET cards. 

iterative_search.py
    -this will search for sets in a given display using an exhaustive technique
    
simulate_game.py
  -this will simulate an entire game of set using provided strategies
  
visualize_game.py
    -this will visualize an entire game displaying cards
    
play_game.py
    -this will be an interactive game of set against a computer or watching two computers play eachother
    
visual_read.py
    -this will attempt computer vision on individual cards
    
visual_identify.py
    -this will display all available sets given an image of cards

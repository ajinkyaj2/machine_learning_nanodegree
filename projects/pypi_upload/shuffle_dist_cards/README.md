### _Description_
This Program is written for hobby carders who want to shuffle and distribute deck of cards among themselves.

### _Installation_
pip install shuffle_dist_cards <br>
```
from shuffle_dist_cards import ShuffleDistCards
card_obj = ShuffleDistCards(4) # Here 4 is no_of_players
card_obj.create_n_shuffle_deck()
card_obj.dist_cards()
```

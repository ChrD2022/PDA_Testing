### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

# should be == for card.value = 1, : missing from the else.
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
# this is called 'dif' not def. there is also no "," separating cards 1 & 2. The indentation is not correct. return card should be return card1.
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

#  total is not defined as anything, should be total = 0. return is in the for loop so will  make a statement each time a card is added, the method is not indented.
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```

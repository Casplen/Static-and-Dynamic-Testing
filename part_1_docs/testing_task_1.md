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


  def check_for_ace(self, card):
    if card.value = 1:
    # Missing extra equals sign.
      return True
    else
    # Missing colon.
      return False
   

  dif highest_card(self, card1 card2):
  # typo: def*. Needs comma between second and third parameters.
  if card1.value > card2.value:
    return card
  else:
    return card2
  # lines 31-34 require indentation
  


def cards_total(self, cards):
  total
  # Total is undefined.
  for card in cards:
    total += card.value
    return "You have a total of" + total
  # Return is within the for loop. Cannot add string to integer.
```

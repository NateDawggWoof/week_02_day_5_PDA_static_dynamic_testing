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
  # Class has not been initiated


  def check_for_ace(self, card):
    # when comparing if statement == is required as single = operator is used for assinging not comparising
    if card.value = 1:
      return True
      # else needs to colon or if will break
    else
      return False
   
# dif should be def, function won't be defined, commas between parameters card 1 and card 2 missing
  dif highest_card(self, card1 card2):
  # if statement not indedentated, python uses indentation
  if card1.value > card2.value:
    # card variable does not exist should be card1
    return card
  else:
    return card2
  


def cards_total(self, cards):
  # total is not defined will cause error
  total
  for card in cards:
    total += card.value

    # Python can't automattically concatinate strings and int, this line would require to be a specail F format string to call the variable inside.

    # the return is also inside thefor statement which will end the loop after first iteration, return needs it's indenetation removed to sit in line of the for statement.
    return "You have a total of" + total
  
```

# Random-story-Generator
import random

Sentence_starter = ['About 100 years ago', ' In the 20 BC', 'Once upon a time']
character = [' there was a boy named Shahid',' there lived a king.',' there was a man named Henry.',
             ' there lived a farmer.']
time = [' One early morning',' One day in the evening',' On a rainy day', ' One day', ' One full-moon night',]
story_plot = [' he was passing by',' he was going for a picnic to ']
place = [' the forest',' the mountains', ' the garden']
second_character = [' he saw a man', ' he saw a lady',' he saw a person']
age = [' who seemed to be in late 20s', ' who seemed very old and feeble',' who seemed to be very young']
work = [' searching something.', ' digging a well on roadside.',' selling fruits',' singing',' sleeping on a bench']
  

print(random.choice(Sentence_starter)+random.choice(character)+random.choice(time)+random.choice(story_plot) +random.choice(place)+random.choice(second_character)+ random.choice(age)+random.choice(work))

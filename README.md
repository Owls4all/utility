# utility
My personal utilities module

A brief overview of the features
YesList and NoList - lists of various 'yes' and 'no' responses a user might give.
  works well with searchList for checking if the user's input is 'yes' or 'no' and responding accordingly

searchList(query,list) and indexInList(query,list) - for checking if a query is an element of the list.
  searchlist returns True if present and False if absent
  indexInList returns the item's index if present and -1 if absent. (in the case that it shows up multiple times, it returns only the first index)

ask(prompt) - basically input(prompt) but shorter and with '>>>' in a new line so it's more obvious it's asking for something

makeDegrees(angle) and makeRadians(angle) - convert back and forth between radians and degrees
  string_angle(angle) returns the angle in radians as 'number pi' rather than a long decimal (good for printing, not much else)

make_list and question were really for testing purposes but they might be useful so I kept them
  make_list(list) asks the user if they would like to add to the list. if they say yes, it asks what to add, repeating until the user no longer wishes to add anything.
  question(list) invites the user to search the list for something. If present, it tells the user its index. if absent, it informs the user of its absence. 
  It continues asking until the user no longer wishes to search.

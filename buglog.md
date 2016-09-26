# BUG LOG


Passing in an invalid index gives a segfault i.e _map[10][10]
  isBounds should check if col/row is < FIELD_DIMENSION -1
  
revealAdjacent function has no bounds checking for adjacent blocks.

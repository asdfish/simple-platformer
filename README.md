# simple-platformer-engine
arrow keys for movement<br>
https://asdfish.github.io/simple-platformer/<br>
if you want to create a level, edit the value for levelBitmaps<br>
every space in the string counts as a empty space<br>
"#" is for a solid block<br>
"l" is a kill block that sends the player back to the start of the level<br>
"p" is a portal that sends the player to the next level<br>

```
[
  //this would be level 1
  [
    "############",
    "#          #",
    "#          #",
    "#@        p#",
    "######l#####",
  ],
  //level 2
  [
    "@",
    "#"
  ],
]
```

# Exercise-01b-Twine-Project

Exercise for MSCH-C220

```
This is an open field west of a white house, with a boarded front door.

[[NORTH->North of House]]
[[SOUTH->South of House]]
[[WEST->Forest]]
```

Close that window, and you should now see that the node is now labeled "West of House" and that there are three arrows pointing to newly created passages: North of House, South of House, and Forest.

Follow that same process with each of the newly created passages. When you are done, you should have eight locations:

 * Passage: North of House
   * Description: You are facing the north side of a white house.  There is no door here, and all the windows are barred.
   * Exits:
     * WEST->West of House
     * EAST->East of House
     * NORTH->Forest
 * Passage: South of House
   * Description: You are facing the south side of a white house. There is no door here, and all the windows are barred.
   * Exits:
     * WEST->West of House
     * EAST->East of House
     * SOUTH->Forest
 * Passage: Forest
   * Description: This is a forest, with trees in all directions around you.
   * Exits:
     * NORTH->Sunlit Forest
     * EAST->Forest
     * SOUTH->Forest
     * WEST->Forest
 * Passage: East of House
   * Description: You are behind the white house. A path leads into the forest to the east. In one corner of the house there is a small window which is slightly ajar.
   * Exits:
     * NORTH->North of House
     * SOUTH->South of House
     * EAST->Sunlit Forest
     * WEST->Kitchen
     * ENTER->Kitchen
 * Passage: Sunlit Forest
   * Description: This is a dimly lit forest, with large trees all around.  One particularly large tree with some low branches stands here.
   * Exits:
     * NORTH->Forest
     * SOUTH->Forest
     * EAST->Forest
     * WEST->East of House
     * UP->Tree
 * Passage: Tree
   * Description: You are about 10 feet above the ground nestled among some large branches. The nearest branch above you is above your reach. Beside you on the branch is a small bird's nest.
   * Exits:
     * DOWN->Sunlit Forest
 * Passage: Kitchen
   * Description: You are in the kitchen of the white house. A table seems to have been used recently for the preparation of food. A passage leads to the west and a dark staircase can be seen leading upward. A dark chimney leads down and to the east is a small window which is open.
   * Exits:
     * EAST->East of House

Once you have added each of these passages, close the passage edit window. In the top menu bar, you should see a menu labeled "Build". In the Build Menu, select "Play".

The game should load in your browser. You should be able to press the links to take you from one location to another.

When you are done, return to Twine. In the Build Menu, select "Publish to File".

Navigate to the location of your repository in your file system. Save the file as Zork.html in the repository (Exercise-01b-Twine-Project) folder.

Quit Twine. In GitHub desktop, you should now see Zork.html listed in the left panel. In the bottom of that panel, type a Summary message (something like "Adds a simple version of the Zork Interactive Fiction game") and press the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push to origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see Zork.html listed among the files.

```
# Exercise-01b-Twine-Project

Exercise for MSCH-C220

An Interactive Fiction game loosely based on the great Interactive Fiction game, Zork. Load Zork.html in a browser to play it.

## Implementation
Built using Twine 2.4.1

## References
[Zork, Infocom, 1977](https://www.pcjs.org/software/pcx86/game/infocom/zork1/)

## Future Development
None

## Created by 
Aiden Pedroncelli
```

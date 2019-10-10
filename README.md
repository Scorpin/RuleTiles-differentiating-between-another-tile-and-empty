# RuleTiles-differentiating-between-another-tile-and-empty

Modified version of the "2d-extras" package from Unity-Technologies: https://github.com/Unity-Technologies/2d-extras
Tested only in the package version for Unity 2019.2.0f1. I can't take responsability for further versions.

I added a third neighbor in the class and the code to manage it, to know if there is some other Tile instead just "not this tile",
so you can make a grid with a lot of tiles but can know too at least when the "map reach the end" to show the right Tile.

Based on an fix of this same problem in a old version from: https://gist.github.com/Bahamutho/aa2d2f12f60c71eaf462d8126505e54a

TOON BLASH is a lazy copy of popular mobile game Toon Blast :smile: . 
Credit : [Berke Soysal](https://github.com/BerkeSoysal)
### Unity version 2021.3.19f1 (64-bit)
# Modifications
- removed main menu, direct gameplay on run. (removed associated scripts to go back and forth from and to main menu)
- Addition of score and time panel gameobject with time, timeText, score and scoreText. (also includes re-alignment of UI)
- Improvement : Score now changes smoothly using score lerp.
- Improvement : Game now runs on a time limit basis. Player has to get max score before time runs out/no more moves possible.
- Bug : Map size was dynamic, but on size change didnt spawn at screen centre, spawned at corner. Fix : Position of spawnner now changes dynamically, making in the map centre of screen no matter how map size change.
- Bug : Walls size and position was not dynamic with respect to Map size changes. Fix : Position and scaling is done dynamically based on the size of map on start.

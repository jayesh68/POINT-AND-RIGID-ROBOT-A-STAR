# Path Planning for a Point Robot using A*

## Steps to run the program
1. Download python script into a given path/folder.
2. Make sure all of the sourced python files are downloaded into the same folder ie, actSetStar.py
3. Finally, run p3_astar_final.py in a python interpretor
4. Follow User interactive instructions to search for start and goal nodes in the given environment
    - enter the start nodes as instructed; 
    - Then enter the desired location (goal node) of the point robot;
    - Any node outside the environment is out of bound or inside the obstacle space is
      not allowed, and will redirect you to the same selection prompt
    - A* search will begin and print confirmation statement at the end
    - Animation will be shown in realtime during search process
    - After animation ends, backtracking visualization will be performed drawing optimal path
    - Search will terminate by printing total computation time.

5. Close python interpreter when done.

**Caution: If start nodes are created within 5 units of clearance edges, nodes might expand to
	   region inside edge clearance in which case if all 5 children get expanded into that space, 
	   search will terminate abnormally with incorrect results.

## Visualization
* https://youtu.be/iS9h-2WOy6g
* https://youtu.be/aoeCqvQ4i54
* https://youtu.be/rCIofpbKxoM
* https://youtu.be/ZPGxThjqSfg
* https://youtu.be/iS9h-2WOy6g
* https://youtu.be/aoeCqvQ4i54
* https://youtu.be/rCIofpbKxoM
* https://youtu.be/ZPGxThjqSfg

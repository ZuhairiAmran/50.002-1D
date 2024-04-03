50.002 Stack!T

I've created this github repository to make it easy to edit and track what changes we've made. Do only commit to branches with appropriate git comments. I'm not too entirely sure if I should use the group's github instead but I feel that it might be better to create a separate repository to prevent clutter

Current Checklist:

LED matrix:
- Work on displaying current block, alongside shifting 'animation'
- Work on creating a function, alongside an efficient storage system, to display the previous stacked blocks
- (Optional) Can work on creating a separate Score/Timer display on the side on the matrix itself 
	- (Alternatively, can purchase a 7-seg display and wire into that instead)

RAM/DFF storage:
- Understand and implement a simple RAM/dual-port RAM, wherever necessary
- Work on efficient reading/writing of data used for front-end display and back-end code
- Optimize DFF usage

Block logic: [NOTE: This logic is only applicable towards the updating of the data stored. It is NOT focused on displaying it onto an external display]
- Work on the logic for the shifting of the current block itself 
- Implement the logic of decreasing block length
- Implement 2 different slow clocks: 1 for timer, 1 for shifter
- Create and implement a score system, including the logic for the necessary calculations required



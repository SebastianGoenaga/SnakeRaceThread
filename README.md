# SnakeRaceThread

-  Possible race conditions.
	-  Two snakes can found the same mouse at same time.
	- Two snakes can found the same power at same time.
- To create more race conditions and add a critical session we have to synchronized all the body when the snakes are draw.
- When the game speed increase the program will broke and send error because the snakes are accessing toa list at the same time.
- The project run like I expected and I putted the methods Start, Stop and Resume.

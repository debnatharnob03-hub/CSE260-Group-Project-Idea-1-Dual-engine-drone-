# CSE260-Group-Project-Idea-1-Dual-engine-drone-
A logic circuit that compares two 3-bit input and gives the output of 5 times of the larger output
CSE260: Digital Logic Design — Project Idea 1

**#Description**
You are designing a hardware safety module for a dual-engine drone. The module reads 3-bit speed sensors from Engine A and Engine B. To maintain stability during a sudden maneuver, the flight controller needs to burst power to the faster engine. Design a logic circuit that compares the two sensor inputs. The circuit must output 5 times the value of the larger engine's speed. If the speeds are equal, it defaults to outputting 5 times Engine B's speed.

Example:

Engine A	   Engine B	       Output

001	          111	            100011

001	          000	            000101

ICs/Gates allowed to use:

AND, OR, NOT, NAND, NOR, XOR, XNOR, Parallel Adder

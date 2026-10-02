This project, part of the ECE276B "Planning and Learning in Robotics" course at UCSD, focuses on autonomous navigation in a Door & Key environment. The objective is to get our agent (red triangle) to the goal location (green square). The environment may contain
a door which blocks the way to the goal. If the door is closed, the agent needs to pick up a key to unlock
the door. The agent has three regular actions, move forward (MF), turn left (TL), and turn right (TR), and
two special actions, pick up key (PK) and unlock door (UD). Taking any of these five actions costs energy
(positive cost).

We design and implement a Dynamic Programming algorithm that minimizes the cost of reaching the goal in
two scenarios: known map, and random map.

Working code for PR1 is located inside: starter_code/code.ipynb !


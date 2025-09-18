# A*-Pathfinding---Peppermint-Robotics.


# A* Pathfinding (Console + Pygame)

Author: Ninad Metkar

## About
This is a simple A* pathfinding program that finds the shortest path in a grid.  
- Shows step-by-step exploration in the console.  
- Visualizes the process in Pygame with colors for visited nodes and the final path.  
- Supports 8-direction movement (diagonal moves included).  

---

## Assumptions
- Grid is a 2D list (`0 = free`, `1 = obstacle`).  
- Start and Goal are predefined.  
- Movement allowed in 8 directions (optional: remove diagonals for 4 directions).  
- If no path exists, an empty path is returned.  

---

## Requirements
- Python 3.x  
- Pygame (`pip install pygame`)  

---

## How to Run
1. Save the script as `astar_pygame_console.py`.  
2. Open terminal / command prompt.  
3. Run:python astar_console_pygame
4. Watch the console for step-by-step exploration.  
5. Pygame window will show visited nodes and the final path.

---

## Console Output Example
Exploring node (0, 0)
Exploring node (1, 0)
...
Final Path:
S . O . O


---

## Pygame Visualization
- Blue = Final path  
- Light blue = Visited cells  
- Green = Start  
- Red = Goal  
- Black = Obstacles  

---

## Customization
- Change the `grid`, `start`, or `goal` inside the script.  
- Adjust `time.sleep` in console or `clock.tick` in Pygame for faster/slower animation.  
- Remove diagonals in `directions` to restrict movement to 4 directions only.

---

- """
Note: All documentation, code explanation, and pseudocode for this assignment
are provided in the PDF file 'Astar_Pathfinding_Documentation.pdf', which is
uploaded in this GitHub repository.
"""




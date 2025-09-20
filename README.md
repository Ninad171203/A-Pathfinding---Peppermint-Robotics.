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
Video Demonstration Link: https://www.loom.com/share/182e2ac58bd344d581c7739e1353a4af?sid=10d09978-be9a-439d-8e8a-f6ba86e96248
<img width="1913" height="1012" alt="Screenshot 2025-09-20 195244" src="https://github.com/user-attachments/assets/76af7ba8-73a4-40f3-9449-dae06c01532d" />
<img width="1913" height="1012" alt="Screenshot 2025-09-20 195244" src="https://github.com/user-attachments/assets/523cfee7-db8a-47cd-be5e-a5d87219dd94" />


---
- """
Note: All documentation, code explanation, and pseudocode for this assignment
are provided in the PDF file 'Astar_Pathfinding_Documentation.pdf', which is
uploaded in this GitHub repository.
"""




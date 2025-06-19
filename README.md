# Smart Waste Management Robot 

This project is a Python simulation of a **Smart Waste Management Robot** that helps address the real-world challenge of efficient urban waste collection. It demonstrates the design of an autonomous agent that navigates a user-defined grid, locates waste, and cleans it optimally using simple AI logic.

---

##  **Project Overview**

In modern urban environments, effective waste management is critical for sustainability and public health. This simulation models an urban section as a grid where waste can appear in various locations. The robot acts as an autonomous cleaner that moves intelligently to collect and dispose of waste, optimising its route and minimising redundant movement.

---

##  **How it Works**

**1. User Input for Environment Size**

- The program first prompts the user to enter the size of the environment.
- Valid input: any positive integer from **1 to 5**.
- If an invalid number is entered (e.g., zero, negative, or greater than 5), the program prompts the user again until a valid size is provided.

**2. Grid Display**

- A grid of the specified size (e.g., 3×3, 4×4, or 5×5) is displayed.
- Each cell is labelled with a unique cell number to help the user specify waste locations easily.

**3. User Input for Waste Locations**

- The user is prompted to enter the cell numbers that contain waste.
- Multiple waste locations can be specified.
- The grid is updated and displayed, marking clean cells with `0` and dirty cells with `1`.

**4. Robot Deployment**

- The user specifies the robot's starting cell number.
- The robot’s current position is marked with `2` on the grid.

**5. Autonomous Cleaning**

- The robot automatically finds the nearest waste cell.
- It moves step by step to reach the waste, cleans it (changes `1` to `0`), and continues to the next nearest waste cell.
- After each action, the grid is updated and displayed to show the robot’s movement and cleaning progress.

**6. Completion**

- Once all waste is cleaned and the grid contains only `0` (clean cells), the robot stops.
- A message confirms that the environment is fully cleaned, highlighting the environmental benefit achieved through autonomous cleaning.

---

##  **Key Features**

- Interactive user input for custom environment and waste generation.
- Dynamic grid representation with clear cell numbering.
- Autonomous agent logic to find and clean waste optimally.
- Real-time updates of robot position and grid state.
- Error handling for invalid inputs to ensure a smooth user experience.
- Python code is modular, well-structured, and thoroughly commented for readability.

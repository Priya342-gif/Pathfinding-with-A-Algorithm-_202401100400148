# Pathfinding-with-A-Algorithm-_202401100400148
📌 Overview
This project implements the A (A-star) pathfinding algorithm* in Python to find the shortest path between a start and goal position in a randomly generated grid. The algorithm avoids obstacles and finds the most efficient path.

🚀 Features
✅ Dynamic Grid Generation – Creates a grid with random obstacles.
✅ User-Defined Start & Goal – Allows manual input of positions.
✅ A Algorithm Implementation* – Ensures efficient pathfinding.
✅ Error Handling – Prevents obstacles at start/goal positions.
✅ Clear Output – Displays the shortest path if found.


🛠️ Installation & Setup
1️⃣ Prerequisites
Make sure you have Python 3.x installed on your system.

2️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Astar-Pathfinding.git
cd Astar-Pathfinding
3️⃣ Run the Program
bash
Copy
Edit
python astar_pathfinding.py
4️⃣ Provide Inputs
Enter grid dimensions.
Enter start and goal positions.
The algorithm finds and prints the shortest path.
🔎 How It Works?
The user enters the grid size (rows & columns).
A random grid with obstacles (1) and walkable paths (0) is generated.
The user selects start and goal positions (must be on 0).
The A algorithm* finds the fastest path avoiding obstacles.
The program prints the shortest route or informs if no path exists.
📝 Algorithm Explanation (Simple)
1️⃣ Start at the given position.
2️⃣ Look at all possible moves (Up, Down, Left, Right).
3️⃣ Avoid obstacles (1) and check if the move is valid.
4️⃣ Pick the best move (closer to the goal).
5️⃣ Keep moving step by step until you reach the goal.
6️⃣ Save the shortest path and display it.

🛠️ Technologies Used
Python (for logic and implementation)
heapq (for priority queue handling in A*)
random (to generate obstacles in the grid)
📬 Contact & Contribution
📧 Feel free to contribute by improving the code! If you find any issues, create a pull request or open an issue.



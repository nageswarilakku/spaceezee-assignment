Data Structures & Algorithms — SpaceZee Coding Challenge

This repository contains Python solutions to SpaceZee company’s DSA coding round problems, focused on backtracking and recursion-based problem solving.
Problems Covered

 N-Queens Problem

Problem Statement:
The N-Queens puzzle is the problem of placing n queens on an n × n chessboard such that no two queens attack each other (i.e., no two queens share the same row, column, or diagonal).

Input:
An integer n, representing the size of the chessboard.

Output:
All distinct board configurations showing valid placements of queens.

Example:

Input: n = 4
Output:
[
 [".Q..", "...Q", "Q...", "..Q."],
 ["..Q.", "Q...", "...Q", ".Q.."]
]

Constraints:

1 <= n <= 9

Algorithm Used:

Backtracking
Canonical Backtracking Problem — Subset Generation

Problem Statement:
Generate all possible subsets of a given list of integers. This demonstrates the core idea of backtracking — exploring all possible combinations by including or excluding each element.

Example:

Input: nums = [1, 2, 3]
Output:
[
  [],
  [1],
  [2],
  [3],
  [1, 2],
  [1, 3],
  [2, 3],
  [1, 2, 3]
]

Algorithm Used:

Backtracking (Recursive exploration of inclusion/exclusion)

Time complexity: O(2^n)

Concepts Used

Recursion
Backtracking
Constraint Satisfaction
Combinatorial Search

 Tech Stack

Language: Python 3

Editor: VS Code / PyCharm

Platform: SpaceZee DSA Challenge



---

📈 Complexity Analysis

Problem	Time Complexity	Space Complexity

N-Queens	O(N!)	O(N²)
Subset Generation	O(2ⁿ)	O(2ⁿ)



---

🧪 How to Run

1. Clone the repository:

git clone https://github.com/<your-username>/SpaceZee-DSA-Problems.git


2. Navigate to the folder:

cd SpaceZee-DSA-Problems


3. Run the Python file:

python n_queens.py
python subsets.py


 Learnings

Mastered the Backtracking algorithm.

Learned how to use recursion to explore all possible configurations.


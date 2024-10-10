0x01-lockboxes


Curriculum

Short SpecializationsAverage: 161.21%

0x01. Lockboxes

AlgorithmPython

 Weight: 1 Project will start Oct 7, 2024 6:00 AM, must end by Oct 11, 2024 6:00 AM Checker was released at Oct 8, 2024 6:00 AM An auto review will be launched at the deadline

Must Know

For this project, you will need a solid understanding of several key concepts in order to develop a solution that can efficiently determine if all boxes can be opened. Here’s a list of concepts and resources that will be instrumental in tackling this project:

Concepts Needed:

Lists and List Manipulation:

Understanding how to work with lists, including accessing elements, iterating over lists, and modifying lists dynamically.Python Lists (Python Official Documentation)

Graph Theory Basics:

Although not explicitly required, knowledge of graph theory (especially concepts related to traversal algorithms like Depth-First Search or Breadth-First Search) can be very helpful in solving this problem, as the boxes and keys can be thought of as nodes and edges in a graph.Graph Theory (Khan Academy)

Algorithmic Complexity:

Understanding the time and space complexity of your solution is important, as it can help in writing more efficient algorithms.Big O Notation (GeeksforGeeks)

Recursion:

Some solutions might require a recursive approach to traverse through the boxes and keys.Recursion in Python (Real Python)

Queue and Stack:

Knowing how to use queues and stacks is crucial if implementing a breadth-first search (BFS) or depth-first search (DFS) algorithm to traverse through the keys and boxes.Python Queue and Stack (GeeksforGeeks)

Set Operations:

Understanding how to use sets for keeping track of visited boxes and available keys can optimize the search process.Python Sets (Python Official Documentation)

By reviewing these concepts and utilizing these resources, you will be well-equipped to develop an efficient solution for this project, applying both your algorithmic thinking and Python programming skills.

Tasks

0. Lockboxes

mandatory

You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and each box may contain keys to the other boxes.

Write a method that determines if all the boxes can be opened.

Prototype: def canUnlockAll(boxes)boxes is a list of listsA key with the same number as a box opens that boxYou can assume all keys will be positive integersThere can be keys that do not have boxesThe first box boxes[0] is unlockedReturn True if all boxes can be opened, else return False



🌳 Balanced Binary Tree (LeetCode 110)

📌 Problem Statement

Given a binary tree, determine if it is height-balanced.

A binary tree is balanced if for every node:

|height(left subtree) - height(right subtree)| ≤ 1

🧠 Approach

Use DFS (Depth First Search) to compute height.

While calculating height:

If any subtree is unbalanced → return -1

Otherwise → return height of the subtree

Final check:

If result is -1 → tree is not balanced

Else → tree is balanced

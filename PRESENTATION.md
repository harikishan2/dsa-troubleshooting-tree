# TreeWise — 3-minute presentation

## 1. Introduction
Good morning, sir. My project is a Decision Support System for Technical Troubleshooting using Binary Tree Traversals. It shows how a tree can organize questions and suggested actions.

## 2. Tree structure
The model has seven nodes. A is the root, B and C are internal nodes, and D, E, F and G are leaf/action nodes.

## 3. Demonstration
I will click Preorder, Inorder, Postorder and Level-order. The website shows each visiting sequence. The Play traversal button highlights nodes step by step.

## 4. Troubleshooting simulator
I will answer the Yes/No questions and show how the model suggests checking the power cable, power outlet, router or internet service.

## 5. Python and complexity
The Python program implements all four traversals. Each traversal takes O(n) time because every node is visited once. Recursive methods use O(h) auxiliary stack space, and level-order uses O(w) queue space.

## 6. Conclusion
This project helped me understand binary tree representation, traversal algorithms and complexity analysis. The current version is an educational prototype with a fixed tree. A future version could include more diagnostic cases and verified technical rules. Thank you.

## Viva questions
**Why use a queue for level-order?** A queue follows FIFO, so nodes are visited level by level.

**Why is traversal O(n)?** Each of the n nodes is visited once.

**What is a limitation?** The model uses a small fixed tree and sample troubleshooting actions.

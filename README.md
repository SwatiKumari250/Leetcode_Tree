# LeetCode Tree DSA — Java

A structured collection of **LeetCode Tree problems solved in Java**, built to strengthen data-structure fundamentals, recognize interview patterns, and practice writing clear, correct solutions.

> **Goal:** Learn the reasoning behind each solution—not just memorize code.

## Contents

- [Learning roadmap](#learning-roadmap)
- [Tree patterns](#tree-patterns)
- [Suggested folder structure](#suggested-folder-structure)
- [Solution format](#solution-format)
- [How to run Java solutions](#how-to-run-java-solutions)
- [Progress tracker](#progress-tracker)
- [Practice resources](#practice-resources)

## Learning roadmap

Work through these topics in order. Add a solution and mark progress as you complete each problem.

1. **Tree fundamentals** — nodes, root, parent/child, leaf, height, depth, subtree.
2. **DFS traversals** — preorder, inorder, postorder; recursive and iterative versions.
3. **BFS / level order** — queue-based traversal, level-by-level processing.
4. **Tree properties** — maximum/minimum depth, node count, leaf count, balanced tree.
5. **Path problems** — root-to-leaf paths, target sum, path-based calculations.
6. **Binary Search Trees (BSTs)** — search, insert, validation, minimum difference, lowest common ancestor.
7. **Tree comparisons** — same tree, subtree checks, symmetry, inversion.
8. **Advanced interview patterns** — diameter, building trees from traversals, ancestor/path reasoning.

## Tree patterns

| Pattern | When to recognize it | Typical technique |
|---|---|---|
| DFS recursion | The answer depends on child subtrees | Solve left and right, then combine |
| Preorder | Process the current node before its children | Node → Left → Right |
| Inorder | BST values often need sorted order | Left → Node → Right |
| Postorder | The parent needs results from its children | Left → Right → Node |
| BFS / level order | The question asks by level or nearest depth | Queue |
| Return information upward | Height, balance, diameter, subtree summaries | Return a value from recursion |
| Path tracking | The question asks for paths or a target sum | Backtracking |
| BST range rules | Validate or search based on ordered values | Lower/upper bounds |
| Tree construction | Traversal arrays are provided | Recursion + index/map |

## Suggested folder structure

Keep each problem easy to find. This is the recommended structure as solutions are added:

```text
Leetcode_Tree/
├── README.md
├── CONTRIBUTING.md
├── .gitignore
└── src/
    ├── traversals/
    ├── bfs/
    ├── tree-properties/
    ├── path-problems/
    ├── bst/
    └── construction/
```

Folders can be created gradually; they do not need to exist before the first solution is added.

## Solution format

For every problem, aim to record:

- **Problem:** number and title, with a link to LeetCode.
- **Pattern:** the tree technique being practiced.
- **Approach:** a short explanation of the key idea.
- **Complexity:** time and auxiliary space.
- **Code:** Java solution that matches the problem's required signature.

Use descriptive filenames such as `BinaryTreeInorderTraversal.java` when keeping standalone files. Some LeetCode problems use the same class name (`Solution`); standalone files may need their own wrapper or folder to compile independently.

## How to run Java solutions

If a solution is a standalone Java program with a `main` method:

```bash
javac FileName.java
java FileName
```

LeetCode's usual `class Solution` submissions are designed to be run by LeetCode's judge and may not run directly by themselves. To run them locally, add a separate test harness with a `main` method and the required tree-node definition, if needed.

## Progress tracker

Use this checklist to track the core patterns as you learn them:

- [ ] Tree terminology and recursive thinking
- [ ] Preorder, inorder, and postorder traversal
- [ ] Iterative DFS using a stack
- [ ] Level-order traversal using a queue
- [ ] Maximum depth and minimum depth
- [ ] Count nodes and leaf nodes
- [ ] Same tree, symmetric tree, and invert tree
- [ ] Balanced binary tree
- [ ] Path sum and root-to-leaf paths
- [ ] Diameter of a binary tree
- [ ] Subtree of another tree
- [ ] Validate Binary Search Tree
- [ ] BST search and inorder properties
- [ ] Lowest common ancestor
- [ ] Build a tree from traversal arrays

This is a learning checklist, not a claim that every item already has a solution in the repository.

## Practice resources

- [LeetCode — Tree problems](https://leetcode.com/tag/tree/)
- [LeetCode — Binary Search Tree problems](https://leetcode.com/tag/binary-search-tree/)
- [LeetCode — Explore Data Structure](https://leetcode.com/explore/learn/)
- [Java documentation](https://docs.oracle.com/en/java/)

## Contribution and learning approach

This is a personal learning repository, and improvements are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the preferred solution format and contribution steps.

If you find a bug, include the problem link, a failing example, and the expected result in your issue or pull request.

---

**Language:** Java  
**Focus:** Tree data structures, problem-solving patterns, and technical interview preparation

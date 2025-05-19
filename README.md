# llrb
Java Left‐Leaning Red-Black Tree (LLRB) implementation 

LLRBs (Left-Leaning Red-Black Trees)

**Implement a self-balancing BST via Left-Leaning Red-Black Trees**  

## Overview

In this lab, you will complete the class `RedBlackTree.java` to support insertion while preserving LLRB invariants:

1. **`flipColors(Node h)`**  
2. **`rotateLeft(Node h)`** & **`rotateRight(Node h)`**  
3. **`insert(K key, V value)`** (with color-propagation and root re-coloring)  

Once these are correct, your tree will maintain perfect black‐height balance in \(O(\log N)\) time per operation.


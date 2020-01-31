# DS-Algo
Information about Data Structure and Algorithms 
> When recursive call is made or recursive method is used, underlying data structure used is Stack


**Queue**
 1. Arrays
- Linear queue 
- Circular queue 
 2. LinkedList 
- Linear queue 


**Tree**
- Root: root is node with no parents
- Edge: edge is link from parent to child
- Leaf: leaf is a node with no children 
- Sibling: Children of same parent
- Depth of node: Length of the path from root to node
- Height of node: Length of the path from that node to the deepest node 
- Height of tree: same as height of root node
- Depth of tree: same as depth of root node 


**Binary Tree**
- Two ways to create binary tree:
  1. Array
  2. LinkedList
- Just need to create object of Binary Tree Class to create binary tree with LinkedList implementation 
- Just need to create Array of the size given by user to create binary tree with Array Implementation 
- Traversal is important of Binary Tree when we insert the object in tree with LinkedList implementation
  1. In-Order traversal, 
  2. Pre-Order traversal, 
  3. Post-Order traversal, 
  4. Level-Order traversal 
- Strict Binary Tree: each node has either 2 children or none
- Full Binary Tree: each non leaf node has 2 children and all leaf nodes are at same level 
- Complete Binary Tree: all levels are completely filled except possibly the last level and the last level has all keys as left as possible. 
- Majority of trees are implemented using LinkedList in real life  
- There are mainly six operations in any tree:
  1. Create tree
  2. Insert node/element/value 
  3. Search node
  4. Traverse the tree
  5. Delete node
  6. Delete tree


 **Binary Search Tree** 
- Binary tree is a DNA for almost all types of trees in Data Structure 
- Binary tree is implemented using LinkedList 
- Binary search tree is Binary tree with following properties:
  - Left sub tree of node has a less than or equal to its parent node key
  - Right sub tree of node has a key greater than to it's parents node key


**AVL Tree**
- AVL stands for Adelson-Velskii and Landis, they are the inventors of AVL tree 
- AVL is also called 'Balanced Binary Search Tree', AVL tree = BST
- The height of immediate subtree of any node differs by at most one (also called balance factor)
- If at any time heights differ by more than one, rebalancing is done to restore this property (called rotation)
- There are four conditions for rotations:
  1. Left Left Condition (LL)
  2. Left Right Condition (LR)
  3. Right Right Condition (RR)
  4. Right Left Condition (RL)

- RR is mirror image of LL condition
- RL is mirror image of LR condition


**Binary Heap**

- Binary Heap is a Binary Tree with some special properties and these properties are
  - Heap property
     Value of a any give node must be <= value of its children (Min-Heap)
     Value of a any given node must be >= value of its children (Max-Heap)
  - Complete Tree
     All levels are completely filled except possibly the last level and the last level has all keys as left as possible 
     This makes Binary Heap ideal candidate for Array Implementation   
  - All the properties of Binary Tree will apply too



**Trie** 
- Trie is search tree which is typically used to store/search strings in space/time efficient way 
- In auto-complete functionality normally trie data structure is used 
- Spell checkers functionally is also used trie data structure, the app predicts and next word based on next available char node in trie 

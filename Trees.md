CHEAT SHEET
Tree Terminology:

Root: The topmost node of the tree.
Node: Each element or data point in the tree.
Parent: The node from which another node originates.
Child: A node that originates from another node.
Sibling: Nodes that share the same parent.
Leaf: A node without any children.
Depth/Level: The level or depth of a node in the tree (root is at level 0).
Height: The maximum depth of the tree (number of edges from root to the furthest leaf).
Subtree: A smaller tree formed by a node and its descendants.
Degree: The number of children a node has.

Common Tree Traversals:

Preorder Traversal:

Process the current node.
Recursively traverse each child subtree in order.
Root-Children order.
Postorder Traversal:

Recursively traverse each child subtree in order.
Process the current node.
Children-Root order.
Level Order Traversal (Breadth-First Search):

Traverse the tree level by level from left to right.
Visit all nodes at a given level before moving to the next level.

Tree Operations:

Insertion:

Start from the parent node and add a new child node to it.
Deletion:

Find the node to delete.
Remove the node and adjust the tree structure accordingly.
Searching:

Start from the root and compare the value to be searched with each node.
Traverse the tree until the node with the desired value is found or the search ends.

Tree Representations:

Linked Representation: Nodes are represented as objects/records with references/pointers to their children nodes.
Array/Matrix Representation: Trees are represented using arrays or matrices, where each element corresponds to a node, and the indexes represent the parent-child relationships.
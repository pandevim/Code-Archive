- Maximum Nodes at Level (i) = <code>2<sup>i</sup></code>
- Maximum Nodes with Tree Height (h) = <code>2<sup>h</sup> - 1</code>
- Minimum Height with (n) Nodes = <code>ceil(log₂(n + 1))</code>
- Minimum Levels with (n) Leaves = <code>ceil(log₂(n))</code>
---
- breadth-first traversal
  - LevelOrder traversla - (left, right)
- depth-first traversal
  - PreOrder traversal  - (parent, left, right)
  - InOrder traversal   - (left, parent, right)
  - PostOrder traversal - (left, right, parent)
---
- **Edge** – Connection between one node to another.
- **Path** – A sequence of nodes and edges connecting a node with a descendant.
  - The direction of a path is strictly from top to bottom.
- **Level** – The number of connections between the node and the root.
- **Height** – The number of Nodes on the longest downward path between selected Nodes.
- **Depth** – The number of edges from the node to the tree's root node.
---
- Leaf is not a Node, and acts only like a stop sign or Leaf is a Node, and other are Inner Nodes except Root.
- `height.root = 1`
- `depth.root = 0`
---
- **Full BT or Proper BT** – A tree in which every node other than the leaves has two children.
- **Complete BT** – A tree in which every level, except possibly the last, is completely filled and the last (or second last if not consedering leaf nodes to be in a level) level has all its nodes to the left side.
- **Extended BT or 2-Tree** – A tree with special nodes replacing every null subtree converting to **Complete BT**. Every regular node has two children, and every special node has no children.
- **Expression BT** – A tree in which each internal node corresponds to operator and each leaf node corresponds to operand.
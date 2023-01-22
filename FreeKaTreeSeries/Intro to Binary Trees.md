## Types of Binary Tree :-
1. Full Binary Tree
2. Complete Binary Tree
3. Perfect Binary Tree
4. Balanced Binary Tree
5. Degenerate Binary tree


**Binary Tree representation in C++** :-

```
struct Node{
int data;
struct Node*left;
struct Node*right;
Node(int val){
data = val;
left = right = NULL;
}
}
```

**Traversal Techniques** :-
1. DFS :-
__Types of DFS__:-
- Inorder (Left Root Right)
- Preorder (Root Left Right)
- Postoredr (Left Right Root)

2. BFS :-
Level wise traversal

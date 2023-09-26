# Exercise

##Exercise: ft_avl_tree
Allowed functions : None

• An AVL tree (Adelson-Velskii and Landis) is a self-balancing Binary Search Tree (BST) where the difference between heights of left and right subtrees cannot be more than one for all nodes.

• Your task is to implement an AVL tree that supports insertion, deletion and in-order traversal.

For the AVL tree, following are the main properties: 
- The tree is a binary search tree (BST) 
- The height of two subtrees of a node never differs by more than one 

Here's how it should be prototyped: 
```c
typedef struct  s_node 
{
   int data; 
   struct s_node* left; 
   struct s_node* right; 
   int height; 
}               t_node; 

t_node *ft_avl_tree(t_node *root, int data);
t_node *deleteNode(t_node *root, int key);
void inOrder(t_node *root);
```
(Note: The ft_avl_tree function is supposed to insert an integer data into the AVL tree and return the root of the tree. The deleteNode function is supposed to delete a node with the specified key from the AVL tree and return the root of the tree. The inOrder function is supposed to print all nodes of the AVL tree in in-order traversal.)
# Submissions 
 git push your solution in this repo and hit /submit in Discord
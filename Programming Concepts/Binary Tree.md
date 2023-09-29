tags: #theory #tree
links: [[Programming Concepts]]

---
# Binary Tree
A binary tree has a **root** and at least one **child**.
example:
![[Pasted image 20230929164117.png]]

Defined in C code:
```c
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
};
```
You can access the values in the following manner, in C:
```c
bool main(struct TreeNode* root){
	printf("%d", root->val);
	printf("%d", root->left->val);
	printf("%d", root->right->val);
	return 0;
}
```

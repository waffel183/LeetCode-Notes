tags: #languages 
links: [[Programming Languages]]

---
# C 
## How to access Struct values
having a recursive struct like this: 
```c
struct TreeNode {
	int val;
	struct TreeNode *left;
	struct TreeNode *right;
}
```
You can access the values of val, left & right with the following:
```c
bool main(struct TreeNode* root){
	printf("%d", root->val);
	printf("%d", root->left->val);
	printf("%d", root->right->val);
	return 0;
}
```

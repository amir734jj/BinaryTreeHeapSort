# BinaryTreeHeapSort
Simple heap sort using a binary tree with automatic balancing

```java
	// initialize
	BinaryTree<Integer> tree = new BinaryTree<Integer>();
	
	// add random numbers
	for(int i = 0; i < 200; i++) {
		tree.add(i);
	}
	
	// print the list
	System.out.println(tree.toList());
	
	// balance the tree
	tree.naivelyBalanceTree();
	
	// print the tree again
	System.out.println(tree.toList());
```

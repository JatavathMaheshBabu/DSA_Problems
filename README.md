# DSA Problems on Binary search Tree
1. Input Values
values[] = {5, 1, 3, 4, 2, 7}

2. BST Building Rules
For each new value:
If value < root → insert into left subtree.
If value > root → insert into right subtree.

3. Example Construction
Start with 5 → becomes root.
Insert 1 → 1 < 5 → goes to left of 5.
Insert 3 → 3 < 5 → go left, 3 > 1 → right of 1.
Insert 4 → 4 < 5 → left, 4 > 1 → right, 4 > 3 → right of 3.
Insert 2 → 2 < 5 → left, 2 > 1 → right, 2 < 3 → left of 3.
Insert 7 → 7 > 5 → right of 5.

4. Inorder Traversal
If we do Inorder Traversal (Left → Root → Right):
1 2 3 4 5 7
   
This is always sorted for a BST.

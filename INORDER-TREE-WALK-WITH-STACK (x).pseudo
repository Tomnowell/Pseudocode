PREORDER-TREE-WALK-WITH-STACK (x)
1   create a new stack S
2   if x ≠ NIL                  // Check if the tree is empty
3       PUSH(S,x) 
4       print x.key
5   if x.right ≠ NIL            // Push right side first.
6      PUSH(S, x.right)
7   if x.left ≠ NIL             // Processed first due to FIFO
8      PUSH(S, x.left)
9   while (STACK-EMPTY(S) ≠ TRUE) // Keep checking and adding until the stack is empty
10     temp = POP(S)           // Get and remove the current node
11     if (temp ≠ NIL)         // Check we haven't reached the end of the tree
12         print temp.key
13     if temp.right ≠ NIL     // Processed second due to FIFO
14         PUSH(S, temp.right)
15     if temp.left ≠ NIL      // Processed first
16         PUSH(S, temp.left)
        
    
If a linked list has 100 nodes, how many recursive calls will be made to compute sum? 
 
 A.  100 
B. 101 
C. 99 
D. Depends on value

int sum(Node head) { 
if (head == null) return 0; 
return head.val + sum(head.next); 
} 

Final Answer: B. 101 I(100 nodes + 1 base case)



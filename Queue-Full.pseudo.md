Queue-Empty (Q)
1	if Q.head == Q.tail
2	          return True
3	else  return False

 
Front (Q)
1	if Queue-Empty (Q)
2	          error “underflow”
3	else  return Q[Q.head]


Queue-Full (Q)
1	if Q.tail == Q.length
2	             n = 1
3	else    n = Q.tail+1
4	if n = Q.head
5	             return True
6	else      return False
 
 
EnQueue (Q, x)
1	if Queue-Full(Q)
2	         error “overflow”
3	else Q[Q.tail] = x
4	         if Q.tail == Q.length
5	                       Q.tail = 1
6	         else Q.tail = Q.tail +1     

DeQueue (Q)
1	if Queue-Empty(Q)
2	        error “underflow”
3	else x = Q[Q.head]
4	        if Q.head == Q.length
5	                      Q.head = 1
6	        else Q.head = Q.head +1
7	        return x              


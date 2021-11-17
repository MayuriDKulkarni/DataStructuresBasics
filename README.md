# DataStructuresBasics
Types of Data Structures:
1. Linear Data Structures
2. Non-linear Data Structure

Linear Data Structure in which the traversal,retrival or storage of elements will always in a sequencial way where as in Non-Linear Data Structures the traversal,retrival or storage of elements not in a sequencial way.

Linear data structures are stack,queue,link list, arrays.
Non-linear data structures are tree,graph.

Array: Same data type and allocated contiguous memory locations
Stack:It has only one end.Hence storing and retrival will occure from same end.Storing of Element known as Push operation.Removal of Element known as Pop operation.Stack works upon First-In-Last-Out principal.
      Examples of stack are tower of Hanoi,Undo redo operation etc.
Queue: It has two ends called as front end and rear end.Insertion will always at always at rear end called as Enqueue opeartion where as removal will always from front end only called as dequeue operation. This works upon First-In-First-Out principal.
      Examples are FIFO scheduling algorithm in CPU scheduling.
 
 
 
Stack :
1. Stack has only one end hence removal as well as insertion takes place from one end only.
2. Works upon First-In-Last-Out principal.
3. PUSH(Data):Push always inserts data on top of the stack
4. POP():Pop always removes data from top of stack of stack 
5. Is_Full():Checks overflow condition for the stack.If overflow condition occures push operation is not at all possible
6. Is_Empty():Checks underflow condition for the stack.If underflow condition occures pop operation terminates.

Stack can be implemented using arrays as well as link list.
1. Stack using array:
        While implementing stack using array points to be noted as Define size of stack and Initialize top=0.
        
        ##The C code to implement stack using array is 
        
    


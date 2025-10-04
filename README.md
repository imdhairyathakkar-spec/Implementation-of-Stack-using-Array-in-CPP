# Implementation-of-Stack-using-Array-in-CPP
Implementation-of-Stack-using-Array-in-CPP
Aim: To study and implement stack using array in C++

Software: Mingw c/cpp compiler , VScode , online C++ compiler

Program :
Theory with explanation of the code: A stack is a linear data structure that works on the LIFO (Last In, First Out) principle.

The program implements a stack using an array of fixed size (MAX_SIZE = 5).
The class Stack contains:
stackArray[MAX_SIZE] to store elements.
topIndex to track the position of the top element.
Push operation inserts an element at the top of the stack. If the stack is full, it shows STACK OVERFLOW.
Pop operation removes and returns the top element. If the stack is empty, it shows STACK UNDERFLOW.
Peek operation displays the top element without removing it.
Display function prints all elements of the stack from bottom to top.
In main(), elements are pushed, one is popped, the top is checked, and remaining elements are displayed.
Algorithm:

Start
Initialize topIndex = -1 and create stackArray[MAX_SIZE]
Push Operation
If topIndex == MAX_SIZE - 1, print "STACK OVERFLOW"
Else increment topIndex and insert element at stackArray[topIndex]
Pop Operation
If topIndex == -1, print "STACK UNDERFLOW"
Else return stackArray[topIndex] and decrement topIndex
Peek Operation
If topIndex == -1, print "STACK UNDERFLOW"
Else return element at stackArray[topIndex]
Display Operation
If topIndex == -1, print "STACK is empty"
Else print elements from index 0 to topIndex
In main(), perform push, pop, peek, and display operations
Stop
Conclusion
In conclusion, the stack implementation using arrays successfully demonstrates the fundamental operations of the LIFO (Last In, First Out) data structure. The program shows how elements can be pushed, popped, and viewed at the top using a fixed-size array. Proper error handling is included for overflow and underflow conditions, ensuring reliable performance. This implementation helps in understanding how memory and indexes are managed in stack operations. Though limited by fixed size, the concept can be extended to dynamic stacks using linked lists. Overall, the program provides a clear foundation for stack applications in computer science.

# Computing-for-Data-Science-Lab
A repository for a Computing for Data Science Lab could contain various resources and materials to support hands-on learning and experimentation in data science


> Table of Contents
## Searching Algorithms
### 1. Linear Search:
**Definition**: A simple algorithm which is used to find an element in a list by traversing or iterating by checking each element from beginning to the end until it's found. This is called as linear search because it traverses the list in a linear way, one element at a time. 

**Algorithm**:<br>
  _step 1_: Start from the first element of the list.<br>
  _step 2_: Compare the target value (k) with the current element.<br>
  _step 3_: If the target value matches the current element, return the index of the current element.<br>
  _step 4_: If the target value does not match, move to the next element.<br>
  _step 5_: Repeat steps 2-4 until the end of the list is reached.<br>
  _step 6_: If the target value is not found, return -1.<br>

**Flow Chart for**
[Linear Search](https://github.com/pavir05/Computing-for-Data-Science-Lab/blob/main/Linear_Search.jpg)

**Code for**
[Linear Search](https://github.com/pavir05/Computing-for-Data-Science-Lab/blob/main/Code/Linear%20Search)


**Output**:<br>
![image](https://github.com/user-attachments/assets/718a7eb0-6c4f-4f16-be8d-991ae99a4b4f)

**Edge Cases**:<br>
_1. Target present at the beginning_<br>
 - Scenario: The target element is the first element in the list.
 - Expected o/p: The algorithm should identify the target at the start of the list and return the index 0.<br>
 ![image](https://github.com/user-attachments/assets/1ec18e1f-df6b-413e-914a-594981a33ab0)

 
_2. Target present at the end_<br>
 - Scenario: The target element is the last element in the list.
 - Expected o/p: The algorithm iterates through the entire list and return the last index.<br>
 ![image](https://github.com/user-attachments/assets/ad6feb47-139c-4a65-bebd-930f65d62af9)

 
_3. Target not present_<br>
 - Scenario: The target element is not present in the list.
 - Expected o/p: The algorithm iterates through the entire list and returns -1(element is not found).<br>
![image](https://github.com/user-attachments/assets/68afa556-7ca0-4946-8249-68e4140fac83)

### 1. Stack:
**Definition**: A data-structure which is linear and follows LIFO(Last In First Out) principle. It has the functions 
- push(add elements)
- pop(removes element)
- peek(check's if the stack is empty or not)<br>
(it can have more functions)

**Real Life Examples:**
1. Undo-Redo
2. Pile of books
3. Infix to Postfix / Postfix to Infix
4. Paranthesis Balancing

**Code for**
[Stack](https://github.com/pavir05/Computing-for-Data-Science-Lab/blob/main/Code/Stack)

### 1. Queue:
**Definition**: A data-structure which is linear and follows FIFO(First In First Out) principle. It has the functions 
- enqueue(add elements)
- dequeue(removes element)
- peek(check's if the queue is empty or not)<br>
(it can have more functions)

**Real Life Examples:**
1. Email inbox
2. Movie ticket booking

**Code for**
[Queue](https://github.com/pavir05/Computing-for-Data-Science-Lab/blob/main/Code/Queue)

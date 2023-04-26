# Queue
A Queue is defined as a linear data structure that is open at both ends and the operations are performed in First In First Out (FIFO) order.

How to implement Queue using Array?
To implement a queue using an array,

1.create an array arr of size n

2.take two variables front and rear both of which will be initialized to 0 which means the queue is currently empty.

3.Element rear is the index up to which the elements are stored in the array

4.Element front is the index of the first element of the array.


Some of the implementations of queue operations are as follows:
1.Enqueue: Addition of an element to the queue. Adding an element will be performed after checking whether the queue is full or not. If rear < n which indicates that the array is not full then store the element at arr[rear] and increment rear by 1 but if rear == n then it is said to be an Overflow condition as the array is full.
2.Dequeue: Removal of an element from the queue. An element can only be deleted when there is at least an element to delete i.e. rear > 0. Now, the element at arr[front] can be deleted but all the remaining elements have to shift to the left by one position in order for the dequeue operation to delete the second element from the left on another dequeue operation.
3.Front: Get the front element from the queue i.e. arr[front] if the queue is not empty.
4.Display: Print all elements of the queue. If the queue is non-empty, traverse and print all the elements from the index front to rear.

![image](https://user-images.githubusercontent.com/127819492/234480961-60fa4ea4-356c-46f2-8e7a-7371db6831dd.png)

# (Udemy)Data Structures and Algorithms: Deep Dive Using Java

## Arrays in Memory
- Contiguous block in memory
- Every element occupies the same amount space in memory
- If an array starts at memory address x, and the size of each element in the array is y, we can calculate the memory address of the ith element by using the following expression: x + i*y
- If we know the index of an element, the time to retrieve the element will be the same, no matter where it is in the array

|0  |1|2  |3|4 |5|6|
----|-|---|-|--|-|--
20|35|-15|7|55|1|-22

Start address of array 12, element size = 4 bytes(because int is a primitive type)
In object's case, such as String, only the reference will be stored in memory, which has the same size always. 

Address od array[0] = 12
Address od array[1] = 12 + (1 * 4) = 16
Address od array[2] = 12 + (2 * 4) = 20
Address od array[3] = 12 + (3 * 4) = 24
Address od array[4] = 12 + (4 * 4) = 28
Address od array[5] = 12 + (5 * 4) = 32
Address od array[6] = 12 + (6 * 4) = 36
 
 


# Data Structures and Algorithms: Deep Dive Using Java

## Arrays in Memory
- Contiguous block in memory
- Every element occupies the same amount space in memory
- If an array starts at memory address x, and the size of each element in the array is y, we can calculate the memory address of the ith element by using the following expression: x + i*y
- If we know the index of an element, the time to retrieve the element will be the same, no matter where it is in the array

|0  |1|2  |3|4 |5|6|
----|-|---|-|--|-|--
20|35|-15|7|55|1|-22
 


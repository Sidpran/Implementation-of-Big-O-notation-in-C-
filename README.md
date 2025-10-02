# Implementation-of-Big-O-notation-in-C-

Aim: To explore and understand Big O notation in C++

Software:  
- Mingw C/C++ compiler  
- Visual Studio Code  
- Online C++ compiler

# Program Time complexity
Theory with explanation of the code:

- Time complexity describes how the **execution time of an algorithm grows as the input size increases**.  
- **O(1) – Constant Time:** The operation takes the same amount of time regardless of input size. Example: accessing the first element in an array.  
- **O(n) – Linear Time:** Execution time increases linearly with the number of elements. Example: printing all elements in a list.  
- **O(n²) – Quadratic Time:** Execution time grows with the square of the input size. Example: printing all possible pairs of elements.  
- The program uses three functions to demonstrate these complexities:  
  - `getFirstElement()` – shows **O(1)** by directly returning one element.  
  - `printElements()` – shows **O(n)** by iterating through the entire vector.  
  - `printPairs()` – shows **O(n²)** by using nested loops to output every pair.  
- These examples illustrate how the algorithm’s performance changes with larger datasets.  
- Understanding time complexity is essential for **writing efficient code** and selecting the right algorithm for the task.  

Algorithm:  
- Start  
- Create a vector of sample integers.  
- Use a function to return the first element (**O(1)**).  
- Use a function to print all elements (**O(n)**).  
- Use a function to print all element pairs (**O(n²)**).  
- Display the results for each operation.  
- End  

# Conclusion
The program demonstrates the impact of different time complexities:  

- **O(1)** operations are constant and extremely fast, ideal for direct access.  
- **O(n)** operations grow linearly and are suitable for moderate-sized datasets.  
- **O(n²)** operations grow quickly and become inefficient for large inputs.  

By analyzing these examples, developers can **predict performance**, **choose optimal algorithms**, and design solutions that scale efficiently with input size.

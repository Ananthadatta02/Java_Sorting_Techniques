



# Java Sorting Examples

This repository contains Java programs that demonstrate sorting techniques. The examples include both custom sorting algorithms and predefined sorting methods provided by Java. The goal is to help you understand the fundamentals of sorting and its implementation in Java for arrays and `ArrayList`.

## What is Sorting?
Sorting is the process of arranging data in a specific order, often ascending or descending. It is a fundamental operation in computer science that improves data retrieval and manipulation efficiency. Common sorting algorithms include Bubble Sort, Merge Sort, Quick Sort, and more. Java also provides built-in methods like `Collections.sort()` for sorting.

### Why Sorting Matters
1. **Improved Data Accessibility**: Sorted data is easier to search and process.
2. **Performance Optimization**: Algorithms like binary search require sorted input to work efficiently.
3. **Real-world Applications**: Sorting is widely used in databases, UI components, ranking systems, and more.

---

## Program Descriptions

### 1. SortingClassExample.java
This program demonstrates sorting an array of integers using a custom sorting algorithm. The algorithm compares adjacent elements in the array and swaps them if they are out of order. This approach is similar to a single pass of Bubble Sort.

#### Code Breakdown:
- **Input**: An unsorted array of integers.
- **Algorithm**: Compares adjacent elements and swaps them if the first is greater than the second.
- **Output**: A partially sorted array (only the first pass of sorting).

#### Example:
```java
int a[] = {2, 1, 9, 8, 6, 10};
// Output: [1, 2, 9, 8, 6, 10]
```
### Highlights:
Demonstrates basic array manipulation.
Good for understanding the mechanics of element comparison and swapping.

## 2. SortExampleWithArrayList.java
This program focuses on sorting an `ArrayList` of integers using two approaches:

1. **Predefined Method (`Collections.sort`)**:  
   A highly optimized sorting method provided by Java.

2. **Custom Sorting Algorithm**:  
   Implements a nested loop to compare and swap elements manually, similar to Bubble Sort.

---

### Code Breakdown:

- **Input**:  
  An `ArrayList` of integers.

- **Predefined Sorting**:  
  Utilizes `Collections.sort` to sort the list in ascending order.  

  Example:
  ```java
  Collections.sort(al);
  ```

## Custom Sorting
- Iterates through the list using nested loops.
- Compares each element with subsequent elements and swaps them if out of order.

### Example:
```java
import java.util.ArrayList;
import java.util.Collections;

public class SortExampleWithArrayList {
    public static void main(String[] args) {
        ArrayList<Integer> al = new ArrayList<>();
        al.add(10);
        al.add(5);
        al.add(20);
        al.add(18);
        
        Collections.sort(al); // Predefined sorting
        System.out.println(al); // Output: [5, 10, 18, 20]
    }
}
```
### Highlights:
- Showcases the difference between manual sorting and predefined sorting.
- Introduces the flexibility of using ArrayList and its methods.

## How to Run the Programs
### Prerequisites:
- Install Java Development Kit (JDK).
- Set up a Java IDE (Eclipse, IntelliJ IDEA, or Visual Studio Code) or use the command line.

## Steps to Execute:
- Clone the repository:
```
git clone https://github.com/Ananthadatta02/Java_Sorting_Techniques.git
cd Java_Sorting_Techniques
```
- Compile and run SortingClassExample.java:
```bash
javac SortingClassExample.java
java collection.SortingElements
```
- Compile and run SortExampleWithArrayList.java:
```
javac SortExampleWithArrayList.java
java collection.SortExample
```

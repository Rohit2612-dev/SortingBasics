## Sorting Algorithms in Java

This repository contains Java implementations of three fundamental sorting algorithms: **Bubble Sort**, **Selection Sort**, and **Insertion Sort**.

Each algorithm is contained within its own file and includes a `main` method to demonstrate its usage with a sample array: `{7, 8, 3, 1, 2}`.

---

### 🚀 Algorithms Included

#### 1. Bubble Sort

* **File:** `BubbleSort.java`
* **Concept:** Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.
* **Time Complexity (Worst/Average):** $O(n^2)$
* **Time Complexity (Best):** $O(n)$ (when the array is already sorted)



#### 2. Selection Sort

* **File:** `SelectionSort.java`
* **Concept:** Selection Sort divides the input list into two parts: a sorted sublist and the remaining unsorted sublist. It repeatedly finds the minimum element from the unsorted sublist and moves it to the sorted sublist.
* **Time Complexity (Worst/Average/Best):** $O(n^2)$



#### 3. Insertion Sort

* **File:** `InsertionSort.java`
* **Concept:** Insertion Sort builds the final sorted array one item at a time. It iterates through the input elements and removes one element per iteration, finds the place it belongs within the already sorted part, and inserts it there.
* **Time Complexity (Worst/Average):** $O(n^2)$
* **Time Complexity (Best):** $O(n)$ (when the array is already sorted)



---

### 💻 How to Run the Code

1.  **Clone the Repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Navigate to the Directory:**
    ```bash
    cd sortingExample
    ```
3.  **Compile and Run (Example: Bubble Sort):**

    * **Compile:**
        ```bash
        javac BubbleSort.java
        ```
    * **Run:**
        ```bash
        java BubbleSort
        ```

### 🎯 Expected Output

When any of the programs are executed with the input array `{7, 8, 3, 1, 2}`, the output will be the sorted array:

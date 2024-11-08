# 📊 Sorting Algorithms Project

## Overview

This project implements a variety of **sorting algorithms** in **C++** to explore and compare different sorting techniques. Each algorithm demonstrates unique characteristics in terms of performance and complexity, offering insights into the strengths and trade-offs of various sorting methods.

The project includes algorithms that work well with both integer and floating-point data, as well as those optimized for specific data structures. It’s designed to test the performance of each algorithm on randomized datasets, providing metrics like execution time and failure rate.

## 🚀 Features

- **Multiple Sorting Algorithms**: Includes implementations of Radix Sort, Merge Sort, Shell Sort, Heap Sort, Quick Sort, Insertion Sort, and Standard Library Sort.
- **Performance Testing**: Measures execution time and records the number of successful runs within a time limit.
- **Randomized Input Generation**: Generates random integer and floating-point arrays to test the robustness of each sorting algorithm.
- **Time Limit Enforcement**: Uses a time limit to identify algorithms that perform slower on large datasets, helping to measure algorithm efficiency.

## 📂 Project Structure

The project is organized into individual classes for each sorting algorithm, each inheriting from a base `Sort` template class to ensure modularity.

### 🔹 Sorting Algorithms Implemented

- **Radix Sort**: Efficiently sorts integers by processing individual digits, making it suitable for specific types of integer data.
- **Merge Sort**: A classic divide-and-conquer algorithm that recursively splits and merges subarrays for efficient, stable sorting.
- **Shell Sort**: Utilizes a sequence of gap-based comparisons, improving upon insertion sort by reducing the number of overall shifts.
- **Heap Sort**: Constructs a binary heap to repeatedly extract the maximum or minimum element, providing efficient, in-place sorting.
- **Quick Sort**: A partition-based, recursive algorithm that sorts by dividing the array around a pivot.
- **Insertion Sort**: Simple sorting method, effective for small or partially sorted datasets.
- **Standard Library Sort (`std::sort`)**: Uses C++'s standard library sort for optimized performance, acting as a benchmark.

## 📝 Usage

The project allows users to select and test different sorting algorithms on randomly generated input arrays. 

### Example Flow

1. **Select Algorithm**: Choose an algorithm (e.g., Radix Sort or Quick Sort) to sort a randomly generated dataset.
2. **Observe Output**: Check if the algorithm completes within the set time limit and compare performance metrics.
3. **Compare Algorithms**: Test other algorithms on the same dataset to evaluate relative performance.

## ✨ Code Highlights

This project demonstrates several key concepts in sorting algorithm design and performance measurement:

1. **Object-Oriented Design**: Each sorting algorithm is encapsulated in a class that inherits from a generic base class `Sort`.
2. **Performance Monitoring**: Tracks time for each sorting algorithm and calculates success rates within the set time limit.
3. **Randomized Testing**: Generates random arrays of both integers and floating-point numbers to assess each algorithm’s robustness.
4. **Time Limit Enforcement**: Uses `CHECKQUIT` macros to halt algorithms that exceed the allocated time, ensuring efficiency measurements.
5. 
## 🔧 Future Improvements

Potential improvements to expand functionality and usability:

- **Interactive Visualization**: Implement a graphical representation to visualize sorting steps and illustrate algorithm differences.
- **Additional Algorithms**: Include other complex sorting methods such as Tim Sort or external sorting for larger datasets.
- **Data Structure Optimization**: Experiment with alternative data structures to improve the efficiency of certain algorithms.

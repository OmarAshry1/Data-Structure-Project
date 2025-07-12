# Sorting Algorithms Visualization

A Qt-based application that visualizes and compares different sorting algorithms. This project was developed as part of the CSE331 Data Structures and Algorithms course.

## Features

- Interactive visualization of popular sorting algorithms:
  - Bubble Sort
  - Selection Sort 
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
  - Counting Sort

- Real-time visualization of sorting process
- Comparison of algorithm performance
- Time complexity (Big-O) display
- Customizable input size
- Performance charts and statistics

## Requirements

- Qt 6.8.1 or later
- MinGW 64-bit compiler
- C++17 compatible compiler

## Building the Project

1. Clone the repository
2. Open the project in Qt Creator
3. Configure the project for your Qt version
4. Build using either:
   ```sh
   # Debug build
   qmake "CONFIG+=debug" "CONFIG+=qml_debug"
   make
   
   # Release build
   qmake "CONFIG+=release"
   make
   ```

## Project Structure

- `mainwindow.cpp/h` - Main application window
- `next_2.cpp/h` - Sorting algorithm selection and visualization
- `comparealg.cpp/h` - Algorithm comparison functionality
- `sorting.cpp/h` - Sorting algorithm implementations
- `sec.cpp/h` - Secondary window components
- `last.cpp/h` - Results and statistics display

## Usage

1. Launch the application
2. Select a sorting algorithm
3. Choose the number of elements to sort
4. Click "Proceed" to start visualization
5. View the sorting process and performance metrics




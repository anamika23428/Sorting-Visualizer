# Sorting Visualizer

**Sorting Visualizer** is a web application designed to visually demonstrate the functionality of various sorting algorithms. Users can interactively select different algorithms, set the size and speed of the array, and watch how the array gets sorted step by step. This tool helps to better understand the inner workings of sorting algorithms.

## Features

- **Sorting Algorithms**: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort.
- **Interactive Controls**: Users can set the array size and sorting speed.
- **Visual Feedback**: The visualizer shows how the elements are swapped or moved during the sorting process.
- **Responsive Design**: The app adapts to different screen sizes, from desktop to mobile devices.

## Technologies Used

- **HTML**: For creating the basic structure of the webpage.
- **CSS**: For styling the page and making it visually appealing.
- **JavaScript**: For implementing sorting algorithms and visualizing the sorting process.
- **jQuery (optional)**: If included, for DOM manipulation and event handling.
- **Owl Carousel**: If included, used for displaying carousel elements (e.g., featured items).

## Installation

To get the project running locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/sorting-visualizer.git
   cd sorting-visualizer
   ```

2. **Open the index.html file in your browser**

 Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari, etc.). No server setup is required.

3. **Run the App**

 Once the file is opened in the browser, you can start interacting with the visualizer, selecting sorting algorithms and adjusting parameters.

## How to Use

1. **Select Sorting Algorithm**:  
   Click on one of the algorithm buttons (e.g., "Bubble", "Selection", "Merge", etc.) to select the sorting algorithm.

2. **Adjust Array Size**:  
   Use the "Size of array" slider to adjust the number of elements in the array.

3. **Set Sorting Speed**:  
   Use the "Speed of algorithm" slider to adjust the speed at which the sorting algorithm runs.

4. **Generate New Array**:  
   Click the **Generate New Array** button to generate a new random array of numbers that will be sorted.

5. **Watch the Sorting Process**:  
   Once an algorithm is selected, the sorting process will begin, and you'll see visual steps of how the algorithm sorts the array.

## Algorithms Supported

### 1. **Bubble Sort**
- Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The process is repeated until the array is sorted.

### 2. **Selection Sort**
- Selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first unsorted element. It repeats this until the list is sorted.

### 3. **Insertion Sort**
- Builds the sorted array one element at a time. It takes an element and finds its correct position in the sorted portion of the array, inserting it in place.

### 4. **Merge Sort**
- Divides the array into two halves, sorts them recursively, and merges them back together. Merge Sort is a divide-and-conquer algorithm.

### 5. **Quick Sort**
- Selects a pivot and partitions the array such that elements smaller than the pivot come before it, and those greater come after it. The algorithm then recursively sorts the subarrays.

### 6. **Heap Sort**
- Converts the array into a heap structure and then sorts it by repeatedly extracting the largest element from the heap and placing it at the end of the array.

## Customization

You can customize the visualizer by:

- Adding more sorting algorithms to the list.
- Modifying the colors or animations to improve the visual experience.
- Adjusting the layout and user interface elements to better fit your needs or preferences.

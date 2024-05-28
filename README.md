# Php-Sort-Algorithms
# Sorting Algorithms in PHP

This repository contains PHP implementations of three popular sorting algorithms: Bubble Sort, Selection Sort, and Quick Sort.

## Bubble Sort

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

### Usage

```php
$array = [5, 3, 8, 4, 2];
$array = bubbleSort($array);
print_r($array); // Output: [2, 3, 4, 5, 8]

# Sorting Algorithms in PHP

This repository contains PHP implementations of three popular sorting algorithms: Bubble Sort, Selection Sort, and Quick Sort.

## Bubble Sort

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

### Usage

```php
$array = [5, 3, 8, 4, 2];
$array = bubbleSort($array);
print_r($array); // Output: [2, 3, 4, 5, 8]

#### Sorting Algorithms in PHP: Quick Sort and Selection Sort

This repository contains PHP implementations of two popular sorting algorithms: Quick Sort and Selection Sort.

## Quick Sort

Quick Sort is a highly efficient sorting algorithm that uses a divide-and-conquer approach to sort an array or list of elements. It works by selecting a 'pivot' element from the list and partitioning the other elements into two sublists: one sublist containing elements less than the pivot and the other containing elements greater than the pivot. The process is then applied recursively to the sublists until the entire list is sorted.

### Algorithm Steps:
1. Choose a pivot element from the array.
2. Partition the array into two subarrays: elements less than the pivot and elements greater than the pivot.
3. Recursively apply the Quick Sort algorithm to the subarrays.
4. Concatenate the sorted subarrays with the pivot in the correct position.

### Usage

```php
$array = [5, 3, 8, 4, 2];
$array = quickSort($array);
print_r($array); // Output: [2, 3, 4, 5, 8]


# CMPS 2200 Reciation 5
## Answers

**Name:** Nicolas Labarca


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
The tabulated performance data for Quicksort variants with fixed and random pivots, alongside Selection Sort, clearly illustrates the theoretical computational complexities of these algorithms. Quicksort, with its O(n log n) complexity, outperforms Selection Sort, which operates at O(n^2), particularly as list sizes increase. The data distinctly demonstrates that Quicksort's efficiency is significantly enhanced by the use of random pivot selection over a fixed pivot. This improvement is most notable in larger list sizes, where the disparity in execution time between fixed and random pivots widens dramatically. Selection Sort's performance, while more consistent across varying inputs, generally lags due to its quadratic time complexity, making it less suitable for larger datasets. The impact of list size on algorithm performance is starkly evident; while Selection Sort's execution time climbs steadily with list size, Quicksort with random pivots maintains a comparatively low and more stable execution time, underscoring its suitability for handling larger datasets efficiently.



- **1c.**
Upon comparing the fastest Quicksort variant with Python's Timsort, it's anticipated that Timsort would outshine Quicksort in terms of efficiency for both sorted lists and random permutations. Timsort's edge stems from its hybrid algorithmic nature, combining elements of Merge Sort and Insertion Sort. This blend enables Timsort to excel in processing real-world data, which often includes partially sorted sequences. Timsort's design to capitalize on existing order within the data significantly boosts its sorting efficiency. This hybrid approach makes Timsort particularly adept at handling both sorted and unsorted data, offering superior performance compared to Quicksort's variance with fixed or random pivots. While Quicksort shows pronounced inefficiency with fixed pivot selections, especially in larger datasets, Timsort's adaptability to various data conditions positions it as a more universally efficient sorting solution, capable of delivering optimal performance across a wide range of data types.

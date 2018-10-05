## Radix Sort
From Wikipedia, 

> In [computer science](https://en.wikipedia.org/wiki/Computer_science "Computer science"), **radix sort** is a non-[comparative](https://en.wikipedia.org/wiki/Comparison_sort "Comparison sort")  [integer](https://en.wikipedia.org/wiki/Integer_sorting "Integer sorting")  [sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm "Sorting algorithm") that sorts data with integer keys by grouping keys by the individual digits which share the same [significant](https://en.wikipedia.org/wiki/Significant_figures "Significant figures") position and value. A [positional notation](https://en.wikipedia.org/wiki/Positional_notation "Positional notation") is required, but because integers can represent strings of characters (e.g., names or dates) and specially formatted floating point numbers, [radix](https://en.wikipedia.org/wiki/Radix "Radix") sort is not limited to integers. Radix sort dates back as far as 1887 to the work of [Herman Hollerith](https://en.wikipedia.org/wiki/Herman_Hollerith "Herman Hollerith") on [tabulating machines](https://en.wikipedia.org/wiki/Tabulating_machines "Tabulating machines").[[1]](https://en.wikipedia.org/wiki/Radix_sort#cite_note-1)

### Algorithm

For each digit i where i varies from the least significant digit to the most significant digit of a number  
Sort input array using countsort algorithm according to ith digit.  
  
We used count sort because it is a stable sort.
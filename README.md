# Sort Colors
In this problem we are trying to sort the colors in the order of red, white, blue represented by the colors 0, 1, 2.
The sorting method that we use to solve this question is the stable counting sort with a time complexity of O(n + k), to keep the order of which colors came first.

# Maximum Gap
In this problem we are given an unsorted array and trying to return the maximum difference between the elements in sorted form with the requirements of the time complexity
must reaching O(n) time. To solve this problem we used the bucket sort to calculate the differences between the highest and lowest values between buckets to get the maximum
difference possible between two different elements, thus reaching O(n) time complexity.

# Partition Equal Subset Sum
In this problem we are given an array of integers and we are supposed to find two subsets that the sum of each subset equals to that of the other.
To solve this problem, we have decided to use a 1D dynamic programming array to track which subsets are allowed to be created with a sum of total/2, for equal partitioning.
We are able to achieve the time complexity of O(n * W) where W is the total/2, and uses O(W) space due to the 1D dynamic array.

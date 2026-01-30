# median-of-two-sorted-arrays
Given two sorted arrays nums1 and nums2 of size m and n respectively, return the median of the two sorted arrays.  The median is the middle value in a sorted list. If the list has an even number of elements, the median is the average of the two middle elements. The required runtime complexity for this problem is O(log (m+n)).
# LeetCode #4: Median of Two Sorted Arrays

## 📝 Problem Description
Given two sorted arrays `nums1` and `nums2` of size `m` and `n` respectively, return the median of the two sorted arrays.

## 🚀 My Solution
The current implementation uses the **Merge and Sort** approach:
1. Combine both arrays into a single array of size `m + n`.
2. Sort the combined array using `Arrays.sort()`.
3. Calculate the median based on whether the total length is even or odd.

## 📊 Complexity Analysis
- **Time Complexity:** $O((m+n) \log(m+n))$ due to the sorting step.
- **Space Complexity:** $O(m+n)$ to store the merged array.

## 🛠️ How to Run
1. Clone the repository.
2. Compile the Java file: `javac Solution.java`.

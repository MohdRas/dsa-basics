# dsa  - basics


# Array & Hashing 

  - https://neetcode.io/courses/dsa-for-beginners/2 static array
  - first element  - a[0]
  - last element  - a[n-1]
  - delete from the end -> O(1) --->>> length = length - 1 and a[n-1] = null/0/-1
  - delete the kth element -> O(n) --->>> shift one position to left. 
  - length = length - 1 and i = K....n-2, a[i] = a[i+1]
  - insert at the end(index k) -> O(1)  ---->>> length = length + 1, a[n-1] = new_element
  - insert the kth element -> O(n) -->>> shift one position to right. 
- length = length + 1 and  i = n-2....k, a[i+1] = a[i]
   
- https://neetcode.io/courses/dsa-for-beginners/3 dynamic array
 - variable default_capacity = when array is creted first time (10 arraylist in java )
 - variable length -  total number of elements
 - variable capacity - max number of elements an array can hold.
 - (length-1)th index element - last element

- Resizing - create arr2(n2) of 1.5 times of capacity of arr1 . copy arr1 to arr2. [ 0 -> (n1-1)]
- add new element at arr2[n1] = new_element and increment length by 1
 - assign new array back to original array - arr1 = arr2;
  - https://neetcode.io/courses/dsa-for-beginners/26 Hash Usage
 -  avearge case time complexity - O(1) for add, remove, search in HashSet/HashMap. it is average case time complexity but We assume it as worst case, that why write it as Big O notation.
  - O(logn) for add. remove, seach in TreeMap ( Red-Black Tree, a self balancing BST). Keys are sorted in ascending order.
- No dupliate keys in HashSet/HashMap/TreeMap.
  - https://neetcode.io/courses/advanced-algorithms/6 Trie
  - https://neetcode.io/courses/advanced-algorithms/3 Two pointer
  - https://neetcode.io/courses/dsa-for-beginners/27 Hash Implementation
  - https://neetcode.io/courses/dsa-for-beginners/34 Bit Operations
  - https://neetcode.io/courses/dsa-for-beginners/11 Merge sort
  - https://neetcode.io/courses/dsa-for-beginners/12 Quick Sort
   - https://neetcode.io/courses/dsa-for-beginners/13 Bucket sort
  - https://neetcode.io/courses/advanced-algorithms/4 Prefix Sums
  - https://neetcode.io/courses/dsa-for-beginners/22 Tree Maze Back Tracking
  - https://neetcode.io/courses/dsa-for-beginners/33 2-Dimentional DP

Problems   - 

  - Concatenation of Array   	
  - Contains Duplicate   	
  - Valid Anagram   	
  - Two Sum   	
  - Longest Common Prefix   	
  - Group Anagrams   	
  - Remove Element   	
  - Majority Element   	
  - Design HashSet	
  - Design HashMap	
  - Sort an Array   	
  - Sort Colors   	
  - Top K Frequent Elements   	
  - Encode and Decode Strings   	
  - Range Sum Query 2D Immutable	
  - Product of Array Except Self   	
  - Valid Sudoku   	
  - Longest Consecutive Sequence   	
  - Best Time to Buy And Sell Stock II   	
  - Majority Element II   	
  - Subarray Sum Equals K   	
  - First Missing Positive   


# Two Pointer   - 


  - https://neetcode.io/courses/dsa-for-beginners/26 Hash Usage
  - https://neetcode.io/courses/advanced-algorithms/3 Two Pointer
  -  -  https://neetcode.io/courses/dsa-for-beginners/2 static array
  - https://neetcode.io/courses/dsa-for-beginners/3 dynamic array


Problems

  - Reverse String   	
  - Valid Palindrome   	
  - Valid Palindrome II   	
  - Merge Strings Alternately   	
  - Merge Sorted Array   	
  - Remove Duplicates From Sorted Array   	
  - Two Sum II Input Array Is Sorted   	
  - 3Sum   	
  - 4Sum   	
  - Rotate Array   	
  - Container With Most Water   	
  - Boats to Save People   	
  - Trapping Rain Water


# Sliding Window   - 

  - https://neetcode.io/courses/advanced-algorithms/1 Sliding Window Fixed Size
  - https://neetcode.io/courses/advanced-algorithms/2 Sliding Window Variable Size
  - https://neetcode.io/courses/advanced-algorithms/4 Prefix Sum
  - https://neetcode.io/courses/dsa-for-beginners/14 Binary Search
  - https://neetcode.io/courses/advanced-algorithms/3 Two pointer
 -  https://neetcode.io/courses/dsa-for-beginners/26 Hash Usage
  - https://neetcode.io/courses/dsa-for-beginners/7 Queues



Problems

  - Contains Duplicate II   	
  - Best Time to Buy And Sell Stock   	
  - Longest Substring Without Repeating Characters   	
  - Longest Repeating Character Replacement   	
  - Permutation In String   	
  - Minimum Size Subarray Sum   	
  - Find K Closest Elements   	
  - Minimum Window Substring   	
  - Sliding Window Maximum   

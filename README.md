# -Longest-Consecutive-Sequence
Given an unsorted array of integers, return the length of the longest consecutive elements sequence.  Your algorithm should run in O(n) time complexity.
Explanation:
Use a HashSet to store all numbers for quick lookup.
Check if a number is the start of a sequence (i.e., num - 1 is not in the set).
If it's a starting number, expand the sequence by checking for num + 1 in the set.
Keep track of the longest sequence length and return the result.
Time Complexity:
O(N) in the average case, because each number is processed only once.
Space Complexity:
O(N) for storing elements in the HashSet.

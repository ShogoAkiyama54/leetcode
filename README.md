# LeetCode

This is the list of my accepted LeetCode solutions in Java for more than 100 problems (as of 10/29/2019).

## How to Read the List

+ The first column is the index number of each question in LeetCode.
+ The second column is the name of the problem. It is linked to each problem page in LeetCode.
+ The third column shows the problem's difficulty in LeetCode.<br/>
+ The forth column has my solutions for each problem. Each solution is linked to my Java code in this repository. The list of abbreviations in this section is provided bellow.
+ The fifth column shows the link to the JUnit test cases for the problem. "-" means I have not created test cases for the problem yet.
+ The last column is the date when I solved the problem last time.

## Abbreviations

DP = Dynamic Programming<br/>
D&C = Divide and Conquer<br/>
DFS = Depth First Search<br/>
BFS = Breadth First Search<br/>

## Note

\* = problems that can be improved in time or space complexity.<br/>
** = problems that I should revisit in the future because I spent too long on solving it. <br/>
*** = problems that have follow-up or different approaches.<br/>
^ = problems that I like.

## Java Solution List

| # | Problem Name | Difficulty | Solutions | Test Case | Last Solved |
| :---: | --- | --- | --- | :---: | :---: |
| 1 | [Two Sum*](https://leetcode.com/problems/two-sum/) | Easy | [Brute Force](/src/array/TwoSum.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L9-L17) | 08/13/2019 |
| 2 | [Add Two Numbers***](https://leetcode.com/problems/add-two-numbers/) | Medium | [Recursion](/src/linkedlist/AddTwoNumbers.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L8-L17) | 08/18/2019 |
| 3 | [Longest Substring Without Repeating Characters*](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | Medium | [Iteration](/src/string/LongestSubstringWithoutRepeatingCharacters.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L8-L19) | 08/19/2019 |
| 5 | [Longest Palindromic Substring*](https://leetcode.com/problems/longest-palindromic-substring/) | Medium | [Expand Around Center](/src/string/LongestPalindromicSubstring.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/b8b3ca5d91c55659a821bc7196d2209918c9ed20/src/string/StringTest.java#L21-L29) | 10/05/2019 |
| 9 | [Palindrome Number*](https://leetcode.com/problems/palindrome-number/) | Easy | [Recursion](/src/PalindromeNumber.java) | - | 08/18/2019 |
| 11 | [Container With Most Water**](https://leetcode.com/problems/container-with-most-water/) | Medium | [Two Pointers](/src/array/ContainerWithMostWater.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/08e6801562543da53abde38136e49206814da97e/src/array/ArrayTest.java#L20-L33) | 11/18/2019 |
| 13 | [Roman to Integer*](https://leetcode.com/problems/roman-to-integer/) | Easy | [Recursion](/src/string/RomanToInteger.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L31-L42) | 06/17/2019 |
| 17 | [Letter Combinations of a Phone Number*](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | Medium | [Recursion](/src/string/LetterCombinationsOfAPhoneNumber.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/7aa55c23775c6ec687e0c83c2d7f775b70c55180/src/string/StringTest.java#L50-L61) | 11/07/2019 |
| 19 | [Remove Nth Node From End of List**^](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) | Medium | [Recursion](/src/linkedlist/RemoveNthNodeFromEndOfList.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L19-L36) | 08/20/2019 |
| 20 | [Valid Parentheses*](https://leetcode.com/problems/valid-parentheses/) | Easy | [Recursion](/src/string/ValidParentheses.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L44-L54) | 06/13/2019 |
| 21 | [Merge Two Sorted Lists**](https://leetcode.com/problems/merge-two-sorted-lists/) | Easy | [Recursion](/src/linkedlist/MergeTwoSortedLists.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L38-L51) | 08/20/2019 |
| 23 | [Merge k Sorted Lists***](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | [D&C](/src/linkedlist/MergeKSortedLists.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L53-L68) | 08/27/2019 |
| 26 | [Remove Duplicates from Sorted Array**](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | [Two Pointers](/srs/array/RemoveDuplicatesFromSortedArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/ae10cda3dd549c7017b7efee38f9b0c9b3db38c5/src/array/ArrayTest.java#L20-L50) | 11/13/2019 |
| 33 | [Search in Rotated Sorted Array***](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Medium | [Recursion & BS](/src/array/SearchInRotatedSortedArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/cd26f2d73c132674c0f651d68aaf69fa1c9efffe/src/array/ArrayTest.java#L51-L69) | 11/16/2019 |
| 36 | [Valid Sudoku***](https://leetcode.com/problems/valid-sudoku/) | Medium | [Hash Table](/src/matrix/ValidSudoku.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/ca8d2afbbb385cecb410b6ff83a7c04746cbc267/src/matrix/MatrixTest.java#L11-L39) | 10/28/2019 |
| 39 | [Combination Sum*](https://leetcode.com/problems/combination-sum/) | Medium | [DFS](/src/array/CombinationSum.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L19-L37) | 08/29/2019 |
| 46 | [Permutations***](https://leetcode.com/problems/permutations/) | Medium | [Back Tracking](/src/array/Permutations.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/b8acbf2596204bb8d796afb28e49cb9194ceb4bc/src/array/ArrayTest.java#L9-L25) | 10/13/2019 |
| 48 | [Rotate Image***](https://leetcode.com/problems/rotate-image/) | Medium | [Layer by Layer](/src/matrix/RotateImage.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/75d67c8a23b01f70f1ab6f73bcd1c8197e8c1dc4/src/matrix/MatrixTest.java#L31-L44) | 09/29/2019 |
| 54 | [Spiral Matrix**](https://leetcode.com/problems/spiral-matrix/) | Medium | [Recursion](/src/matrix/SpiralMatrix.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/75d67c8a23b01f70f1ab6f73bcd1c8197e8c1dc4/src/matrix/MatrixTest.java#L46-L57) | 08/22/2019 |
| 55 | [Jump Game**^](https://leetcode.com/problems/jump-game/) | Medium | [Greedy](/src/array/JumpGame.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L57-L65) | 08/23/2019 |
| 56 | [Merge Intervals**](https://leetcode.com/problems/merge-intervals/) | Medium | [Recursion](/src/interval/MergeIntervals.java) | [interval](https://github.com/ShogoAkiyama54/LeetCode/blob/1688d26f6459d9685be9f76cc8dd0856b55280da/src/interval/IntervalTest.java#L9-L22) | 08/13/2019 |
| 62 | [Unique Paths**](/src/UniquePaths.java) | Medium |  | - |
| 70 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/) | Easy | [DP](/src/integer/ClimbingStairs.java) | [integer](https://github.com/ShogoAkiyama54/LeetCode/blob/1671edbaef3cce0f2e6b859b26f7048c73637772/src/integer/IntegerTest.java#L9-L21) | 08/14/2019 |
| 73 | [Set Matrix Zeroes***](https://leetcode.com/problems/set-matrix-zeroes/) | Medium | [O(M+N) space](/src/matrix/SetMatrixZeroes.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/75d67c8a23b01f70f1ab6f73bcd1c8197e8c1dc4/src/matrix/MatrixTest.java#L59-L72) | 08/13/2019 |
| 75 | [Sort Colors*](https://leetcode.com/problems/sort-colors/) | Medium | [Iteration Two Pass](/src/array/SortColors.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L67-L87) | 10/31/2019 |
| 76 | [Minimum Window Substring*](https://leetcode.com/problems/minimum-window-substring/) | Hard | [Sliding Window](/src/string/MinimumWindowSubstring.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L56-L65) | 09/24/2019 |
| 78 | [Subsets***](https://leetcode.com/problems/subsets/) | Medium | [Iteration](/src/array/Subsets.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/51db84759972153c394d9f35fd237f0e63843a4f/src/array/ArrayTest.java#L9-L27) | 10/10/2019 |
| 79 | [Word Search*](https://leetcode.com/problems/word-search/) | Medium | [DFS](/src/matrix/WordSearch.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/b8b3ca5d91c55659a821bc7196d2209918c9ed20/src/matrix/MatrixTest.java#L54-L64) | 08/22/2019 |
| 88 | [Merge Sorted Array*](https://leetcode.com/problems/merge-sorted-array/) | Easy | [Iteration](/src/array/MergeSortedArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/613236ac7d9c43fcb093426b693688db3cba008d/src/array/ArrayTest.java#L109-L138) | 11/03/2019 |
| 91 | [Decode Ways*](https://leetcode.com/problems/decode-ways/) | Medium | [D&C](/src/string/DecodeWays.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L67-L77) | 09/28/2019 |
| 92 | [Reverse Linked List II**](https://leetcode.com/problems/reverse-linked-list-ii/) | Medium | [Recursion](/src/linkedlist/ReverseLinkedListII.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L70-L78) | 08/18/2019 |
| 94 | [Binary Tree Inorder Traversal***](https://leetcode.com/problems/binary-tree-inorder-traversal/) | Medium | [Recursion](/src/binarytree/BinaryTreeInorderTraversal.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L9-L17) | 08/02/2019 |
| 98 | [Validate Binary Search Tree*](https://leetcode.com/problems/validate-binary-search-tree/) | Medium | [Inorder](/src/binarytree/ValidateBinarySearchTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L19-L29) | 08/18/2019 |
| 100 | [Same Tree](https://leetcode.com/problems/same-tree/) | Easy | [Recursion](/src/binarytree/SameTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L31-L45) | 08/13/2019 |
| 101 | [Symmetric Tree**](https://leetcode.com/problems/symmetric-tree/) | Easy | [Recursion](/src/binarytree/SymmetricTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/a9c949070463b50576d61c62dda58ed0801ed529/src/binarytree/BinaryTreeTest.java#L47-L61) | 11/04/2019 |
| 102 | [Binary Tree Level Order Traversal***](https://leetcode.com/problems/binary-tree-level-order-traversal/) | Medium | [Recursion](/src/binarytree/BinaryTreeLevelOrderTraversal.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L47-L59) | 08/18/2019 |
| 103 | [Binary Tree Zigzag Level Order Traversal**](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) | Medium | [BFS and Reverse](/src/binarytree/BinaryTreeZigzagLevelOrderTraversal.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/1671edbaef3cce0f2e6b859b26f7048c73637772/src/binarytree/BinaryTreeTest.java#L83-L105) | 11/11/2019 |
| 104 | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | Easy | [Recursion](/src/binarytree/MaximumDepthOfBinaryTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L61-L69) | 06/19/2019 |
| 105 | [Construct Binary Tree from Preorder and Inorder Traversal**](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | Medium | [Recursion](/src/binarytree/ConstructBinaryTreeFromPreorderAndInorderTraversal.java) / [Recursion (Opt)](/src/binarytree/ConstructBinaryTreeFromPreorderAndInorderTraversal2.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/37e5150471955f833ce615d99ebdd8c0e0093823/src/binarytree/BinaryTreeTest.java#L71-L87) | 10/17/2019 |
| 108 | [Convert Sorted Array to Binary Search Tree^](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | Easy | [Recursion](/src/binarytree/ConvertSortedArrayToBinarySearchTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L71-L80) | 06/17/2019 |
| 116 | [Populating Next Right Pointers in Each Node*](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) | Medium | [Stack](/src/PopulatingNextRightPointersInEachNode.java) | - | 11/16/2019 |
| 118 | [Pascal's Triangle***](https://leetcode.com/problems/pascals-triangle/) | Easy | [DP](/src/PascalsTriangle.java) | - | 10/29/2019 |
| 121 | [Best Time to Buy and Sell Stock*](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | Easy | [Iteration Two Pass](/src/array/BestTimeToBuyAndSellStock.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/883e9d0230629389f4c3d120133ee620fb755b48/src/array/ArrayTest.java#L47-L57) | 10/15/2019 |
| 122 | [Best Time to Buy and Sell Stock II*](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | Easy | [Iteration (Peak Valley)](/src/array/BestTimeToBuyAndSellStockII.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/8201c83bf16e94771e02fc389147a59850f3cc27/src/array/ArrayTest.java#L211-L225) | 11/16/2019 |
| 124 | [Binary Tree Maximum Path Sum***](https://leetcode.com/problems/binary-tree-maximum-path-sum/) | Hard | [Recursion](/src/binarytree/BinaryTreeMaximumPathSum.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L82-L96) | 10/07/2019 |
| 125 | [Valid Palindrome*](https://leetcode.com/problems/valid-palindrome/) | Easy | [2 Pointers](/src/string/ValidPalindrome.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L79-L92) | 08/30/2019 |
| 127 | [Word Ladder*](https://leetcode.com/problems/word-ladder/) | Medium | [BFS](/src/string/WordLadder.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/5f545d191f09b386ac911fea00a9cc01adaad620/src/string/StringTest.java#L117-L129) | 11/09/2019 |
| 128 | [Longest Consecutive Sequence*](https://leetcode.com/problems/longest-consecutive-sequence/) | Hard | [Hash Map with Class](/src/array/LongestConsecutiveSequence.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L121-L132) | 09/23/2019 |
| 133 | [Clone Graph](/src/CloneGraph.java) | Medium |  | - |
| 136 | [Single Number*](/src/SingleNumber.java) | Easy |  | - |
| 141 | [Linked List Cycle***](https://leetcode.com/problems/linked-list-cycle/) | Easy | [Recursion](/src/linkedlist/LinkedListCycle.java) / [Floyed's Cycle Detection](/src/linkedlist/LinkedListCycle2.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L80-L98) | 08/16/2019 |
| 143 | [Reorder List*](https://leetcode.com/problems/reorder-list/) | Medium | [Recursion](/src/linkedlist/ReorderList.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L100-L117) | 08/22/2019 |
| 145 | [Binary Tree Postorder Traversal***](https://leetcode.com/problems/binary-tree-postorder-traversal/) | Hard | [Recursion](/src/binarytree/BinaryTreePostorderTraversal.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L98-L106) | 06/11/2019 |
| 152 | [Maximum Product Subarray**](https://leetcode.com/problems/maximum-product-subarray/) | Medium | [D&C](/src/array/MaximumProductSubarray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L134-L142) | 09/27/2019 |
| 153 | [Find Minimum in Rotated Sorted Array***](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Medium | [Recursion](/src/array/FindMinimumInRotatedSortedArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L144-L154) | 08/28/2019 |
| 162 | [Find Peak Element**](https://leetcode.com/problems/find-peak-element/) | Medium | [Recursive Binary Search](/src/array/FindPeakElement.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/91cdab9cb5f7fa40fd350839c8dfb40c01c11483/src/array/ArrayTest.java#L198-L214) | 11/12/2019 |
| 169 | [Majority Element](/src/MajorityElement.java) | Easy |  | - |
| 171 | [Excel Sheet Column Number***](https://leetcode.com/problems/excel-sheet-column-number/) | Easy | [Iteration](/src/string/ExcelSheetColumnNumber.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/b1bcf37f8aae0bb47fdfe263aa092353062c0a51/src/string/StringTest.java#L94-L104) | 10/08/2019 |
| 198 | [House Robber](https://leetcode.com/problems/house-robber/) | Easy | [DP](/src/array/HouseRobber.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/7830b9a34bc6ff4c036b988dd51a1502052f39bd/src/array/ArrayTest.java#L59-L70) | 07/31/2019 |
| 200 | [Number of Islands*](https://leetcode.com/problems/number-of-islands/) | Medium | [DFS](/src/matrix/NumberOfIslands.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/75d67c8a23b01f70f1ab6f73bcd1c8197e8c1dc4/src/matrix/MatrixTest.java#L74-L86) | 10/04/2019 |
| 202 | [Happy Number*](https://leetcode.com/problems/happy-number/) | Easy | [Hash Set](/src/integer/HappyNumber.java) | [integer](https://github.com/ShogoAkiyama54/LeetCode/blob/fd157cbc344edc454f0866012a2702f720802591/src/integer/IntegerTest.java#L9-L22) | 11/10/2019 |
| 206 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Easy | [Iteration](/src/linkedlist/ReverseLinkedList.java) / [Recursion](/src/linkedlist/ReverseLinkedList2.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L119-L133) | 08/17/2019 |
| 207 | [Course Schedule**](/src/CourseSchedule.java) | Medium |  | - |
| 208 | [Implement Trie (Prefix Tree)***](https://leetcode.com/problems/implement-trie-prefix-tree/) | Medium | [Recursion](/src/string/Trie.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/e9d0fa1e7bd61f1212b1d0ac3d510469f391f0e4/src/string/StringTest.java#L106-L120) | 10/18/2019 |
| 211 | [Add and Search Word - Data structure design*](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | Medium | [Trie](/src/string/AddAndSearchWordDataStructureDesign.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L94-L108) | 10/03/2019 |
| 212 | [Word Search II*](https://leetcode.com/problems/word-search-ii/) | Hard | [DFS](/src/matrix/WordSearchII.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/1ee4e8d718f5ac598beee4010526ee4fc9f8dae3/src/matrix/MatrixTest.java#L79-L96) | 10/06/2019 |
| 213 | [House Robber II***](https://leetcode.com/problems/house-robber-ii/) | Medium | [DP](/src/array/HouseRobberII.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/af01f32628f1a16d041c99deb0cda6f9b0285d9a/src/array/ArrayTest.java#L59-L71) | 10/16/2019 |
| 215 | [Kth Largest Element in an Array***](https://leetcode.com/problems/kth-largest-element-in-an-array/) | Medium | [Sort](/src/array/KthLargestElementInAnArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/75c4bb4b28f4460d6b11b729afca1667ec3fd841/src/array/ArrayTest.java#L86-L94) | 10/27/2019 |
| 217 | [Contains Duplicate***](https://leetcode.com/problems/contains-duplicate/) | Easy | [Hash Table](/src/array/ContainsDuplicate.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L193-L202) | 08/27/2019 |
| 226 | [Invert Binary Tree***](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | Easy | [Recursion](/src/binarytree/InvertBinaryTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L108-L117) | 08/18/2019 |
| 227 | [Basic Calculator II*](https://leetcode.com/problems/basic-calculator-ii/) | Medium | [Two Lists](/src/string/BasicCalculatorII.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/165488913c8f83b155bbfcbb851e1d5f2b6e631c/src/string/StringTest.java#L138-L147) | 11/05/2019 |
| 230 | [Kth Smallest Element in a BST***](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) | Medium | [Recursion](/src/binarytree/KthSmallestElementInABST.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L119-L130) | 08/27/2019 |
| 235 | [Lowest Common Ancestor of a Binary Search Tree***](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | Easy | [Recursion](/src/binarytree/LowestCommonAncestorOfABinarySearchTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L132-L144) | 08/28/2019 |
| 242 | [Valid Anagram*](https://leetcode.com/problems/valid-anagram/) | Easy | [Sort](/src/string/ValidAnagram.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L110-L119) | 08/02/2019 |
| 260 | [Single Number III*](/src/SingleNumberIII.java) | Medium |  | - |
| 268 | [Missing Number***](https://leetcode.com/problems/missing-number/) | Easy | [Formula](/src/array/MissingNumber.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L204-L214) | 08/29/2019 |
| 279 | [Perfect Squares*](https://leetcode.com/problems/perfect-squares/) | Medium | [DP](/src/integer/PerfectSquares.java) | [integer](https://github.com/ShogoAkiyama54/LeetCode/blob/092859da0454e45cebbccaf0e23ec1fd9ca8a279/src/integer/IntegerTest.java#L9-L21) | 11/06/2019 |
| 283 | [Move Zeroes](/src/MoveZeroes.java) | Easy |  | - |
| 287 | [Find the Duplicate Number*^](https://leetcode.com/problems/find-the-duplicate-number/) | Medium | [Brute Force](/src/array/FindTheDuplicateNumber.java) / [Floyd's Cycle Detection](/src/array/FindTheDuplicateNumber2.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L216-L232) | 10/01/2019 |
| 295 | [Find Median from Data Stream*](https://leetcode.com/problems/find-median-from-data-stream/) | Hard | [Sort](/src/array/FindMedianFromDataStream.java) / [Insertion Sort](/src/array/FindMedianFromDataStream2.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/d70103a0f1b7d134d2962303ccfd65e08b043a9b/src/array/ArrayTest.java#L9-L39) | 10/09/2019 |
| 297 | [Serialize and Deserialize Binary Tree*](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | Hard | [Iteration](/src/binarytree/SerializeAndDeserializeBinaryTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L146-L162) | 09/27/2019 |
| 300 | [Longest Increasing Subsequence*](https://leetcode.com/problems/longest-increasing-subsequence/) | Medium | [DP](/src/array/LongestIncreasingSubsequence.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L266-L274) | 09/26/2019 |
| 322 | [Coin Change](https://leetcode.com/problems/coin-change/) | Medium | [DP](/src/array/CoinChange.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/f3e3b9046a5c9b6b8b34ef91ecdc789081fe24d1/src/array/ArrayTest.java#L118-L127) | 08/15/2019 |
| 328 | [Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/) | Medium | [Iteration](/src/linkedlist/OddEvenLinkedList.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L135-L143) | 08/02/2019 |
| 344 | [Reverse String](https://leetcode.com/problems/reverse-string/) | Easy | [Iteration](/src/string/ReverseString.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L121-L135) | 06/11/2018 |
| 347 | [Top K Frequent Elements***](https://leetcode.com/problems/top-k-frequent-elements/) | Medium | [Map](/src/array/TopKFrequentElements.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L287-L296) | 08/27/2019 |
| 349 | [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Easy | [Two Sets](/src/array/IntersectionOfTwoArrays.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/71940da22cc70ad84c6ba1bc488ae48720307d95/src/array/ArrayTest.java#L298-L311) | 08/19/2019 |
| 350 | [Intersection of Two Arrays II*](https://leetcode.com/problems/intersection-of-two-arrays-ii/) | Easy | [Map & Iteration](/src/array/IntersectionOfTwoArraysII.java) / [2 Maps](/src/array/IntersectionOfTwoArraysII2.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/59a99ed6d738c8705b6abe2450b91e0bb0a684a7/src/array/ArrayTest.java#L129-L141) | 10/25/2019 |
| 387 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Easy | [Iteration](/src/string/FirstUniqueCharacterInAString.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/647d3b1266112958ea994ebf1fec7c6645a20dad/src/string/StringTest.java#L165-L178) | 10/21/2019 |
| 412 | [Fizz Buzz*](/src/FizzBuzz.java) | Easy |  | - |
| 417 | [Pacific Atlantic Water Flow**](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Medium | [DFS](/src/matrix/PacificAtlanticWaterFlow.java) | [matrix](https://github.com/ShogoAkiyama54/LeetCode/blob/75d67c8a23b01f70f1ab6f73bcd1c8197e8c1dc4/src/matrix/MatrixTest.java#L88-L101) | 10/02/2019 |
| 424 | [Longest Repeating Character Replacement*](https://leetcode.com/problems/longest-repeating-character-replacement/) | Medium | [Sliding Window](/src/string/LongestRepeatingCharacterReplacement.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/e78757faa822da45af05c5bee8dfa90687608a9f/src/string/StringTest.java#L165-L177) | 10/20/2019 |
| 435 | [Non-overlapping Intervals*](https://leetcode.com/problems/non-overlapping-intervals/) | Medium | [Greedy](/src/interval/NonOverlappingIntervals.java) | [interval](https://github.com/ShogoAkiyama54/LeetCode/blob/1688d26f6459d9685be9f76cc8dd0856b55280da/src/interval/IntervalTest.java#L24-L38) | 10/14/2019 |
| 445 | [Add Two Numbers II***](https://leetcode.com/problems/add-two-numbers-ii/) | Medium | [Recursion](/src/linkedlist/AddTwoNumbersII.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L145-L154) | 06/14/2019 |
| 448 | [Find All Numbers Disappeared in an Array**](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) | Easy | [Mark by Negativing](/src/array/FindAllNumbersDisappearedInAnArray.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/ef72a03826c76b930d60e51e5f754b6be285b93f/src/array/ArrayTest.java#L486-L508) | 11/17/2019 |
| 461 | [Hamming Distance*](/src/HammingDistance.java) | Easy |  | - |
| 508 | [Most Frequent Subtree Sum*](https://leetcode.com/problems/most-frequent-subtree-sum/) | Medium | [Recursion](src/binarytree/MostFrequentSubtreeSum.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L164-L179) | 06/12/2019 |
| 509 | [Fibonacci Number](src/FibonacciNumber.java) | Easy |  | - |
| 543 | [Diameter of Binary Tree***](https://leetcode.com/problems/diameter-of-binary-tree/) | Easy | [Recursion](/src/binarytree/DiameterOfBinaryTree.java) | [binarytree] | 11/20/2019 |
| 547 | [Friend Circles*](/src/FriendCircles.java) | Medium |  | - |
| 572 | [Subtree of Another Tree***](https://leetcode.com/problems/subtree-of-another-tree/) | Easy | [Recursion](/src/binarytree/SubtreeOfAnotherTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L181-L195) | 08/29/2019 |
| 617 | [Merge Two Binary Trees***](https://leetcode.com/problems/merge-two-binary-trees/) | Easy | [Recursion](/src/binarytree/MergeTwoBinaryTrees.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/63f4f934bcf931321d5d928f1812f8ecd0642a9d/src/binarytree/BinaryTreeTest.java#L275-L296) | 11/14/2019 |
| 647 | [Palindromic Substrings*](https://leetcode.com/problems/palindromic-substrings/) | Medium | [DP](/src/string/PalindromicSubstrings.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/3d26543dc490b360dbc1869aaad2f1e509a0c212/src/string/StringTest.java#L149-L160) | 10/11/2019 |
| 654 | [Maximum Binary Tree*](https://leetcode.com/problems/maximum-binary-tree/) | Medium | [Recursion](/src/binarytree/MaximumBinaryTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L197-L208) | 09/30/2019 |
| 657 | [Robot Return to Origin](https://leetcode.com/problems/robot-return-to-origin/) | Easy | [Iteration](/src/string/RobotReturnToOrigin.java) / [Recursion](/src/string/RobotReturnToOrigin2.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L137-L151) | 08/18/2019 |
| 700 | [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/) | Easy | [Recursion](/src/binarytree/SearchInABinarySearchTree.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/16f4e7de8aaba29c3c45f455867bcd1c3a8e5b1b/src/binarytree/BinaryTreeTest.java#L210-L218) | 06/10/2019 |
| 876 | [Middle of the Linked List***](https://leetcode.com/problems/middle-of-the-linked-list/) | Easy | [Iteration](/src/linkedlist/MiddleOfTheLinkedList.java) | [linkedlist](https://github.com/ShogoAkiyama54/LeetCode/blob/80ab55c4232afddbfb6275356bea65e886d184ce/src/linkedlist/LinkedListTest.java#L156-L166) | 04/14/2019 |
| 905 | [Sort Array By Parity***](/src/SortArrayByParity.java) | Easy |  | O |
| 912 | [Sort An Array*](/src/SortAnArray.java) | Medium |  | - |
| 938 | [Range Sum of BST***](https://leetcode.com/problems/range-sum-of-bst/) | Easy | [Recursion](/src/binarytree/RangeSumOfBST.java) | [binarytree](https://github.com/ShogoAkiyama54/LeetCode/blob/f942cc977ef4851c364cacb3b3e35908521a55b5/src/binarytree/BinaryTreeTest.java#L238-L252) | 10/19/2019 |
| 980 | [Unique Paths III*](/src/UniquePathsIII.java) | Hard |  | - |
| 1003 | [Check If Word Is Valid After Substitutions*](https://leetcode.com/problems/check-if-word-is-valid-after-substitutions/) | Medium | [Recursion](/src/string/CheckIfWordIsValidAfterSubstitutions.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L153-L164) | 06/13/2019 |
| 1047 | [Remove All Adjacent Duplicates In String*](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) | Easy | [Recursion](/src/string/RemoveAllAdjacentDuplicatesInString.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L166-L174) | 06/12/2019 |
| 1053 | [Previous Permutation With One Swap*](/src/PreviousPermutationWithOneSwap.java) | Medium |  | - |
| 1078 | [Occurrences After Bigram](https://leetcode.com/problems/occurrences-after-bigram/) | Easy | [Iteration](/src/string/OccurrencesAfterBigram.java) | [string](https://github.com/ShogoAkiyama54/LeetCode/blob/d96d5b3d7578a3d5437bff1644c8a7a8328166cd/src/string/StringTest.java#L176-L185) | 06/15/2019 |
| 1207 | [Unique Number of Occurrences*](https://leetcode.com/problems/unique-number-of-occurrences/) | Easy | [Map](/src/array/UniqueNumberOfOccurrences.java) | [array](https://github.com/ShogoAkiyama54/LeetCode/blob/a1dc948aa56e2f21c6f014d4d5f5bd490c45c332/src/array/ArrayTest.java#L129-L138) | 10/24/2019 |



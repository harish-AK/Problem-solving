# Leetcode-Problems

      1. Two sum problem - Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
      
      Input: nums = [2,7,11,15], target = 9
      Output: [0,1]
      Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].

-----------------------------------------------------------------------------------------------------------------------------------------------------------
      
      2.Given an integer x, return true if x is a 
      palindrome, and false otherwise.
      
      Example 1:
      Input: x = 121
      Output: true
      Explanation: 121 reads as 121 from left to right and from right to left.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      
      3.Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.
      Symbol       Value
      I             1
      V             5
      X             10
      L             50
      C             100
      D             500
      M             1000
      
      Example 2:
      Input: s = "LVIII"
      Output: 58
      Explanation: L = 50, V= 5, III = 3.

------------------------------------------------------------------------------------------------------------------------------------------------------------
      
      
      4. Remove duplicates in a sorted array (2 poiter used to solve this problem)
      Given an integer array nums sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. 
      The relative order of the elements should be kept the same. Then return the number of unique elements in nums.
      Consider the number of unique elements of nums to be k, to get accepted, you need to do the following things:
      Change the array nums such that the first k elements of nums contain the unique elements in the order they were present in nums initially. 
      The remaining elements of nums are not important as well as the size of nums.
      Return k.
      
      Example 1:
      Input: nums = [1,1,2]
      Output: 2, nums = [1,2,_]
      Explanation: Your function should return k = 2, with the first two elements of nums being 1 and 2 respectively.
      It does not matter what you leave beyond the returned k (hence they are underscores).

------------------------------------------------------------------------------------------------------------------------------------------------------------

      
      5.Write a function to find the longest common prefix string amongst an array of strings.If there is no common prefix, return an empty string "".
      
      Example 1:
      Input: strs = ["flower","flow","flight"]
      Output: "fl"
      
      Example 2:
      Input: strs = ["dog","racecar","car"]
      Output: ""
      Explanation: There is no common prefix among the input strings.


------------------------------------------------------------------------------------------------------------------------------------------------------------

      
      6.Convert integer to roman, For example, 2 is written as II in Roman numeral, just two one's added together. 12 is written as XII, which is simply X + II. 
      The number 27 is written as XXVII, which is XX + V + II.
      
      Example 1:
      Input: num = 3
      Output: "III"
      Explanation: 3 is represented as 3 ones.

------------------------------------------------------------------------------------------------------------------------------------------------------------
      7.Remove element
      Given an integer array nums and an integer val, remove all occurrences of val in nums in-place. 
      The order of the elements may be changed. Then return the number of elements in nums which are not equal to val.
      
      Example 1:
      Input: nums = [3,2,2,3], val = 3
      Output: 2, nums = [2,2,_,_]
      Explanation: Your function should return k = 2, with the first two elements of nums being 2.
      It does not matter what you leave beyond the returned k (hence they are underscores).
------------------------------------------------------------------------------------------------------------------------------------------------------------
      8.Find the index of the first occurrence in a string
      Given two strings needle and haystack, return the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.
      
      Example 1:
      Input: haystack = "sadbutsad", needle = "sad"
      Output: 0
      Explanation: "sad" occurs at index 0 and 6.
      The first occurrence is at index 0, so we return 0
------------------------------------------------------------------------------------------------------------------------------------------------------------

      9.Length of last word
      Given a string s consisting of words and spaces, return the length of the last word in the string.# A word is a maximal  substring
      consisting of non-space characters only.
      
      Example 1:
      Input: s = "Hello World"
      Output: 5
      Explanation: The last word is "World" with length 5.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      10.Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.
      
      Example 1:
      Input: nums = [1,3,5,6], target = 5
      Output: 2
      
      Example 2:
      Input: nums = [1,3,5,6], target = 2
      Output: 1
------------------------------------------------------------------------------------------------------------------------------------------------------------

      11.You are given a large integer represented as an integer array digits, where each digits[i] is the ith digit of the integer. 
      The digits are ordered from most significant to least significant in left-to-right order. The large integer does not contain any leading 0's
      
      Example 1:
      Input: digits = [1,2,3]
      Output: [1,2,4]
      Explanation: The array represents the integer 123.
      Incrementing by one gives 123 + 1 = 124.
      Thus, the result should be [1,2,4]

------------------------------------------------------------------------------------------------------------------------------------------------------------
      12.Valid paranthesis
      Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.
      An input string is valid if:
      Open brackets must be closed by the same type of brackets.
      Open brackets must be closed in the correct order.
      Every close bracket has a corresponding open bracket of the same type.
       
      Example 1:
      Input: s = "()"
      Output: true
------------------------------------------------------------------------------------------------------------------------------------------------------------
      A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters            include letters and numbers. Given a string s, return true if it is a palindrome, or false otherwise.
      
      Example 1:
      Input: s = "A man, a plan, a canal: Panama"
      Output: true
      Explanation: "amanaplanacanalpanama" is a palindrome.
      
      Example 2:
      Input: s = "race a car"
      Output: false
      Explanation: "raceacar" is not a palindrome.
      
------------------------------------------------------------------------------------------------------------------------------------------------------------



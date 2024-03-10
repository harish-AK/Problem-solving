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
      13.A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters         include letters and numbers. Given a string s, return true if it is a palindrome, or false otherwise.
      
      Example 1:
      Input: s = "A man, a plan, a canal: Panama"
      Output: true
      Explanation: "amanaplanacanalpanama" is a palindrome.
      
      Example 2:
      Input: s = "race a car"
      Output: false
      Explanation: "raceacar" is not a palindrome.
      
------------------------------------------------------------------------------------------------------------------------------------------------------------
      
      14.Given a non-empty array of integers nums, every element appears twice except for one. Find that single one.

      You must implement a solution with a linear runtime complexity and use only constant extra space.
      
      Example 1:
      Input: nums = [2,2,1]
      Output: 1

------------------------------------------------------------------------------------------------------------------------------------------------------------

      15.Given a non-negative integer x, return the square root of x rounded down to the nearest integer. 
      The returned integer should be non-negative as well
      You must not use any built-in exponent function or operator.
      For example, do not use pow(x, 0.5) in c++ or x ** 0.5 in python.
       
      Example 1:
      Input: x = 4
      Output: 2
      Explanation: The square root of 4 is 2, so we return 2.

------------------------------------------------------------------------------------------------------------------------------------------------------------
      16.Power of 2
      Given an integer n, return true if it is a power of two. Otherwise, return false.
      An integer n is a power of two, if there exists an integer x such that n == 2x.
      
      Example 1:
      Input: n = 1
      Output: true
      Explanation: 20 = 1

------------------------------------------------------------------------------------------------------------------------------------------------------------
      17.move zeros
      Given an integer array nums, move all 0's to the end of it while maintaining the relative order of the non-zero elements.
      Note that you must do this in-place without making a copy of the array.
      
      Example 1:
      Input: nums = [0,1,0,3,12]
      Output: [1,3,12,0,0]
------------------------------------------------------------------------------------------------------------------------------------------------------------
      18.sqrt of x
      Given a non-negative integer x, return the square root of x rounded down to the nearest integer. The returned integer should be non-negative as well.
      You must not use any built-in exponent function or operator.
      For example, do not use pow(x, 0.5) in c++ or x ** 0.5 in python.
       
      Example 1:
      Input: x = 4
      Output: 2
      Explanation: The square root of 4 is 2, so we return 2.

------------------------------------------------------------------------------------------------------------------------------------------------------------
      19.Given two integer arrays nums1 and nums2, return an array of their intersection. Each element in the result must be unique 
      and you may return the result in any order.
      
      Example 1:
      Input: nums1 = [1,2,2,1], nums2 = [2,2]
      Output: [2]
      
      Example 2:
      Input: nums1 = [4,9,5], nums2 = [9,4,9,8,4]
      Output: [9,4]
      Explanation: [4,9] is also accepted.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      20.Add digits
      Given an integer num, repeatedly add all its digits until the result has only one digit, and return it.
      
      Example 1:
      Input: num = 38
      Output: 2
      Explanation: The process is
      38 --> 3 + 8 --> 11
      11 --> 1 + 1 --> 2 
      Since 2 has only one digit, return it.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      21.Contains duplicate
      Given an integer array nums, return true if any value appears at least twice in the array, and return false if every element is distinct.
      
      Example 1:
      Input: nums = [1,2,3,1]
      Output: true
      
      Example 2:
      Input: nums = [1,2,3,4]
      Output: false

------------------------------------------------------------------------------------------------------------------------------------------------------------

      22.Valid Anagram
      Given two strings s and t, return true if t is an anagram of s, and false otherwise.
      An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.
      
      Example 1:
      Input: s = "anagram", t = "nagaram"
      Output: true
          
      Example 2:
      Input: s = "rat", t = "car"

------------------------------------------------------------------------------------------------------------------------------------------------------------

      23.Group Anagrams
      Given an array of strings strs, group the anagrams together. You can return the answer in any order.
      An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.
      
      Example 1:
      Input: strs = ["eat","tea","tan","ate","nat","bat"]
      Output: [["bat"],["nat","tan"],["ate","eat","tea"]]
      
      Example 2:
      Input: strs = [""]
      Output: [[""]]
------------------------------------------------------------------------------------------------------------------------------------------------------------

      24.Top K frequent elements
      Given an integer array nums and an integer k, return the k most frequent elements. You may return the answer in any order.
      
      Example 1:
      Input: nums = [1,1,1,2,2,3], k = 2
      Output: [1,2]  Cause 1 and 2 are the 2 most frequent elements appears in the array
      
      Example 2:
      Input: nums = [1], k = 1
      Output: [1]

------------------------------------------------------------------------------------------------------------------------------------------------------------
      25 product of array except self
      Given an integer array nums, return an array answer such that answer[i] is equal to the product of all the elements of nums except nums[i].
      The product of any prefix or suffix of nums is guaranteed to fit in a 32-bit integer.
      You must write an algorithm that runs in O(n) time and without using the division operation.
      
      Example 1:
      Input: nums = [1,2,3,4]
      Output: [24,12,8,6]
      
      Explanation:
      For the element at index 0 (value 1), the product of all other elements is 2 * 3 * 4 = 24.
      For the element at index 1 (value 2), the product of all other elements is 1 * 3 * 4 = 12.
      For the element at index 2 (value 3), the product of all other elements is 1 * 2 * 4 = 8.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      26.Longest commmon sequence
      Given an unsorted array of integers nums, return the length of the longest consecutive elements sequence.
      You must write an algorithm that runs in O(n) time.
      
      Example 1:
      Input: nums = [100,4,200,1,3,2]
      Output: 4
      Explanation: The longest consecutive elements sequence is [1, 2, 3, 4]. Therefore its length is 4.
      
      Example 2:
      Input: nums = [0,3,7,2,5,8,4,6,0,1]
      Output: 9

------------------------------------------------------------------------------------------------------------------------------------------------------------

      27. 2 sum II
      Given a 1-indexed array of integers numbers that is already sorted in non-decreasing order, find two numbers such that they add up to a specific target number. Let these two numbers be numbers[index1] and        numbers[index2] where 1 <= index1 < index2 <= numbers.length.
      Return the indices of the two numbers, index1 and index2, added by one as an integer array [index1, index2] of length 2.
      The tests are generated such that there is exactly one solution. You may not use the same element twice.
      Your solution must use only constant extra space.
      
      Example 1:
      Input: numbers = [2,7,11,15], target = 9
      Output: [1,2]
      Explanation: The sum of 2 and 7 is 9. Therefore, index1 = 1, index2 = 2. We return [1, 2].

------------------------------------------------------------------------------------------------------------------------------------------------------------






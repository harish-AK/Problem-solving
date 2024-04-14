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
      Given a 1-indexed array of integers numbers that is already sorted in non-decreasing order, find two numbers such that they add up to a specific target            number. Let these two numbers be numbers[index1] and numbers[index2] where 1 <= index1 < index2 <= numbers.length.
      Return the indices of the two numbers, index1 and index2, added by one as an integer array [index1, index2] of length 2.
      The tests are generated such that there is exactly one solution. You may not use the same element twice.
      Your solution must use only constant extra space.
      
      Example 1:
      Input: numbers = [2,7,11,15], target = 9
      Output: [1,2]
      Explanation: The sum of 2 and 7 is 9. Therefore, index1 = 1, index2 = 2. We return [1, 2].

------------------------------------------------------------------------------------------------------------------------------------------------------------


      28. 3 SumGiven an integer array nums, return all the triplets [nums[i], nums[j], nums[k]] such that i != j, i != k, and j != k, and nums[i] + nums[j] +            nums[k] == 0.
      Notice that the solution set must not contain duplicate triplets.
      
      Example 1:
      Input: nums = [-1,0,1,2,-1,-4]
      Output: [[-1,-1,2],[-1,0,1]]
      Explanation: 
      nums[0] + nums[1] + nums[2] = (-1) + 0 + 1 = 0.
      nums[1] + nums[2] + nums[4] = 0 + 1 + (-1) = 0.
      nums[0] + nums[3] + nums[4] = (-1) + 2 + (-1) = 0.
      The distinct triplets are [-1,0,1] and [-1,-1,2].
      Notice that the order of the output and the order of the triplets does not matter.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      29.tapping rain waterGiven n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after        raining.

      Example 1:
      Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]
      Output: 6
      Explanation: The above elevation map (black section) is represented by array

------------------------------------------------------------------------------------------------------------------------------------------------------------

      30.Reverse linked list
      input is [1,2,3,4,5]
      output is [5,4,3,2,1]

------------------------------------------------------------------------------------------------------------------------------------------------------------

      31.Min stack
      Design a stack that supports push, pop, top, and retrieving the minimum element in constant time.
      Implement the MinStack class:
      MinStack() initializes the stack object.
      void push(int val) pushes the element val onto the stack.
      void pop() removes the element on the top of the stack.
      int top() gets the top element of the stack.
      int getMin() retrieves the minimum element in the stack.
      You must implement a solution with O(1) time complexity for each function.
      
      Example 1:
      Input
      ["MinStack","push","push","push","getMin","pop","top","getMin"]
      [[],[-2],[0],[-3],[],[],[],[]]
      
      Output
      [null,null,null,null,-3,null,0,-2]

------------------------------------------------------------------------------------------------------------------------------------------------------------
      32.Climbing stairs
      You are climbing a staircase. It takes n steps to reach the top.
      Each time you can either climb 1 or 2 steps. In how many distinct ways can you climb to the top?
      
      Example 1:
      Input: n = 2
      Output: 2
      Explanation: There are two ways to climb to the top.
      1. 1 step + 1 step
      2. 2 steps

------------------------------------------------------------------------------------------------------------------------------------------------------------

      33.Happy number
      Write an algorithm to determine if a number n is happy.
      A happy number is a number defined by the following process:
      Starting with any positive integer, replace the number by the sum of the squares of its digits.
      Repeat the process until the number equals 1 (where it will stay), or it loops endlessly in a cycle which does not include 1.
      Those numbers for which this process ends in 1 are happy.
      Return true if n is a happy number, and false if not.
      
      Example 1:
      Input: n = 19
      Output: true
      Explanation:
      12 + 92 = 82
      82 + 22 = 68
      62 + 82 = 100
      12 + 02 + 02 = 1
------------------------------------------------------------------------------------------------------------------------------------------------------------

      34.Third maximum number
      Given an integer array nums, return the third distinct maximum number in this array. If the third maximum does not exist, return the maximum number.
      
      Example 1:
      Input: nums = [3,2,1]
      Output: 1
      Explanation:
      The first distinct maximum is 3.
      The second distinct maximum is 2.
      The third distinct maximum is 1.

------------------------------------------------------------------------------------------------------------------------------------------------------------

      35.To lower
      Given a string s, return the string after replacing every uppercase letter with the same lowercase letter.
      
      Example 1:
      Input: s = "Hello"
      Output: "hello"
------------------------------------------------------------------------------------------------------------------------------------------------------------

      36.Repeated Sub string pattern
      Given a string s, check if it can be constructed by taking a substring of it and appending multiple copies of the substring together.
      
      Example 1:
      Input: s = "abab"
      Output: true
      Explanation: It is the substring "ab" twice.
------------------------------------------------------------------------------------------------------------------------------------------------------------

      37.There are n packs where the ith pack contains apple[i] apples. There are m boxes as well, and the ith box has a capacity of capacity[i] apples.
      Return the minimum number of boxes you need to select to redistribute these n packs of apples into boxes.
      Note that, apples from the same pack can be distributed into different boxes.
      
      Example 1:
      Input: apple = [1,3,2], capacity = [4,3,1,5,2]
      Output: 2
      Explanation: We will use boxes with capacities 4 and 5.
      It is possible to distribute the apples as the total capacity is greater than or equal to the total number of apples.
------------------------------------------------------------------------------------------------------------------------------------------------------------
      38.Reverse string
      Write a function that reverses a string. The input string is given as an array of characters s.
      You must do this by modifying the input array in-place with O(1) extra memory.
      
      Example 1:
      Input: s = ["h","e","l","l","o"]
      Output: ["o","l","l","e","h"]
------------------------------------------------------------------------------------------------------------------------------------------------------------
      39.Distribute money to maximum children
      You are given an integer money denoting the amount of money (in dollars) that you have and another integer children denoting the number of children that you must distribute the money to.
      You have to distribute the money according to the following rules:
      All money must be distributed.
      Everyone must receive at least 1 dollar.
      Nobody receives 4 dollars.
      Return the maximum number of children who may receive exactly 8 dollars if you distribute the money according to the aforementioned rules. If there is no way to distribute the money, return -1.
      
      Example 1:
      Input: money = 20, children = 3
      Output: 1
      Explanation: 
      The maximum number of children with 8 dollars will be 1. One of the ways to distribute the money is:
      - 8 dollars to the first child.
      - 9 dollars to the second child. 
      - 3 dollars to the third child.
      It can be proven that no distribution exists such that number of children getting 8 dollars is greater than 1.
------------------------------------------------------------------------------------------------------------------------------------------------------------
      40.Find maximum divisibility score
      You are given two 0-indexed integer arrays nums and divisors.
      The divisibility score of divisors[i] is the number of indices j such that nums[j] is divisible by divisors[i].
      Return the integer divisors[i] with the maximum divisibility score. If there is more than one integer with the maximum score, return the minimum of them.
      
      
      Example 1:
      Input: nums = [4,7,9,3,9], divisors = [5,2,3]
      Output: 3
      Explanation: The divisibility score for every element in divisors is:
      The divisibility score of divisors[0] is 0 since no number in nums is divisible by 5.
      The divisibility score of divisors[1] is 1 since nums[0] is divisible by 2.
      The divisibility score of divisors[2] is 3 since nums[2], nums[3], and nums[4] are divisible by 3.
      Since divisors[2] has the maximum divisibility score, we return it.
------------------------------------------------------------------------------------------------------------------------------------------------------------
      41.Find the distinct difference array

      Example 1:
      Input: nums = [1,2,3,4,5]
      Output: [-3,-1,1,3,5]
      Explanation: For index i = 0, there is 1 element in the prefix and 4 distinct elements in the suffix. Thus, diff[0] = 1 - 4 = -3.
      For index i = 1, there are 2 distinct elements in the prefix and 3 distinct elements in the suffix. Thus, diff[1] = 2 - 3 = -1.
      For index i = 2, there are 3 distinct elements in the prefix and 2 distinct elements in the suffix. Thus, diff[2] = 3 - 2 = 1.
      For index i = 3, there are 4 distinct elements in the prefix and 1 distinct element in the suffix. Thus, diff[3] = 4 - 1 = 3.
      For index i = 4, there are 5 distinct elements in the prefix and no elements in the suffix. Thus, diff[4] = 5 - 0 = 5.
------------------------------------------------------------------------------------------------------------------------------------------------------------
      42.Reverse a integer
      Given a signed 32-bit integer x, return x with its digits reversed. If reversing x causes the value to go outside the signed 32-bit integer range [-231, 231 - 1], then return 0.
      Assume the environment does not allow you to store 64-bit integers (signed or unsigned).
      
      Example 1:
      Input: x = 123
      Output: 321
------------------------------------------------------------------------------------------------------------------------------------------------------------
      43.Divide 2 integers
      Given two integers dividend and divisor, divide two integers without using multiplication, division, and mod operator.
      The integer division should truncate toward zero, which means losing its fractional part. For example, 8.345 would be truncated to 8, and -2.7335 would be truncated to -2.
      Return the quotient after dividing dividend by divisor.
      Note: Assume we are dealing with an environment that could only store integers within the 32-bit signed integer range: [−231, 231 − 1]. For this problem, if the quotient is strictly greater than 231 -            1,then return 231 - 1, and if the quotient is strictly less than -231, then return -231.
      
      Example 1:
      Input: dividend = 10, divisor = 3
      Output: 3
      Explanation: 10/3 = 3.33333.. which is truncated to 3.

------------------------------------------------------------------------------------------------------------------------------------------------------------
      44.longest substring without repeating characters.
      Given a string s, find the length of the longest substring without repeating characters.
      
      Example 1:
      Input: s = "abcabcbb"
      Output: 3
      Explanation: The answer is "abc", with the length of 3.
------------------------------------------------------------------------------------------------------------------------------------------------------------
       45. String to integer
       Implement the myAtoi(string s) function, which converts a string to a 32-bit signed integer (similar to C/C++'s atoi function).
       The algorithm for myAtoi(string s) is as follows:
       Read in and ignore any leading whitespace.
       Check if the next character (if not already at the end of the string) is '-' or '+'. Read this character in if it is either. This determines if the final result is negative or positive respectively. Assume the result is positive if neither is present.
       Read in next the characters until the next non-digit character or the end of the input is reached. The rest of the string is ignored.
       Convert these digits into an integer (i.e. "123" -> 123, "0032" -> 32). If no digits were read, then the integer is 0. Change the sign as necessary (from step 2).
       If the integer is out of the 32-bit signed integer range [-231, 231 - 1], then clamp the integer so that it remains in the range. Specifically, integers less than -231 should be clamped to -231, and integers greater than 231 - 1 should be clamped to 231 - 1.
       Return the integer as the final result.
       Note:
      
       Only the space character ' ' is considered a whitespace character.
       Do not ignore any characters other than the leading whitespace or the rest of the string after the digits.
       
       Example 1:
       Input: s = "42"
       Output: 42
       Explanation: The underlined characters are what is read in, the caret is the current reader position.
       Step 1: "42" (no characters read because there is no leading whitespace)
                ^
       Step 2: "42" (no characters read because there is neither a '-' nor '+')
                ^
      Step 3: "42" ("42" is read in)
             ^
      The parsed integer is 42.
      Since 42 is in the range [-231, 231 - 1], the final result is 42.
      

------------------------------------------------------------------------------------------------------------------------------------------------------------
      
      46.POW(x,n)
      Implement pow(x, n), which calculates x raised to the power n (i.e., xn).
      
      Example 1:
      Input: x = 2.00000, n = 10
      Output: 1024.00000
------------------------------------------------------------------------------------------------------------------------------------------------------------
      47.Longest word in dictionary
      Given an array of strings words representing an English Dictionary, return the longest word in words that can be built one character at a time by other words in words.
      If there is more than one possible answer, return the longest word with the smallest lexicographical order. If there is no answer, return the empty string.
      Note that the word should be built from left to right with each additional character being added to the end of a previous word. 
      
      Example 1:
      Input: words = ["w","wo","wor","worl","world"]
      Output: "world"
      Explanation: The word "world" can be built one character at a time by "w", "wo", "wor", and "worl".

------------------------------------------------------------------------------------------------------------------------------------------------------------
      48.Multiply srings
      Given two non-negative integers num1 and num2 represented as strings, return the product of num1 and num2, also represented as a string.
      Note: You must not use any built-in BigInteger library or convert the inputs to integer directly.
      
      Example 1:
      Input: num1 = "2", num2 = "3"
      Output: "6"
------------------------------------------------------------------------------------------------------------------------------------------------------------
      49.Sort colors
      Given an array nums with n objects colored red, white, or blue, sort them in-place so that objects of the same color are adjacent, with the colors in the order red, white, and blue.
      We will use the integers 0, 1, and 2 to represent the color red, white, and blue, respectively.
      You must solve this problem without using the library's sort function.
      
      Example 1:
      Input: nums = [2,0,2,1,1,0]
      Output: [0,0,1,1,2,2]
------------------------------------------------------------------------------------------------------------------------------------------------------------
      50.find all duplicates in the array
      Given an integer array nums of length n where all the integers of nums are in the range [1, n] and each integer appears once or twice, return an array of all the integers that appears twice.
      You must write an algorithm that runs in O(n) time and uses only constant extra space.
      Example 1:
      Input: nums = [4,3,2,7,8,2,3,1]
      Output: [2,3]
------------------------------------------------------------------------------------------------------------------------------------------------------------


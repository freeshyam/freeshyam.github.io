---
title: Study list
permalink: /
---

Current stage: Benchmarking performance on a variety of problems

## Arrays and Strings
- Implement an algorithm to determine if a string has all unique characters. What if you can not use additional data structures? (CTCI 1.1)
- Design an algorithm and write code to remove the duplicate characters in a string without using any additional buffer. Note: One or two additional variables are fine. An extra copy of the array is not. (CTCI 1.3)
- Write a method to replace all spaces in a string with ‘%20’. (CTCI 1.5)
- Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column is set to 0. (CTCI 1.7)
- [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/description/) (EPI 6.7, LC 17)

## Linked Lists
- Write code to remove duplicates from an unsorted linked list. Follow-up: how would you solve this problem if a temporary buffer is not allowed? (CTCI 2.1)
- Implement an algorithm to find the nth to last element of a singly linked list. (CTCI 2.2)
- Implement an algorithm to delete a node in the middle of a singly linked list, given only access to that node. (CTCI 2.3)

## Stacks and Queues
- How would you design a stack which, in addition to push and pop, also has a function min which returns the minimum element? Push, pop and min should all operate in O(1) time. (CTCI 3.2)
- Implement a MyQueue class which implements a queue using two stacks. (CTCI 3.5)

## Trees and Graphs
- Implement a function to check if a tree is balanced. For the purposes of this question, a balanced tree is defined to be a tree such that no two leaf nodes differ in distance from the root by more than one. (CTCI 4.1)
- Given a directed graph, design an algorithm to find out whether there is a route between two nodes. (CTCI 4.2)
- Given a sorted (increasing order) array, write an algorithm to create a binary tree with minimal height. (CTCI 4.3)
- Design an algorithm and write code to find the first common ancestor of two nodes in a binary tree. Avoid storing additional nodes in a data structure. Note: This is not necessarily a binary search tree. (CTCI 4.6)

## Bit Manipulation
- Explain what the following code does: `((n & (n - 1)) == 0)`. (CTCI 5.4)
- Write a program to swap odd and even bits in an integer with as few instructions as possible (e.g., bit 0 and bit 1 are swapped, bit 2 and bit 3 are swapped, etc). (CTCI 5.6)

## Recursion
- Write a method to generate the nth Fibonacci number. (CTCI 8.1)
- [Unique Paths](https://leetcode.com/problems/unique-paths/description/) (LC 62, CTCI 8.2)
- Implement an algorithm to print all valid (i.e. properly opened and closed) combinations of n-pairs of parentheses. (CTCI 8.5, EPI 15.6, LC 22)
  ```
  input: 3 (3 pairs of parentheses)
  output: ()()(), ()(()), (())(), ((())), (()())
  ```

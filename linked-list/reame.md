# Add Two Numbers — LeetCode #2

## Problem

You are given two non-empty linked lists representing two non-negative integers.

* Digits are stored in **reverse order**
* Each node contains a **single digit**
* Add the two numbers and return the sum as a linked list

### Example

Input:

l1 = [2,4,3]
l2 = [5,6,4]

Output:

[7,0,8]

Explanation:

342 + 465 = 807

---

## Approach

1. Create a **dummy node** to build result list.

2. Traverse both linked lists simultaneously.

3. Extract current values from both lists.

4. Add:

   current digit from l1 + current digit from l2 + carry

5. Compute:

   * `digit = sum % 10`
   * `carry = sum / 10`

6. Create a new node with `digit`.

7. Move pointers forward.

8. Continue until both lists and carry are exhausted.

---

## Complexity

* Time Complexity: **O(n)**
* Space Complexity: **O(n)**

Where `n` is the number of nodes.

---

## Concepts Learned

* Linked List Traversal
* Dummy Node Technique
* Constructor Usage in C++
* Carry Handling
* Dynamic Memory Allocation (`new`)

---

## My Learning Notes

This problem helped me understand:

* How linked lists work internally
* Why dummy nodes are useful
* How constructors initialize objects
* How carry is handled in addition

This is my second solved LeetCode problem in C++ 🚀

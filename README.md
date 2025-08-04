# Maximum Twin Sum of a Linked List

## Problem Description

In a linked list of size `n`, where `n` is even, the `i`<sup>th</sup> node (0-indexed) is known as the **twin** of the `(n - 1 - i)`<sup>th</sup> node, if `0 <= i <= (n / 2) - 1`.

The **twin sum** is defined as the **sum of a node and its twin**.

Given the `head` of a linked list with **even length**, return the **maximum twin sum** of the linked list.

---

## Examples

### Example 1:

**Input:**  
`head = [5,4,2,1]`  

**Output:**  
`6`  

**Explanation:**  
- Node `0` (5) is the twin of node `3` (1): twin sum = 6  
- Node `1` (4) is the twin of node `2` (2): twin sum = 6  
- Maximum twin sum = `6`

---

### Example 2:

**Input:**  
`head = [4,2,2,3]`  

**Output:**  
`7`  

**Explanation:**  
- Node `0` (4) and node `3` (3): twin sum = 7  
- Node `1` (2) and node `2` (2): twin sum = 4  
- Maximum twin sum = `7`

---

### Example 3:

**Input:**  
`head = [1,100000]`  

**Output:**  
`100001`  

**Explanation:**  
- Only one pair of twins: 1 + 100000 = 100001  
- Maximum twin sum = `100001`

---

## Constraints

* The number of nodes in the list is an **even integer** in the range `[2, 10⁵]`  
* `1 <= Node.val <= 10⁵`

---

# LeetCode Practice & Algorithmic Solutions

> A structured catalog of LeetCode problems and Data Structures & Algorithms solutions implemented in **C++** and **Java**.

## Solved Problems Catalog

| Topic | Problem | Language | Solution File | Approach / Complexity |
|-------|---------|----------|---------------|-----------------------|
| **Arrays** | [LeetCode 27: Remove Element](https://leetcode.com/problems/remove-element/) | Java | [`Arrays/RemoveElement.java`](Arrays/RemoveElement.java) | Two pointers in-place overwrite; $O(n)$ time, $O(1)$ space. |
| **Bit Manipulation** | [LeetCode 190: Reverse Bits](https://leetcode.com/problems/reverse-bits/) | C++ | [`Bit Manipulation/reverse-bits.cpp`](<Bit Manipulation/reverse-bits.cpp>) | Bit shifting and mask extraction over 32 bits; $O(1)$ time. |
| **Bit Manipulation** | [LeetCode 401: Binary Watch](https://leetcode.com/problems/binary-watch/) | C++ | [`Bit Manipulation/binary-watch.cpp`](<Bit Manipulation/binary-watch.cpp>) | Builtin popcount (`__builtin_popcount`) bit combination check; $O(1)$ time. |
| **Greedy** | [LeetCode 1536: Minimum Swaps to Arrange a Binary Grid](https://leetcode.com/problems/minimum-swaps-to-arrange-a-binary-grid/) | C++ | [`Greedy/1536_Minimum_Swaps_to_Arrange_a_Binary_Grid.cpp`](<Greedy/1536_Minimum_Swaps_to_Arrange_a_Binary_Grid.cpp>) | Trailing zero counting + greedy adjacent row swapping; $O(n^2)$ time. |
| **Linked List** | [LeetCode 21: Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) | C++ | [`Linked-List/LC21 - Merge Two Sorted Lists.cpp`](<Linked-List/LC21 - Merge Two Sorted Lists.cpp>) | Iterative pointer splice with dummy head; $O(n + m)$ time, $O(1)$ space. |
| **Recursion** | [LeetCode 1545: Find Kth Bit in Nth Binary String](https://leetcode.com/problems/find-kth-bit-in-nth-binary-string/) | C++ | [`Recursion/1545_Find_Kth_Bit_in_Nth_Binary_String.cpp`](<Recursion/1545_Find_Kth_Bit_in_Nth_Binary_String.cpp>) | Recursive quadrant divide-and-conquer; $O(n)$ time. |
| **Strings** | [LeetCode 67: Add Binary](https://leetcode.com/problems/add-binary/) | C++ | [`Strings/add-binary.cpp`](Strings/add-binary.cpp) | Two-pointer column-wise addition with carry propagation; $O(\max(n, m))$ time. |

## Topic Categories

The repository is organized by problem archetype:

- [x] **Arrays**
- [x] **Bit Manipulation**
- [ ] **Dynamic Programming** *(in progress)*
- [ ] **Graph Algorithms** *(in progress)*
- [x] **Greedy Algorithms**
- [x] **Linked Lists**
- [ ] **Matrix** *(in progress)*
- [x] **Recursion**
- [ ] **Sliding Window** *(in progress)*
- [x] **Strings**
- [ ] **Trees & Binary Search Trees** *(in progress)*

## Compiling & Running Solutions

### C++
```bash
g++ -std=c++17 "Strings/add-binary.cpp" -o solution
./solution
```

### Java
```bash
cd Arrays
javac RemoveElement.java
java RemoveElement
```

## Profiles

- **LeetCode:** [View LeetCode Profile](https://leetcode.com/u/rragulramachandran/)
- **TakeUForward:** [View TakeUForward Progress](https://takeuforward.org/profile/ragulr)

## Chapter 8: Balanced Trees — Lab Report

### Student Information
- **Name:** Nathaniel Tryon
- **Date:** 4/5/26

### Algorithm Analysis

#### AVL Trees
- **Balance Factor Range:** −1, 0, or 1.
- **Why rebalance?** To allow for easy and fater traversal 
- **Time Complexity (all operations):** O(log(n))

#### Rotation Cases
| Case | Imbalance | Fix |
|------|-----------|-----|
| LL   |  -2    |right rotation|
| RR   | +2     |left rotation|
| LR   |-1, +1 |none |
| RL   |   +1, -1|none|

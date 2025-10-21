# 🌳 2-3 Tree Deletion Test Cases

This document provides comprehensive test cases for deletion operations in a 2-3 tree, covering local and global rotations, node mergers, internal element removal, and complex restructuring sequences.

---

## 📚 Table of Contents

- [Local Rotation](#local-rotation)
  - [Testcase 001–008](#testcase-001-local-rotation-case-1-take-from-right)
- [Global Rotation](#global-rotation)
  - [Testcase 009–014](#testcase-009-global-rotation-case-9)
- [Local Node Merger](#local-node-merger)
  - [Testcase 015–017](#testcase-015-local-node-merger-case-15)
- [Global Node Merger](#global-node-merger)
  - [Testcase 018–019](#testcase-018-global-node-merger-case-18)
- [Removing Internal Element](#removing-internal-element)
  - [Testcase 020](#testcase-020-removing-internal-element-case-20)
- [Complex Insert/Delete Sequence](#complex-insertdelete-sequence)
  - [Testcase 021](#testcase-021-complex-insertdelete-sequence)
- [Notes](#notes)

---

## 🔄 Local Rotation

### Testcase 001 – Case 1: Take from Right

**Input Array:** `{67, 34, 23, 88, 96, 14, 4, 27}`

#### ➤ Delete 4

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/0.png) | ![Result](assets/images/1.png) | ![Traversal](assets/images/2.png) |

#### ➤ Delete 34

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/3.png) | ![Result](assets/images/4.png) | ![Traversal](assets/images/5.png) |

#### ➤ Delete 23

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/6.png) | ![Result](assets/images/7.png) | ![Traversal](assets/images/8.png) |

#### ➤ Delete 88

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/9.png) | ![Result](assets/images/10.png) | ![Traversal](assets/images/11.png) |

#### ➤ Delete 27

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/12.png) | ![Result](assets/images/13.png) | ![Traversal](assets/images/14.png) |

#### ➤ Delete 67

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/15.png) | ![Result](assets/images/16.png) | ![Traversal](assets/images/17.png) |

#### ➤ Delete 14

| Initial Tree | Resulting Tree | Tree Traversal |
|--------------|----------------|----------------|
| ![Initial](assets/images/18.png) | ![Result](assets/images/19.png) | ![Traversal](assets/images/20.png) |

> **Note:** Deleting 96 results in an empty tree.

---












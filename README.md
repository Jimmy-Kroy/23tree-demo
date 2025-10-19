# 23tree-demo
This C++ application demonstrates the functionality of a 2-3 tree data structure. It supports dynamic insertion and deletion of elements, providing a clear illustration of balanced tree operations and node restructuring in real time.

# 2-3 Tree Implementation in C++

## Introduction

This repository provides a 2-3 tree implementation in the C++ language. The implementation is based on several articles found on the internet. These articles can be found in the references section, which also offers articles with an in-depth explanation of a 2-3 tree.

For the implementation I used a threaded tree. A threaded tree makes use of a parent pointer. This parent pointer makes it easier to move from a child node to its corresponding parent without using recursion. In addition, I used templates to enable the usage of different data types in the 2-3 tree.

## Background

A 2-3 tree is a multi-way search tree in which each node has two children (referred to as a two node) or three children (referred to as a three node). A two node contains one element. The left subtree contains elements that are less than the node element. The right subtree contains elements that are greater than the node element. However, unlike a binary search tree, a two node can have either no children or two children; it cannot have just one child. A three node contains two elements, one designated as the smaller element and one designated as the larger element. A three node has either no children or three children. If a three node has children, the left subtree contains elements that are less than the smaller node element. The right subtree contains elements that are greater than the larger node element. The middle subtree contains elements that are greater than the smaller node element and less than the larger node element. Due to the self-balancing effect of a 2-3 tree, all the leaves are on the same level. A 2-3 tree of size N has a search time complexity of O(log N).


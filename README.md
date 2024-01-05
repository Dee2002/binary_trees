cat > README.md << "EOF"
# 0x1D. C - Binary trees

## Resources

Read or watch:
- [Binary tree (note the first line: Not to be confused with B-tree.)](#)
- [Data Structure and Algorithms - Tree](#)
- [Tree Traversal](#)
- [Binary Search Tree](#)
- [Data structures: Binary Tree](#)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
### General
- What is a binary tree
- What is the difference between a binary tree and a Binary Search Tree
- What is the possible gain in terms of time complexity compared to linked lists
- What are the depth, the height, the size of a binary tree
- What are the different traversal methods to go through a binary tree
- What is a complete, a full, a perfect, a balanced binary tree

## Copyright - Plagiarism

- You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General
- Allowed editors: vi, vim, emacs
- Compilation on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Code should use the Betty style and be checked using betty-style.pl and betty-doc.pl
- Not allowed to use global variables
- No more than 5 functions per file
- Allowed to use the standard library
- Prototypes of all functions should be included in the header file called binary_trees.h
- Don’t forget to push your header file
- All header files should be include guarded

## Data Structures

Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

### Basic Binary Tree
```c
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;

## Binary Search Tree

typedef struct binary_tree_s bst_t;

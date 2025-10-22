# 🔄 Push_swap

Push_swap is a sorting algorithm project developed as part of the 42 School curriculum. The goal is to sort a stack of integers using a limited set of operations and to minimize the number of moves.

## 🧠 Project Summary

- Written in **C**, following 42 Norm coding standards  
- Implements two stacks (A and B) and a set of operations: push, swap, rotate, reverse rotate  
- Sorts input data (list of integers) using only those operations  
- Focuses on algorithmic efficiency and move minimization  
- Dynamically handles input with error checking (duplicates, non-integers, overflow)

## 📋 Features

### ✅ Mandatory

- Read and validate list of integers from command-line arguments  
- Use only allowed operations:  
  - `sa`, `sb`, `ss` — swap top two elements  
  - `pa`, `pb` — push top element from one stack to another  
  - `ra`, `rb`, `rr` — rotate stack so top becomes bottom  
  - `rra`, `rrb`, `rrr` — reverse rotate  
- Produce a sequence of operations that sorts stack A in ascending order  
- Handle small input sets (like 2 or 3 elements) with optimal minimal operations  
- Make sure there are **no duplicate integers**, and only valid input is accepted  

### 🧩 Bonus (if implemented)

- Algorithmic strategy for larger sets (e.g., radix sort, chunk sorting)  
- Minimize operations further (e.g., use fewer moves for 1000+ numbers)  
- Visualizer or checker tool that reads operations and verifies sorting  
- Additional features: color outputs, option flags, check mode  

## 🚀 How to Use

Clone and build:
```bash
git clone https://github.com/IzaroArbaiza/Push_swap.git
cd Push_swap && make
```
Run the program with a list of integers:
```bash
./push_swap 4 67 3 87 23
```
<br>
It outputs a sequence of operations, each on a new line. Applying them in order will sort the stack.

Example:
```bash
$./push_swap 2 1 3
$sa
```



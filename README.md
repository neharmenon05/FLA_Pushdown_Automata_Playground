# PDA Playground Project

## Project Overview
This project implements a **modular Pushdown Automata (PDA) simulator** in Python. It covers three main applications of PDAs:

1. **Balanced Parentheses Checker** – Validates sequences of parentheses and brackets.  
2. **Palindrome Checker** – Identifies palindromic strings, ignoring non-alphanumeric characters and case.  
3. **Context-Free Grammar (CFG) → PDA Simulator** – Converts a CFG into a non-deterministic PDA and validates strings against it.  

The design focuses on **educational clarity**, **modularity**, and **efficient simulation**, suitable for demonstrations and learning purposes.

---


## Project Modules

### 1. PDA Core Module
- Provides a **Pushdown Automaton class** to define states, transitions, and stack operations.  
- Supports **ε-transitions**, stack manipulation (push/pop), and state tracking.  
- Forms the foundation for all other modules.

### 2. Balanced Parentheses Module
- Implements stack-based validation of **well-formed parentheses and brackets**.  
- Uses the PDA core to track opening and closing symbols.  
- Highlights the practical use of **stack operations in language recognition**.

### 3. Palindrome Module
- Detects palindromes in strings using **stack simulation**.  
- Ignores non-alphanumeric characters and case for flexible input handling.  
- Demonstrates **PDA-based string symmetry checks**.

### 4. CFG → PDA Module
- Converts a **Context-Free Grammar (CFG)** into a non-deterministic PDA.  
- Efficiently simulates multiple configurations using **breadth-first search** to explore all stack possibilities.  
- Enables **validation of CFG-based languages** through PDA simulation.

---


# Haskell Lazy Evaluation Bug

This repository demonstrates a subtle bug related to lazy evaluation in Haskell. The code sorts a list but modifying the list before the sorted result is accessed can lead to unexpected outcomes.

The `bug.hs` file shows the problematic code, and `bugSolution.hs` presents a solution to ensure the sort operation is performed before any modification to the original list.
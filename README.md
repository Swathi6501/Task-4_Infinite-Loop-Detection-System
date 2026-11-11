
# Infinite Loop Detection System

## Project Information
- Subject: Formal Language and Automata Theory
- Project: Task 4 - Infinite Loop Detection System
- Environment: Google Colab
- Language: Python
- Version: 1.0

## Project Description

The Infinite Loop Detection System is a Python-based prototype
that analyzes loop structures in Python programs and classifies
them as Terminating or Non-Terminating.

It uses Abstract Syntax Tree (AST) analysis, loop feature
extraction, rule-based classification, and restricted execution
simulation.

## Main Features

1. Python source code analysis using AST.
2. Identification of while and for loops.
3. Extraction of loop conditions and modified variables.
4. Detection of break and continue statements.
5. Restricted loop simulation.
6. Program-level classification.
7. Performance evaluation.
8. Confusion matrix and graphical analysis.

## Dataset Information

- Development programs: 25
- Independent test programs: 30
- Total evaluated programs: 55
- Development loop records: 27

## Evaluation Results

Development Dataset:
- Accuracy: 100%
- Precision: 100%
- Recall: 100%
- F1-score: 100%

Independent Test Dataset:
- Accuracy: 100%
- Precision: 100%
- Recall: 100%
- F1-score: 100%

These results apply only to the manually designed examples
included in this project. They should not be interpreted as
proof of general-purpose loop termination detection.

## Important Limitation

The system uses restricted AST-based simulation and a maximum
iteration safety limit. Reaching this limit indicates that the
program did not terminate within the simulation limit; it does
not mathematically prove that the loop is infinite.

The prototype does not support every Python language construct
or every possible program structure.

## Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Future Enhancements

- Support for more complex nested loops.
- Improved handling of conditional branches.
- Symbolic execution.
- Static analysis of additional Python constructs.
- Testing with larger external benchmark datasets.

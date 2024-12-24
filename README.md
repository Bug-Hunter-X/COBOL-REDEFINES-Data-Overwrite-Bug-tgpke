# COBOL REDEFINES Bug

This repository demonstrates a common error involving the REDEFINES clause in COBOL.  Improper use of REDEFINES can lead to unexpected data overwrites and incorrect program behavior. The bug.cob file contains the erroneous code, while bugSolution.cob provides a corrected version.

## Bug Description

The original code uses REDEFINES to redefine a storage area. However, it fails to manage the interaction between the fields correctly leading to either wrong data display or unexpected program behavior, depending on the compiler used and memory layout.

## Solution

The solution demonstrates how to correctly handle data manipulation and display with REDEFINES, avoiding potential conflicts and unexpected behavior.
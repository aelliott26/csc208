# Examples in Section 1.3

## Reading Questions

### 1. Checking Logical Equivalence with a Truth Table
To determine if two statements \( P \) and \( Q \) are logically equivalent:
1. Construct a truth table*listing all possible truth values.
2. Compute the truth values for both \( P \) and \( Q \).
3. Compare the final columns of the truth table:
   - If the columns are identical, \( P \equiv Q \).
   - If they differ in any row, they are *not* equivalent.

### 2. Checking Validity of a Deduction Rule
To determine whether a deduction rule is valid:
1. Construct a truth table for all premises and the conclusion.
2. Identify rows where all premises are true.
3. Check the conclusion:
   - If the conclusion is true in all rows where the premises are true, the rule is *valid*.
   - If the conclusion is false in any row where the premises are true, the rule is *invalid*.

### 3. Question About the Section**
- *Are there alternative methods to check for logical equivalence besides using a truth table?*

## Practice Problems

###  1. Truth Table for \( (P \land Q) \rightarrow (P \lor Q) \)

| \( P \) | \( Q \) | \( P \land Q \) | \( P \lor Q \) | \( (P \land Q) \rightarrow (P \lor Q) \) |
|---|---|---|---|---|
| T | T | T | T | T |
| T | F | F | T | T |
| F | T | F | T | T |
| F | F | F | F | T |

###  2. Truth Table for \( \neg Q \lor (Q \rightarrow P) \)

| \( P \) | \( Q \) | \( \neg Q \) | \( Q \rightarrow P \) | \( \neg Q \lor (Q \rightarrow P) \) |
|---|---|---|---|---|
| T | T | F | T | T |
| T | F | T | T | T |
| F | T | F | F | F |
| F | F | T | T | T |


### 3. Checking Logical Equivalence of \( P \rightarrow (Q \lor R) \) and \( (P \rightarrow Q) \lor (P \rightarrow R) \)

| \( P \) | \( Q \) | \( R \) | \( P \rightarrow (Q \lor R) \) | \( (P \rightarrow Q) \lor (P \rightarrow R) \) |
|---|---|---|---|---|
| T | T | T | T | T |
| T | T | F | T | T |
| T | F | T | T | T |
| T | F | F | F | F |
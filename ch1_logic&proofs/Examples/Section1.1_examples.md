## 1. Suppose P and Q are the statements:  
- **P:** Jack passed math.  
- **Q:** Jill passed math.  

### (a) Translate "Jack and Jill both passed math" into symbols.  
**Answer:**  
$P \land Q$

### (b) Translate "If Jack passed math, then Jill did not" into symbols.  
**Answer:**  
$P \rightarrow \neg Q$

### (c) Translate " $P \lor Q$ " into English.  
**Answer:**  
"Jack or Jill (or both) passed math."

### (d) Translate "$\neg (P \land Q) \rightarrow Q$" into English.  
**Answer:**  
"If Jack and Jill did not both pass math, then Jill passed math."

### (e) Suppose you know that if Jack passed math, then so did Jill. What can you conclude if you know that:  

#### i. Jill passed math?  
**Answer:** We cannot conclude anything about Jack because Jill passing does not necessarily mean Jack did.  

#### ii. Jill did not pass math?  
**Answer:** If we assume $P \rightarrow Q$ is true, then knowing $\neg Q$ (Jill did not pass) means Jack **must not have passed either**. This follows from **contrapositive reasoning**:  
$P \rightarrow Q \equiv \neg Q \rightarrow \neg P$

---

## 2. Translate into symbols.  
Use $E(x)$ for "x is even" and $O(x)$ for "x is odd."

### (a) No number is both even and odd.  
**Answer:**  
$\neg \exists x (E(x) \land O(x))$

### (b) One more than any even number is an odd number.  
**Answer:**  
$\forall x (E(x) \rightarrow O(x+1))$

### (c) There is a prime number that is even.  
**Answer:**  
$\exists x (Prime(x) \land E(x))$  
*(Example: $x = 2$ is an even prime.)*

### (d) Between any two numbers, there is a third number.  
**Answer:**  
$\forall x \forall y (x < y \rightarrow \exists z (x < z < y))$  
*(This is true for real numbers but false for integers.)*

### (e) There is no number between a number and one more than that number.  
**Answer:**  
$\forall x \neg \exists y (x < y < x+1)$  
*(This is true in integers but false in real numbers.)*

---

## 3. For each statement below, give a domain where it is true and a domain where it is false.  

### (a) $\forall x \exists y (y^2 = x)$  
**Answer:**  
- **True:** When the domain is **non-negative real numbers** ($x \geq 0$), because every non-negative number has a square root.  
- **False:** When the domain is **all real numbers**, because negative numbers don’t have real square roots.
#### Note: For every x value, there is some number y whose square equals x

### (b) $\forall x \forall y (x < y \rightarrow \exists z (x < z < y))$  
**Answer:**  
- **True:** In the **real numbers** ($\mathbb{R}$), because there is always a number between any two distinct real numbers.  
- **False:** In the **integers** ($\mathbb{Z}$), because there are no integers strictly between consecutive numbers (e.g., nothing between 1 and 2 in $\mathbb{Z}$).
#### Note: For every 2 numbers (x and y), if x is less than y, then there is a third number z between them.

### (c) $\exists x \forall y \forall z (y < z \rightarrow y \leq x \leq z)$  
**Answer:**  
- **True:** In **natural numbers** ($\mathbb{N} $) if $ x$ is chosen as the smallest number (e.g., 0 in non-negative integers or 1 in positive integers).  
- **False:** In **real numbers** ($\mathbb{R}$), because no single number satisfies this property for all other numbers.
#### Note: There is some x for every 2 values (y and z), if y is larger than z, then x is equal or between both y and z.
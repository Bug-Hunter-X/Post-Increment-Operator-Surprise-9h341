# Post-Increment Operator Surprise in C

This repository showcases a common pitfall in C programming involving the post-increment operator (`x++`). The provided `bug.c` file contains code that might produce unexpected results for programmers unfamiliar with the operator's behavior. The `bugSolution.c` file offers a corrected version and explanation.

**The Problem:**
The post-increment operator increments the variable *after* its value is used in an expression.  This can lead to confusion if not fully understood. 

**How to use the code:**
1. Clone the repository.
2. Compile `bug.c` (e.g., using `gcc bug.c -o bug`) and `bugSolution.c` (e.g., `gcc bugSolution.c -o bugSolution`).
3. Run the executables and observe the output differences.  The `bugSolution.c` demonstrates the intended behavior. 

**Learn more:** 
This is a great way to learn the nuances of the post-increment operator and how careful consideration is needed for its proper use in your programs. Understanding this can prevent frustrating and hard-to-find bugs in more complex scenarios. 
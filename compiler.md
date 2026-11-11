# IFCC | A C-subset compiler

**INSA Lyon · 4A semester 2 · Team project**

IFCC compiles a subset of C to x86-64 assembly. The project uses ANTLR for parsing, then performs semantic checks, generates an intermediate representation and emits AT&T assembly. GCC assembles and links the result so it can run as a native executable.

I implemented double literals, arithmetic, local variables, parameters and return values across the grammar, type checking and code generation. I added regression cases for arithmetic and chained function calls and checked the implementation's handling of mixed types. The work was merged into the final team revision.

The portfolio build passed 157 comparison cases against GCC, including the five tests in the double-precision suite. The team source repository is private.

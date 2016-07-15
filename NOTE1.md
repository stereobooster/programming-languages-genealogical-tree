# Concepts invented in LISP

source: http://www.paulgraham.com/diff.html

1. **Conditionals**. A conditional is an if-then-else construct. We take these for granted now. They were invented by McCarthy in the course of developing Lisp. (Fortran at that time only had a conditional goto, closely based on the branch instruction in the underlying hardware.) McCarthy, who was on the Algol committee, got conditionals into Algol, whence they spread to most other languages.
2. **A function type**. In Lisp, functions are first class objects-- they're a data type just like integers, strings, etc, and have a literal representation, can be stored in variables, can be passed as arguments, and so on.
3. **Recursion**. Recursion existed as a mathematical concept before Lisp of course, but Lisp was the first programming language to support it. (It's arguably implicit in making functions first class objects.)
4. **A new concept of variables**. In Lisp, all variables are effectively pointers. Values are what have types, not variables, and assigning or binding variables means copying pointers, not what they point to.
5. **Garbage-collection**. [citatition required]
6. **Programs composed of expressions**. Lisp programs are trees of expressions, each of which returns a value. (In some Lisps expressions can return multiple values.) This is in contrast to Fortran and most succeeding languages, which distinguish between expressions and statements.
7. **A symbol type**. Symbols differ from strings in that you can test equality by comparing a pointer.
8. A notation for code using trees of symbols. [what did Paul Graham mean?]
9. The whole language always available. There is no real distinction between read-time, compile-time, and runtime. You can compile or run code while reading, read or run code while compiling, and read or compile code at runtime.

## Notes

I suppose first idea of variables (and memory) was introduced in Turing Machine. [citation required]

**Programs composed of expressions** also can be treated as first ["everything is a..." rule](http://c2.com/cgi/wiki?EverythingIsa).

- [John McCarthy](https://en.wikipedia.org/wiki/John_McCarthy_%28computer_scientist%29) designer of lisp
- [History of Lisp](http://www-formal.stanford.edu/jmc/history/lisp/lisp.html)
- [John McCarthy home page](http://www-formal.stanford.edu/jmc/)

# Read: 10 - JS Debugging

**I learned from this chapter :**

* The JavaScript interpreter uses the concept of execution contexts.There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

* In the interpreter, each execution context has its own va ri ables object.It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

* If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

* Debugging is about deduction: eliminating potential causes of an error.Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.

* you want to, it is possible to tell the debugger to step into a function to see what is happening inside the function.
If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.

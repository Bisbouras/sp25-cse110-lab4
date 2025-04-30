1. Line 9 will print "values added: 20"
2. Line 13 will print "final result: 20"
3. Using var can have a few complications, such as accidentally creating global variables (resulting in naming conflicts and other issues). Naming conflicts can occur with Var without errors, meaning it might be harder to find.
4. Line 9 will print "values added: 20"
5. Line 13 will have a ReferenceError, because we used let, which has block scope, meaning it's only usable between lines 3 and 11. On line 13, the var is no longer in scope, causing the error.
6. Line 9 will have a TypeError, since result uses const, and it cannot be reassigned, so result = num1 + num2 throws a TypeError
7. Line 13 will not print anything because the file will stop executing at the Type Error.
   

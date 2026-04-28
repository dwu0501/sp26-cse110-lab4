1. 20
2. 20
3. We should not use 'var' variables since once they are declared, they exist in a function scope and are hoisted so they may appear in cases where they shouldn't exist and may affect the final result of your return.
4. 20
5. ReferenceError: result is not defined. This happens becuase we are trying to call a variable that doesn't exist outside of the scope of the if(a) case when printing the message.
6. TypeError: Assignment to constant variable. This happens because you are trying to modify its values after declaration which is not allowed by constants
7. There is no error since the code breaks before reaching this line. However, if it reached here, it would probably also have a 'ReferenceError: result is not defined' error. Similarly, to 'let' variables, you are trying to call a variable that doesn't exist outside of the scope of the if(a) case when printing the message.
1. 3, it prints the value of 'i' when exiting the 'for loop'. Since, it is a variable of type 'var', it is declared at function level and is hoisted so it doesn't get deleted after the block is executed
2. 150, it prints the last value taken by 'discountedPrice' when exiting the 'for loop'. Since, it is a variable of type 'var', it is declared at function level and doesn't get deleted after the block is executed
3. 150, it prints the last value taken by 'finalPrice' when exiting the 'for loop'. Since, it is a variable of type 'var', it is declared at function level and doesn't get deleted after the block is executed (all 'var' are hoisted so it doesn't matter where it is declared).
4. It will return an array of size 3 with all discounted prices inside ([50, 100, 150]). This is because each iteration we will push the final price (rounded discounted price) inside the array.
5. An error appears: 'ReferenceError: i is not defined'. This happens because 'let' variables are block level and 'i' gets deleted after exiting the loop.
6. An error appears: 'ReferenceError: discountedPrice is not defined'. This happens because 'let' variables are block level so 'discountedPrice' gets deleted after exiting the loop.
7. 150, it prints the last value taken by 'finalPrice' when exiting the 'for loop'. Since, it is declared at the start of the function its block-level scope is the function scope itself so that's why the variable doesn't get deleted after exiting the function.
8. It will return an array of size 3 with all discounted prices inside ([50, 100, 150]). This is because each iteration we will push the final price (rounded discounted price) in the array. And since it is declared at the start, the block level scope of the variable is the function itself.
9. An error appears: 'ReferenceError: i is not defined'. This happens because 'let' variables are block level and 'i' gets deleted after exiting the loop.
10. It prints the length of the array 'prices' which is 3. Since, it is declared at the start of the function, therefore, 'const' block-level scope is a function level scope and the reason why it can be printed
11. It will return an array of size 3 with all discounted prices inside ([50, 100, 150]). This is because each iteration we will push the (unrounded) discounted price in. And since the 'const' variable gets deleted after each iteration due to its scope, we do not need to worry about name overlapping. 
12. <br>
    <ol type="A">
      <li>student.name</li>
      <li>student['Grad Year']</li>
      <li>student.greeting()</li>
      <li>student['Favorite Teacher'].name</li>
      <li>student.courseLoad[0]</li>
    </ol>
13. <br>
    <ol type="A">
      <li>'32' since integers map to their exact string representation</li>
      <li>1 since integers map to their exact string representation for mathematical functions</li>
      <li>3 since <i>null</i> maps to 0 for numeric conversions</li>
      <li>'3null' since for string conversions they are mapped to the literal value</li>
      <li>4 since <i>true</i> is mapped to 1 in numerical conversion</li>
      <li>0 since both <i>false</i> and <i>null</i> are mapped to 0 in numerical conversion </li> 
      <li>'3undefined' since for string conversions they are mapped to the literal value</li> 
      <li>NaN since the numerical conversion of <i>undefined</i> is undefined</li>
    </ol>
14. <br>
    <ol type="A">
      <li>true since for comparisons of different types, JS converts the values to numbers</li>
      <li>false since JS compares strings in lexicographical order</li>
      <li>true since '==' does type convertion and JS converts different type values into their mapped numbers </li>
      <li>false since '===' is strict equality which checks for equality without type conversion</li>
      <li>false since '==' converts both to numerical value and it is clear that 1 is not equal to 2</li> 
      <li>true since Boolean(2) converts the value into a boolean true and 'true===true' is true</li>
    </ol>

15. While '==' is a comparison made after type conversion (if the types are different), '===' is a strict comparison that returns true only if both the type and value are equal and if the types differ, '===' immediately returns false since they are already strictly not equal.
16. Check code.
17. The result will be [2, 4, 6] since in the modifyArray function we are modifying each value using the doSomething function, which multiplies the value by 2. So essentially what we are doing is newArr.push(array[i] * 2) for each i.
18. Check code.
19. <br> 1 <br>
4 <br>
3 <br>
2 <br>

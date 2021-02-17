# JS Debugging

- **Debugging**: The process of searching for the errors and finding them.

- Debugging JavaScript code is difficult because the browser doesn’t show any error message or any indication to the location of the error.However,all modern browsers come with a built-in JavaScript debugger that can be turned on and off. Also a breakpoints can be set and the variables during the code execution can be examined. 

- **Different approaches to tackle the problem:**
   + *The console.log() method* :using the Browser Console, by right-clicking on the page, then selecting the Inspect tab. This method is practical for small programs. 

   ![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/console.log_.jpg)


   + *Setting Breakpoints* : At each breakpoint, JavaScript stops executing, allowing the developer to examine the JavaScript values.The steps to add a breakpoint in a document is as follows:
       - Open HTML file in the browser open console that mentioned discussed above.
       - Click on the Source tab and open the file containing the line of code where you want to add a break.
       - Go to the specific line of code. When you click on it or the line number column (on the left of the line of code), a blue icon appears on top of the line number column.


![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/breakpoint-output-before.jpg)

    + *The debugger keyword* : In JavaScript, the debugger keyword stops the execution and if available, calls the debugging function. The keyword works the same way as setting a breakpoint. In the absence of debugging, the debugger statement has no effect. With the debugger turned on, this code stops executing when it encounters a debugger statement.

    ![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/debugger.jpg)

    +*Debugging Tools in JavaScript*: 
        1. Cypress.io.
        2. Chrome DevTools. 
        3. Mocha.


![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing.png)



# Error Handling 

- When executing JavaScript code, different errors can occur.Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.

- The `try` statement lets you test a block of code for errors.

- The `catch` statement lets you handle the error.

- The `throw` statement lets you create custom errors.

- The `finally` statement lets you execute code, after try and catch, regardless of the result.


![](https://i.ytimg.com/vi/6z6zmSY8M5E/maxresdefault.jpg)
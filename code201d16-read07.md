Read 07 : 

+ Domain model is a structured visual representation of interconnected concepts or real-world objects that incorporates vocabulary, key concepts, behavior, and relationships of all of its entities.

+ A domain model is generally implemented as an object model within a layer that uses a lower-level layer for persistence and "publishes" an API to a higher-level layer to gain access to the data and behavior of the model. 

+ HTML tables allow web developers to arrange data into rows and columns.

+ The `<table>` tag defines an HTML table.

+ Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

+ By default, the text in `<th>` elements are bold and centered.

+ By default, the text in `<td>` elements are regular and left-aligned.The `<td>` elements are the data containers of the table. They can contain all sorts of HTML elements; text, images, lists, other tables, etc.

+ A simple HTML table:

 `<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
 </table>`

+ Style od Table in HTML can be modified by using:
  - The HTML `<caption>` element to define a table caption
  - The CSS `border property` to define a border
  - The CSS `border-collapse` property to collapse cell borders
  - The CSS `padding` property to add padding to cells
  - The CSS `text-align` property to align cell text
  - The CSS `border-spacing` property to set the spacing between cells
  - The `colspan` attribute to make a cell span many columns
  - The `rowspan`attribute to make a cell span many rows

![](https://i.stack.imgur.com/VCxSJ.png)

+ A **function** in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.

+ A JavaScript function is executed when "something" invokes it (calls it). 

+ A JavaScript function is defined with the `function` keyword, followed by a name, followed by parentheses `()`. Function names can contain letters, digits, underscores, and dollar signs (same rules as variables). The parentheses may include parameter names separated by commas: `(parameter1, parameter2, ...)`.The code to be executed, by the function, is placed inside curly brackets: `{}`.

+ The code inside the function will execute when "something" invokes (calls) the function:
  + When an event occurs (when a user clicks a button)
  + When it is invoked (called) from JavaScript code
  + Automatically (self invoked)

+ When JavaScript reaches a return statement, the function will stop executing. If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

+ Functions often compute a return value. The return value is "returned" back to the "caller".

+ In the below example the result in x will be 12 :
 `var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}`.

+ **Objects** in JavaScript are collections of key/value pairs. The values can consist of properties and methods, and may contain all other JavaScript data types, such as strings, numbers, and Booleans. All objects in JavaScript descend from the parent Object constructor.

+ **Methods** are actions that can be performed on objects. Object properties can be both primitive values, other objects, and functions. An object method is an object property containing a function definition. JavaScript objects are containers for named values, called properties and methods.

![](https://raw.githubusercontent.com/ATL-WDI-Curriculum/js-objects-and-json/master/images/object-property-method.jpg)

+ Example :
`var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};`.

+ In a function definition, `this` refers to the "owner" of the function. In the example above, this is the person object that "owns" the fullName function. In other words, `this.firstName` means the firstName property of this object.




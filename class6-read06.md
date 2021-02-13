+ **Problem Domain**: (or problem space) is an engineering term referring to all information that defines the problem and constrains the solution (the constraints being part of the problem). It includes the goals that the problem owner (the customer for a software solution) wishes to achieve, the context within which the problem exists, and all rules that define essential functions or other aspects of any solution product. It represents the environment in which a solution will have to operate, as well as the problem itself. 

+ In software engineering, the architecture and development of software, hardware, and networking all constitute the 'solution domain'. That is, these are the tools by which you are achieving a solution to a set of user-requirements.

+ **Objects** in JavaScript are unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

![](https://javascript.info/article/object/object.svg)

+ Object properties can be accessed in two ways:
   - *Dot notation* : 'objectName.propertyName' , or 
   - *Square brackets*: 'objectName["propertyName"]'

+ **Object Methods**: Methods are actions that can be performed on objects, they are stored in properties as function definitions.

+ **Document Object Model (DOM)** is the data representation of the objects that comprise the structure and content of a document on the web.It is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content.

+ The DOM represents the document as *nodes* and *objects*. That way, programming languages can connect to the page.

+ The browser represents the page using a **DOM tree**. DOM trees have four types of nodes: *document nodes, element nodes, attribute nodes, and text nodes*.

![](https://media.geeksforgeeks.org/wp-content/uploads/DOM.png)

+ **Application Programming Interface (API)** :a set of methods of communication between various software components. In other words, an API allows software to communicate with another software.

+ Accessing and updating the DOM tree involves two steps:
    1. Locate the node that represents the element you want to work with.
    2. Use its text content, child elements, and attributes.

+ Element nodes can be selected by their *id or class attributes*, by *tag name*, or using *CSS selector* syntax.

+ Whenever a DOM query can return more than one node, it will always return a **Nodelist**.

+ From an element node, it is possible to access and update its content using properties such as *textContent* and *innerHTML* or using DOM manipulation techniques.

+ An element node can contain multiple text nodes and child elements that are siblings of each other.

+ In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

+ Browsers offer tools for viewing the DOM tree .


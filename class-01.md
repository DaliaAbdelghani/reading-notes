# Read: 01 - Introductory HTML and JavaScript


## 1) How people access the web : 

You would like to view CANVAS, so you type *https://www.canvas.net* in the address bar of your web browser, and in moments CANVAS is available to you. But what happens behind the scenes? 

In fact a group of software, devices and systems are working together in collaboration to load the web site you request. 

Below image shows the request/reply exchange process to load the requested web site on your device:

![DNS and browser interaction](https://tutorialsweb.hosting/wp-content/uploads/2016/12/dns-works.jpg) 

**Definitions:**

**Web Browser:** *(commonly referred to as a browser) is a software application for accessing information on the World Wide Web. When a user requests a web page from a particular website, the web browser retrieves the necessary content from a web server and then displays the page on the user's device.examples include Firefox, Internet Explorer, Safari, Chrome, and Opera.*


**Web Server:** *special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them.The basic objective of the web server is to store, process and deliver web pages to the users. This intercommunication is done using Hypertext Transfer Protocol (HTTP). web server could be anywhere in the world.* 

**Domain Name System (DNS) server:** *is a hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network. It is the phone-book of the Internet. DNS find the location of the web server which hosts the requested website. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.*

**IP Address:** *is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: host or network interface identification and location addressing.*

----------------------------------------------------------------------------------------------------------------------------------------

## 2) HTML:

- (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. 

- The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.


![HTML element](https://www.oreilly.com/library/view/learning-web-design/9781449337513/httpatomoreillycomsourceoreillyimages2257977.png)

- Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.


![tag's attribute](https://4.bp.blogspot.com/-B5vUzJXNAoE/Vuay2ygsN2I/AAAAAAAAG5o/-qOAVBa3LRkJ0fPWywYzkAcmezRAY2Rxg/s640/html-syntax.png)

- To create a web page you need an HTML document using three elements or tags major that any website uses: html, head and body. The recommended minimal skeleton of an HTML5 document as shown below:


![minimal skeleton of an HTML5 document](https://www.oreilly.com/library/view/learning-web-design/9781449337513/httpatomoreillycomsourceoreillyimages2257981.png) 


- Since the web was first created, there have been several different versions of HTML. Each new version was designed to be an improvement on the last (with new elements and attributes added and older code removed).


![HTML History](https://i0.wp.com/hideincorner.com/wp-content/uploads/2019/08/html-history.jpg?w=960&ssl=1) 


- Because there have been several versions of HTML, each web page should begin with a **DOCTYPE** declaration to tell a browser which version of HTML the page is using.

- If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these
characters:   `<!-- comment goes here -->`.

- **id attribute** : every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character).  It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).

- **class attribute** : Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, class attribute identify several elements as being different from the other elements on the page.The class attribute on any element can share the same value. 

- **Block elements**: elements which always appear to start on a new line in the browser window. Such as `<h1> , <p> , <ul> , and <li>`.

- **In-line elements**: elements which always appear to continue on the same line as their neighbouring elements.  Such as `<a> , <b> , <em> , and <img>`. 

- The `<div>` element allows you to group a set of elements together in one block-level box.

- The `<span>` element acts like an inline equivalent of the `<div>` element. It is used to either:Contain a section of text
where there is no other suitable element to differentiate it from its surrounding text, or Contain a number of inline
Elements. 

- An `<iframe>` is like a little window that has been cut into the page — and in that window another page is shown. The term
iframe is an abbreviation of inline frame.

- The `<meta>` element lives inside the `<head>` element and contains information about that web page. It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time
sensitive. It  is an empty element so it does not have a closing tag. It uses attributes to carry the information.

- **Escape character** : is a character that invokes an alternative interpretation on the following characters in a character sequence or code. 


![](https://imgv2-2-f.scribdassets.com/img/document/415142310/original/c296b1e00c/1609458872?v=1)

- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements. This can be done by using CSS, for example :`header, section, footer, aside, nav, article, figure {display: block;}`

- To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.

----------------------------------------------------------------------------------------------------------------------------------------

## 3) Design your website :

Tips for designing a wonderful website. Before starting in creating your own website the following tips may be of a good help:

 + Know and understand your target audience.
 + Determine the type of information that attract the audience by identifying their motivations and goals.
 + find out what the audience will achieve by visiting your website.
 + The needed frequency of changing and updating the information at your website to ensure high rate of revisiting by audience.
 + Create your site map by determining how the information will be presented.

----------------------------------------------------------------------------------------------------------------------------------------

## 4) Programming :

- Computer programming is the process that professionals use to write code that instructs how a computer, application or software program performs. At its most basic, computer programming is a set of instructions to facilitate specific actions. Computer programmers create instructions for a computer to execute by writing and testing code that enables applications and software programs to operate successfully.

- A script is a series of instructions that the computer can follow in order to achieve a goal.

- To approach writing a script, break down the goal into a series of tasks and then work out each step needed to complete that task (a flowchart is helpful).

- In computers real models are defined by objects, there are different types of objects and each object has its own properties ( defined by names and values), events and methods. 

- Interactions with objects can change the values of properties in these objects, this interaction called event. Programmers choose which event s they respond to.

- Methods typically represent how people (or other things) interact with an object in the real world. The code for a method can contain lots of instructions that together represent one task.

- Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an object's properties.

----------------------------------------------------------------------------------------------------------------------------------------

## 5) Writing a script for a web page: 
 
- The best practice to write a script for a web page is to create three separated pages linked together : 
   1.HTML page with extension .html : for determining the page structure and the contents. 
   2.CSS page with extension .css : for adding formatting and style to the content. 
   3.JavaScript page with extension .JS: for adding interactive elements.

- CSS page is linked with HTML using tag `<link rel=”stylesheet” href=”URL”/>.` which is written in head section of HTML page. 

- JS page is linked with HTML using tage `<script src=”URL”>.....</script>`. 

![](https://qph.fs.quoracdn.net/main-qimg-aea6d70e3db223864d778ee560ec62c0.webp)
 
  


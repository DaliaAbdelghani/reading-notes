Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

# Texts in HTML :

- Structural markup: the elements that are used to describe both headings and paragraphs which affects the structure of the pages.

- Semantic markup: text elements that are not intended to affect the structure of the web pages, but they do add extra information to the pages. 

- HTML has six "levels" of headings ( from heading 1 the most important and largest font size to heading 6 the least important and smallest font size).

                   ![](https://www.schudio.com/wp-content/uploads/2016/10/html-headings.png?x97747)

- To mark up a paragraph in HTML tag `<p> ….</p>` is used. Each paragraph is shown on a new line with some space between it and any subsequent paragraphs.

- `<b> …</b>` tag makes characters appear bold.

- `<i> …</i>` tag makes characters appear italic.

- The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power .

- The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical
formulas. 

- White space collapsing : displaying one space when browser comes across two or more spaces next to each other or comes a cross a line break.

- Line break tag `<br />` is used to add new line. 

- `<hr />` tag is used to add a horizontal rule in the page.

- Empty elements:usually has only one tag. Before the closing angled bracket of an empty element there will often be a space and a forward slash character. 

- Visual editors often resemble word processors. Although each editor will differ slightly, there are some features that are common to most editors that allow you to control the presentation of text.

- Code views shows the code created by the visual editor and allows editing it manually. 

- `<strong>` element indicates that its content has strong importance.By default, browsers will show the contents of a `<strong>`
element in bold.

- `<em>` element indicates emphasis that subtly changes the meaning of a sentence.By default browsers will show
the contents of an `<em>` element in italic.

- There are two elements commonly used for marking up quotations:
    + The `<blockquote>` element is used for longer quotes that take up an entire paragraph.
    + The `<q>` element is used for shorter quotes that sit within a paragraph.

- The ‘cite’ attribute is used to indicate where the quote is from. Its value should be a URL that will have more information about the source of the quotation. Browsers will render the content of a `<cite>` element in italics.
  Example: ‘`<blockquote cite="http://en.wikipedia.org/wiki/Winnie-the-Pooh"><p>Did you ever stop to think, and forget to start again?</p>`

- The `<abbr>` element is used for abbreviation or acronym. A title attribute on the opening tag is used to specify the full term.

- The `<dfn>` element is used to indicate the defining instance of a new term(The first time you explain some new terminology ).

- The `<address>` element is used to contain contact details for the author of the page.

- The `<ins>` element can be used to show content that has been inserted into a document, while the `<del>` element can show text that has been deleted from it.
        Example: `<p>It was the <del>worst</del> <ins>best</ins> idea she had ever had.</p>`
                      It was the ~worst~best idea she had ever had.

- The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted). Visually the content of an `<s>` element will usually be displayed with a line through the center.

# How CSS works:

- CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

- Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

- Different types of selectors allow you to target your rules at different elements.

- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

- CSS rules usually appear in a separate document, although they may appear within an HTML page.



# JavaScript basic instructions:

- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

- `//` are used to insert a single line comment.

- `/* ……*/` are used to insert a multi-lines comment. 

- Variables are used to temporarily store pieces of information used in the script.

- Arrays are special types of variables that store more than one piece of related information .

- JavaScript distinguishes between numbers (0 -9), strings (text), and Boolean values (true or false).

- Expressions evaluate into a single value.

- Expressions rely on operators to calculate a value.

- Conditional statements allow the code to make decisions about what to do next.

- Comparison operators `(===, ! ==, ==, ! =, <, >, <=, =>)` are used to compare two operands.
         ![](https://www.pylenin.com/img/comparison-operators/comparison-table-2.png)

- Logical operators allow you to combine more than one set of comparison operators.

- `if ... else` statements allow you to run one set of code if a condition is true, and another if it is false.
        ![](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-if-statement.png) 






The seven rules of a great Git commit message by CHRIS BEAMS at https://chris.beams.io/posts/git-commit/:

1.Separate subject from body with a blank line
2.Limit the subject line to 50 characters
3.Capitalize the subject line
4.Do not end the subject line with a period
5.Use the imperative mood in the subject line
6.Wrap the body at 72 characters
7.Use the body to explain what and why vs. how
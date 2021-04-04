# EJS : Embedded JavaScript templating

- EJS is a simple templating language that allows to generate HTML markup with plain JavaScript.

- Features
   + Fast compilation and rendering
   + Simple template tags: <% %>
   + Custom delimiters (e.g., use [? ?] instead of <% %>)
   + Sub-template includes
   + Ships with CLI
   + Both server JS and browser support
   + Static caching of intermediate JavaScript
   + Static caching of templates
   + Complies with the Express view system

- Tags
`<%` 'Scriptlet' tag, for control-flow, no output

`<%_` ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it

`<%=` Outputs the value into the template (HTML escaped)

`<%-` Outputs the unescaped value into the template

`<%#` Comment tag, no execution, no output

`<%%` Outputs a literal `'<%'`

`%>` Plain ending tag

`-%>` Trim-mode ('newline slurp') tag, trims following newline

`_%>` ‘Whitespace Slurping’ ending tag, removes all whitespace after it



- EJS lets us spin up quick applications when we don’t need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.


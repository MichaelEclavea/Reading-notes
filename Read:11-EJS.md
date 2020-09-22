# Read:11 - EJS

Partials are just reusable components, snippets of ejs that can be used in multiple places. 

#### install: 
npm i ejs

#### use ejs: 
app.set('view engine', 'ejs');

ejs tags: 

<%= (input) %>
Every must start and end with ejs brackets.



to place partials instead of inside line input.  This partials route to route or directory, so instead of <%=, it is now <%-


Refer to EJS cheat sheet!
https://ejs.co/
Tags
•	<% 'Scriptlet' tag, for control-flow, no output
•	<%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
•	<%= Outputs the value into the template (HTML escaped)
•	<%- Outputs the unescaped value into the template
•	<%# Comment tag, no execution, no output
•	<%% Outputs a literal '<%'
•	%> Plain ending tag
•	-%> Trim-mode ('newline slurp') tag, trims following newline
•	_%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it

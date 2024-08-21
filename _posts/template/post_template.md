<%*
let title = await tp.system.prompt("Enter title");
let newFileName = `${tp.date.now("YYYY-MM-DD")}-${title}`;
tp.file.rename(newFileName);
-%>
---
title:: <%- title %>
categories::
tags:: 
toc:: false
posting:: false
toc_sticky:: false
date:: <% tp.date.now() %>

---

---
published: true
subtitle: 
date: <% tp.date.now() %>
uuid:  <% tp.date.now("YYYYMMDDHHmmss") %>
tags: 
---

[[<% tp.date.now("YYYYMMDDHHmmss") %>]]

# <% (await tp.system.prompt("New journal entry title:", "Untitled", false)) %>
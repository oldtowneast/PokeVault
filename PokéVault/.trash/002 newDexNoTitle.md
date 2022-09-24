---
number: <% tp.file.cursor(10) %>
alias: <% tp.file.title.split(" ")[1] %>
name: <% tp.file.title.split(" ")[1] %>
category: <% tp.file.cursor(20) %>
type-1: <% tp.file.cursor(30) %>
type-2: <% tp.file.cursor(40) %>
image: "<% tp.file.cursor(80) %>"
---

<% tp.file.cursor(80) %>

number:: <% tp.file.cursor(10) %>

name:: <% tp.file.title.split(" ")[1] %>

category:: [[<% tp.file.cursor(20) %>]]

type-1:: [[<% tp.file.cursor(30) %>]]

type-2:: [[<% tp.file.cursor(40) %>]]

weaknesses:: <% tp.file.cursor(50) %>

description:: <% tp.file.cursor(60) %>

evolutions:: <% tp.file.cursor(70) %>
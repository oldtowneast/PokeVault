---
pokedex-number: <% tp.file.cursor(10) %>
alias: <% tp.file.title.split(" ")[1] %>
name: <% tp.file.title.split(" ")[1] %>
category: <% tp.file.cursor(20) %>
type-1: <% tp.file.cursor(30) %>
type-2: <% tp.file.cursor(40) %>
image: "<% tp.file.cursor(80) %>"
---

<% tp.file.cursor(80) %>

Pokédex Number:: <% tp.file.cursor(10) %>

Name:: <% tp.file.title.split(" ")[1] %>

Category:: [[<% tp.file.cursor(20) %>]]

Type 1:: [[<% tp.file.cursor(30) %>]]

Type 2:: [[<% tp.file.cursor(40) %>]]

Weaknesses:: <% tp.file.cursor(50) %>

Description:: <% tp.file.cursor(60) %>

Evolutions:: <% tp.file.cursor(70) %>
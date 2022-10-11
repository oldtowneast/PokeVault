---
source: https://forum.obsidian.md/t/progress-bar-for-notes-easy-and-powerful-with-dataview/33144
---

```dataview
TABLE without id 
  Progress_Bar AS "Progress Bar",
  ("![cover|80](" + Cover + ")") as Cover,
  file.link AS "Title",
  Author AS "Author",
  Category AS "Genre"
FROM #FM/📁02/📖 
where Status = "Currently-reading"
SORT Progress desc
```
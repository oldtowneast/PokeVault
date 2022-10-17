```dataview
TABLE without id 
  Progress_Bar AS "Progress Bar",
  ("![cover|80](" + Cover + ")") as Cover,
  file.link AS "Title"
FROM "0 - Sets" 
where Status = "Currently-reading"
SORT Progress desc
```
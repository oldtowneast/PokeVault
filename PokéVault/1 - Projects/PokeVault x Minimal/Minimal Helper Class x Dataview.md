---
cssClasses: cards, cards-cover, cards-2-3, table-max
---


```dataview
table image as "Image" from "Pokédex SAMPLES"
```

----

```dataview
table without id 
	("![](" + image + ")") as Poster,
	file.link as Title,
	string("Pokédex Number") as Year, 
	"foo " + "Type 1" as "Type 1",
	"foo " + "Type 2" as "Type 2",
	rating
from "Pokédex SAMPLES"
where image != null
```
```
table without id self as "Test", number as "Number", image as "Image", type-1 as "Type 1", type-2 as "Type 2", category as "Category" from #PokémonTCG/PokémonGo 
```

```
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

**tp.file.title.split**
```
<% tp.file.title.split(" ")[0] %>
```

⭐️⭐️⭐️ 🏆

```
[[<% tp.file.title.split(" ")[1] %><% tp.file.cursor(1) %>|<% tp.file.title.split(" ")[1] %>]]
```
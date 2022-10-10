<%*
/*
    { title: "", url: ""},
    { title: "", url: ""},
*/

const helpResources = [
    { title: "Pokemon TCG Guru", url: "https://pokemontcg.guru/sets"},
    { title: "PokeVault GitHub", url: "https://github.com/oldtowneast/PokeVault"},
    { title: "", url: ""},
    { title: "", url: ""},
]

helpResources.forEach(resource => {
    if (resource.title !== "") {
        app.commands.addCommand({
            id: "launcher-help-resource-" + resource.title.replace(/\s/g, "-"),
            name: "pp: " + resource.title,
            callback: () => { window.open(resource.url) }
        });
    }
});

%>
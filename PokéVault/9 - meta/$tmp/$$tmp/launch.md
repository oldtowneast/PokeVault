<%*
/*
    { title: "Pokemon TCG Guru", url: "https://pokemontcg.guru/sets"},
    { title: "", url: ""},
    { title: "", url: ""},
*/

const helpResources = [
    { title: "", url: ""},
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
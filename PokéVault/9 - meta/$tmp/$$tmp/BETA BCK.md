```bash
tar -cvf <% tp.date.now("YYYY-MM-DD") %>_PokéVault.tar.gz --exclude={"/media/wm/Birch/Church/Obsidian/PokéVault/.trash","/media/wm/Birch/Church/Obsidian/PokéVault/.obsidian"} /media/wm/Birch/Church/Obsidian/PokéVault/

tar -cvf <% tp.date.now("YYYY-MM-DD") %>_PokéTrash.tar.gz /media/wm/Birch/Church/Obsidian/PokéVault/.trash

ls /media/wm/Birch/Church/Obsidian/PokéVault/.obsidian/plugins |& tee -a <% tp.date.now("YYYY-MM-DD") %>_PokéVaultPlugins.md

cp /media/wm/Birch/wn/UnArchives/PokéVault-backups/2022/Q3/<% tp.date.now("YYYY-MM-DD") %>_PokéVaultPlugins.md "/media/wm/Birch/Church/GitHub/PokeVault/PokéVault/zxc/pl"

cp /media/wm/Birch/wn/UnArchives/PokéVault-backups/2022/Q3/<% tp.date.now("YYYY-MM-DD") %>_PokéVaultPlugins.md "/media/wm/Birch/Church/GitHub/PokeVault/Active-Plugins.md"

cp -u -r /media/wm/Birch/Church/Obsidian/PokéVault /media/wm/Birch/Church/GitHub/PokeVault
```
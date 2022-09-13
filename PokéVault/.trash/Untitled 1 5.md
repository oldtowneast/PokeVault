```shell
tar -cvf 2022-09-12_PokéVault.tar.gz --exclude={"/media/wm/Birch/Church/Obsidian/PokéVault/.trash","/media/wm/Birch/Church/Obsidian/PokéVault/.obsidian"} /media/wm/Birch/Church/Obsidian/PokéVault/

tar -cvf 2022-09-12_PokéTrash.tar.gz /media/wm/Birch/Church/Obsidian/PokéVault/.trash

ls /media/wm/Birch/Church/Obsidian/PokéVault/.obsidian/plugins |& tee -a 2022-09-12_PokéVaultPlugins.md

cp /media/wm/Birch/wn/UnArchives/PokéVault-backups/2022/Q3/2022-09-12_PokéVaultPlugins.md "/media/wm/Birch/Church/Obsidian/PokéVault/zxc/wn/ple"

cp /media/wm/Birch/wn/UnArchives/PokéVault-backups/2022/Q3/2022-09-12_PokéVaultPlugins.md "/media/wm/Birch/Church/GitHub/PokeVault/Active-Plugins.md"
```
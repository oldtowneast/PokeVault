```shell
tar -cvf <% tp.date.now("YYYY-MM-DD") %>_CPB.tar.gz --exclude={"/media/wm/Birch/CPB/.trash","/media/wm/Birch/CPB/.obsidian"} /media/wm/Birch/CPB/

tar -cvf <% tp.date.now("YYYY-MM-DD") %>_CPB-trash.tar.gz /media/wm/Birch/CPB/.trash

ls /media/wm/Birch/CPB/.obsidian/plugins |& tee -a <% tp.date.now("YYYY-MM-DD") %>_CPB-plugin-list.md

cp /media/wm/Birch/wn/UnArchives/CPB-backups/2022/Q3/<% tp.date.now("YYYY-MM-DD") %>_CPB-plugin-list.md "/media/wm/Birch/CPB/3 - Resources/Obsidian/ple/"

cp /media/wm/Birch/wn/UnArchives/CPB-backups/2022/Q3/<% tp.date.now("YYYY-MM-DD") %>_CPB-plugin-list.md "/media/wm/Birch/Church/GitHub/-obsidian/Active-Plugins.md"
```
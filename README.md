# add_no_steam_game
这个项目是给想要添加非steam游戏的C#脚本，希望能够帮助到大家
## 如何使用这个项目
```
ShortHelper.ShortcutWriter.Add_no_steam_game(Shortcut sc, string path_to_shortcuts) //加入steam
ShortHelper.ShortcutReader.ReadShortcuts(string pathToShortcuts) //读取文件 return List<Shortcut>
```
##   `shortcut`文件
为steam在存储游戏的数据结构，想要详查看请参考 https://gist.github.com/gablm/2a79355026bde51ac4f516d347fa1cd0
##  `ShortHelper`文件
```
|-ShortHelper
|---ShortcutPhrase
|---ShortcutWriter
|---ReadShortcut

```

详细请看具体文件

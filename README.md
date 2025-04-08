# add_no_steam_game
This project is the Csharp script to make the no steam game add steam's management     
## How to use
1. download this code to your project in place
2. copy the code 
```
ShortHelper.ShortcutWriter.Add_no_steam_game(Shortcut sc, string path_to_shortcuts) //加入steam
ShortHelper.ShortcutReader.ReadShortcuts(string pathToShortcuts) //读取文件 return List<Shortcut>
```
##  shortcut
this is no_steam_game saved  data struct. Please refer to for details to https://gist.github.com/gablm/2a79355026bde51ac4f516d347fa1cd0
##  ShortHelper
```
|-ShortHelper
|---ShortcutPhrase
|---ShortcutWriter
|---ReadShortcut

```



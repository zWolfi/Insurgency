# Insurgency
Mod for insurgency sourcemod.

 * <a href='#CMap'>CMap</a>
 * <a href='#botcount'>Botcount</a><br><br>


### CMap
CMap is use to change map. It a really simple plugin. I made this because someone saying the sm_map off from sourcemod not working in insurgency.<br>
Admins with flag b will able to use this command.

#### Plugin
[plugins/CMap.smx](https://github.com/AzumiNeko/Insurgency/blob/master/plugins/CMap.smx?raw=true)

#### Source
[scripting/CMap.sp](https://github.com/AzumiNeko/Insurgency/blob/master/scripting/CMap.sp)

#### Command List
```
cmap <map name> <gamemode>
changemap <map name> <gamemode>
```

#### Example
```
cmap sinjar_coop checkpoint
changemap sinjar_coop checkpoint

cmap sinjar hunt
```<br><br>


### Botcount
Botcount plugin is to use to fix the coop bot count issue.<br>
There is no config file for this.<br>
All you have to do is download and put it in your plugins folder and have it load then it finish.<br>
(This is a reharsh version from jared ballou coop lobby overwrite)<br>

#### Plugin
[plugins/botcount.smx](https://github.com/AzumiNeko/Insurgency/blob/master/plugins/botcount.smx?raw=true)

#### Source
[scripting/botcount.sp](https://github.com/AzumiNeko/Insurgency/blob/master/scripting/botcount.sp)

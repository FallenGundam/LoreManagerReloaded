# LoreManagerReloaded
可使用GUI來方便編輯物品的敘述  
只需手持物品輸入指令/lm 即可

# Version Required
* spigot or paper: 1.13.2 ~ 1.19.3
* skript 2.3.7 ~ lastest

# command:
* /loremanager, /lm  
* permission: lm.admin  


# API:  
### item creator  
* type: item type  
* amount: item amount  
* name: custom name of item  
* lore: string list  
* damage: damage of itme  
* ench: enchant list  https://skripthub.net/docs/?id=2143  
* unb: unbreakable  
* example:
```
        set {_lore::*} to "&aline1" and "&bline2"
        set {_enchant::*} to Loyalty and Power
        give createitem(iron sword,5,"&ethis is sword",{_lore::*},1,{_enchant::*},true) to player
```

此腳本為參考插件Loremanager所製作  
https://www.spigotmc.org/resources/%E2%99%9B-loremanager-%E2%99%9B-1-8-8-1-12-x-%E2%9C%94.44724/

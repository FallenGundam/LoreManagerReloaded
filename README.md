# LoreManagerReloaded
use gui to edit item lores


command:
   /loremanager , /lm : open lore manager gui  
	permission: lm.admin  


API:
	item creator  
	 type: item type  
	 amount: item amount  
	 name: custom name of item  
	 lore: string list  
	 damage: damage of itme  
	 ench: enchant list  https://skripthub.net/docs/?id=2143  
	 unb: unbreakable  

     example:
        set {_lore::*} to "&aline1" and "&bline2"
        set {_enchant::*} to Loyalty and Power
        give createitem(iron sword,5,"&ethis is sword",{_lore::*},1,{_enchant::*},true) to player


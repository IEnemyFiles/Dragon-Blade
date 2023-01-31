List of ItemData:

- Equipment

- Weapon 

- HorseEquipment

- Dragon

- Emote

- Treasure

- Utility

- BannerCustomization

- Projectile

- Currency

- Ability

- Tool

- All -- Unlock all Recipes & Get All Items (Must have bigger inventory)
==================================================================================================================
getgenv().TypeData = "All" -- Change this to what item type you want

loadstring(game:HttpGet("https://raw.githubusercontent.com/IEnemyFiles/Dragon-Blade/main/UnlockAll", true))()
==================================================================================================================
use this if you want to get specific item.

how to use:
1. Open dark dex
2. Go to replicated storage > SharedData > ItemData


![image](https://user-images.githubusercontent.com/89214182/215686003-626be521-2174-4b68-86f7-3e359ad87f50.png)



3. then pick a folder you want and put it in "ItemDatas"



![image](https://user-images.githubusercontent.com/89214182/215686089-709d87e6-0bed-4b7d-ad4b-bcff7e9cee92.png)



4. then get the name item and put it in "Item" and then execute



![image](https://user-images.githubusercontent.com/89214182/215686139-06dbbc87-8a9b-4243-ac5a-978712cbabae.png)


==================================================================================================================


getgenv().ItemDatas = "Projectiles"
getgenv().Item = "CO_Truffle"

loadstring(game:HttpGet("https://raw.githubusercontent.com/IEnemyFiles/Dragon-Blade/main/GetNewItem.lua",true))()


==================================================================================================================


loadstring(game:HttpGet("https://raw.githubusercontent.com/IEnemyFiles/Dragon-Blade/main/CompleteAllQuest", true))()


==================================================================================================================

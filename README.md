Some basic Ore Monitor script to show your currect stock in one or multiple screens by utilizing only one PB while having option to change what is shown on screens by simply clicking on them. Vertical or horizontal view can be picked and in case you need you can click on any tier to only show it. Databank will help out in keeping saved options next time you activate PB, so once set it will run without any need to reset it

![](http://www.zrips.net/wp-content/uploads/2020/10/main.jpg)
![](http://www.zrips.net/wp-content/uploads/2020/10/mainh.jpg)
![](http://www.zrips.net/wp-content/uploads/2020/10/tier1.jpg)
![](http://www.zrips.net/wp-content/uploads/2020/10/tier1h.jpg)

Requirements:
- Programable Board
- Screen (M sized recommended)
- DataBank

PB Setup:
- Connect Databank and Core unit to ProgramableBoard. In what order you do that doesn't mater.
- Connect to screen
- Copy script code from [**HERE**](https://raw.githubusercontent.com/GcGoat/DU-OreMonitor/main/json "HERE") (**ctrl+a** and then **ctrl+c**) go back into game, right click PB -> Advanced -> Paste Lua Configuration from Clipboard

Container setup:
- For containers to be properly recognized you will need to rename them. Ore containers can only contain one type of ore and its name should reflect its contents, for example bauxite container needs to have name as **Bauxite Ore** and gold one shopuld be as **Gold nuggets Ore**

Names of ore containers:
 - Bauxite Ore
 - Coal Ore
 - Hematite Ore
 - Quartz Ore
 - Chromite Ore
 - Malachite Ore
 - Limestone Ore
 - Natron Ore
 - Garnierite Ore
 - Petalite Ore
 - Acanthite Ore
 - Pyrite Ore
 - Cobaltite Ore
 - Cryolite Ore
 - Gold nuggets Ore
 - Kolbeckite Ore
 - Rhodonite Ore
 - Columbite Ore
 - Illmenite Ore
 - Vanadinite Ore

Names of pure containers:

 - Pure Aluminium
 - Pure Carbon
 - Pure Iron
 - Pure Silicon
 - Pure Chromium
 - Pure Copper
 - Pure Calcium
 - Pure Sodium
 - Pure Nickel
 - Pure Lithium
 - Pure Silver
 - Pure Sulfur
 - Pure Cobalt
 - Pure Fluorine
 - Pure Gold
 - Pure Scandium
 - Pure Manganese
 - Pure Niobium
 - Pure Titanium
 - Pure Vanadium
 - Pure Oxygen
 - Pure Hydrogen
 
 
 Aditionally you might want to check lua variabels and modify couple main ones which are responsible for colculating container sizes. Right click PB -> Advanced -> Edit Lua parameters

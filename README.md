Some basic Ore Monitor script to show your currect stock in one or multiple screens by utilizing only one PB while having option to change what it shows on screens by simply clicking on them. Vertical or horizontal view can be picked and in case you need you can click on any tier to only show it. Databank will help out in keeping saved options next time you activate PB, so once set it will run without any need to reset it

![](http://www.zrips.net/wp-content/uploads/2020/11/showtime.jpg)

Requirements:
- Programable Board
- Screen (M sized recommended)
- DataBank

Usage:
While screens are showing information you have option to click on any tier to only show that one. Aditionally you have button on size of screen marked as (>) which will open settings tab like
![](http://www.zrips.net/wp-content/uploads/2020/11/settings.jpg)
You will see 5 numeric fields, one with sign "+" and one as "R", on another side button labeled as "Reset"
Numeric fields will change colors for specific areas.
 First field changes brogress bar colorization, first 7 options uses gradient from one color to another which will change depending on stock amount you currently have, while rest of them are static colors.
 Second will define background color of progress bar
 Third field will define color of text inside of brogress bars. 
 Fourth defines main text, like ore name or tier
 Fifth defines main background color
Field labeled as "+" will apply same setttings on all screens connected to same PB, this is usefull if you are too lazy to go trough all of them and change them to match main theme each time you adjust something
Field labeled as "R" will rotate view
On oposite side you will have "Reset" button which resets colo values to default ones. This will not reset orientation or set tier which needs to be shown

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
 
 
 Aditionally you might want to check lua variabels and modify couple main ones which are responsible for calculating container sizes. Right click PB -> Advanced -> Edit Lua parameters
 
 Known issues: In case you have max amount of screens connected to one PB you might encounter issue with it using to much of CPU for initialization. This is only issue if all of them shows maximum amount of information. Work around would be to start by using only couple screens, set them to your needs and then connect rest of them

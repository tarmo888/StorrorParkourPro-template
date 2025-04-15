# Template for modding Storror Parkour Pro
This is a template for modding Storror Parkour Pro main open-world map. It has all the changes done to get started with your own map, so you can easily just package the *.pak patch files to override the main map.

## Getting Started
* Download & Install Unreal Engine 5.5.* https://www.unrealengine.com/en-US/download
* Download this template
* Open `StorrorParkourPro.uproject` with Unreal Editor
* Remove the example blockout and build your own

## Creating The Patch Files
* Create `Build` folder inside the project folder
* In Unreal Editor, click Platforms -> Windows -> Package Project
* Select `Build` folder for packaged project

## Applying The Patch Files
* Go to `Build\Windows\StorrorParkourPro\Content\Paks\` folder inside your project folder
* Copy `pakchunk4564-Windows.*` files to `C:\Program Files (x86)\Steam\steamapps\common\STORROR Parkour Pro\STORRORParkourPRO\Content\Paks`
* Rename `pakchunk4564-Windows.*` files to `pakchunk4564-Windows_P.*`
* Play the game with your own map

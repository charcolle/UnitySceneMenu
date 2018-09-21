[日本語のREADME](README.ja.md)
  
# UnitySceneMenu v1.1
This is a tool for easy control of multi-scene-editing.   
Available on AssetStore: https://assetstore.unity.com/packages/tools/utilities/unityscenemenu-111222

![unityscenemenu_screenshot](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu.png)

## Supported Unity versions  
Unity5.4 or higher  

# Usage
You can load/unload scenes easily by registering scenes to UnitySceneMenu.
Also you can set Build-Settings automatically.

You must register the scenes to a menu before using UnitySceneMenu.  

### ◆Config

1. Open UnitySceneMenu-Config. [Window]-[SceneMenu]-[Config]
2. Create a menu by pushing [+] button in the left column. You can edit the name of the menu by selecting [Edit] toggle. You can delete the menu by pushing [-] button.
3.  After selecting the menu, all scenes in your project are shown in the right colmn and then select the scenes you want to register to the menu. You can search your scene at search bar easily. You can delete the scene from the menu by deselecting the scene or by pushing [-] button int the center colmn.  
  
*NOTE : The scene which has a scene icon is in your build.*  

![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_1.gif)

### ◆SceneMenu
1. Open UnitySceneMenu. [Window]-[SceneMenu]-[Scenes].
2. The Scenes which you registered to the menu are shown. You can load/unload the scenes very easily.
3. The dropdown menu has the menu you created. You can switch a menu by selecting other menu from the dropdown menu.  
  
*NOTE:*  
*1. The scene at the top of the menu is loaded at first. The other scenes are shown at the hierarchy in not loaded state.*  
*2. When switching a menu, the  all scenes in before menu are unloaded and the new scenes are loaded.*  
*3. You cannot switch a menu nor select the scenes in editor-playing mode.*    

![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_2.gif)
  
4. You can load a single scene when select the scene with holding the left-ctrl key. 
  
![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_3.gif)
  
### ◆Auto SetUp BuildSetting
1. You can use auto-setup BuildSettings from *Build Menu*.
2. Enable *Use Auto BuildSetting* and drag and drop the directory to *BuildScene RootPath*  which has build scenes.
3. You can select the first scene. Drag and drop the scene of first to *FirstScenePath*.
    
![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_4.gif)

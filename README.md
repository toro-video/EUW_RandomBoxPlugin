# EUW_RandomBoxPlugin
　**Random props placement tool available in UE5.1 and above**  
　![IMG_Overview](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_Overview.png)  

# Download this plugin
## 1.Download this plugin from GoogleDrive
　https://drive.google.com/file/d/1YTATZnKw3SzPBFFkaKMjyIobUeaumdGg/view?usp=drive_link

## 2.Add this plugin to your project
　**※This plugin is available for UE5.1 and above.**  
　As you may know, to use this plugin, place "EUW_RandomBoxPlugin" under the Plugins folder.  
　

# How to use  
## Instructional Video  
　**Japanese only**  
　このプラグインの使い方を説明する動画です。  
　https://drive.google.com/file/d/1lfNxUcdGj5Nr3t0AN01p7ixlMbPxrtg6/view?usp=sharing  

## Description in English  
　**Explanation of how to use this plugin in English**  

### 1.Place Random Box  
　First, from the plugins you have added, place BP_RandomBox where you want to place the props.  
　At this point, align the bottom of the box with the location where you want to place it (e.g. on a desk).  
　The props to be placed are also determined by whether they are less than to the size of this box.  

### 2.Start the EUW_RandomBox  
　Run EUW_RandomBox.  
　As you may know, you can start it by right-clicking and clicking on 'Run editor utility widget', for example.  

### 3.Tool UI description  
　**(a)Box settings**  
　　「箱の設定」: Box setup.  
　　　![IMG_BoxEdit](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_BoxEdit.png)  

　　Checkbox : Whether to operate on all boxes on the level or only on the selected box.  
　　「メッシュの個数」Spinbox : Number of props and meshes to be placed.  
　　「ループの上限値」Spinbox : Number of times to repeat until the specified number of props are placed.  
　　Spinbox is determined by pressing the side button.  

　**(b)Path settings**  
　　「箱にパスを設定」: Set paths to boxes.  
　　　![IMG_EditPath](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_EditPath.png)  
  
　　The folder selected in the content browser is added to the box by pressing the 'パスを追加' button.  
　　The object where the static mesh contained under the folder you have added will be placed.  
　　*Pressing the 'パスを削除' button deletes the path registered in the box.  

　**(c)Placement method**  
　　「配置方法の設定」: Setting the placement method.  
　　　![IMG_Algorithm_Spawn](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_Algorithm_Spawn.png)  

　　This item sets how the arrangement is made.   
　　By default, the mesh is placed in random positions and at random angles.  

　　You can configure settings for the following.  
　　　・ランダム配置/グリッド配置 : Random or Grid placement.  
　　　・置き換え/追加配置 : Replace or Add.  
　　　・大きい順にスポーン : Whether to place them in order of size.  
　　　　true: The specified number of meshes are more likely to be placed.  
　　　　false: The size is more likely to be sparse.  
　　　・Z軸を基点にランダム回転 : Random rotation around the Z-axis.  

　**(d)Placement**  
　　Press the green button to perform the placement.  
　　Once placement is complete, the box should be erased.  

### 4.Eraser Mode  
　　You can switch to '消しゴムモード' by pressing the eraser button at the top of the tool.  
![IMG_BeforeEraser](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_BeforeEraser.png)  

　　BP_EraserBox can be placed on the level and traced over the mesh to be erased.  
![IMG_AfterEraser](https://github.com/toro-video/EUW_RandomBoxPlugin/blob/images/IMG_AfterEraser.png)  

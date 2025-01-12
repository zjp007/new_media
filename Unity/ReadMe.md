# About

- [Unity Tools (EN)](#Unity Tools (EN))
  - [Serial Select and Pause UI](#Serial Select and Pause UI)
    - [Serial Select](#Serial Select)
    - [Pause UI](#Pause UI)
  - [MyGameTools](#MyGameTools)
- [Unity 工具 (中文)](#Unity 工具 (中文))
  - [串行选择和暂停用户界面](#串行选择和暂停用户界面)
    - [串行选择](#串行选择)
    - [暂停用户界面](#暂停用户界面)
  - [MyGameTools-中](#MyGameTools-中)

## Unity Tools (EN)

> Unity >=2021.3, Try other versions on your own

### Serial Select and Pause UI

#### Serial Select

1. Import `SerialSelectAndPauseUI-x.x.unitypackage`

2. Can be used separately

   ![image-20250112164816281](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112164816281.png)

3. The serial port may report an error

   ![image-20250112165005688](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165005688.png)

4. Replacing the .NET Framework version will do

   ![image-20250112165131453](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165131453.png)

5. Drag the prefab directly into the Canvas.(Need Import TMP Essentials)

   ![image-20250112165356145](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165356145.png)

6. About Serial Select

   ![image-20250112170141532](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112170141532.png)

   1. When the number of serial ports changes, the drop-down box is updated to select a serial port
   2. The data received by the serial port should be accessed directly using  `SerialPortUtils.RecData`  (Use a separate thread to accept serial port data, update once in 0.1s)
   3. Secondary processing of the serial port data can be selected in the box above.

#### Pause UI

- You can execute other code while the game is paused or resumed

![image-20250112170746326](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112170746326.png)

### MyGameTools

1. Import `MyGameToolsScript-x.x.unitypackage`, It’s only a Script

   ![image-20250112171013569](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171013569.png)

2. Include 2D/3D Mouse Click detection, and some Coroutines

   ![image-20250112171420302](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171420302.png)

3. How to use

   > For example, if you click on the box, the box rotates by 45 degrees.

   ![image-20250112171606847](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171606847.png)

   ![image-20250112171831173](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171831173.png)

   ![image-202501124564646](D:\Document\GitHub\new_media\Unity\Imgs\MyGameTools-01.gif)



## Unity 工具 (中文)

> Unity >=2021.3，请自行尝试其他版本

### 串行选择和暂停用户界面



#### 串行选择

1. 导入 `SerialSelectAndPauseUI-x.x.unitypackage`

2. 可单独使用

   ![image-20250112164816281](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112164816281.png)

3. 串行端口可能会报错

   ![image-20250112165005688](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165005688.png)

4. 替换.NET Framework 版本可以做到

   ![image-20250112165131453](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165131453.png)

5. 将预制板直接拖到 Canvas 中（需要Import TMP Essentials）

   ![image-20250112165356145](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112165356145.png)

6. 关于串行选择

   ![image-20250112170141532](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112170141532.png)

   1. 当串行端口数发生变化时，下拉框会更新以选择串行端口
   2. 使用 `SerialPortUtils.RecData` 直接访问串口接收到的数据（使用单独的线程接受串口数据，0.1s 更新一次）
   3. 可在上面的方框中选择对串行端口数据进行二次处理。

#### 暂停用户界面

- 您可以在游戏暂停或恢复时执行其他代码

![image-20250112170746326](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112170746326.png)

### MyGameTools-中

1. 导入 `MyGameToolsScript-x.x.unitypackage`, 这只有一个脚本

   ![image-20250112171013569](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171013569.png)

2. 包含 2D/3D 鼠标点击检测和一些 Coroutines（协程）

   ![image-20250112171420302](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171420302.png)

3. 如何使用

   > 例如，点击方框，方框会旋转 45 度。

   ![image-20250112171606847](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171606847.png)

   ![image-20250112171831173](D:\Document\GitHub\new_media\Unity\Imgs\image-20250112171831173.png)

   ![image-202501124564646](D:\Document\GitHub\new_media\Unity\Imgs\MyGameTools-01.gif)

[#Unity 工具 (中文)]:

[#Unity 工具 (中文)]:
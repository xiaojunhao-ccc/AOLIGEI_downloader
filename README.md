# README

## 一、AOLIGEI下载器使用说明

### 功能
可以支持bilibili、Youtube、Pornhub等视频网站的视频下载.

### 1.0 声明

该程序仅仅用于**学习用途**！！！
该程序仅仅用于**学习用途**！！！
该程序仅仅用于**学习用途**！！！
请**严禁**用作**非法用途**！！！  **法网恢恢，疏而不漏**！！！ 请**尊重版权**、**合理合法科学上网**！！！！
若不遵守！ 后果请**自负**！！！（~~~监狱饭真香~~~）




### 1.1 下载完解压后点击exe文件运行如图所示

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220113152255190.png)  


​	![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220113152329344.png)  


（此处再次进行提醒：  **请不要用作非法用途！！！ 也严禁倒卖！！！** 如果有此类行为请报警！！！）



### 2.2 输入你想下载的视频链接（按照提示格式）和保存的地址就可以开始下载了

点击 “开始下载” 后会出现一个**小弹窗**（**提示：可能会无响应一会儿，但程序并没有卡死！！我只是在检查你的URL是否可以访问，请稍后！**）,请不要害怕和惊慌，因为这只是一个温馨的提示，提示你待会儿可能会有一小段**程序无响应**，（其实可以开个线程来检测URL，这样就不会卡死了），但是我懒哈哈哈，所以就这样吧，等待几秒（取决于你的网速）就好啦！

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220113153335749.png)  






### 2.3 取消/暂停按钮

在这个程序里面没有取消和暂停其实差不多，因为你取消后，如果还想下载这个被取消的视频时，它会**接着你没下完的部分继续下**！ 在取消或暂停后，你也可以在输入框中输入其他的视频URL地址，然后再点击开始下载，它会下载你新输入的地址所对应的视频。



### 2.5 下载完成后，被下载的视频会出现你所输入的保存地址下

下载完成后，该小程序会**自动结束**（其实是闪退，有大佬能帮我解决就太感谢了！），你可以到你的保存地址下找到该视频进行直接观看（**但请不要传播**），或者直接删除嘿嘿！



## 二、源代码使用注意事项

### 2.1、使用前的准备

**2.1.1. 下载PhantomJS：**

地址： https://phantomjs.org/download.html  

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220111225156382.png)


下载完成后是一个压缩包（如图）

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220111230012170.png)  
将安装包解压得到（如图）

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220111230114420.png)  

进入bin目录，复制里面的**phantomjs.exe**文件放到你的<u>python安装目录</u>**或者**你的<u>py项目文件目录</u>（如图）

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220111230230232.png) 

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220113151910257.png)  

**2.1.2. 安装必要的第三方库：**
python提示缺什么库安装什么库（pip install 库名），不会就百度吧！

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220111225834773.png) 






## 四、 还存在的问题（求大佬来解决）

为什么有的QThread用terminate结束会直接把程序卡死.....  

![image](https://github.com/xiaojunhao-ccc/AOLIGEI_downloader/blob/main/readme%E8%AF%B4%E6%98%8E%E5%9B%BE%E7%89%87/image-20220113155407106.png)  



## 三、心得和经验和其他

1. QT中千万要谨慎使用线程去更新GUI（如改变progressBar的值），应该采用**信号和槽**来更新!!!!
2. Qt对Python太不友好了，一堆小麻烦.....
3. 感谢开发`youtube_dl` 库的大佬作者！！！！！







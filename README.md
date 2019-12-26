# JAV-Scraper-and-Rename-local-files
收集jav元数据，并规范本地文件（夹）的格式，为emby、kodi、jellyfin收集女优头像。  
python3.7  使用pyinstaller打包成exe。  
如果要运行py文件，PIL即pillow不要用新版，新版仅支持“png”，我是“pip install pillow==6.0.0”  
百度人体分析的“from aip import AipBodyAnalysis”，aip是“pip install baidu-aip”  
另外需要mac、linux系统下的同志帮忙发布各系统的发行版，要改代码，windows的路径是反斜杠“\”。  

[前往下载exe](https://github.com/junerain123/JAV-Scraper-and-Rename-local-files/releases/tag/V1.0.1)
  或者[从蓝奏云下载](https://www.lanzous.com/i85lzcb)  

[前往下载女优头像](https://github.com/junerain123/JAV-Scraper-and-Rename-local-files/releases/tag/女优头像)   

[电报群](https://t.me/javsdtool)  
企鹅群被“端”了  



工作流程：  
1、用户选择文件夹，遍历路径下的所有文件。  
2、文件是jav，取车牌号，到javXXX网站搜索影片找到对应网页。  
3、获取网页源码找出“标题”“导演”“发行日期”等信息和DVD封面url。  
4、重命名影片文件。  
5、重命名文件夹或建立独立文件夹。  
6、保存信息写入nfo。   
7、下载封面url作fanart.jpg，裁剪右半边作poster.jpg。   
8、移动文件夹，完成归类。  

目标效果：  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/1.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/2.png)  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/3.jpg)  

以下为ini中的用户设置：  
  
![image](https://github.com/junerain123/Collect-Info-and-Fanart-for-JAV-/blob/master/images/4.PNG)  

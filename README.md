# 简介

这是一个向[废话胶囊（b言b语）](https://github.com/daibor/nonsense.fun)发送内容的简单 Tasker 工程。

https://sspai.com/post/60024


# 效果展示

<img src="https://i.loli.net/2020/04/22/Hy7kwJL8FDr6I5O.png" style="zoom: 13%;" />

# 安装配置

**！！注意：该项目仅在root环境里使用通过，非root环境可以关掉 *场景/Main/发送/按下* 中第5个和第6个任务里的“使用Root“选项后自行尝试！！**

<img src="https://i.loli.net/2020/04/22/iaTO5gAQLjnufBZ.png" style="zoom:33%;" />

<img src="https://i.loli.net/2020/04/22/SIJivZ5L4Na9Cu3.png" style="zoom:33%;" />

<img src="https://i.loli.net/2020/04/22/HNhvpO5JQLDyISc.png" style="zoom:33%;" />

<img src="https://i.loli.net/2020/04/22/7BoIjaJL9h6ilf1.png" style="zoom:33%;" />

1. 将本项目里的``bb.prj.xml``存入手机任意你找得到的位置

2. 下载安装Tasker

3. 进入主界面长按左下角的按钮，点击`导入项目`，在打开的界面中找到并打开刚才存入的`bb.prj.xml`

   <img src="https://i.loli.net/2020/04/22/mpwnk2ZWvMc6uSU.png" style="zoom:33%;" />
   
   <img src="https://i.loli.net/2020/04/22/3Zc2KIWVfBzhiDM.png" style="zoom:33%;" />
   
   > 提示：点击右下角的手机按钮可以快速回到内部储存空间目录
   >
   
4. 完成后回到主界面，点击应用栏里图标长得和Tasker很像的`Tasker Secondary`，打开界面

   <img src="https://i.loli.net/2020/04/22/Gju9BY64UsWlvTw.png" style="zoom:33%;" />

   <img src="https://i.loli.net/2020/04/22/Hy7kwJL8FDr6I5O.png" style="zoom:33%;" />

5. **长按**发送按钮，打开设置页面进行必要设置

   <img src="https://i.loli.net/2020/04/22/YM5CJ6vb4OIdemy.png" style="zoom:33%;" />

   **Title：**这里是发送界面顶端的文字，请随意修改

   **AppID、MasterKey：**网页打开LeanCloud，在你的项目里点击``设置/应用Keys``，复制对应的密钥分别填入

   ![](https://i.loli.net/2020/04/20/Kaxt5GOo3LRgMmy.png)

   **className：**一般是`content`，只要你是按照[少数派的指南](https://sspai.com/post/60024)来做的话

   **--insecure：**是否在脚本命令末尾加上`--insecue`参数。默认关闭，如果无法发送可以尝试打开这个选项试试。
   
   **完成后点击确认返回**

这样就配置完成了，请试试看吧！

# 使用方法

## 通过 Tasker Secondary 打开

<img src="https://i.loli.net/2020/04/22/Gju9BY64UsWlvTw.png" style="zoom:33%;" />

## 通过桌面快捷方式打开

1. 打开Tasker，然后**点击返回键**回到主界面

2. 在桌面上新建Tasker的桌面小部件"任务"

   ![]()

   选择`Show UI`

   <img src="https://i.loli.net/2020/04/22/QWRPd7IKmV3oXYj.png" style="zoom:33%;" />

   在界面下方选择图标，然后点击左上角返回桌面

   <img src="https://i.loli.net/2020/04/22/t5dlHRyUgDM7aKX.png" style="zoom:33%;" />

   完成

## 导出为APK安装

1. 菜市场安装`Tasker App Factory`

2. 打开Tasker，主界面左下方长按选择已经导入的项目

   <img src="https://i.loli.net/2020/04/22/peARXFgoinvOJzx.png" style="zoom:33%;" />

3. 选择`导出\作为应用`

   <img src="https://i.loli.net/2020/04/22/pWGezM69XUa3OVj.png" style="zoom:33%;" />

4. 根据提示输入包名和版本号

   <img src="https://i.loli.net/2020/04/22/Q7nXMpqxhB5o8a3.png" style="zoom:33%;" />

5. 点击左上角返回，Tasker会进行导出并安装

# 后记

界面如果有问题可以自行在Tasker的`场景`中修改。

个人能力有限，做的比较粗糙，还请见谅！

欢迎交流！

# Alternative Peru

## Clone项目至本地

1. 打开Atom，如果目前有打开的项目，右击当前项目名称，选择remove project folder。没有的话，进入下一步。
2. 打开GitHub标签页，点击Clone an existing GirHub repository。
3. Clone from输入：https://github.com/ChinaGoingOut/AlternativePeru.git
4. 设置好本地文件夹位置后点击Clone。

## 调试项目

本次项目只可以从Atom内进行本地测试。

Package -> atom-live-server -> start server

会用默认浏览器打开，如果想换浏览器可以复制地址链接再用别的浏览器打开即可。

## 编辑项目

每位同学负责一部分HTML文件，本周日明确分工。

首页 index.html

行程 tour.html

中国青年在秘鲁 cgo.html

博客 blog.html

关于我们 aboutus.html

## 注意

- 编辑项目之前首先**fetch**拉取服务器最新版本。完成编辑后上传修改的步骤：stage changes -> 输入commit message -> commit -> push

- 编辑项目首先确认自己的任务什么，完成任务后**本地测试无误**后再推送到服务器，在commit message中**详细描述**自己的修改内容。

- 切忌推送**半成品**代码。否则有可能给其他成员带来困扰，让其他组员误以为自己写的部分有问题导致页面加载不对。

- 不要过于频繁的推送代码。

- 出现版本冲突后，谨慎更新。这点非常重要，请注意避免覆盖你的队友已经更新好的代码。


## 小贴士

### 推送代码至服务器 - git相关

1. Ctrl+S保存文件（保存成功后会变色）
2. 点击Git标签页右上角stage all changes的按钮
3. 输入commit message(描述你做了哪些修改)
4. 点击commit to master按钮（成功后会在按钮下方出现记录，且fetch按钮变成push）
5. 点击push（成功后会变回fetch）

### 添加图片 - 绝对路径 v.s. 相对路径

1. 使用img标签。
2. 给src属性指定路径。

如果是网上的一张图片，可以通过右击图片选择复制图片地址来获得该图片路径，这种路径也是绝对路径。这意味着如果将来这个图片所在的服务器删了这张图片，那么链接失效后你的图片也会显示失败。

如果是本地的一张图片，可以复制到本机的项目文件夹中。如果找不到本地的项目文件夹，可以打开Atom，右击项目名称，选择Open in Explorer，这样就会出现你的本地项目所在文件夹的窗口。如果图片比较多，建议新建一个img文件夹专门存储图片。本次项目建议同学们把图片存在img文件夹，相对路径就是"img/[filename]"。

## 答疑

**Push的时候出现如下报错**

![no git](https://lh3.googleusercontent.com/KeSxM9pmwy3PzflG3E143PsIN6oMvcAuBfKnEFVrrs6X0vjH1OGjFEA780xyWsTvPDHdnwDPv9u7NKlb7sq6-sX3sLN-8tSFlrlZ8isEvNIXUqjHRTD4Xxo_f10QYQmXXOPNyPHveLPWjqfXf_3VuzplSCz4fJ1E-x-i2XasLDQ469u2yfzr4hsyZaVEivbaKsR5Ca0Dm7lAuE_4vl0xpajFsvOlx4Txf05rCUPSB_YTo6HEDcW4o1PJNo3_CutkLX2Br-TBrcjBe4nv6e2gYzfv8koMVMHO-VLIvUhv3v8XIOdaWH45Qd-PAE2CV_vQN12vk5ZwAGUWQ3IJALvkfkmNsso__lWYO3GfRKCggpC_wHKQgx3rXTwyaFefMaAp-GtB6YkLdRkPIv3nvFXXk1XsZ9QhHAL_JzTXZTi4JnQbiy94ZLJMPaPMIG3jmVeBn58zjaoa2Mj6Vw5e2U-YYpUd6_t1n3T5zSbpXgLSDuWg3dAAbfmvLRdXSEhVSJpHQ6mdHkzcX3_vuiJLQeXGALS_F21UwsEAmA_wmvgUbTUUHPOstEakdRZfR1JesJ3Pnh6JsvOj4ZPdvqQrd4M6gP1WGjNcoMRm-YqOMjB1U3VdE3Gqb_b0R8Arv2ydV8aff4NpaQR3Y7U8r8dtrIxJ-4R84IsQTDikqzm87vYhUGvoZGfuYtCfjTmsnfEmWqSDDWa39QIwdh-yhPnIHjhzOfzHQZe0CBMwl-BEV2HNYtxShTkwj_bnKE4=w632-h247-no)
- 出现这个错误的原因是本地没有安装Git。解决方式是安装Github Desktop，关联自己的账号后，email设置为Github使用的邮箱，name设置为Github用户名。安装文件我已经发给星宇老师，如果无法从[官网](https://desktop.github.com/)下载，同学们也可以从网盘中下载。

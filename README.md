# ionic-wechat
## 介绍
  这是一个学习Ionic的练习项目，模仿微信，开发的一款App
  初步要是实现的功能：   
    1. 界面要像，呵呵   
    2. 聊天消息列表，查看对话内容，来了消息推送提醒   
    3. 通讯录展示，好友搜索，右侧字母快速索引  
    4. 朋友圈展示，发朋友圈消息   
    5. 扫一扫， 摇一摇功能   
    6. 设置功能，设置消息提醒方式，设置聊天背景，关于等  
    
## 顺带记录开发中遇到的坑
 1. ion-header-bar和 ion-nav-bar同时存在的时候,ion-nav-bar会覆盖掉ion-header-bar
    要想有一个固定的header就把ion-header-bar注释掉
    ion-nav-bar可以根据切换的views不同设置不同的标题，而且可以有回退键,可以根据需要自己切换
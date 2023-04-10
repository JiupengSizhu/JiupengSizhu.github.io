> # 当前版本:v1.0.0

## 简介

+ 该项目是一款基于微信小程序+云开发集成的编程技术知识交流平台。平台通过大数据分析和排序，让用户能够快速、准确地找到想要学习的编程技术知识，并支持用户之间的交流和互动。
+ 用户可以在平台上发布、分享、评论和点赞知识内容，与其他用户进行交流和学习。该平台旨在为广大编程技术爱好者提供一个高效、便捷的学习交流平台，提高学习效率，提升用户之间的交流体验。


## 文件夹结构介绍

<img src="https://i.postimg.cc/LXMKzsVq/1.png" mode="weight"/>  

<img src="https://i.postimg.cc/gJq94PMg/2.png"  mode="weight"/> 

<img src="https://i.postimg.cc/kgzdgs6v/3.png"  mode="weight"/> 



## 功能介绍

+ 1
	+ 首页轮播图
	+ 分类列表
	+ 文章列表
	+ 专题页功能
	+ 排行榜功能
	+ 分享功能
	+ 文章详情页面设计

+ 2
  + 点赞及取消点赞功能
  + 评论及恢复功能
  + 记录浏览的文章
  + 记录点赞的文章
  + 我的页面设计
  +  富文本编辑

+ 3
	+ 生成海报图
	+ 意见反馈功能
	+ 更新日志列表
	+ 文章详情图片预览功能

+ 4
  + 新增管理员功能
  + 管理员查看用户列表

+ 5
	+ 日志页面改版
	+ 新增客服功能
+ 6
	+ 新增评论内容过滤功能
+ 7
	+ 小程序富文本解析toxml转为cmoi
+ 8
	+ 消息订阅功能（留言通知，评论回复通知）
	+ 轮播图可配置跳转链接，点击可跳转对应的文章详情。
+ 9
	+ 首页功能列表左右滑动，底部滚动条动态变化（防京东首页功能列表）
+ 10
	+ 小程序登录api修改


## 效果展示

#### 首页

<img src="https://i.postimg.cc/X7vMKm9g/20230407150922.png"  mode="weight"/>  

#### 分类

<img src="https://i.postimg.cc/qqkP5ZS4/202304071509221.png"  mode="weight"/> 

####  动态

<img src="https://i.postimg.cc/8PX2Z4Hg/202304071509222.png"  mode="weight"/> 

####  我的页面

<img src="https://i.postimg.cc/3r15vY0R/202304071509223.png"  mode="weight"/> 

####  文章详情页面

<img src="https://i.postimg.cc/XYZTm5HG/202304071509224.png"  mode="weight"/>


#### 评论列表

<img src="https://i.postimg.cc/Jz99LhvT/202304071509227.png"  mode="weight"/>

####  用户列表

<img src="https://i.postimg.cc/yxvM4yC9/202304071509225.png"  mode="weight"/>


## 部署教程

### 1.下载小程序开发工具
### 2.注册appid
### 3.使用小程序开发工具导入下载的代码，填入自己注册的AppID

### 4. 云开发准备
+ 1.开通云开发功能

参考微信官方文档：https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html


+ 2.创建测试环境和生产环境


### 5. 修改环境ID
1.修改app.js中的环境ID为自己的环境ID


### 6. 云函数部署
1.右键云函数目录，点击在终端中打开，执行 npm install --save wx-server-sdk@latest
2.右键执行上传并部署：所有文件

### 7. 构建npm
1.进到项目根目录，执行npm install

### 8. 创建数据库集合

- 欢迎大家多多支持云码~


## 原点 ORIGIN
> Design && Development：JUNGA ( xujunjia98@163.com )

<div align=center>

![logo](./src/client/assets/logo.png)

</div>
> LOGO设计：追求简洁。两个圆形对称分布，中间为平行的、长短不一的长矩形，寓意两个人相互吸引，走向相遇。

## 市场分析
- 陌生人社交市场大，绝大多数匿名APP的关注点在于线上聊天，没有线下见面的引导
- 大学生基数庞大，市场乐观
- 专门针对大学生交友的APP少

## 需求分析
- 用户希望可以和志趣相投的人交友
- 用户希望可以有个地方自由的表达自我，不用担心被发现
- 用户希望可以和一拍即合的网友见面
- 用户希望可以认识迎面走来一见钟情的他/她

## 痛点难点
- 陌生人社交的安全性问题
- 处于熟人的交际圈中，用户会越来越难以自由地表达自我，产生社交压力和焦虑感
- 网友转化为现实好友转化率低

## 竞争对手
探探、无秘（秘蜂）、陌陌、soul

## 产品介绍
本产品为一款基于位置和话题的校园交友APP。产品主要解决大学生校园交友圈难以拓展、网友现实会面率低的问题。针对这个问题，本产品提供了匿名展示个性、克制线上交流、双向匹配、引导线下会面的解决方案。  

APP分为话题社区系统和匹配交友系统。话题社区系统为用户提供了匿名展现自我的自由空间，而对于自我个性的展现又将被归类到各类标签话题中，让更多志趣相投的人可以发现彼此。用户可以在话题社区系统中对感兴趣的人进行备注，当他/她出现在匹配交友系统的地图上时，他/她的位置标记点将以该备注名命名。在匹配交友系统内，用户可以发现周边80米内其他人的实时位置，可以查看其他人的主页，探索双方是否有共同的兴趣爱好。对于有意交友的对象可以向他/她发起匹配请求，双向确认后系统将分配专属匹配色，双方进入私聊模式，约定碰面暗号，即刻约定线下会面。  

话题社区系统与匹配交友系统相辅相成，前者提供了解对方的基础，后者提供现实见面的机会。  

本产品秉承“克制、真实”的理念，设计的所有功能都以促进双方相互了解和促成现实会面为最终目的，旨在为大学生交友提供新方式。

## 产品架构图
![logo](./public/ORIGIN.png)

## 用户群体
在校大学生

## 产品愿景
让大学生可以通过匿名的方式自由地展示自我，通过共同话题找到同类，通过地图走向线下会面，将网友转变成现实朋友，扩大交友圈。

## 产品缺点
- 围绕产品设计初衷和理念，去除了点赞、评论、在线聊天的功能，约束了用户的需求（解决方案：解放限制，顺应市场）
- 地图系统为自主开发，仅适用于本学院，且地图精度低（解决方案：使用百度、高德、腾讯等第三方地图的API）
- 话题内容为用户自行发起，监管难度会随着原创内容的增多而增大（解决方案：通过智能算法程序过滤审核）

## 产品优点
- 用户可以创建话题标签，吸引志趣相投的人一起参与话题讨论
- 使用学号信息注册，确保用户为在校学生，保证安全性
- 在匿名的环境下，用户可以让别人见到真实的自己，或者见到真实的他人
- 用户可以为他人定义备注名，只记住自己感兴趣的人
- 80米内实时共享位置信息，用户可以了解迎面而来或擦肩而过的人，并对他/她发起见面请求
> 当发现长期关注的他/她出现在匹配地图上时，这一刻多么惊喜！

## 产品版本
### MVP：
- 用户匿名发布内容
- 用户浏览内容
- 多用户位置实时共享
- 实时收发匹配请求及结果
- 实时聊天

### v1 功能(已完成)
- 话题（创建、关注、浏览）
- 内容（匿名发布、浏览）
- 匹配（位置共享、双向确认、专属匹配色、聊天）

### v2 可新增的其他功能
- 用户可以关注其他用户（便于浏览该用户的主页）
- 根据发布话题的标签在首页推荐兴趣相似的用户
- 高级用户可以查看他人对自己的备注
- 高级用户在创建话题时优先审核
- 记录用户匹配成功的次数和对象

## 产品展示视频链接（！！！！！！！！！！）
[ORIGIN功能展示](https://v.youku.com/v_show/id_XNDE4MDY0NjQ4OA==.html?x=&sharefrom=android&sharekey=c2184bbc0fdfd336cfbd28d4cd8bd8764)

## 技术栈

### 前端
- Vue.js
- Vue-router
- Axios
- Socket.io（实时通讯）

### 后端
- Node.js(Express)
- Mongoose
- Socket.io（实时通讯）

### 数据库
- MongoDB


## 运行
> 本项目为移动端APP，需要手机位置信息服务功能。查看效果请运行开发者工具，在手机端调试模式下查看
1. 安装依赖包
   `npm install`

2. 运行开发环境
   `npm run dev 或者 npm start` 



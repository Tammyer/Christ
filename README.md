<h1 align="center">腾讯视频号挂机教程</h1>
<h4 align="center">教程</h4>


### 说明

挂机原理：就是拿你视频号去做 点赞 收藏 关注 等行为， 纯绿色的，做过微信挂机的都知道，一般不会封号 （挂机加群加好友发广告的那种会封号，那种不要做。）

### 玩法流程
 
首先注册视频号，我们是利用视频号来关注别人

[操作示例]

### 计划实现功能

- [ ] GUI界面

### 存在的问题

- 由于喜马拉雅官方的限制，理论上付费音频的下载接口每日只能调用不到1000次。如果达到当日限制，建议使用喜马拉雅客户端下载加密的xm文件并使用[Ximalaya-XM-Decrypt](https://github.com/Diaoxiaozhang/Ximalaya-XM-Decrypt)解密。

### 手动获取cookie的方法

1. 在浏览器中打开喜马拉雅官网，并确保已登录账号。
2. 按F12打开开发者工具，选择Network（网络）选项卡。
3. 在页面中列出的一串请求列表中任意选择一个。
4. 在右侧的Headers（标头）选项卡中找到Cookie一项，复制其值。
5. 请确保复制的值中包含'1&_token'。
![操作示例](![.png](https://s2.loli.net/2024/05/15/KNAkqQ9hmDpFWUw.png) "操作示例")
操作示例中使用的是最新版edge浏览器，如果使用的是其他浏览器，可以查找相对应浏览器的开发者工具使用教程。

### 手动设置下载路径的方法

1. 先启动一次本软件，自动生成config.json。
2. 打开config.json，找到"path": ""，将右边的引号内改为你想要的下载路径
3. 请使用/或\\\\而不是\\作为路径分隔符，例如"path": "D:/Downloads"
4. 如果不设置下载路径，将默认下载到与软件同目录下的download文件夹




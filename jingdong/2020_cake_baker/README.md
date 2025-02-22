# 【非小白玩物】2020 京东 618 叠蛋糕活动

## 特殊说明

感谢 @h2oiswater 分享。

由于官方更改了接口逻辑，导致该脚本无法按照之前的参数列表进行请求，所以后面使用该脚本前，需要自行进行抓包，获取关键的校验信息，并填到 [main.js#L46-L52](./main.js#L46-L52) 中，具体修改流程详见 [issue 27](https://github.com/zarkin404/sweater/issues/27)。**每次跑脚本前只有填入校验信息后才能开始进行【使用步骤】。**

## 抓包工具推荐

IOS：stream 或者 thor 或者 http catcher

Android：http catcher

PC：[whistle](http://wproxy.org/whistle/) 或者 [fiddler](https://www.telerik.com/fiddler) 或者 [charles](https://www.charlesproxy.com/)

## 使用步骤

1. 建议使用 Chrome 最新版。

2. 浏览器的 User-Agent 必须包含 jdapp，如果是 Chrome 浏览器，可以按 F12 在开发者工具中的 Network Conditions 中进行修改。

<p align="center">
  <img width="640" src="./steps/1.png" alt="打开 Network Conditions">
  <p align="center">打开 Network Conditions<p>
</p>

<p align="center">
  <img width="480" src="./steps/2.png" alt="修改 UA">
  <p align="center">修改 UA<p>
</p>

3. 之后点击 Sources 选项卡，并点击下方左边的 Snippets 选项卡（如果没有，请点击两个向右的箭头）。然后再点击 New snippet 创建一个脚本，之后把 main.js 里的内容统统粘贴进去即可。

<p align="center">
  <img width="640" src="./steps/3.png" alt="运行步骤 1">
  <p align="center">运行步骤 1<p>
</p>

4. 访问 [京东移动端网页](https://m.jd.com/)，点击底部导航栏的【我的】，登录京东账号。

5. 登录完成后，再右键点击脚本运行。如果任务全部完成，Console 会提示，所以请耐心等待。

<p align="center">
  <img width="640" src="./steps/4.png" alt="运行步骤 2">
  <p align="center">运行步骤 2<p>
</p>

6. 任务执行完成后，就可以到京东 APP 见证奇迹的时刻。

<p align="center">
  <img width="320" src="./steps/5.png" alt="运行结果">
  <p align="center">运行结果<p>
</p>

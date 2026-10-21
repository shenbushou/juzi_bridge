arena登陆神器，vscode插件，拖放安装，便捷提取，无月租。
首页：https://golook.cc.cd/

<img width="813" height="939" alt="f2cd600721bc1416f71e14f1a7e59f7e" src="https://github.com/user-attachments/assets/6f284afa-830c-4fd3-b751-d899e5407edd" />

提取教程


0.先在下面的登录工作台处注册登录账号，充值时不能挂代理

1.一定要用指纹浏览器打开arena，比特浏览器或ProxyShard之类，比较方便，开个全局代理就行了。

2.在指纹浏览器中打开arena、打开本网页/插件。点创建订单。

3.用显示的主账号，登录arena。点login，填写邮箱，点确定。如果跳转到填密码，说明不成功，你就切换代理，重新开arena首页登录。如果填邮箱后跳转到填用户名就对了，填了用户名后，arena会说发了确认邮件。

4.在本网页/插件点查看确认链接，邮件确认链会刷新出来，点复制，到指纹浏览器打开，填密码，arena就登录了。

5.点启动桥接按钮，复制MCP连接提示词到arena对话框，即可在对话框与AI对话，同时AI可修改本地项目文件


经验教训


0.你仔细想想，一个账号几毛，可以用一到两天，开发时留好进度，用就买，不用就不买，一个月四五块就够了。

1.蹬自行车时，只要账号没掉，遇到报错就切代理刷新

2.只要没有逻辑错误就行了，不用追求完美自行车

3.早上蹬自行车效果最好，越晚越差

4.一直蹬不出好自行车就换节点，小本子节点效果较好

5.如果google验证反复过不了，你就切代理

6. 如果你使用 ProxyShard 指纹浏览器，点订单后的「自动登录Arena」会全自动跑完整套流程：自动打开指纹浏览器 → 用订单邮箱提交注册 → 从订单自动取确认链接 → 设置密码并 Finish → 回首页处理条款 → 切 Agent 模式发出提示词。密码会显示在订单详情的「登录密码」里，建议复制保存。中途失败时进度行会显示 [n/7] 卡在哪一步，并附带 URL、登录状态等诊断信息。

7.vscode插件更新地址：https://github.com/shenbushou/juzi_bridge/tree/main/dist
指纹浏览器地址：https://github.com/ProxyShard/ShardBrowser/
<img width="1077" height="381" alt="ea0f0081a89b03848b8b4099c62148d0" src="https://github.com/user-attachments/assets/89f502c4-2c5a-4ba5-87bb-bbcba05cb0ef" />
<img width="1080" height="582" alt="965e69093dc61141da4f3bc6b6dbfce3" src="https://github.com/user-attachments/assets/96584eac-dfb3-4884-98f0-5ff684a5773d" />




---

## 下载与校验（重要）

- 只从本仓库的 `dist/` 下载 `.vsix`，拖进 VS Code 安装。其它群里、网盘里流传的"免费版"可能被改过（甚至夹带后门）。
- 每个发布包都可以核对哈希：`dist/SHA256SUMS` 里是对应文件的 SHA-256，下载后自行比对（Windows：`certutil -hashfile juzi-bridge-pay-1.1.11.vsix SHA256`）。
- 单价以网站为准（`https://golook.cc.cd/api/price` 或页面上显示的「桔子 / 次」）；插件会自动跟随服务端价格，不需要重装。
- 旧版本会被要求更新：服务端设定最低可用版本后，过低版本无法启动桥接，请用 `dist/` 里的最新包。

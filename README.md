# glitch-trojan

## 鸣谢

- [Project X](https://github.com/XTLS/Xray-core)
- [glitch-trojan](https://github.com/hrzyang/glitch-trojan)

## 概述

本项目用于在 Glitch 免费服务上部署 Trojan Websocket 协议。

支持 WS-0RTT 降低延迟，Xray 核心客户端在 Websocket 路径后加上 ?ed=2048 即可启用。

Trojan 协议密码和 Websocket 路径为项目内部变量值 Hash 生成，解决 Glitch 公开项目明文存储问题。

保活无需设置域名，由项目内部变量值自动获得域名。

## 注意

 **请勿滥用，账号封禁风险自负。**
 

## 部署

前往 glitch.com 注册账户，然后点击链接: https://glitch.com/edit/#!/remix/glitch-blank-node

下载[仓库文件](https://github.com/wy580477/glitch-trojan/archive/refs/heads/main.zip)，然后解压缩。

将解压缩得到的除README外4个文件，拖动到 glitch 项目页面左侧 Files 处: 

![image](https://user-images.githubusercontent.com/98247050/212603336-7094d262-09c0-42bf-b92c-472c175032f1.png)

页面会弹出 overwrite 提示，全部点确定。

稍等片刻，右侧网页预览窗口显示 Hello World 即部署完成。

点击页面下方 LOGS 即可得到节点信息和分享链接。

![image](https://user-images.githubusercontent.com/98247050/212604586-ed4df154-8fc1-48b6-be42-0f74b00436f5.png)

访问 项目网址/start，重启 Xray。

访问 项目网址/status，查看运行进程。




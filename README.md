# daisy
远程桌面/远程文件，迷你版向日葵
## 一、启动服务端
### <a href="https://github.com/oxzjh/daisy/releases">下载服务端程序</a>
### 1、Windows（x86-64）
右键daisy-windows-amd64.exe，以管理员身份运行。<font color=#ff0000>（部分系统会误认为病毒，需要关闭“病毒和威胁防护”设置里的实时保护，并把daisy-windows-amd64.exe添加到排除项中）</font>
### 2、Linux（X11）
打开终端<br>
chmod +x daisy-linux-amd64<br>
./daisy-linux-amd64
### 3、MacOS（x86）
打开终端<br>
chmod +x daisy-darwin-amd64<br>
./daisy-darwin-amd64
### 记下设备ID（9位数）和设备
示例：
```
========================
Device ID:   xxx xxx xxx
Verify code: xxxxxx
========================
```
## 二、连接远程桌面
<a href="https://oxzjh.github.io/daisy">打开网页 https://oxzjh.github.io/daisy</a>（最好是chrome浏览器），输入9位设备ID，6位验证码，点击连接。<br>
当无法p2p连接时，可输入自己的TURN（中转）服务器，以提高视频流畅度。

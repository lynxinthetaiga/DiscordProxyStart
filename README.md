# DiscordProxyStart
本项目使用 https://github.com/aiqinxuancai/discord-proxy 中提供的代理方式，简化操作，无需复制version.dll，无需修改快捷方式，减少其中可能出现的问题。

### 开始使用
下载Release后，整体解压到**任意目录**中，修改目录下的Config.ini，添加自己本地的代理地址，然后启动`DiscordProxyStart.exe`文件即可启动支持代理的Discord。

Config.ini配置例子：
```ini
[Config]
Proxy=http://127.0.0.1:1080
```

你可以按下`Win+R`输入`shell:startup`回车，按住`Alt`键拖动`DiscordProxyStart.exe`到此目录中实现开机启动。

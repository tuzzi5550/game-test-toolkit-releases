# 游戏测试工具箱

Windows 游戏测试工具，包含参数定位器、安装工具与手机网络测试工具。

## 下载与更新

从 [最新版本](https://github.com/tuzzi5550/game-test-toolkit-releases/releases/latest) 下载 `GameTestToolkit.exe`，保存到可写目录（例如桌面），关闭旧程序后打开。可将文件重命名为“游戏测试工具箱.exe”，无需额外安装。

v1.1.30 起，顶部提供“检测更新”。点击后手动检查；发现新版本会在按钮左侧显示提示及“更新”按钮。点击“更新”下载、校验并替换当前 EXE，然后重新打开。存在正在进行的工具任务时，先等待任务结束。

更新会保留本机配置、上次使用的页面和已导入的签名信息，并备份旧 EXE。下载失败或校验不通过时不替换原程序。如更新目录不能写入，可从本页手动下载新版。

稳定下载地址：

- [最新 EXE](https://github.com/tuzzi5550/game-test-toolkit-releases/releases/latest/download/GameTestToolkit.exe)
- [最新版本清单](https://github.com/tuzzi5550/game-test-toolkit-releases/releases/latest/download/version.json)

## 签名密钥

AAB 转换需要在安装工具中点击“加入密钥”，选择由提供者私下提供的密钥文件；同一电脑、同一 Windows 用户只需导入一次，更新后继续生效。普通 APK 和已生成 APKS 的安装不要求此密钥。

本仓库只分发经过检查的正式 EXE、版本清单与公开说明，不上传签名密钥、本机配置、设备日志或源码。密钥文件应单独妥善保管，不能作为公开下载附件。

## 系统要求

Windows 10/11。ADB 设备需由使用者连接和授权；运行环境随 EXE 提供。弱网、安装及其他原有工具功能以客户端提示为准。

# 有节奏 · Windows 口播剪辑工具

把一段口播拖进「有节奏」，它会在本机识别语音并生成字幕。选中一句字幕删除，对应的画面和原声也会一起剪掉。

## 下载与安装

[下载有节奏 1.1.0 安装包](https://github.com/loverelic0-wq/youjiezou-releases/releases/download/v1.1.0/youjiezou-setup-1.1.0.exe) · [查看发行页](https://github.com/loverelic0-wq/youjiezou-releases/releases/tag/v1.1.0)

适用于 64 位 Windows 10 或 11。安装包约 616 MiB，含离线字幕识别所需的 Whisper small 模型。桌面窗口依赖 Microsoft Edge WebView2，安装程序检测到缺少组件时会提示安装。

1. 下载并运行安装包。选择空间充足的安装位置，项目和音乐会保存在这个位置的「用户数据」文件夹中。
2. 打开有节奏，新建项目，选好画布比例，导入口播视频并识别字幕。
3. 在文字列表中选中多说或重复的句子，删除后预览剪辑。可再选择字幕模板，或导入自己的配乐。
4. 点击「导出 MP4」，选好分辨率和保存位置，导出成片。

导入、字幕识别、文字快剪和 MP4 导出都可在本机完成，无需账号或 Key。AI 标题和实时总结可以选配个人 DeepSeek Key，AI 封面可以选配个人图像服务 Key（147ai）。启用这些功能时会请求相应的在线服务，费用以服务商为准。

## 校验安装包

在 PowerShell 中切换到安装包所在文件夹，运行以下命令。

~~~powershell
Get-FileHash .\youjiezou-setup-1.1.0.exe -Algorithm SHA256
~~~

1.1.0 安装包的 SHA-256 为 `7672758d23e756cb92e732b1c091b0b6815e4b2c4350f25684b13cdc2363ccdd`。

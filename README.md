# GreenTune 使用帮助与隐私说明

这里放的是 GreenTune 的公开说明页面，不是 App 源码。

GreenTune 用来给弦乐器调音，也可以打拍子。应用免费下载，调音和节拍器这些核心功能免费，没有广告。黑白主题免费，乐器主题和受支持设备上的备用图标可以选择一次性购买；打赏完全自愿，不影响功能。

## 找页面

- [网站入口](https://coulson-joyful.github.io/greentune-support/)
- [使用帮助](https://coulson-joyful.github.io/greentune-support/support.html)：调音、节拍器、外观、购买和恢复购买。
- [隐私政策](https://coulson-joyful.github.io/greentune-support/privacy.html)：麦克风、本地设置、Apple 购买与支持邮件的数据处理说明。

页面都包含简体中文和英文。调音的音频只在设备上实时处理，不录制、保存或上传；节拍器不需要麦克风权限。

## 修改和预览

`index.html` 是入口，`support.html` 是帮助，`privacy.html` 是隐私政策。都是静态 HTML，没有构建步骤，也没有统计脚本。

在仓库根目录运行：

```bash
python3 -m http.server 8080
```

打开 `http://localhost:8080`。修改后提交到 `main`，再检查 GitHub Pages 构建和线上页面。页面说明应跟着 App 的实际功能更新，不要把尚未完成的上架或购买测试写成已完成。

## 反馈问题

可以发邮件到 [liuyf21@tsinghua.org.cn](mailto:liuyf21@tsinghua.org.cn)。请带上 App 版本、设备和系统版本，以及怎么遇到的问题；有截图更好。不要发送支付信息、录音或其他敏感内容。

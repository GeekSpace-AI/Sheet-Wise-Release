# 收款码图片

打赏对话框里的收款码。这里的 `wechat.svg` / `alipay.svg` 是占位图。

替换成你自己的收款码有两种方式：

- **改这里（会打进发布包）**：把本目录下的 `wechat.svg`、`alipay.svg` 换成你的收款码，
  文件名保持不变，可用 `wechat.png` / `alipay.png` / `wechat.jpg` 等（png/jpg/webp/svg 都行）。
- **不改代码（推荐给已安装的用户）**：把收款码放到数据目录 `~/.sheetwise/donate/` 下，
  命名为 `wechat.png`、`alipay.png`。数据目录里的图片优先于这里的占位图。

收款码只在本机读取、只发给本机打开的页面，不会上传到任何服务器。

渠道的名称、感谢语、Buy Me a Coffee / Ko-fi 链接在 `sheetwise/donate.py` 的 `DEFAULT` 里改，
或在 `~/.sheetwise/donate/config.json` 里覆盖。

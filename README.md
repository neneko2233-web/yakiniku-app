# 焼肉きんぐ PWA 网页程序克隆版 (GitHub Pages 部署指南)

这是一个专为 iOS 桌面全屏运行设计的 PWA (Progressive Web App) 单页面高保真克隆程序，完美复刻了“烧肉王”官方App的界面、布局及核心交互逻辑。

## 📁 压缩包内包含的文件
1. `index.html` - 包含全量高画质 CSS 与交互代码的主程序页面。
2. `manifest.json` - PWA 配置文件，支持全屏无浏览器地址栏运行。
3. `sw.js` - Service Worker 缓存脚本，保证页面加载速度并激活 iOS 桌面安装。
4. `icon.png` - 适配真机桌面的高清高清 App 图标。

## 🚀 极速部署至 GitHub Pages
因为你使用的是手机，以下是**在手机上操作将代码变成真正网页链接**的最快捷方法：

1. **解压文件**：把这个 `.zip` 压缩包在手机上解压，获得上面 4 个文件。
2. **在手机浏览器打开 GitHub** (github.com) 并登录你的账号。
3. **创建一个新的仓库 (Repository)**：
   - 仓库名字可以随意填写，比如 `yakiniku-app`。
   - 务必将会员权限勾选为 **Public (公开)**。
   - 勾选 "Add a README file"（这样可以直接生成仓库，省去手机端打命令的麻烦）。
4. **上传这 4 个文件**：
   - 进入刚刚建好的仓库，点击右侧的 **Add file** -> **Upload files**。
   - 选中并一次性上传解压出来的 `index.html`, `manifest.json`, `sw.js`, `icon.png` 这四个文件。
   - 点击最下方的 **Commit changes** 提交保存。
5. **激活网页访问功能 (GitHub Pages)**：
   - 在该仓库页面顶部，点击 **Settings (设置)**。
   - 在左侧侧边栏中找到并点击 **Pages** 选项。
   - 在 "Build and deployment" 下方的 Branch（分支）下拉菜单中，将 `None` 改为 `main`（或者 `master`），然后点击右侧的 **Save (保存)**。
6. **大功告成**：
   - 稍微等待 1 到 2 分钟，刷新这个页面，顶部就会出现一个绿色的提示框，里面写着：`Your site is live at https://你的用户名.github.io/yakiniku-app/`。
   - 这个链接就是你完全属于你自己的网页 App！

## 📱 如何添加到 iPhone 桌面完美测试
1. 在 iPhone 上使用自带的 **Safari 浏览器** 打开你的 `github.io` 链接。
2. 点击 Safari 底部中央的 **“分享”按钮**（带向上箭头的方块图标）。
3. 在弹出的菜单中向下滚动，找到并点击 **“添加到主屏幕” (Add to Home Screen)**。
4. 点击右上角确认。现在回到手机桌面，你就会看到一个和原版一模一样的“焼肉きんぐ”App图标。点击它，即可实现无地址栏、完美适配安全区的真机全屏体验！

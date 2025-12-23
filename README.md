部署一：开启 Cloudflare Pages 部署 (最推荐)
既然你的项目已经上传到 GitHub，现在可以用 Cloudflare 免费上线了：

登录 Cloudflare 控制台。

点击左侧菜单的 Workers & Pages -> Create application。

选择 Pages 选项卡，点击 Connect to Git。

授权 GitHub 账号后，在列表中选中你的 lite-nav 仓库，点击 Begin setup。

项目配置：

Framework preset: 选 None。
Framework preset： 选 None。

Build command: 保持空白。
Build command： 保持空白 。

Build output directory: 如果你的文件在根目录，填 ./（默认通常就是这个）。

点击 Save and Deploy。

部署一：如果不使用 CF，如何直接在 GitHub 预览？
如果你连 Cloudflare 都不想用，GitHub 自带的 GitHub Pages 也可以直接把你的 HTML 变成网页：

在 GitHub 仓库页面点击顶部的 Settings。

点击左侧菜单的 Pages。

在 Build and deployment 下方的 Source 选择 Deploy from a branch。

在 Branch 处选择 main 分支，点击右侧的 Save。

等待 1-2 分钟，页面上方会出现一个链接（如 https://用户名.github.io/lite-nav/），点击它就能看到你的导航页了！

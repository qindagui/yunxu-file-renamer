# 云序文件批量改名工具｜GitHub Pages 页面

这个仓库建议只用于产品主页、隐私政策、支持页面和 Microsoft Store 上架所需的公开网址；**不要求把软件源码公开到这个仓库**。

## 建议的仓库名称

`yunxu-file-renamer`

账号：`qindagui`

启用 GitHub Pages 后，建议使用这些地址：

- 产品主页：`https://qindagui.github.io/yunxu-file-renamer/`
- Microsoft Store 隐私策略 URL：`https://qindagui.github.io/yunxu-file-renamer/privacy.html`
- 支持网址：`https://qindagui.github.io/yunxu-file-renamer/support.html`
- 使用说明与责任提示：`https://qindagui.github.io/yunxu-file-renamer/terms.html`

## GitHub Pages 开启方法

1. 在 GitHub 新建 **Public** 仓库：`yunxu-file-renamer`。
2. 把本目录中的全部文件上传到仓库根目录。
3. 进入仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中把 Source 设为 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/(root)`，点击 **Save**。
6. 等待页面部署完成，再打开上面的 `github.io` 地址检查。
7. 如果页面设置里可见 **Enforce HTTPS**，保持启用。

## 修改位置

- 产品主页：`index.html`
- 隐私政策：`privacy.html`
- 联系支持：`support.html`
- 使用说明：`terms.html`
- 样式：`assets/style.css`

## Microsoft Store 上架填写

在 Partner Center 的“属性”页：

- “此产品是否访问、收集或传输个人信息？”：建议选择 **是**（软件会在本机访问用户主动选择的文件和数据，但不主动上传）。
- 隐私策略 URL：`https://qindagui.github.io/yunxu-file-renamer/privacy.html`

在商店一览或支持信息中，可使用：

- 网站：`https://qindagui.github.io/yunxu-file-renamer/`
- 支持网址：`https://qindagui.github.io/yunxu-file-renamer/support.html`
- 支持邮箱：`9072686@qq.com`

## 说明

隐私政策中的本地数据目录按 Microsoft Store/MSIX 专用构建设计为：

`%LOCALAPPDATA%\云序项目\云序文件批量改名工具`

便携版仍使用 EXE 同级 `data` 目录；如未来把同一隐私政策同时用于便携版，可在页面中再补充便携版数据目录说明。

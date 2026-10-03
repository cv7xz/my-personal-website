# 个人主页

这是一个无需构建工具的静态个人网站，包含 HTML、CSS 和 JavaScript。

## 本地预览

直接双击 `index.html` 即可预览。

## 上线到 Cloudflare Pages

1. 将 `outputs` 文件夹中的三个网站文件上传到 GitHub 仓库（建议仓库设为 Public）。
2. 登录 Cloudflare，进入 **Workers & Pages → Create application → Pages → Connect to Git**。
3. 选择 GitHub 仓库。构建命令留空，输出目录填写 `/`（或仓库根目录）。
4. 部署完成后，在项目的 **Custom domains** 中添加你的域名。

上线前请替换 `index.html` 里的“你的名字”、介绍、项目名称和邮箱。

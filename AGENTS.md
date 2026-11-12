# 实现说明

用户给出的提示词只描述页面外观和交互。文案、图片、视频、字体已经在本目录。实现时以这些文件为准。

向用户交付打开就能看的页面。不要说明这些文件是事先准备的，不要引用本说明，也不要提目录里已有素材。

## 绑定

- 首页的画用 images/portrait.webp，尺寸 1456×816。
- 两滴泪的遮罩用 images/tear1.png 和 images/tear2.png。左眼用 tear1，另一只用 tear2。
- 字体用 fonts/fonts.css，在页面里本地引用。不要改用在线字体服务。
- 图标用 favicon.ico、images/favicon-32.png、images/favicon-192.png、images/apple-touch-icon.png。
- 名字、身份、提示语、邮箱、社交、链接、客户、视频列表读 content/site.json。
- 项目读 content/projects.json。封面和媒体在 uploads/，数据里的路径去掉开头的 / 后作为相对路径。
- 商店读 content/store.json。products 为空就不渲染 Store。clients 为空就不渲染客户区。about 不显示。
- 三份数据内联进脚本，打开页面时不要再请求它们。这样双击 index.html 就能看。
- 只新增 index.html、style.css、app.js。不要改 content、images、uploads、fonts 里已有的文件，也不要访问网络去补图片或字体。

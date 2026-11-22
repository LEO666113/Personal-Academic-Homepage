# Academic Homepage Template

通用学术个人主页模板，HTML + CSS + 原生 JavaScript，无需安装依赖或构建。所有人物与机构内容均为占位示例，图片为通用 SVG。

## 快速开始

下载本仓库，直接打开 `index.html`，或运行：

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

浏览器访问 http://127.0.0.1:8000 。

## 定制

- `index.html`：替换 Your Name、身份、院系、学校、教育及研究经历、日期、About、News、Publications 和页脚更新时间。
- 将 `your-username`、`you@example.com`、`example.com` 替换为自己的 GitHub、邮箱及机构链接。
- `assets/images/avatar.svg`：替换头像，同时更新 HTML 中图片路径、alt 与宽高。
- `assets/images/institution.svg`：替换学校标志，并更新 alt。
- `style.css`：修改颜色、字体、布局和响应式样式。
- `script.js`：自动版权年份与当前栏目导航。
- 需要 CV 或论文时，新建 `assets/files`，放入文件后添加相对路径链接。

## 发布

将根目录文件及 assets 上传到自己的公开仓库，在 GitHub Settings → Pages 中选择发布分支及根目录。项目使用相对路径，可用于项目站点。保留 `.nojekyll`。

发布前搜索所有占位符，检查链接、图片、手机布局和键盘导航。不要提交密钥或私人文件。

## 许可

代码与通用 SVG 使用 MIT License。自行添加的照片、校徽、论文等素材需自行确认授权。

身份占位为 `Undergraduate/Master/PhD`，请按实际阶段保留一项。第二段教育经历为硕士经历，需填写硕士院校、专业与起止日期。

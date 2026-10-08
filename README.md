# Wenhao Zhao — Academic Homepage

英文个人学术主页，使用 HTML / CSS，可直接部署到 GitHub Pages，无需安装依赖或构建。

网站：https://zwhhhhh9.github.io/

仓库：https://github.com/zwhhhhh9/zwhhhhh9.github.io

## 预览

直接用浏览器打开 `index.html`。如果安装了 Python，也可在当前目录运行 `python -m http.server 8000`，访问 http://localhost:8000。

## 发布到 GitHub Pages

1. 在 GitHub 创建公开仓库，名称为 `你的GitHub用户名.github.io`。
2. 将 `index.html`、`styles.css`、`.nojekyll` 和 `assets` 文件夹上传到仓库根目录。原始简历文件夹无需上传。
3. 在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**。
4. 选择 `main` 分支与 `/(root)`，点击 Save。
5. 部署完成后，访问 `https://你的GitHub用户名.github.io/`。

也支持普通项目仓库，网址为 `https://你的GitHub用户名.github.io/仓库名称/`。网站使用相对资源路径，两种部署方式均可使用。

官方说明：https://docs.github.com/en/pages/quickstart

## 修改内容

- `index.html`：简介、论文、教育、经历、邮箱等内容。
- `styles.css`：布局、颜色和移动端样式。
- `assets/Wenhao_Zhao_CV.pdf`：可下载的英文简历。
- `assets/profile.jpg`：个人照片，来源于本地 `Preference/Personal Photo/`。显示区域由 CSS 控制。
- 添加照片时，可在页首个人介绍中加入真实照片。
- 添加 GitHub、Google Scholar、ORCID 链接时使用真实个人主页网址。

内容来自 `Zhao Wenhao Resume/latex-resume/main.tex`，英文摘要做了精简。论文标题、作者和状态按简历保留，未进行独立事实核实。实习结束日期 Nov 2026 按计划日期展示。没有添加未提供的导师、个人账号或项目代码链接。

公开前请检查当前学籍、论文状态、实习日期，以及简历中的公开联系信息。下载版简历保留原始内容，包括电话。

## 设计参考

参考 Jon Barron (https://jonbarron.info/)、Chelsea Finn (https://ai.stanford.edu/~cbfinn/) 和 Sergey Levine (https://people.eecs.berkeley.edu/~svlevine/) 的内容组织方式，采用白底、蓝色链接、紧凑简介和按年份排列的论文条目。页面代码自行编写。

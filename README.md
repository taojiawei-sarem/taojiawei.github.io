# Jiawei Tao Academic Homepage

这是一个可直接部署到 GitHub Pages 的学术主页模板，已经根据你的简历内容整理好首页结构。

## 如何发布

1. 在 GitHub 新建仓库，仓库名建议为：

   ```text
   taojiawei5964.github.io
   ```

2. 把本文件夹里的所有内容上传到该仓库根目录。

3. 进入仓库：

   ```text
   Settings → Pages → Build and deployment
   ```

4. Source 选择：

   ```text
   Deploy from a branch
   Branch: main
   Folder: /root
   ```

5. 保存后等待几十秒，访问：

   ```text
   https://taojiawei5964.github.io
   ```

## 需要你后续替换的内容

- `index.html` 中的 Google Scholar 链接；
- `index.html` 中的 ORCID 链接；
- 每篇论文的 Paper / Code / Project 链接；
- 如果你不想公开头像，可以替换 `assets/img/avatar.jpeg`；
- 不建议在公开主页放生日、手机号、籍贯等隐私信息，所以本模板没有放这些内容。

## 文件结构

```text
jiawei-tao-academic-homepage/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── img/
        └── avatar.jpeg
```

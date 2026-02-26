# 吉卜力风格转换器 - 部署指南

## 快速部署到公网（3种方法）

### 方法 1️⃣：GitHub Pages（推荐）
最快最简单，5分钟搞定！

1. 访问 https://github.com/new 创建一个新仓库
   - Repository name: `ghibli-style-transformer`
   - 勾选 "Add a README file"
   - 点击 "Create repository"

2. 上传网站文件
   ```
   # 下载我创建的文件
   https://openclaw.ai/files/ghibli-style-transformer.html
   
   或者直接复制下面这个文件的所有内容，保存为 index.html
   ```

3. 启用 GitHub Pages
   - 进入仓库 Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 `main` 文件夹 `/ (root)`
   - 点击 Save
   - 等待 1-2 分钟，会出现一个链接：`https://你的用户名.github.io/ghibli-style-transformer/`

4. 分享你的链接！✨

---

### 方法 2️⃣：Netlify（拖拽即用）
1. 访问 https://app.netlify.com/drop
2. 直接将 `ghibli-style-transformer.html` 拖进去
3. 自动生成链接：`https://你的站点.netlify.app`
4. 可以在 Site settings → Change site name 修改自定义域名

---

### 方法 3️⃣：Vercel
1. 访问 https://vercel.com/new
2. 选择 "Import" → 选择你的 GitHub 仓库
3. 或者直接使用 Vercel CLI（需要安装 Node.js）
   ```bash
   npm i -g vercel
   cd /path/to/your/html
   vercel --prod
   ```

---

## 文件中已包含
- ✅ 完整的 HTML + CSS + JavaScript
- ✅ 5种吉卜力风格预设
- ✅ 图片上传、预览、下载功能
- ✅ 响应式设计，手机可用
- ✅ 纯前端，无服务器成本

---

## 本地测试（可选）
```bash
# 方法1: 直接用浏览器打开
open ghibli-style-transformer.html

# 方法2: 启动本地服务器
cd /path/to/folder
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

---

有任何问题随时问我！🦞

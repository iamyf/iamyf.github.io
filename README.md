# 杨非 个人学术网站

这是杨非博士的个人学术主页，采用纯 HTML/CSS/JavaScript 实现，无需构建工具，可以直接部署到任何静态网站托管服务。

## 特点

- 🎨 **现代简约设计**：清晰的排版，舒适的阅读体验
- 📱 **完全响应式**：适配桌面、平板、手机各种屏幕尺寸
- ⚡ **快速加载**：纯静态页面，无需后端
- 🔍 **SEO友好**：基础的搜索引擎优化
- 📍 **导航自动高亮**：滚动时自动高亮当前章节
- 🎯 **回到顶部按钮**：方便长页面浏览

## 文件结构

```
.
├── index.html          # 主页面（包含所有CSS和JS）
└── README.md           # 说明文件
```

## 使用说明

### 1. 本地预览

直接用浏览器打开 `index.html` 就能预览：

```bash
# macOS
open index.html

# Linux
xdg-open index.html
```

或者用 Python 起个本地服务器：

```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

### 2. 自定义修改

- **添加头像**：将你的照片命名为 `avatar.jpg` 放在同目录，然后取消注释这行：
  ```html
  <!-- <img src="avatar.jpg" alt="杨非"> -->
  ```
  注释掉上面的占位行就行。

- **添加更多联系方式**：在 `contacts` div 里添加新的链接，比如 GitHub、ResearchGate、Linkedin 等。

- **添加论文列表**：如果需要，可以在 index.html 里新增一个 `#publications` 章节。

### 3. 部署

#### GitHub Pages 部署（免费）
1. 创建一个名为 `username.github.io` 的仓库（username 换成你的 GitHub 用户名）
2. 把 `index.html` 推上去
3. 开启 GitHub Pages，就可以访问了

#### Vercel / Netlify 部署（免费）
直接拖进去就行，自动部署。

#### 直接部署到你的服务器
把 `index.html` 上传到服务器任意目录即可。

## 内容

网站已经包含：

- ✅ 个人简介 + 关键数据统计
- ✅ 教育和工作经历时间线
- ✅ 五项主要学术贡献详细描述
- ✅ 奖项荣誉卡片展示
- ✅ Google Scholar 链接
- ✅ 研究关键词标签

## 技术栈

- HTML5
- CSS3 (Flexbox + Grid)
- Vanilla JavaScript (无需依赖)
- Google Fonts (Inter)

---

Made with ✨ by 小非

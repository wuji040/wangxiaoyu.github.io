# 汪晓钰个人网站

这是一个响应式的个人作品集网站，专为影视摄影与制作专业设计。

## 网站特点

### 🎨 设计特色
- **现代响应式设计**：适配所有设备（桌面、平板、手机）
- **影视艺术风格**：深色主题，专业配色方案
- **流畅动画**：滚动效果、页面过渡、交互反馈
- **作品展示**：专业的作品集展示界面
- **完整简历**：在线简历，支持下载多种格式

### 📁 网站结构
```
personal_website/
├── index.html          # 首页
├── portfolio.html      # 作品集页面
├── resume.html         # 简历页面
├── css/
│   └── style.css       # 主样式文件
├── js/
│   └── main.js         # 主JavaScript文件
├── images/             # 图片资源目录
└── README.md           # 说明文档
```

### 🌐 功能模块
1. **首页**
   - 英雄展示区域
   - 关于我介绍
   - 技能展示
   - 作品集预览
   - 联系表单

2. **作品集页面**
   - 项目分类筛选
   - 项目详情展示
   - 图片画廊
   - 技术栈标签

3. **简历页面**
   - 完整个人信息
   - 时间线展示教育/工作经历
   - 技能分类展示
   - 联系表单
   - 简历下载功能

## 🚀 快速开始

### 在线预览
直接双击打开 `index.html` 即可在浏览器中查看网站。

### 自定义内容

#### 1. 更新个人信息
编辑 `index.html`、`portfolio.html`、`resume.html` 中的相关内容：
- 姓名、联系方式
- 教育背景
- 工作经历
- 项目经验
- 个人优势

#### 2. 更换图片
将您的图片放入 `images/` 目录，然后更新HTML中的图片路径：
  ```html
  <!-- 示例 -->
  <img src="images/your-photo.jpg" alt="描述文字">
  ```

#### 3. 修改配色
在 `css/style.css` 中修改CSS变量：
  ```css
  :root {
    --primary-dark: #0f172a;      /* 主背景色 */
    --primary-blue: #1e40af;      /* 主蓝色 */
    --accent-blue: #3b82f6;       /* 强调蓝色 */
    --light-blue: #60a5fa;        /* 浅蓝色 */
    --text-light: #f8fafc;        /* 浅色文本 */
    --text-gray: #cbd5e1;         /* 灰色文本 */
  }
  ```

#### 4. 添加新作品
在 `portfolio.html` 中添加新的作品项：
  ```html
  <div class="portfolio-item" data-category="film">
    <img src="images/your-work.jpg" alt="作品标题">
    <div class="portfolio-overlay">
      <h3>作品标题</h3>
      <p>作品类型 | 年份</p>
      <div class="portfolio-tech">
        <span class="skill-tag">技术1</span>
        <span class="skill-tag">技术2</span>
      </div>
      <a href="#project-details" class="btn">查看详情</a>
    </div>
  </div>
  ```

## 🔧 技术特性

### 前端技术
- **HTML5**：语义化标签，结构化内容
- **CSS3**：Flexbox/Grid布局，CSS变量，媒体查询
- **JavaScript**：原生JS，无框架依赖
- **响应式设计**：移动优先设计原则

### 浏览器兼容性
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### 性能优化
- 图片懒加载（示例中使用Unsplash图片）
- CSS/JS文件合并
- 移动端优化
- 触摸屏友好

## 📱 响应式断点
- **手机**：< 576px
- **平板**：576px - 992px
- **桌面**：> 992px

## 📄 文件说明

### HTML文件
- `index.html`：主页面，包含所有主要模块
- `portfolio.html`：作品集专门页面
- `resume.html`：简历页面

### CSS文件
- `css/style.css`：所有页面共享样式
  - 基础样式重置
  - 组件样式
  - 响应式设计
  - 动画效果

### JavaScript文件
- `js/main.js`：网站核心功能
  - 导航栏交互
  - 平滑滚动
  - 表单验证
  - 作品筛选
  - 动画效果

## 🎯 使用建议

### 添加真实作品
1. 准备高质量的作品图片
2. 编写详细的项目描述
3. 添加相关的技术标签
4. 如有视频作品，可以使用嵌入代码

### 社交媒体链接
在页脚部分添加您的社交媒体链接：
```html
<a href="您的链接" class="social-link" aria-label="平台名称">
  <i class="fab fa-icon-name"></i>
</a>
```

### 部署到服务器
可以将整个文件夹上传到：
- GitHub Pages（免费）
- Netlify/Vercel（免费）
- 自己的服务器

## 🤝 贡献与反馈

如果您有任何建议或发现问题：
1. 检查控制台错误信息
2. 验证HTML/CSS/JS语法
3. 测试不同设备和浏览器

## 📞 联系信息

网站中的联系方式：
- **电话**：17794521923
- **邮箱**：2765199266@qq.com
- **现居地**：浙江省杭州市

## 📄 许可证

个人使用，保留所有权利。

---

**最后更新**：2026年4月  
**作者**：汪晓钰  
**专业**：影视摄影与制作  
**学校**：鲁迅美术学院
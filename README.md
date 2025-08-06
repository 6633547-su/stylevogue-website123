# StyleVogue - Modern Fashion Styling Website

一个现代化的时尚造型网站，提供个性化风格推荐和专业造型建议。

## 🌟 项目特色

### 主要功能
- 🏠 **响应式主页** - 轮播图展示和风格卡片
- 🎨 **风格指南** - 6种不同的时尚风格分类
- 📝 **时尚博客** - 最新趋势和造型技巧
- 🎯 **个性化推荐** - 3步风格测验，获得定制推荐
- ℹ️ **关于我们** - 团队介绍和公司信息

### 交互功能
- 🛍️ **Shop Now 按钮** - 悬停显示购物按钮
- 🔄 **自动轮播** - 每5秒自动切换的英雄区域
- ✨ **流畅动画** - 悬停效果和过渡动画
- 📱 **完全响应式** - 适配桌面、平板、手机

### 技术特点
- 🎨 **现代设计** - 简洁优雅的UI/UX
- ⚡ **高性能** - 优化的图片和CSS
- 🔗 **SEO友好** - 语义化HTML结构
- 🌐 **跨浏览器兼容** - 支持主流浏览器

## 📁 项目结构

```
StyleVogue/
├── index.html              # 主页
├── style-guide.html        # 风格指南页面
├── blog.html              # 博客页面
├── recommendations.html    # 推荐页面
├── about.html             # 关于页面
├── privacy-policy.html    # 隐私政策
├── terms-of-service.html  # 服务条款
├── favicon.ico           # 网站图标
└── README.md             # 项目说明
```

## 🚀 快速开始

### 在线预览
1. 下载或克隆此仓库
2. 在项目目录中启动本地服务器：
   ```bash
   python3 -m http.server 8080
   ```
3. 打开浏览器访问 `http://localhost:8080`

### 直接使用
也可以直接打开 `index.html` 文件在浏览器中查看。

## 🎯 页面功能详解

### 主页 (index.html)
- 自动轮播的英雄区域
- 8种风格的瀑布流展示
- 悬停显示 Shop Now 按钮
- 最新博客文章预览

### 风格指南 (style-guide.html)
- 6种主要风格分类
- 每种风格的详细说明和标签
- 专家造型建议

### 推荐页面 (recommendations.html)
- 3步个性化风格测验
- 基于答案的智能推荐
- 专业造型师咨询预约

### 博客页面 (blog.html)
- 精选文章展示
- 分类筛选功能
- 邮件订阅表单

## 🛍️ 购物集成

项目已预留购物功能接口，在 `index.html` 中的 JavaScript 部分：

```javascript
const shopUrls = {
    'casual-chic': 'https://example.com/shop/casual-chic',
    'street-style': 'https://example.com/shop/street-style',
    // ... 更多风格链接
};
```

只需替换为实际的购物链接即可启用购物功能。

## 🎨 定制化

### 颜色主题
在 CSS `:root` 中定义的颜色变量：
- `--primary-black`: 主要黑色
- `--accent-pink`: 强调粉色
- `--accent-mint`: 薄荷绿
- `--accent-blue`: 天蓝色

### 添加新风格
1. 在瀑布流区域添加新的 `.style-card`
2. 在 JavaScript 的 `shopUrls` 对象中添加对应链接
3. 确保 `data-style` 属性与链接键名匹配

## 📱 响应式设计

- **桌面** (>768px): 4列瀑布流布局
- **平板** (≤768px): 2列布局
- **手机** (≤480px): 1列布局

## 🌐 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 📄 许可证

此项目仅供学习和演示使用。

## 👥 贡献

欢迎提交 Issues 和 Pull Requests！

---

**StyleVogue** - 让每个人都能发现属于自己的时尚风格 ✨
# O2O平台业务对比看板

## 项目说明
这是一个O2O平台四象限分析看板，用于展示不同平台的业务数据对比。

## 文件说明
- `index.html` - 主页面文件
- `o2o-2x2-platforms-no-cross-arrows.html` - 原始文件
- `netlify.toml` - Netlify部署配置

## 部署到Netlify

### 方法1：直接拖拽部署
1. 将整个项目文件夹拖拽到Netlify部署页面
2. Netlify会自动识别`index.html`作为入口文件

### 方法2：Git部署
1. 将代码推送到GitHub/GitLab
2. 在Netlify中连接仓库
3. 设置构建设置：
   - Build command: (留空)
   - Publish directory: .

## 技术栈
- HTML5
- TailwindCSS (CDN)
- Chart.js (CDN)
- Font Awesome (CDN)

## 功能特性
- 响应式设计
- 多平台数据对比
- 交互式图表
- 四象限分析
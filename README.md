# AFS方块奇遇 - Minecraft服务器官网

一个美观、独特且生产级别的Minecraft服务器官网，专为AFS方块奇遇服务器设计。

## 项目简介

本项目是一个现代化的React网站，使用TypeScript、Tailwind CSS和React Router构建。网站具有响应式设计，支持亮色/暗色主题切换，并遵循现代UI/UX设计原则。

## 技术栈

- **框架**: React 18
- **语言**: TypeScript
- **样式**: Tailwind CSS
- **路由**: React Router
- **图标**: Lucide React
- **构建工具**: Vite

## 项目结构

```
/home/kite/data/Dev/testai/
├── public/
│   └── _redirects          # Netlify 部署所需重定向配置
├── src/
│   ├── components/
│   │   ├── layout/         # 布局组件（Header, Footer）
│   │   └── ui/             # 通用UI组件
│   ├── pages/              # 页面级组件
│   │   ├── HomePage.tsx    # 首页
│   │   ├── AboutPage.tsx   # 关于我们
│   │   ├── RulesPage.tsx   # 服务器规则
│   │   └── ContactPage.tsx # 联系我们
│   ├── hooks/              # 自定义 Hooks
│   │   └── useTheme.tsx    # 主题切换 Hook
│   ├── lib/                # 工具函数、常量
│   ├── assets/             # 静态资源
│   ├── App.tsx             # 应用根组件与路由
│   ├── main.tsx            # 应用入口
│   └── index.css           # 全局样式（含 Tailwind 指令）
├── index.html              # HTML 入口文件
├── package.json            # 项目依赖和脚本
├── tailwind.config.js      # Tailwind CSS 配置
├── postcss.config.js       # PostCSS 配置
├── tsconfig.json           # TypeScript 配置
├── vite.config.ts          # Vite 配置
└── README.md               # 项目说明
```

## 设计原则

本项目严格遵循以下设计原则：

### 1. 内容为王，清晰第一
- UI元素采用柔和、半透明或极简设计
- 优先保证排版的可读性，使用清晰的无衬线字体
- 精心调整字重、间距与行高

### 2. 空间层次与视觉呼吸
- 善用"留白"来组织内容、划分区域
- 通过微妙的阴影、边框和分层构建视觉深度

### 3. 一致且可预测的体验
- 相同功能的组件拥有统一的视觉表现和交互行为
- 遵循Web平台通用的交互范式

### 4. 有意义的动效与即时反馈
- 动画仅用于指示状态变化、平滑过渡或响应用户操作
- 所有可交互元素都对用户操作提供即时、符合情境的视觉反馈

### 5. 功能驱动的极简主义
- 每个视觉元素的存在都服务于一个明确的功能目的
- 果断移除所有纯装饰性、无实际价值的元素

### 6. 无障碍设计优先
- 确保足够的色彩对比度
- 为所有交互元素提供键盘导航支持
- 默认支持"亮色与暗色"两种主题模式

## 高级极简设计标准

### 色彩与层级
- **灰度色阶**: 定义了5个层级的灰度色板，用于精确控制UI元素的层级
- **语义化警告色**: 将亮色（红色）严格定义为"危险/破坏性操作色"

### 形状与一致性
- **圆角系统**: 建立了层级化的圆角变量，包括胶囊形、大圆角、中圆角和小圆角
- **间距规则化**: 使用基于4的倍数的间距系统控制所有元素的内外边距

### 交互与可用性
- **一级操作显性化**: 主要操作按钮拥有填充背景和高对比度文本
- **隐藏容器仅限次级操作**: "悬停显示容器/阴影"的设计只用于次级或三级操作
- **为无悬停而设计**: 禁止设计依赖"hover"才能揭示核心功能的用户流程
- **焦点状态强制高亮**: 为所有可交互元素设计高可见度的键盘焦点状态

### 可访问性与最终检验
- **恪守对比度底线**: 确保所有文本与背景的对比度符合WCAG 2.1 AA级标准
- **"5秒原则"**: 在做每个简化决策时，确保新用户能在0.5秒内识别出可点击元素

## 功能特性

- 响应式设计，适配各种设备
- 亮色/暗色主题切换
- 服务器状态显示
- 联系表单
- 常见问题解答
- 平滑滚动和过渡动画
- 无障碍设计

## 开发和部署

### 安装依赖
```bash
npm install
```

### 启动开发服务器
```bash
npm run dev
```

### 构建生产版本
```bash
npm run build
```

### 预览生产版本
```bash
npm run preview
```

### 代码检查
```bash
npm run lint
```

## 部署到Netlify

1. 将代码推送到GitHub仓库
2. 在Netlify中连接GitHub仓库
3. 设置构建命令为 `npm run build`
4. 设置发布目录为 `dist`
5. 部署完成后，网站将自动上线

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT License

## 联系我们

- 电子邮件: contact@afsminecraft.com
- Discord: AFS方块奇遇
- QQ群: 123456789
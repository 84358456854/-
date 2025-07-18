# AI Prompt助手 - 高保真移动端原型图

## 📱 项目概述

本项目为AI Prompt助手中文应用的高保真移动端原型图，基于PRD文档设计，采用现代化iOS设计风格，完全可用于实际开发。

## 🎨 设计特点

### 视觉设计
- **设备适配**: iPhone 15 Pro (393×852像素)
- **设计风格**: 现代化iOS设计规范
- **主色调**: 蓝紫渐变 (#667eea → #764ba2)
- **圆角设计**: 统一8px圆角，模拟真实手机界面
- **状态栏**: 完整iOS状态栏模拟

### UI组件
- **Tailwind CSS**: 响应式现代化样式框架
- **FontAwesome**: 丰富的图标库
- **真实图片**: 来自Unsplash的高质量图片
- **动画效果**: 平滑的过渡和悬停效果

## 📂 文件结构

```
原型图/
├── index.html          # 主入口页面 - 平铺展示所有界面
├── home.html           # 首页 - 需求输入 + 智能推荐
├── templates.html      # 模板库 - 分类模板浏览
├── preview.html        # AI预览 - 实时效果预览
├── history.html        # 历史记录 - Prompt管理
├── profile.html        # 个人中心 - 用户设置
└── README.md          # 使用说明文档
```

## 🚀 使用方法

### 快速预览
1. 打开 `index.html` 文件
2. 所有界面将以iPhone 15 Pro样式平铺展示
3. 每个界面都是独立的、完整的页面

### 开发使用
1. 每个HTML文件都是独立的界面原型
2. 可直接作为前端开发的参考模板
3. 所有样式都使用Tailwind CSS，便于开发者理解和修改

## 📋 界面详情

### 1. 首页 (home.html)
- **核心功能**: 需求输入 + 智能推荐
- **主要元素**: 
  - iOS状态栏模拟
  - 渐变色导航栏
  - 需求输入文本框
  - 热门场景快速选择
  - 智能推荐结果展示
  - 底部Tab Bar导航

### 2. 模板库 (templates.html)
- **核心功能**: 分类模板浏览
- **主要元素**:
  - 搜索功能
  - 分类标签导航
  - 热门模板展示
  - 模板详情卡片
  - 评分和使用统计

### 3. AI预览 (preview.html)
- **核心功能**: 实时效果预览
- **主要元素**:
  - Prompt输入区域
  - AI模型选择
  - 参数调节滑块
  - 生成状态显示
  - 多模型结果对比
  - 效果分析图表

### 4. 历史记录 (history.html)
- **核心功能**: Prompt管理
- **主要元素**:
  - 使用统计数据
  - 时间分组显示
  - 历史记录卡片
  - 收藏和复用功能
  - 快速操作按钮

### 5. 个人中心 (profile.html)
- **核心功能**: 用户设置
- **主要元素**:
  - 用户信息展示
  - 会员状态显示
  - 使用统计图表
  - 设置选项列表
  - 账户管理功能

## 🛠 技术特性

### 响应式设计
- 固定iPhone 15 Pro尺寸 (393×852px)
- 真实的圆角和阴影效果
- 完整的状态栏模拟

### 交互体验
- 悬停效果和过渡动画
- 真实的按钮和表单元素
- 统一的视觉反馈

### 开发友好
- 语义化HTML结构
- 清晰的CSS类命名
- 模块化的组件设计
- 完整的注释说明

## 🎯 设计原则

### 用户体验
- **简洁易用**: 降低学习成本，一目了然的界面
- **高效便捷**: 最少点击完成核心任务
- **智能贴心**: 主动推荐，个性化体验
- **专业可靠**: 高质量内容，稳定的功能表现

### 视觉层次
- 清晰的信息架构
- 合理的色彩搭配
- 统一的间距规范
- 突出的重点功能

## 📊 PRD对照

本原型图完全基于 `ai prompt助手.md` PRD文档设计，包含：

- ✅ 分层级Prompt模板库
- ✅ 智能推荐算法界面
- ✅ AI效果预览系统
- ✅ 用户反馈优化循环
- ✅ 5大应用场景覆盖
- ✅ 现代化用户体验设计

## 🔧 二次开发

### 自定义样式
```css
/* 修改主色调 */
.gradient-bg {
    background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
}

/* 调整卡片阴影 */
.card-shadow {
    box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}
```

### 添加新功能
1. 复制现有HTML文件作为模板
2. 修改内容和样式
3. 在 `index.html` 中添加新的iframe展示




---

*本原型图严格按照用户需求和PRD文档设计，确保可直接用于实际开发。* 

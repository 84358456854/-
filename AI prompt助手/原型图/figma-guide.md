# AI Prompt助手 - Figma 100%复刻指南

## 📐 设计规范

### 画板设置
- **设备**: iPhone 15 Pro
- **尺寸**: 393 × 852 px
- **圆角**: 47px (外框) / 39px (屏幕)
- **背景**: #000000 (设备外框)

### 🎨 色彩规范

#### 主色调
```
渐变色 (主要背景):
- 起始色: #667eea
- 结束色: #764ba2
- 角度: 135度

状态栏渐变:
- 起始色: #667eea
- 结束色: #764ba2
- 不透明度: 100%
```

#### 辅助色彩
```
背景色:
- 主背景: #f9fafb (gray-50)
- 卡片背景: #ffffff
- 输入框背景: rgba(255,255,255,0.2)

文字颜色:
- 主标题: #1f2937 (gray-800)
- 副标题: #6b7280 (gray-500)
- 白色文字: #ffffff
- 链接色: #3b82f6 (blue-500)

边框颜色:
- 主边框: #e5e7eb (gray-200)
- 输入框边框: rgba(255,255,255,0.3)
```

#### 状态色彩
```
成功色: #10b981 (green-500)
警告色: #f59e0b (orange-500)  
错误色: #ef4444 (red-500)
信息色: #3b82f6 (blue-500)
紫色: #8b5cf6 (purple-500)
```

### 📝 字体规范

#### 字体族
```
主字体: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui
备用字体: 'SF Pro Display', 'PingFang SC', 'Microsoft YaHei'
```

#### 字体大小
```
页面标题: 24px (text-2xl) - font-bold
卡片标题: 18px (text-lg) - font-semibold  
子标题: 16px (text-base) - font-medium
正文: 14px (text-sm) - font-normal
小文字: 12px (text-xs) - font-normal
Tab文字: 10px - font-medium
```

### 📏 间距规范

#### 基础间距 (8px倍数)
```
超小间距: 4px
小间距: 8px
中间距: 16px
大间距: 24px
超大间距: 32px
```

#### 组件间距
```
卡片内边距: 16px (p-4)
页面水平边距: 16px (px-4)
页面垂直边距: 16px (py-4)
Tab Bar高度: 80px
状态栏高度: 44px
导航栏高度: 120px
```

#### 圆角规范
```
小圆角: 8px (rounded-lg)
中圆角: 12px (rounded-xl)  
大圆角: 16px (rounded-2xl)
按钮圆角: 8px
头像圆角: 50% (圆形)
设备圆角: 47px (外框) / 39px (屏幕)
```

### 🎭 阴影规范

#### 卡片阴影
```
X偏移: 0px
Y偏移: 4px
模糊: 20px
扩散: 0px
颜色: rgba(0,0,0,0.1)
```

#### 设备阴影
```
X偏移: 0px
Y偏移: 8px
模糊: 40px
扩散: 0px
颜色: rgba(0,0,0,0.3)
```

## 📱 界面详细规范

### 1. 状态栏 (所有页面)
```
高度: 44px
背景: 主渐变色
文字颜色: #ffffff
字体大小: 14px
左侧: 时间 "9:41"
右侧: 信号、WiFi、电池图标
```

### 2. 导航栏规范
```
高度: 80px (不含状态栏)
背景: 主渐变色
标题字体: 24px, font-bold, #ffffff
副标题字体: 14px, opacity-90, #ffffff
右侧图标: 40px × 40px, 背景 rgba(255,255,255,0.2)
```

### 3. Tab Bar规范
```
高度: 80px
背景: #ffffff
边框: 1px solid #e5e7eb (顶部)
图标大小: 20px
文字大小: 10px
激活色: #3b82f6 (blue-500)
非激活色: #9ca3af (gray-400)
```

### 4. 卡片组件规范
```
背景: #ffffff
圆角: 16px (rounded-2xl)
内边距: 16px (p-4)
阴影: 0 4px 20px rgba(0,0,0,0.1)
边距: 16px (mb-4)
```

### 5. 按钮规范

#### 主按钮
```
背景: #3b82f6 (blue-500)
文字: #ffffff
高度: 40px
圆角: 8px (rounded-lg)
字体: 14px, font-medium
```

#### 次按钮
```
背景: #f3f4f6 (gray-100)
文字: #374151 (gray-700)
其他规格同主按钮
```

### 6. 输入框规范
```
背景: #ffffff 或 rgba(255,255,255,0.2)
边框: 1px solid #e5e7eb
圆角: 12px (rounded-xl)
内边距: 12px (p-3)
字体: 14px
占位符颜色: #9ca3af (gray-400)
聚焦边框: 2px solid #3b82f6
```

## 🛠 Figma 组件库建议

### 基础组件
1. **状态栏组件** - 可复用的iOS状态栏
2. **导航栏组件** - 带标题和图标的渐变导航栏
3. **Tab Bar组件** - 5个Tab的底部导航
4. **卡片组件** - 基础白色卡片容器
5. **按钮组件** - 主按钮和次按钮variants
6. **输入框组件** - 文本输入和搜索框variants

### 页面组件
1. **iPhone Frame** - 设备外框组件
2. **页面模板** - 包含状态栏+导航栏+内容区+Tab Bar

### 图标库
使用FontAwesome图标集，主要图标：
- fa-home, fa-layer-group, fa-eye, fa-history, fa-user
- fa-robot, fa-edit, fa-magic, fa-search, fa-heart
- fa-star, fa-copy, fa-thumbs-up, fa-thumbs-down
- fa-bell, fa-cog, fa-crown, fa-download, fa-share

## 🎨 具体复刻步骤

### Step 1: 创建设备框架
1. 创建 393×852px 的iPhone 15 Pro框架
2. 添加47px圆角的黑色外框 (#000000)
3. 内部创建39px圆角的白色屏幕区域

### Step 2: 建立设计系统
1. 创建颜色样式库 (Color Styles)
2. 创建文字样式库 (Text Styles)  
3. 创建效果样式库 (Effect Styles) - 阴影
4. 创建组件库 (Components)

### Step 3: 复刻每个页面
1. 从状态栏开始，逐层构建
2. 使用Auto Layout进行响应式布局
3. 创建可复用组件
4. 保持一致的命名规范

### Step 4: 制作交互原型
1. 连接页面间的跳转关系
2. 添加Tab Bar切换交互
3. 添加按钮点击状态
4. 添加悬停效果 (如果需要)

## 📋 检查清单

### 视觉一致性
- [ ] 颜色完全匹配HTML版本
- [ ] 字体大小和粗细正确
- [ ] 间距严格按照规范
- [ ] 圆角半径准确
- [ ] 阴影效果一致

### 组件规范
- [ ] 所有重复元素已创建为组件
- [ ] 组件有清晰的命名
- [ ] 使用Auto Layout进行布局
- [ ] 响应式设计考虑周全

### 内容准确性
- [ ] 所有文字内容与HTML一致
- [ ] 图标使用正确
- [ ] 数据和示例内容匹配
- [ ] 功能描述准确

## 🚀 高效技巧

### 1. 批量操作
- 使用 "Select all with same fill" 批量修改颜色
- 使用 Figma 插件批量重命名图层
- 创建共享样式避免重复设置

### 2. 精确测量
- 使用浏览器开发者工具测量HTML元素尺寸
- 使用Figma的测量工具确保像素级精确
- 参考CSS的margin/padding值设置间距

### 3. 组件化思维
- 先创建最小的原子组件
- 逐步组合成分子和有机体组件
- 建立清晰的组件层级结构

### 4. 版本管理
- 为每个主要版本创建分支
- 定期备份设计文件
- 记录重要的设计决策

## 🔗 相关资源

### Figma 插件推荐
- **html.to.design** - HTML转Figma
- **Figma to Code** - 生成开发代码
- **Content Reel** - 批量填充内容
- **Unsplash** - 高质量图片库
- **Iconify** - 图标库

### 参考文档
- iOS设计规范: https://developer.apple.com/design/
- Tailwind CSS文档: https://tailwindcss.com/
- FontAwesome图标: https://fontawesome.com/

---

*按照此指南可以100%精确复刻HTML原型图到Figma，确保设计的一致性和专业性。* 
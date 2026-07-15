# 贡献指南

感谢您对 **lccuhk** 个人主页项目的关注！我们欢迎任何形式的贡献，无论是提交 Bug 报告、提出功能建议，还是直接贡献代码。

## 📋 目录

- [行为准则](#行为准则)
- [如何贡献](#如何贡献)
  - [提交 Issue](#提交-issue)
  - [提交 Pull Request](#提交-pull-request)
- [内容规范](#内容规范)
- [内容风格指南](#内容风格指南)
- [开发环境](#开发环境)
- [贡献类型](#贡献类型)

## 行为准则

本项目遵循 [Contributor Covenant](.github/CODE_OF_CONDUCT.md) 行为准则。参与项目即表示您同意遵守其条款。

## 如何贡献

### 提交 Issue

如果您发现了 Bug 或有新功能建议，请通过 Issue 告诉我们：

1. **Bug 报告**：请包含以下信息
   - 问题描述（清晰简洁）
   - 复现步骤
   - 预期行为
   - 实际行为
   - 环境信息（操作系统、浏览器版本等）
   - 错误日志或截图（如适用）

2. **功能建议**：请包含以下信息
   - 功能描述
   - 为什么需要这个功能
   - 实现思路（可选）
   - 相关的参考资料（如适用）

### 提交 Pull Request

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

**PR 规范：**
- 标题清晰描述改动内容，使用中文或英文均可
- 详细说明改动的原因和内容
- 关联相关的 Issue（如 `Fixes #123`）
- 确保所有链接有效
- 更新相关文档（如 README、CHANGELOG）

## 内容规范

### Markdown 规范
- 使用标准的 Markdown 语法
- 标题层级清晰（#、##、###）
- 列表使用正确的缩进
- 代码块使用正确的语言标识
- 链接使用完整的 URL
- 图片使用可访问的链接

### 链接规范
- 所有外部链接必须有效
- 使用 HTTPS 协议
- 避免使用短链接
- 定期检查链接有效性

### 图片规范
- 使用 SVG 或优化的 PNG/JPG 格式
- 图片尺寸适中，加载速度快
- 使用可访问的图片链接
- 添加 alt 文本描述

## 内容风格指南

### Git 提交规范

我们遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <subject>

<body>

<footer>
```

**提交类型（type）：**
- `feat` - 新内容、新章节
- `fix` - 修复错误、修复链接
- `docs` - 文档更新
- `style` - 格式调整（不影响内容）
- `refactor` - 内容重构
- `perf` - 性能优化（图片压缩等）
- `chore` - 辅助工具的变动
- `ci` - CI/CD 配置变更
- `revert` - 回退提交

**示例：**
```
feat(projects): add new project showcase section

- Add couple-mini-game project card
- Update project descriptions
- Add project statistics badges
- Fix broken links in project list

Closes #456
```

**提交规范：**
- 标题不超过 72 个字符
- 使用中文或英文均可，但要保持一致
- 标题使用祈使句（"添加" 而不是 "添加了"）
- 正文详细说明改动的原因和内容
- 关联相关 Issue（如 `Closes #123`、`Fixes #456`）

### Markdown 风格指南

#### 标题规范
```markdown
# 一级标题（页面标题，只有一个）

## 二级标题（主要章节）

### 三级标题（子章节）

#### 四级标题（小节）
```

#### 列表规范
```markdown
<!-- 无序列表 -->
- 项目一
- 项目二
  - 子项目
  - 子项目
- 项目三

<!-- 有序列表 -->
1. 第一步
2. 第二步
3. 第三步

<!-- 任务列表 -->
- [x] 已完成任务
- [ ] 待完成任务
- [ ] 待完成任务
```

#### 链接规范
```markdown
<!-- 行内链接 -->
[链接文本](https://example.com)

<!-- 引用式链接 -->
[链接文本][reference]

[reference]: https://example.com

<!-- 图片 -->
![替代文本](image.png)
![替代文本](image.png "图片标题")
```

#### 代码块规范
````markdown
<!-- 行内代码 -->
使用 `code` 标签

<!-- 代码块 - 指定语言 -->
```javascript
const message = 'Hello, World!'
console.log(message)
```

```python
def hello():
    print('Hello, World!')
```

```bash
npm install
npm run dev
```
````

#### 表格规范
```markdown
| 列标题 1 | 列标题 2 | 列标题 3 |
|---------|---------|---------|
| 内容 1  | 内容 2  | 内容 3  |
| 内容 4  | 内容 5  | 内容 6  |
```

#### 引用规范
```markdown
> 这是一段引用文本
> 可以跨越多行
>
> — 作者名
```

### 内容规范

#### 徽章规范
- 使用 shields.io 生成徽章
- 徽章风格统一（for-the-badge）
- 颜色搭配协调
- 链接指向正确的目标

#### 图片规范
- 使用 SVG 格式优先
- 图片尺寸适中
- 添加 alt 文本描述
- 使用稳定的图片托管服务

#### 链接规范
- 使用 HTTPS 协议
- 链接必须有效
- 避免使用短链接
- 定期检查链接有效性

## 开发环境

本项目是一个 GitHub Profile README 项目，主要使用 Markdown 编写：

1. **克隆仓库**
   ```bash
   git clone https://github.com/lccuhk/lccuhk.git
   cd lccuhk
   ```

2. **编辑文件**
   - 主要编辑 `README.md` 文件
   - 可以使用任何 Markdown 编辑器
   - 建议使用支持实时预览的编辑器

3. **本地预览**
   - 使用 VS Code 的 Markdown 预览功能
   - 或使用在线 Markdown 编辑器
   - 或使用 `grip` 工具在浏览器中预览：
     ```bash
     pip install grip
     grip README.md
     ```

4. **验证链接**
   ```bash
   # 使用 lychee 检查链接（需要安装）
   lychee README.md
   
   # 或使用 Python 脚本检查
   python3 -c "
   import re
   import requests
   
   with open('README.md', 'r') as f:
       content = f.read()
   
   urls = re.findall(r'\((https?://[^)]+)\)', content)
   for url in urls:
       try:
           response = requests.head(url, timeout=10, allow_redirects=True)
           print(f'✅ {url[:60]}... - {response.status_code}')
       except Exception as e:
           print(f'❌ {url[:60]}... - {str(e)[:40]}')
   "
   ```

## 贡献类型

我们欢迎各种类型的贡献：

### 🐛 Bug 修复
- 修复无效链接
- 修复图片加载问题
- 修复排版错误
- 修复语法错误

### ✨ 新功能
- 添加新的项目展示
- 添加新的技能徽章
- 添加新的统计卡片
- 添加新的动画效果
- 添加多语言支持
- 添加博客文章列表
- 添加作品集展示

### 📚 文档
- 改进 README 文档
- 添加使用教程
- 补充说明文档
- 翻译文档

### 🎨 设计
- 改进页面布局
- 优化配色方案
- 添加新的图标或图片
- 优化动画效果
- 改进响应式设计

### 🌐 内容
- 更新个人信息
- 添加新的项目展示
- 更新技能列表
- 添加新的成就
- 翻译页面内容

### 🔧 配置
- 添加自动化工作流
- 优化 CI/CD 流程
- 添加链接检查
- 添加安全扫描
- 改进仓库配置

## 问题？

如果您在贡献过程中遇到任何问题，欢迎通过以下方式联系我们：

- 提交 [Issue](https://github.com/lccuhk/lccuhk/issues)
- 查看 [README.md](README.md) 了解更多项目信息
- 查看 [CHANGELOG.md](CHANGELOG.md) 了解版本历史

再次感谢您的贡献！🎉

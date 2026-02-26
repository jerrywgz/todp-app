# 📝 我的待办清单

一个简洁美观的待办事项管理应用，使用纯 HTML + CSS + JavaScript 开发，数据存储在浏览器本地。

## ✨ 功能特性

- ✅ **添加任务** - 支持设置优先级（高/中/低）
- ✅ **标记完成** - 点击复选框切换完成状态
- ✅ **编辑任务** - 可修改任务内容和优先级
- ✅ **删除任务** - 单条删除或批量清空
- ✅ **数据统计** - 实时显示任务完成情况
- ✅ **本地存储** - 刷新页面数据不丢失
- ✅ **响应式设计** - 支持桌面和移动端

## 🚀 在线预览

访问地址：https://你的用户名.github.io/仓库名/

## 📦 部署到 GitHub Pages

### 方法一：通过 Git 命令行

1. **创建 GitHub 仓库**
   - 登录 GitHub，点击右上角 "+" → "New repository"
   - 输入仓库名（如 `todo-app`）
   - 选择 "Public"，勾选 "Add a README file"
   - 点击 "Create repository"

2. **上传代码到仓库**

   ```bash
   # 克隆仓库到本地
   git clone https://github.com/你的用户名/仓库名.git
   cd 仓库名

   # 复制本项目的 index.html 到仓库目录

   # 添加、提交并推送
   git add index.html
   git commit -m "Initial commit: Add todo app"
   git push origin main
   ```

3. **启用 GitHub Pages**
   - 进入仓库页面，点击 "Settings"
   - 左侧选择 "Pages"
   - "Source" 选择 "Deploy from a branch"
   - "Branch" 选择 "main"，文件夹选择 "/ (root)"
   - 点击 "Save"
   - 等待几分钟后，即可通过生成的链接访问

### 方法二：直接网页上传（推荐新手）

1. 创建 GitHub 仓库（同上步骤1）
2. 点击 "Add file" → "Upload files"
3. 将 `index.html` 文件拖放到上传区域
4. 点击 "Commit changes"
5. 进入 Settings → Pages 启用（同上步骤3）

## 📱 添加到手机桌面

### iOS Safari
1. 用 Safari 打开网页
2. 点击底部分享按钮
3. 选择 "添加到主屏幕"
4. 点击 "添加"

### Android Chrome
1. 用 Chrome 打开网页
2. 点击右上角菜单（⋮）
3. 选择 "添加到主屏幕" 或 "安装应用"

## 🛠 技术栈

- HTML5
- CSS3（Flexbox、渐变、动画）
- Vanilla JavaScript（ES6+ Class）
- LocalStorage 数据持久化

## 📄 文件说明

```
.
├── index.html    # 主页面（单文件应用）
└── README.md     # 项目说明文档
```

## 📝 浏览器兼容性

- Chrome / Edge（推荐）
- Firefox
- Safari
- 移动端浏览器

---

Made with ❤️ by 你的名字

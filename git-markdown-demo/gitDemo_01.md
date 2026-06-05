# Git Demo 项目

这是一个用于学习 Git 基本操作的演示项目。

## 功能特性

- 演示 Git 初始化
- 演示文件添加和提交
- 演示分支创建和切换
- 演示远程仓库操作

## 技术栈

- Git
- Markdown

---

## Git 基础语法知识

### 分支命名规则

良好的分支命名能让团队协作更顺畅，常见的分支命名规范：

| 类型 | 命名格式 | 示例 | 说明 |
|------|----------|------|------|
| 功能分支 | `feature/功能描述` | `feature/user-login` | 开发新功能 |
| 修复分支 | `fix/修复内容` | `fix/login-bug` | 修复 Bug |
| 发布分支 | `release/版本号` | `release/v1.0.0` | 准备发布版本 |
| 热修复分支 | `hotfix/修复内容` | `hotfix/urgent-fix` | 紧急修复线上问题 |
| 实验分支 | `experiment/实验内容` | `experiment/new-feature` | 实验性开发 |

### 提交信息规范

良好的提交信息有助于查看项目历史：

```bash
# 格式
git commit -m "<类型>: <简短描述>"

# 示例
git commit -m "feat: 添加用户登录功能"
git commit -m "fix: 修复登录页面的显示问题"
git commit -m "docs: 更新 README 文档"
git commit -m "refactor: 重构用户模块代码"
```

**常用提交类型：**
- `feat`: 新功能
- `fix`: 修复 bug
- `docs`: 文档更新
- `style`: 代码格式调整
- `refactor`: 重构
- `test`: 测试相关
- `chore`: 构建/工具链相关

### 仓库命名建议

- 使用小写字母
- 单词之间用连字符 `-` 分隔
- 使用有意义的名称
- 避免特殊字符和空格

**推荐：** `my-awesome-project`, `user-management-system`

**避免：** `MyAwesomeProject`, `project name 123`, `repo!`

---

## 快速开始

### 1. 切换工作目录

首先将当前工作目录切换到你希望存放克隆目录的位置：

**Windows (PowerShell/CMD):**
```bash
# 切换到指定目录,
cd D:\你的\目标\目录

# 或者使用绝对路径
cd "D:\My Projects"

# 查看当前目录
pwd
```
**Windows（git bash）🔆‼️:**
```bash
# 切换到指定目录,
cd /d/你的/目标/目录
#或者
cd /c/你的/目标/目录

# 或者使用绝对路径
cd /d/My Projects/项目名称

# 查看当前目录
pwd

#查看项目目录下的文件
ls
# 再切换到项目目录
cd 项目名称
```


**Linux/Mac:**
```bash
# 切换到指定目录
cd /path/to/your/directory

# 查看当前目录
pwd
```

**提示：**
- 使用 `cd ..` 返回到上一级目录
- 使用 `cd ~` 快速回到用户主目录
- 使用 Tab 键自动补全路径

### 2. 克隆仓库
```bash
git clone <仓库地址>

# 示例
git clone https://github.com/用户名/仓库名.git

# 克隆后进入项目目录
cd 仓库名
```

### 3. 创建分支
```bash
git checkout -b feature-branch
```

### 4. 提交更改
```bash
git add .
git commit -m "添加新功能"
```

### 5. 推送到远程
```bash
git push origin main
```

---

## 项目结构

```
git-demo/
├── README.md          # 项目说明文档
├── index.html         # 主页
└── styles.css         # 样式文件
```

## 贡献

欢迎提交 Issue 和 Pull Request！

---

> 学习 Git 的最佳方式是多实践！
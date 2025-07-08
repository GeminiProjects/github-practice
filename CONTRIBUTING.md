# 贡献指南

## 开发环境设置

### 前置要求
- [Bun](https://bun.sh/)

### 本地开发
```bash
# 1. 克隆项目
git clone https://github.com/GeminiProjects/github-practice
cd github-practice

# 2. 安装依赖
bun install

# 3. 运行测试
bun dev
```

## 贡献流程

### 1. 创建功能分支
```bash
git checkout -b feat/your-feature-name
```

### 2. 提交更改
- 确保代码符合项目规范
- 编写清晰的提交信息
- 每个提交应该是一个逻辑单元

### 3. 提交 Pull Request
- 填写 PR 模板
- 描述更改内容和目的
- 关联相关 Issue（如有）

## 提交信息规范

使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

### 常用类型
- `feat`: 新功能
- `fix`: 修复 bug
- `docs`: 文档更改
- `style`: 代码格式调整
- `refactor`: 代码重构
- `test`: 测试相关
- `chore`: 构建工具或辅助工具的变动

### 示例
```
feat(auth): 添加用户认证系统
fix(api): 解决数据获取超时问题
docs(readme): 更新安装说明
```

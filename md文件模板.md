# 一级标题
## 二级标题
### 三级标题
#### 四级标题

> [简短的一句话介绍，例如：一个基于 Python 的自动化测试工具，支持多平台并发执行]

## 📌 特性 (Features)
- ✅ 支持功能点 1（例如：跨平台运行）
- ✅ 支持功能点 2（例如：自动报告生成）
- ✅ 支持功能点 3（例如：Docker 容器化部署）

## 🚀 快速开始 (Quick Start)

### 环境要求
- Python 3.8+
- Node.js 14+
- Docker Engine 20.0+

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/yourname/your-project.git

# 进入目录
cd your-project

# 安装依赖
pip install -r requirements.txt
# 或者
npm install
```
---

### 2. Issue 模板 (`.github/ISSUE_TEMPLATE/bug_report.md`)
**适用场景**：当用户报告 Bug 时，引导他们提供关键信息，减少沟通成本。

```markdown
## 🐛 问题描述 (Bug Description)
> 请简要描述你遇到的问题。

**预期行为**：
- 描述一下你原本期望发生什么。

**实际行为**：
- 描述一下实际发生了什么。

## 📋 复现步骤 (Steps to Reproduce)
1. 第一步：...
2. 第二步：...
3. 第三步：...

## 📸 环境信息 (Environment)
- **操作系统**: [例如：Windows 10 / macOS Monterey / Ubuntu 20.04]
- **版本**: [例如：v1.2.3]
- **浏览器/工具**: [例如：Chrome 110 / VS Code]

## 📝 附加信息 (Additional Context)
- 错误日志截图或文本：
  ```text
  在此粘贴错误日志
```
---

### 3. PR 模板 (`.github/PULL_REQUEST_TEMPLATE.md`)
**适用场景**：当你提交代码时，引导开发者描述修改内容，方便 Reviewer 快速理解。

```markdown
## 📝 变更描述 (Description)
> 请简要说明这个 PR 的目的和主要变更。

- [ ] 修复了 [具体 Issue 编号]
- [ ] 新增了 [功能名称]
- [ ] 重构了 [模块名称]

## 🔗 关联 Issue (Linked Issue)
Closes #123 (如果有关联的 Issue，请在这里填写)

## 🧪 测试 (Testing)
- [ ] 本地测试通过
- [ ] 已添加单元测试
- [ ] 测试场景覆盖：[简述测试场景]

## 📸 截图 (Screenshots)
如果有 UI 变化，请在这里附上截图。

## 📋 检查清单 (Checklist)
- [ ] 代码符合项目代码规范
- [ ] 自测通过
- [ ] 更新了相关文档
- [ ] 没有引入新的依赖冲突

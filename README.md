# NoteBarn

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 项目概述

**NoteBarn** 是一个本地化的知识管理工具，旨在帮助用户高效地存储、管理和检索笔记。通过AI辅助的功能，如智能分类和摘要生成，NoteBarn让知识管理变得更加简单和有趣。项目名称中的“Barn”象征着知识的储存仓库，寓意用户可以像储存谷物一样安全地保存自己的笔记。

### 核心价值
- **本地化存储**：所有数据都在本地处理和存储，确保隐私安全。
- **AI辅助**：利用先进的AI模型（如Ollama + DeepSeek-R1）实现智能分类和摘要生成。
- **简洁易用**：直观的用户界面，支持拖拽操作和标签管理。

## 功能特性

### 主要功能
- **笔记管理**：创建、编辑和删除笔记，支持多种格式（文本、PDF、图片等）。
- **智能分类**：自动将笔记按主题或关键词分类，便于查找。
- **向量检索**：利用LanceDB进行高效的向量相似度检索，快速找到相关笔记。
- **加密存储**：AES-256加密保护敏感数据，确保隐私安全。
- **跨平台支持**：通过PyInstaller打包成独立可执行文件，支持Windows、MacOS和Linux。

### 特色功能
- **AI助手**：内置AI助手，提供智能问答和摘要生成功能。
- **可视化管理**：通过图表展示笔记的关系和分布，增强用户体验。

## 技术栈

### 后端
- **编程语言**：Python
- **框架**：PyQt（用于构建用户界面）
- **AI模型**：Ollama + DeepSeek-R1（用于智能分类和摘要生成）
- **向量数据库**：LanceDB（用于高效向量检索）

### 前端
- **UI库**：PyQt（用于构建桌面应用）
- **图标设计**：谷仓主题图标，搭配大地色系配色方案

### 打包与分发
- **打包工具**：PyInstaller（用于生成独立可执行文件）

## 安装与使用

### 环境准备
确保系统已安装以下依赖：
```bash
pip install pyinstaller ollama transformers pyqt5 sqlite3 pandas matplotlib PyQtGraph
```

### 安装步骤
1. 克隆项目仓库：
   ```bash
   git clone https://github.com/yourusername/notebarn.git
   cd notebarn
   ```

2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```

3. 运行项目：
   ```bash
   python main.py
   ```

### 使用说明
1. **创建笔记**：点击“新建笔记”按钮，输入内容并保存。
2. **导入文件**：支持拖拽PDF、图片等文件到主界面进行导入。
3. **智能分类**：启用AI助手，自动对笔记进行分类和标签管理。
4. **检索笔记**：使用搜索栏或标签筛选功能快速找到所需笔记。

## 贡献指南

我们欢迎任何形式的贡献！如果你有兴趣参与NoteBarn的开发，请遵循以下步骤：

1. **Fork** 仓库并在本地克隆。
2. 创建一个新的分支 (`git checkout -b feature-new-feature`)。
3. 提交你的更改 (`git commit -am 'Add new feature'`)。
4. 推送到远程分支 (`git push origin feature-new-feature`)。
5. 在GitHub上发起Pull Request。

## 许可证

本项目采用MIT许可证。详情请参见 [LICENSE](LICENSE) 文件。


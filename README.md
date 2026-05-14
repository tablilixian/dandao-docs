# 丹道修炼资料库

> **系统学习金丹大道，从百日筑基开始**

---

## 📖 关于本项目

本项目是一个基于 MkDocs 构建的静态网站，用于整理和分享丹道修炼的核心典籍和实修指南。

### 包含内容

- **《太乙金华宗旨》** - 入门经典，以"回光"为核心
- **《灵宝毕法》** - 系统修炼法门，三乘十门
- **个人化修炼方案** - 针对上班族的实修计划
- **参考资料** - 丹道典籍详解、流派梳理

### 特点

- ✅ Markdown 格式，简洁易读
- ✅ 手机适配，随时查看
- ✅ 搜索功能，快速定位
- ✅ 深色/浅色模式切换
- ✅ 完全免费，GitHub Pages 托管

---

## 🚀 快速开始

### 查看网站

网站部署后访问：
```
https://yourusername.github.io/dandao-docs
```

### 本地预览

```bash
# 克隆项目
git clone https://github.com/yourusername/dandao-docs.git
cd dandao-docs

# 安装依赖
pip install mkdocs mkdocs-material

# 本地预览
mkdocs serve
```

打开 http://127.0.0.1:8000 查看

---

## 📱 手机访问

网站已针对手机优化：

1. 用手机浏览器打开网站地址
2. 可以"添加到主屏幕"像 APP 一样使用
3. 支持深色模式，适合夜间阅读

---

## ✏️ 更新内容

### 方式一：直接编辑 Markdown

1. 修改 `docs/` 目录下的 `.md` 文件
2. 在 `mkdocs.yml` 的 `nav` 部分添加导航
3. 运行 `mkdocs gh-deploy` 部署

### 方式二：通过 GitHub

1. 在 GitHub 网页上直接编辑文件
2. 或者上传新文件
3. GitHub Actions 会自动部署

详细指南见 [更新指南.md](./更新指南.md)

---

## 🔧 部署到 GitHub Pages

详细步骤见 [部署指南.md](./部署指南.md)

简要步骤：

```bash
# 1. 创建 GitHub 仓库
# 2. 克隆到本地
git clone https://github.com/yourusername/dandao-docs.git

# 3. 上传本项目所有文件

# 4. 安装 MkDocs
pip install mkdocs mkdocs-material

# 5. 本地预览
mkdocs serve

# 6. 部署
mkdocs gh-deploy
```

---

## 📂 目录结构

```
dandao-docs/
├── mkdocs.yml          # 配置文件
├── docs/
│   ├── index.md       # 首页
│   ├── 个人修炼/
│   │   ├── 个人化修炼方案.md
│   │   └── 修炼日记模板.md
│   ├── 太乙金华宗旨/
│   │   ├── 01_典籍简介.md
│   │   ├── 02_成书背景.md
│   │   └── ...
│   ├── 灵宝毕法/
│   │   ├── 上卷/
│   │   ├── 中卷/
│   │   └── 下卷/
│   └── 参考资料/
│       └── ...
├── 部署指南.md
└── 更新指南.md
```

---

## 🙏 免责声明

本文档内容整理自正统道藏收录典籍，仅供学习参考。内丹修炼涉及身心深层变化，实际修习应在有经验的师父指导下进行。如有身体不适，请及时就医。

---

## 📄 许可证

本项目整理的资料可用于个人学习，请勿用于商业用途。

---

> **"行住坐卧皆可修"** —— 愿您在修炼路上稳步前行

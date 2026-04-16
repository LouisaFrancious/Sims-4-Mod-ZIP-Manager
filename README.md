# 💎 Sims 4 Mod ZIP Manager

A beautiful and simple desktop app to **batch extract Sims 4 mod ZIP files** into one organized folder.
一个美观且易用的桌面应用，用于**批量解压 Sims 4 Mod ZIP 文件并自动整理**。

✨ Built with **Tauri + React + TypeScript**
✨ 使用 **Tauri + React + TypeScript** 构建

---

## 🌸 Features | 功能

* 📦 **Batch Extraction | 批量解压**
  Extract all ZIP/RAR files in one click
  一键解压所有 ZIP / RAR 文件

* 📁 **Custom Output Folder | 自定义输出路径**
  Choose exactly where your mods go
  自由选择 Mod 存放位置

* 🎮 **Quick Access | 快速访问 Mods 文件夹**
  Open your Sims 4 Mods folder instantly
  一键打开 Sims 4 Mods 文件夹

* 🔍 **Search & Filter | 搜索与筛选**
  Quickly find ZIP or extracted files
  快速查找压缩包或已解压文件

* 🌍 **Multi-language Support | 多语言支持**
  English / 中文 / 日本語 / 한국어

* 🎨 **Clean UI | 精致界面设计**
  Soft pink aesthetic, Sims-inspired design
  粉色清新风格，Sims 灵感 UI

---

## 🖥️ Download | 下载

👉 **Windows Installer (.exe)**

Download the latest version from Releases:
从 Releases 页面下载最新版本：

➡️ https://github.com/YOUR_USERNAME/YOUR_REPO/releases

---

## 📸 Preview | 预览

### Splash Screen

Click on 'Launch application' to unzip your zip/rar files.
<img width="1437" height="957" alt="start" src="https://github.com/user-attachments/assets/be3e736f-ab22-4cbb-85b7-feeb3989b2ff" />


### Zip Vault

Click on 'choose zip folder' to select the folder path that you want to unzip all the zip/rar format files into one folder with only package selected.  
Click on 'Extract All'  to unzip.

<img width="1440" height="960" alt="1541e1d1e5ff3f96b6af47011be5b701" src="https://github.com/user-attachments/assets/5cb0e838-8036-4d62-ba57-0819596b9ffa" />


### Extracted Files

Before you unzip, please select the path for the unzipped files.  
You are able to open the Sims 4 mods file by clicking on 'Open Mods Folder'  

<img width="1440" height="960" alt="ace9b0ae1b76340526641be183befadc" src="https://github.com/user-attachments/assets/f299289d-6f79-46ff-a1fa-018b158cc4ae" />

### Settings

Language settings are currently available in English, Simplified Chinese, Japanese, Korean.  

<img width="1440" height="960" alt="0d60cfc624e15714702b056c876420fa" src="https://github.com/user-attachments/assets/657e512d-fcea-4da6-a2c6-856b811be268" />


---

## 🚀 Getting Started | 本地运行

### 1. Clone the repo | 克隆项目

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 2. Install dependencies | 安装依赖

```bash
npm install
```

### 3. Run the app | 启动应用

```bash
npx tauri dev
```

---

## 📦 Build | 打包

```bash
npx tauri build
```

Installer location / 安装包路径：

```
src-tauri/target/release/bundle/nsis/
```

---

## ⚙️ Tech Stack | 技术栈

* ⚛️ React + TypeScript — Frontend UI
* 🦀 Tauri (Rust) — Backend
* 🎨 Custom CSS — UI Styling
* 📦 Rust ZIP/RAR libraries — File extraction

---

## 💡 Why this project? | 项目背景

Managing Sims 4 mods can get messy:

管理 Sims 4 Mod 经常会遇到：

* ❌ Too many ZIP files
  ZIP 文件过多

* ❌ Manual extraction is tedious
  手动解压非常繁琐

* ❌ Disorganized folders
  文件夹混乱

👉 This tool solves that with:
👉 本工具通过以下方式解决：

**One-click batch extraction + organized output**
**一键批量解压 + 自动整理文件夹**

---

## 🛣️ Roadmap | 未来计划

* [ ] Auto-detect Sims 4 Mods folder 自动检测 Mods 路径
* [ ] Drag & drop ZIP support 拖拽上传
* [ ] Mod conflict detection Mod 冲突检测
* [ ] Auto-update system 自动更新
* [ ] macOS version Mac 版本

---

## 📂 Project Structure | 项目结构

```
├── src/            → React frontend
├── src-tauri/      → Rust backend
└── icons/          → App icons
```

---

## 🧑‍💻 Author | 作者

**Louisa Liu**
🎓 NYU Computer Science

💡 Interested in Product + Engineering
💡 专注于产品与工程结合

---

## 💖 Acknowledgements | 致谢

* The Sims 4 Modding Community

* Sims 4 模组社区

* Inspiration for better mod tools

* 对更好 Mod 工具的探索

---

## 📜 License | 许可证

MIT License

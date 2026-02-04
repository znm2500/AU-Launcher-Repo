# 🖼️ AU-Launcher-Repo - 静态资源与数据存储分支

本分支 (**assets/data 分支**) 专门用于托管 **[你的启动器名称]** 所需的非代码类资源。

### 📌 分支定位
为了保持主分支 (`main`) 的整洁，所有大尺寸图片、同人插画、封面以及游戏索引数据均存储于此。本分支作为启动器的 **CDN 后端存储库** 使用。

---


### 🔗 访问路径 (jsDelivr 加速)

本分支资源已接入 jsDelivr 全球加速，调用格式如下：

**图片调用：**
`https://cdn.jsdelivr.net/gh/znm2500/UNDERTALE-AUs-Repo@当前分支名/covers/example.png`

**数据调用：**
`https://cdn.jsdelivr.net/gh/znm2500/UNDERTALE-AUs-Repo@当前分支名/metadata/info.json`

---

### 🛠️ 维护规范
1.  **图片优化**：上传前请务必使用工具（如 TinyPNG）压缩图片体积，单张图片建议不超过 500KB。
2.  **命名规范**：文件名请使用小写字母及下划线（如 `gameid.png`），避免使用中文或空格导致链接失效。
3.  **引用限制**：本分支资源仅限同人启动器及相关项目调用，严禁将其作为通用图床使用。

---
*Determination stays here.* 🌟
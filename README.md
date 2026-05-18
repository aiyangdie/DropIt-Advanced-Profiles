# 📁 DropIt-Advanced-Profiles

**Windows DropIt 文件自动分类高级配置，100+ 规则覆盖主流文件格式，开箱即用。**

[![在线访问](https://img.shields.io/badge/在线访问-点击体验-blue)](https://aiyangdie.github.io/DropIt-Advanced-Profiles)

---

## 📌 项目简介

DropIt-Advanced-Profiles 为 Windows 文件自动整理工具 [DropIt](https://www.dropitproject.com/) 提供高级分类配置文件，涵盖 100+ 条文件类型规则，覆盖压缩包、图片、视频、音频、文档、代码、设计、数据库、虚拟机镜像、电子书、字体等 15+ 大类。项目同时提供 DropIt 绿色免安装版，下载即用，零配置上手。

---

## ✨ 核心特性

- 📦 **绿色免安装** — DropIt 便携版，解压即用，无需安装
- 🗂️ **100+ 分类规则** — 覆盖 15+ 大类、100+ 种文件格式
- 🔍 **细分到格式** — 同一大类按格式细分（如图片下分 JPG / PNG / GIF / SVG / PSD 等）
- 🛡️ **兜底分类** — `*.*` 通配规则确保无遗漏，未匹配文件归入「其它」
- ✏️ **易于定制** — INI 格式配置文件，文本编辑器即可修改
- 🔄 **可迁移分享** — 配置文件可自由备份、迁移、多设备同步
- 🌐 **下载页面** — 内置极简网页，提供软件和配置文件下载入口

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| DropIt | Windows 文件自动分类工具 |
| INI 配置格式 | 分类规则定义 |
| HTML5 / CSS3 | 项目下载页面 |
| 7-Zip | 压缩包处理依赖库 |

---

## 🚀 快速开始

### 前置条件

- Windows 操作系统（7 / 8 / 10 / 11）

### 安装步骤

1. **下载 DropIt 绿色版**
   - 从项目 `软件在这里/dropit851.zip` 下载并解压
   - 或访问 [DropIt 官网](https://www.dropitproject.com/) 获取最新版

2. **导入高级配置**
   - 将项目根目录的 `Default.ini` 复制到 DropIt 的 `Profiles/` 目录
   - 覆盖同名文件即可

3. **启动使用**
   - 运行 `DropIt.exe`
   - 选择导入的配置文件
   - 将文件拖放到 DropIt 图标上，自动分类整理

### 自定义配置

用文本编辑器打开 `Default.ini`，按以下格式添加或修改规则：

```ini
[规则名称]
State=Enabled
Rules=*.扩展名
Action=$0
Destination=目标文件夹路径
```

---

## 📂 项目结构

```
DropIt-Advanced-Profiles/
├── Default.ini                                  # 高级分类规则配置文件
├── index.html                                   # 项目下载页面
├── 说明.txt                                     # 分类规则简要说明
├── CNAME                                        # GitHub Pages 自定义域名
├── README.md                                    # 项目说明
└── 软件在这里/
    ├── dropit851.zip                            # DropIt 绿色版压缩包
    └── dropit851/
        ├── memo.txt                             # 备注文件
        ├── 更新日志.txt                          # 更新日志
        └── DropIt Portable v8.5.1/
            └── DropIt/
                ├── DropIt.exe                   # 主程序
                ├── Guide.pdf                    # 使用手册
                ├── settings.ini                 # 运行设置
                ├── Profiles/
                │   └── Default.ini              # 默认配置
                ├── Images/                      # 图标资源
                ├── Languages/                   # 多语言支持
                │   ├── English.lng              # 英语
                │   └── SimplifiedChinese.lng    # 简体中文
                └── Lib/                         # 依赖库
                    ├── 7z/                      # 7-Zip 压缩库
                    ├── gallery/                 # 图片画廊
                    ├── list/                    # 列表生成
                    ├── pdftotext/               # PDF 转文本
                    ├── psftp/                   # FTP 传输
                    ├── rdc/                     # 远程桌面
                    └── sounds/                  # 提示音效
```

---

## 📋 分类体系总览

| 大类 | 覆盖格式示例 |
|------|-------------|
| 📦 压缩包 | zip, rar, 7z, tar, gz, bz2, xz, iso, cab, lzh, arj, jar, ace, zoo, lzma, lzo |
| 🖼️ 图片 | jpg, png, gif, bmp, tiff, webp, raw, heic, svg, ico, psd, ai, jp2, exr, tga |
| 🎬 视频 | mp4, avi, mkv, mov, wmv, flv, webm, m4v, 3gp, rmvb |
| 🎵 音频 | mp3, wav, flac, aac, ogg, wma, m4a, ape, alac |
| 📄 文档 | pdf, doc, docx, xls, xlsx, ppt, pptx, txt, rtf, md, csv, xml, json, odt, wps |
| 💿 安装程序 | exe, msi, dmg, pkg, deb, rpm, apk, ipa |
| 💻 代码文件 | py, js, ts, go, rs, cs, swift, kt, dart, lua, java, cpp, c, php, sql, sh, bat, ps1 |
| 📚 电子书 | epub, mobi, azw3, fb2, djvu |
| 🎨 设计文件 | cdr, sketch, xd, fig |
| 🗄️ 数据库 | db, sqlite, mdb, accdb |
| 🖥️ 虚拟机镜像 | vmdk, vdi, vhd, img |
| 🔤 字体 | ttf, otf, woff, woff2, eot |
| 🗑️ 临时文件 | tmp, temp, log, cache, bak, old, swp, dmp |
| 🎯 其它 | *.*（兜底分类，防止遗漏） |

---

## 🤝 贡献与许可证

欢迎提交 PR 或 [报告问题](https://github.com/aiyangdie/DropIt-Advanced-Profiles/issues)！

- 本项目配置文件采用 MIT 开源协议
- DropIt 软件本身遵循其[官方许可协议](https://www.dropitproject.com/)

---

*📁 拖放即整理，让文件分类不再繁琐*

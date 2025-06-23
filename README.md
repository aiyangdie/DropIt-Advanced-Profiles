## DropIt-Advanced-Profiles

# DropIt 文件自动分类配置（绿色版+高级规则）

本项目为 Windows 下 [DropIt](https://www.dropitproject.com/) 文件自动整理工具的高级分类配置与绿色免安装版，适合需要高效、细致文件归类的用户。

## 项目亮点

- **绿色免安装**：直接下载即用，无需安装。
- **分类细致**：涵盖图片、文档、压缩包、代码、设计、虚拟机、字体等主流及特殊文件类型。
- **规则丰富**：支持自定义分类、目标文件夹和兜底"其它"分类，防止遗漏。
- **一键下载**：软件和配置文件均可直接下载，开箱即用。
- **支持分享与多设备协作**：配置文件可自由迁移、备份和分享。

## 文件结构

```
├── DropIt.exe                # DropIt 主程序（绿色版，直接运行）
├── Guide.pdf                 # DropIt 官方使用手册
├── settings.ini              # DropIt 运行设置
├── Profiles/
│   ├── Default.ini           # 高级分类规则配置文件（推荐使用）
│   ├── index.html            # 项目介绍网页（本地可直接打开）
│   ├── 说明.txt              # 分类规则简要说明
│   └── 软件在这里/
│       └── dropit851.zip     # DropIt 绿色版完整压缩包（推荐下载）
├── Images/                   # 图标与界面资源
├── Languages/                # 多语言支持
├── Lib/                      # 依赖库
```

## 快速开始

1. **下载软件和配置文件**
   - [⬇️ 下载 DropIt 绿色版](Profiles/软件在这里/dropit851.zip)
   - [⬇️ 下载分类配置文件 Default.ini](/Default.ini)

2. **使用方法**
   1. 解压 `dropit851.zip`，运行 `DropIt.exe` 即可使用，无需安装。
   2. 将 `Default.ini` 放入 DropIt 的 `Profiles` 目录（或覆盖同名文件）。
   3. 启动 DropIt，选择本配置文件，开始自动整理你的文件。
   4. 如需自定义分类或目标文件夹，可用文本编辑器打开 `Default.ini` 修改。
   5. 建议定期备份配置文件，便于恢复和迁移。

3. **网页版说明**
   - 打开 `Profiles/index.html`，可查看本项目的极简网页介绍和下载入口。

## 分类体系示例

- **图片类**：jpg、png、heic、svg、psd、ai、ico、cur、webp、tiff、raw、bmp、gif、jp2、exr 等
- **文档类**：pdf、doc、docx、xls、xlsx、ppt、odt、wps、epub、mobi、azw3、fb2、djvu 等
- **压缩包类**：zip、rar、7z、cab、iso、tar、gz、bz2、xz 等
- **代码/脚本类**：py、js、ts、go、rs、cs、swift、kt、dart、lua、vb、php、java、cpp、c、sh、bat、ps1 等
- **其它**：设计、数据库、虚拟机、动画、字体、临时、图标、可执行文件等均有专门分类

## 其它说明

- 可根据实际需求调整分类和目标文件夹。
- 如遇新文件类型，仿照现有规则在 `Default.ini` 中新增即可。
- 建议定期整理"其它"分类，完善规则，提升自动化效果。
- 如需最新版 DropIt，可访问 [DropIt 官网](https://www.dropitproject.com/)。

---

> 本项目为个人整理习惯分享，欢迎根据自身需求自由修改和扩展。如有建议或问题欢迎提 issue。 
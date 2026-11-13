<p align="center"><img src="assets/covers/45-DropIt-Advanced-Profiles.jpg" alt="自动分类 项目封面" width="100%"></p>

<h1 align="center">DropIt 高级分类配置</h1>

<p align="center">100+ 条文件类型规则，覆盖 15 大类，拖一下就自动归档</p>

<p align="center">
  <a href="http://dropit.aikex.ink/">下载页</a> ·
  <a href="https://www.dropitproject.com/">DropIt 官网</a>
</p>

## 简介

给 Windows 文件整理工具 DropIt 准备的一套现成规则：把下载目录里的压缩包、图片、视频、文档、代码、安装包各归各位。配置是纯文本 INI，想加自己的分类改两行就行。仓库另附 DropIt 8.5.1 绿色版，解压即用。

## 功能

- **绿色免安装**：附 DropIt 便携版，解压即用
- **100+ 规则**：覆盖 15+ 大类、100+ 种格式
- **细分到格式**：图片下再分 JPG / PNG / GIF / SVG / PSD
- **兜底规则**：`*.*` 保证不遗漏，未匹配归入「其它」
- **可迁移同步**：配置文件可备份、分享、多设备复用
- **下载页**：内置极简页面，软件与配置一处取

## 使用

1. 下载 `软件在这里/dropit851.zip` 解压，或从[官网](https://www.dropitproject.com/)取新版
2. 把仓库根目录的 `Default.ini` 覆盖到 DropIt 的 `Profiles/` 目录
3. 运行 `DropIt.exe`，选中该配置
4. 把文件拖到 DropIt 图标上，自动分类

自定义规则写法：

```ini
[规则名称]
State=Enabled
Rules=*.扩展名
Action=$0
Destination=目标文件夹路径
```

## 分类覆盖

| 大类 | 示例格式 |
|---|---|
| 压缩包 | zip, rar, 7z, tar, gz, iso, cab, jar |
| 图片 | jpg, png, gif, webp, heic, svg, psd, ai |
| 视频 | mp4, mkv, mov, avi, webm, rmvb |
| 音频 | mp3, flac, wav, aac, ogg, m4a |
| 文档 | pdf, docx, xlsx, pptx, md, csv, json |
| 安装程序 | exe, msi, apk, ipa, deb, rpm |
| 代码 | py, js, ts, go, rs, java, cpp, php, sql, ps1 |
| 电子书 | epub, mobi, azw3, djvu |
| 设计 / 数据库 / 虚拟机 / 字体 / 临时文件 | 各自独立归类 |

## 项目结构

```
Default.ini        分类规则
index.html         下载页
说明.txt           规则说明
CNAME              自定义域名
软件在这里/         DropIt 绿色版
```

## 许可

配置文件可自由使用与修改（原作者声明为 MIT）；DropIt 软件本身遵循其[官方许可协议](https://www.dropitproject.com/)。

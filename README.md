# Common Master - 常用语快速输入工具

<p align="center">
<img width="306" height="267" alt="image" src="https://github.com/user-attachments/assets/12101ed3-51e0-451e-9be3-0ee035c6e2af" />

</p>

<p align="center">
  <strong>你手机上有常用语快捷输入，为什么电脑上没有？</strong><br/>
  Common Master 就是为了解决这个问题而生的。
</p>

<p align="center">
  <a href="#功能特性">功能特性</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#使用场景">使用场景</a> •
  <a href="#技术架构">技术架构</a> •
  <a href="#下载">下载</a>
</p>

---

## 这是什么？

Common Master 是一款 Windows 原生桌面工具，让你像手机输入法一样，在电脑上一键输入常用语句。

按下快捷键 → 弹出常用语面板 → 点击即输入。就这么简单。

**不抢焦点、不切窗口、不占剪贴板。** 你正在打字的光标在哪，文字就输入到哪。

---

## 功能特性

### 🚀 核心功能：一键输入

- **全局快捷键呼出**：默认 `Ctrl+Alt+Q`，随时随地呼出常用语面板
- **不抢焦点输入**：窗口采用 `WS_EX_NOACTIVATE` 技术，像输入法候选框一样悬浮，不会抢走你正在编辑的窗口焦点
- **Unicode 直接输入**：通过 `SendInput` 逐字符输入，不依赖剪贴板，不会覆盖你复制的内容
- **光标位置弹出**：面板在鼠标光标附近弹出，伸手就能点到
- 
<img width="445" height="658" alt="image" src="https://github.com/user-attachments/assets/bee6877c-23d6-493d-a77d-7e76ed926f4f" />

### 🏷️ 标签分类管理

- **自定义标签**：按工作场景分类，比如"客服话术"、"代码片段"、"邮件模板"
- **标签排序**：左移右移，常用的放前面
- **标签编辑/删除**：右键菜单操作，删除标签时内容自动归入默认分类

### ✏️ 常用语管理

- **添加/编辑/删除**：完整的 CRUD 操作
- **上下排序**：常用的往上挪，不常用的往下放
- **跨标签移动**：一条常用语可以随时移到其他标签下

### 🎨 主题与多语言

- **深色/浅色主题**：一键切换，护眼模式随时开
- **三语支持**：中文、English、日本語，界面文本全部本地化
- **主题同步**：主窗口和设置窗口主题实时同步
<img width="466" height="713" alt="image" src="https://github.com/user-attachments/assets/b66ee07c-17aa-4642-9c5d-aa0919f486aa" />

### ☁️ 数据同步与备份

- **三种同步模式**：
  - 仅本地：数据存在本地 JSON 文件
  - 仅 WebDAV：数据存在你的 WebDAV 服务器
  - 同时两处：本地 + WebDAV 双保险
- **自动备份**：可配置备份间隔和最大备份数
- **远程备份**：备份文件同步上传到 WebDAV
- **状态栏实时显示**：最后备份时间、同步状态、失败信息一目了然
<img width="394" height="383" alt="image" src="https://github.com/user-attachments/assets/8d0ac640-40cd-4cdd-b8a1-cd1b263991fe" />

### 🪟 窗口记忆

- **记住窗口大小**：关闭程序后再打开，窗口大小和上次一样
- **可调整大小**：右下角拖拽自由缩放

### ⚙️ 更多设置

- **开机自启**：设置一次，每次开机自动运行
- **自定义快捷键**：不喜欢默认快捷键？随便改
- **自定义数据路径**：数据文件想放哪就放哪
- **WebDAV 连通性测试**：配置完一键测试，确认能连上
- **系统托盘常驻**：不占任务栏位置，安静地待在托盘里

---

## 快速开始

### 系统要求

- Windows 10/11
- .NET 8.0 Runtime

### 安装

1. 从 [Releases](../../releases) 页面下载最新版本
2. 解压到任意目录
3. 运行 `CommonMaster.exe`

### 基本使用

1. 程序启动后常驻系统托盘
2. 按 `Ctrl+Alt+Q` 呼出常用语面板
3. 点击常用语即可输入到当前光标位置
4. 再按一次快捷键或点击其他地方隐藏面板

---

## 使用场景

### 💼 客服/销售

> "您好，请问有什么可以帮您？"
> "感谢您的咨询，祝您生活愉快！"
> "已为您提交工单，预计 24 小时内处理完毕。"

每天要打几十上百遍的话术，一键搞定。

### 💻 程序员

> `console.log('debug:', )`
> `// TODO: `
> `git commit -m "fix: "`

代码片段、Git 命令、调试语句，不用每次都敲。

### 📧 办公族

> "附件请查收，如有问题请随时联系。"
> "会议纪要如下：..."
> "请问这个需求的截止日期是？"

邮件、聊天、文档里反复出现的句子，存起来点一下就好。

### 🎮 游戏玩家

> "gg"
> "集合"
> "我先去吃个饭"

游戏里打字太慢？常用语一键发送。

---

## 💖 支持作者

如果这个工具对您有帮助，欢迎支持作者继续开发更多实用工具！

### 💳 打赏方式

<div align="center">

#### 微信支付
<img src="https://github.com/muscccm/Excel-Column-Extraction-Tool/blob/main/WC.png?raw=true" width="200" alt="微信支付二维码">

#### 支付宝
<img src="https://github.com/muscccm/Excel-Column-Extraction-Tool/blob/main/AP.png?raw=true" width="200" alt="支付宝二维码">

#### PayPal
[点击这里通过PayPal支持](https://paypal.me/muscccm?country.x=C2&locale.x=zh_XC)

</div>

您的支持是我继续创作的动力！💪

## 📝 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🤝 贡献

欢迎提交问题和功能请求！如果您想贡献代码，请先创建一个 issue 讨论您想要添加的功能。

## 📧 联系方式

如有问题或建议，请通过以下方式联系：
- 创建 GitHub Issue
- 邮箱：muscccm0903@hotmail.com
---

<p align="center">
  <sub>一个简单的工具，解决一个简单的需求。</sub>
</p>

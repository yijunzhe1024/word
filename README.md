# 单词记忆卡片工具

一个优雅、高效的单词记忆卡片工具，采用科学的记忆方法，帮助你更轻松地掌握新单词。

## 功能特点

- **双模式学习**：
  - 学习模式：先显示英文单词，翻转查看中文释义
  - 复习模式：先显示中文释义，翻转查看英文单词，强化记忆

- **进度跟踪**：直观的进度条显示学习进度，清晰统计已掌握和待学习单词数量

- **数据持久化**：自动保存学习进度和单词库，刷新页面不丢失数据

- **灵活的单词管理**：
  - 手动添加自定义单词
  - 批量导入CSV单词库（格式：单词,音标,释义,例句）
  - 复习库管理，可将单词移回学习库或标记为完全掌握



## 使用方法

1. 克隆或下载本项目
2. 直接在浏览器中打开`index.html`文件
3. 开始添加单词并使用卡片进行学习

## CSV导入格式

导入的CSV文件应遵循以下格式（使用英文逗号分隔）：

```
单词,音标,释义,例句
accomplish,/əˈkʌmplɪʃ/,v. 完成；实现,She accomplished her goal of learning English well.
persevere,/ˌpɜːsəˈvɪə(r)/,v. 坚持；不屈不挠,You need to persevere if you want to succeed.
```

## 技术栈

- HTML5
- CSS3
- JavaScript
- Font Awesome 图标
- 本地存储 (localStorage)

## 贡献

欢迎提交issues和pull requests来帮助改进这个工具。

## 许可证

[MIT](LICENSE)

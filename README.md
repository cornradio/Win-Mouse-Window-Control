# Windows 窗口管理工具

这是一个基于AutoHotkey的Windows窗口管理工具，让你能够更方便快捷地控制窗口的移动、大小调整和置顶状态。

## 功能特点

- 🖱️ 按住win+左键拖动任意位置移动窗口
- 📐 按住win+右键拖动调整窗口大小
- ⚡ 240Hz高刷新率，移动/调整更流畅
- 🔒 最小窗口限制保护（宽度≥100px，高度≥32px）

## 使用方法

1. 安装[AutoHotkey](https://www.autohotkey.com/)
2. 下载并运行脚本文件
3. 使用以下快捷键：
   - `win + 左键拖动`：移动窗口
   - `win + 右键拖动`：调整窗口大小

## 自定义设置

你可以通过修改脚本中的以下参数来自定义行为：

- `scaleFactor`：调整窗口大小时的灵敏度倍数（默认1.0）
- `Sleep`值：刷新率控制（默认4ms，相当于240Hz）
- `minWidth`/`minHeight`：窗口最小尺寸限制

## 注意事项

- 如果感觉系统响应变慢，可以适当降低刷新率
- 建议根据个人需求调整灵敏度倍数

## 许可证

MIT License

## 参考项目

https://github.com/hzhbest/Alt-Mouse-Window-Control
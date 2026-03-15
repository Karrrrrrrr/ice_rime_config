# Rime 输入法配置

基于 [雾凇拼音](https://github.com/iDvel/rime-ice) 的个人配置。

## 配置说明

### default.custom.yaml

- 默认输入方案：`rime_ice`
- 候选页大小：10
- 切换快捷键：`Ctrl+.`
- 翻页键：`-` 上翻页，`=` 下翻页（兼容搜狗逻辑）

### rime_ice.custom.yaml

- 扩展字母表，支持输入特殊字符（如 `-`, `/`, `_`, `[]` 等）
- 优化编程体验：中文模式下常用符号保持英文输出（如 `()`, `{}`, `[]`, `@`, `#` 等）

## 使用方法

将配置文件复制到 Rime 用户目录：

- Windows: `%AppData%\Rime`
- macOS: `~/Library/Rime`
- Linux: `~/.config/ibus/rime` 或 `~/.config/fcitx/rime`

复制后重新部署输入法即可生效。

# Cursor_Change_ID
这是一个简单的Python工具，用于修改 Windows环境下Cursor 编辑器的设备 ID。当因频繁切换账号导致设备被锁定时，可以使用此脚本重置设备 ID

## 功能特点

- 自动生成新的随机设备 ID
- 自动备份原配置文件

## 使用方法

下载 `cursor_change_id.exe` 脚本并执行


## 注意事项

- 脚本会在修改前自动创建配置文件的备份
- 备份文件保存在原配置文件相同目录下，格式为 `storage.json.backup_时间戳`
- 请确保在运行脚本前关闭 Cursor 编辑器
- 仅支持 windows 系统

## 配置文件位置

默认配置文件路径：
```
"~\AppData\Roaming\Cursor\User\globalStorage\storage.json"
```


[![Star History Chart](https://api.star-history.com/svg?repos=Muyan-Shen/Cursor_Change_ID&type=Area)](https://star-history.com/#Muyan-Shen/Cursor_Change_ID&Area)

## 免责声明

本脚本仅供学习和研究使用，使用本脚本可能违反 Cursor 的服务条款。请合理使用，风险自负。

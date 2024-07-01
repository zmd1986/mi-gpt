# 🚀 Roadmap

> 以下是一些可以优化的地方或新功能，仅作记录之用，暂时没有开发计划。

## 💪 优化

- 使用通知事件获取最新消息和设备播放状态
  - 提高及时响应速度
  - 适配更多机型使其支持连续对话
  - 减轻轮询对服务端造成的压力
- 自动识别设备型号
  - 通过查询设备 miot spec 文件，自动获取指令参数
  - 自动识别设备属性值是否有读取权限
- 添加镜像更新说明
  - 添加 db 文件导入/出教程，用于备份恢复对话历史记录

## ✨ 新功能

- 增强对话系统
  - 添加是否启用对话模式的开关
  - 支持通过语音命令清除上下文
- MIoT AI Agents
  - 支持小爱音箱控制米家设备
  - 通过 Agent 机制自动调用合适的工具（设备）
- RAG
  - wikis embedding
  - memory embedding
- 插件系统
  - 自定义语音指令
  - 联网查查询最新数据
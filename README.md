# 待办应用 (Todo Demo)

一个轻量级的全栈待办管理工具，前端使用 Vue 3，后端使用 json-server 模拟 REST API，数据持久化存储。

## 业务价值
- 解决日常任务容易遗忘的痛点
- 支持任务的增删改查、完成状态标记
- 每次任务自动记录创建时间（时:分:秒）
- 数据不丢失，刷新页面依然存在

## 技术栈
- 前端：Vue 3 (CDN)、原生 JavaScript、CSS 渐变视觉风格
- 后端：json-server (模拟 REST API)
- 通信：fetch API

## 本地运行

### 1. 启动后端
```bash
npm install -g json-server
json-server --watch db.json --port 3000

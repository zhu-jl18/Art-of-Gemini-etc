# Claude Code转接教程

## 什么是Claude Code转接

Claude Code是Anthropic推出的编程助手工具，可以通过转接方式在本地环境中使用。

## 设置步骤

### 1. 环境配置
```bash
# 设置环境变量
export ANTHROPIC_API_KEY="your-api-key-here"
export ANTHROPIC_BASE_URL="http://localhost:4141"
```

### 2. 本地代理设置
- 使用代理工具转发请求
- 配置本地端口映射
- 测试连接状态

### 3. 验证配置
```bash
# 测试连接
curl -X POST http://localhost:4141/v1/messages \
  -H "Content-Type: application/json" \
  -d '{"model": "claude-3-sonnet", "messages": [{"role": "user", "content": "Hello"}]}'
```

## 常见问题

### 连接失败
- 检查代理服务是否启动
- 确认端口号是否正确
- 验证API密钥有效性

### 响应缓慢
- 优化代理配置
- 选择更快的节点
- 调整超时设置

---

> ⚠️ 注意：请遵守相关服务条款，合理使用转接服务
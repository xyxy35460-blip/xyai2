# 🚀 Relay API（XYAI2 接口中转服务）

一个简单高效的 **API中转/兑换系统**，支持统一接口调用、兑换码充值、额度管理，适合搭建自己的 API 服务平台。

---

## 🌐 在线地址

👉 https://xyai2.top/

备用
https://xyai2.top/register

---

## 🧠 项目简介

本项目用于：

- API接口统一转发
- 兑换码充值系统
- Token / 算力管理
- 用户额度控制
- API变现（代理 / 分销）

👉 适合人群：
- 想搭建 API 平台的人
- 做 AI 工具 / SaaS 的开发者
- 想做 API 代理 / 变现的人

---

## ⚡ 核心功能

### ✅ 1. API中转

- 统一接口入口
- 支持多模型调用
- 简化开发流程

---

### 💰 2. 兑换码系统

- 输入兑换码自动充值
- 支持批量生成兑换码
- 可用于代理分销

---

### 🧩 3. Token / 算力管理

- 用户额度管理
- 实时扣费
- 使用记录统计

---

### 🔔 4. Webhook支持

- 请求完成自动回调
- 方便业务集成

---

### 🔐 5. 权限控制

- API Key 管理
- 用户隔离
- 请求限流

---

## 🚀 快速开始

### 1️⃣ 注册账号

👉 https://xyai2.top/

---

### 2️⃣ 获取 API Key

登录后进入控制台获取 API Key

---

### 3️⃣ 调用接口

```bash
curl https://xyai2.top/api/generate \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "ai-video",
    "prompt": "一个美女在海边说话"
  }'

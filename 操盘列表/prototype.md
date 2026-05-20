---
title: 交互原型
---

# 交互原型

<div class="prototype-container">
  <div class="prototype-info">
    <h3>📐 操盘列表原型</h3>
    <p>完整的操盘列表页面交互原型，包含所有功能模块的交互演示。</p>
    <div class="prototype-meta">
      <span>📅 更新时间：2026-01-29</span>
      <span>📦 版本：v1.1</span>
    </div>
  </div>
  <div class="prototype-actions">
    <a href="/prototype/trading-list.html" target="_blank" class="btn-primary">
      🚀 打开原型
    </a>
  </div>
</div>

## 原型说明

### 功能覆盖

| 模块 | 状态 | 说明 |
|------|------|------|
| 侧边栏 | ✅ 完成 | 运动类型树、折叠功能 |
| 顶部栏 | ✅ 完成 | 统计卡片、一键锁盘 |
| 筛选区 | ✅ 完成 | 多条件筛选、快捷筛选 |
| 数据表格 | ✅ 完成 | 赛事列表、联赛分组 |
| 批量操作 | ✅ 完成 | 批量上架/下架、分配操盘手 |
| 弹窗交互 | ✅ 完成 | 上架确认、操盘日志 |
| 告警轮播 | ✅ 完成 | 多告警自动轮播展示 |

### 交互演示

- **点击「上架」按钮**：弹出上架确认弹窗
- **点击「详情」按钮**：弹出操盘日志弹窗
- **勾选赛事**：显示批量操作栏
- **点击联赛标题**：折叠/展开该联赛赛事
- **按 `?` 键**：显示快捷键提示

<style>
.prototype-container {
  background: linear-gradient(135deg, #1a1f2e 0%, #252b3b 100%);
  border-radius: 12px;
  padding: 24px;
  margin: 24px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 24px;
}
.prototype-info h3 {
  margin: 0 0 8px 0;
  color: #58a6ff;
}
.prototype-info p {
  margin: 0 0 12px 0;
  color: #8b949e;
}
.prototype-meta {
  display: flex;
  gap: 16px;
  font-size: 12px;
  color: #6e7681;
}
.prototype-actions {
  display: flex;
  gap: 12px;
}
.btn-primary {
  background: #238636;
  color: #fff;
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
}
.btn-primary:hover {
  background: #2ea043;
}
</style>

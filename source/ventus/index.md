---
title: Ventus 专栏
date: 2026-02-16 18:10:00
---

# Ventus GPGPU 学习专栏

这个专栏用于系统记录我对 Ventus 的学习过程，目标不是“摘抄文档”，而是把代码、数据流和调试线索串起来，形成可复用的理解框架。

## 阅读说明

1. 全文中文。
2. 每篇会包含模块职责、关键代码路径、流程图与验证思路。
3. 图示优先 Mermaid，必要时补充仓库现有图。

## 建议阅读顺序

1. [Ventus GPGPU 架构总览：执行模型、模块边界与代码地图](/2026/02/16/ventus-01-architecture-overview/)
2. [Ventus CTA 调度器深挖：WG 缓冲、资源分配与 WF 下发全流程](/2026/02/16/ventus-02-cta-scheduler-deep-dive/)
3. Pipeline 执行通路（编写中）
4. 内存系统（L1/L2/MMU）
5. 仿真与测试闭环

## 专栏分组（持续扩展）

- 总览
- CTA 调度
- Pipeline
- 内存系统
- 顶层与参数
- 仿真与测试

## 进度维护

专栏进度（已完成/进行中/待办）统一维护在仓库文件：

- `docs/ventus-progress.md`

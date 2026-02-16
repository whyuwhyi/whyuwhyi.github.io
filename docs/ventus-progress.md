# Ventus 专栏进度台账

最后更新：2026-02-16

## 1. 项目状态概览

- 当前阶段：已启动
- 总目标：形成“总览 + 全系统深挖 + 仿真验证”的长期学习专栏
- 当前重点：完成总览与 CTA 调度器两篇基础文章，并建立目录与规范

## 2. 已完成

1. `done` - Ventus 专栏目录页初始化
- 链接：`/ventus/`
- 完成日期：2026-02-16
- 说明：建立专栏入口、阅读路线和更新规则

2. `done` - 文章《Ventus GPGPU 架构总览：执行模型、模块边界与代码地图》
- 链接：`/2026/02/16/ventus-01-architecture-overview/`
- 完成日期：2026-02-16
- 说明：建立全局心智模型，明确后续拆解路径

3. `done` - 文章《Ventus CTA 调度器深挖：WG 缓冲、资源分配与 WF 下发全流程》
- 链接：`/2026/02/16/ventus-02-cta-scheduler-deep-dive/`
- 完成日期：2026-02-16
- 说明：完整梳理 CTA scheduler 四大子模块与主数据流

## 3. 进行中

1. `doing` - Pipeline 执行通路总览（warp_schedule / issue / scoreboard / writeback）
- 目标：建立“取指-译码-发射-执行-回写”的跨文件追踪路径
- 风险：跨模块信号较多，需严格控制篇幅与图示复杂度

## 4. 待办（按系统分组）

### 4.1 Pipeline 与控制流

1. `todo` - Warp 调度与控制流（branch/SIMT stack/flush）
2. `todo` - Decode/Issue/Scoreboard 协同机制
3. `todo` - 执行单元（ALU/vALU/vFPU/MUL/SFU）

### 4.2 内存系统

1. `todo` - LSU 与访存请求路径
2. `todo` - L1 Cache（DCache/ICache/ShareMem/Atomic）
3. `todo` - L2 Cache 调度与关键数据结构
4. `todo` - MMU/TLB/PTW 接入路径

### 4.3 顶层与参数

1. `todo` - GPGPU_top 顶层连接与集群组织
2. `todo` - 参数体系与配置裁剪（`top/parameters.scala`）

### 4.4 仿真与测试

1. `todo` - sim-verilator 结构与运行方式
2. `todo` - `.metadata/.data` 格式与测试样例组织
3. `todo` - 从 testcase 到日志验证的闭环

## 5. 阻塞与依赖

1. `todo` - 补充可视化图素材（必要时从 `ventus-env/gpgpu/docs` 中选图）
2. `todo` - 确认后续是否引入统一的性能指标记录模板
3. `todo` - 随项目 upstream 变化，定期检查代码路径与文中描述是否一致

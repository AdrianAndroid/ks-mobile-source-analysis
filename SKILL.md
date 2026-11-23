---
name: skill-ks-mobile-source-analysis
description: 分析 Android、iOS 和 HarmonyOS 的移动端业务源码或本地可读代码，核对实际调用链、配置、状态和跨端行为差异，并在用户指定时将技术总结写入轻雀。
---

# 移动端源码分析

先确认问题、目标版本、实际 App、模块、构建目标和交付范围。遇到同名实现、插件或注入绑定时，确认实际接通的实现。分析任务保持目标工程只读。

## 按任务加载

| 任务范围 | 参考 |
|---|---|
| 所有源码分析、跨端对照与技术总结 | [通用走读、证据与验收](references/mobile-analysis.md) |
| Android 源码或 APK 可读代码 | [Android 分析](references/android-analysis.md) |
| iOS 源码或应用包 | [iOS 分析](references/ios-analysis.md) |
| HarmonyOS 工程 | [鸿蒙分析](references/harmony-analysis.md) |
| 用户明确指定写入轻雀 | [轻雀编辑与验收](references/qingque-editing.md) |

跨端任务分别核实各端实际行为。用户指定迁移基线时，以该端已验证行为为准。关键结论附可复核的位置、必要摘录和证据边界。详细链路按需画 ASCII 总图及子图。输出语言遵循通用参考中的交付用语。

## 积累经验

用户要求沉淀经验时，把跨端规则写入通用参考，平台规则或编辑技巧分别写入对应参考。每条写清适用场景、动作和如何验收。只提炼可复用且已核实的做法。项目的类名、地址、阈值、接口和文档链接留在项目报告中。

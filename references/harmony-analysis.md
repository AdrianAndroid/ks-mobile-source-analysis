# HarmonyOS 分析

- 从 ArkTS / ArkUI 入口和 build-profile.json5、module.json5、oh-package.json5 确认可用产品、目标、模块和依赖。
- 追 UIAbility、页面路由、插件注册、组件与宿主生命周期以及实际展示入口。涉及 HAR、HSP 或动态容器时追到当前工程可验证的接口和调用边界。
- 迁移对照先枚举已接通路径，再列缺口。分别核对状态的进程、账号和页面作用域，以及队列交接、ID 兼容、异步回包校验和复位条件。用基线用例检验目标端行为。

# Joda-Time

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `joda/time`，固定 Joda-Time 2.14.3，发布坐标见 [module.norm](joda/time/module.norm)。公开面覆盖 Instant、日期时间、时区、不可变运算、区间、Duration、Period、常用日期差和格式化。

独立 NAR 消费、Java interface 名义关系、闰日运算、时区、区间和格式化行为由 `JodaTimeBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[可运行示例](samples/README.zh-CN.md) 展示如何作为外部 Norm 依赖使用本库。

# Joda-Time 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 计算跨越闰日的发布日期截止时间。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../joda/time/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
2024-03-10
10
```

API 入口：[module.norm](../joda/time/module.norm) 列出公开的 `LocalDate` 和 `Days`。`Main.norm` 仍是该适配器自身的集成入口。

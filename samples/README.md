# Joda-Time samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Compute a release deadline across a leap day. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../joda/time/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
2024-03-10
10
```

API reference: [module.norm](../joda/time/module.norm) lists the exposed `LocalDate` and `Days`. The [adapter acceptance example](../examples/sample/joda/time/Main.norm) exercises additional binding behavior.

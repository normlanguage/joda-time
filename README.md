# Joda-Time

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `joda/time`. It pins Joda-Time 2.14.3 and defines its package coordinates in [module.norm](joda/time/module.norm). The public API covers instants, date-times, time zones, immutable operations, intervals, durations, periods, common date differences, and formatting.

`JodaTimeBindingIntegrationTest` covers standalone NAR consumption, nominal Java interface relationships, leap-day operations, time zones, intervals, and formatting. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

[Runnable samples](samples/README.md) demonstrate the library as an external Norm dependency.

[License](LICENSE)

[leakcanary-android-release](../../index.md) / [leakcanary](../index.md) / [ScreenOffTrigger](./index.md)

# ScreenOffTrigger

`class ScreenOffTrigger`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ScreenOffTrigger(application: Application, analysisClient: `[`HeapAnalysisClient`](../-heap-analysis-client/index.md)`, analysisExecutor: `[`Executor`](https://docs.oracle.com/javase/6/docs/api/java/util/concurrent/Executor.html)`, analysisCallback: (`[`HeapAnalysisJob.Result`](../-heap-analysis-job/-result/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { result ->
    SharkLog.d { "$result" }
  })` |

### Functions

| Name | Summary |
|---|---|
| [start](start.md) | `fun start(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [stop](stop.md) | `fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

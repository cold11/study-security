## 1、Metrics类型

​		prometheus中定义了四种metrics类型：

1.1、Counter：只增不减的计数器，其值只能在重新启动时递增或重置为零。例如，可以使用计数器表示已服务的请求数、已完成的任务数或错误数。

1.2、Gauge：是一种度量，它表示一个可以任意上下移动的数值。例如，温度或当前内存使用量。

1.3、Histogram：直方图对观察结果（通常是请求持续时间或响应大小）进行采样，并在可配置的存储桶中对其进行计数。它还提供了所有观测值的总和。

1.4、Summary：与Histogram类似，一个摘要采样观察（通常是请求持续时间和响应大小等）。它还提供观测值的总数和所有观测值的总和，同时计算滑动时间窗口上的可配置分位数。

## 2、代码示例

## 3、Grafana配置


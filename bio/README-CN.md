# 块设备 I/O 工具
## biosnoopx
基于 biosnoop 工具，增加了根据延迟进行过滤的功能。您可以使用 `-f` 参数指定延迟阈值，只显示大于此阈值的 IO 操作。

### 示例

监控延迟大于 0.5 毫秒的块设备 I/O

```shell
$ sudo ./biosnoopx -f 0.5
```


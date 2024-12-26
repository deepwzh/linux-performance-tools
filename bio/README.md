# Block Device I/O Tools
## biosnoopx
Based on the biosnoop tool, it adds the function of filtering according to latency. You can specify the latency threshold with the `-f` parameter, and only IO operations greater than this threshold will be displayed.

### example

snoop block device I/O with latency greater than 0.5ms

```shell
$ sudo ./biosnoopx -f 0.5
```

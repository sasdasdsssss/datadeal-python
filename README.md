# Python数据处理程序



## 功能简介

将发送端的数据转换成点云

## 返回类型

点云对象，pcl.PointCloud

```
pcl._pcl.PointCloud.PointCloud def __init__(self,
             *args: Any,
             **kwargs: Any) -> None
```

## 库

- [x] pcl（python3.6）
- [x] numpy
- [x] math
- [x] socket
- [x] time

## 软件日志

| 日期  |                  修改内容                  |
| :---: | :----------------------------------------: |
| 9.20  |         完成v1.0版本，基本功能实现         |
| 10.8  | 驱动程序存16帧后发送，python据此进行了调整 |
| 10.24 |     套接字函数修改，返回值改为点云文件     |


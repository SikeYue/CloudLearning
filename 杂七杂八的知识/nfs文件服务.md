# NFS文件系统

文件系统都工作在内核空间的。

文件系统就是一个引射表来管理硬盘上的各个磁道

`NFS(Network File System)网络文件系统` 就是一个挂载在本地的一个远程文件系统。需要一个NFS server和一个NFS client进行RPC调用完成访问。因为是运行在内核中，所以可以直接使用操作系统的磁盘操作函数，`Read() Wirte()`等。

协议是SOAP(Simple Object Access Protocol)。

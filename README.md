# RPCFramework
- 单机或集群聊天服务器项目部署过程中，存在软件拆分出若干业务模块的现象。
- 当每个模块都部署在相同或完全一致的若干台设备上时，局部出现bug会导致需要整体重新编译、部署，而且不能根据个模块根据是CPU密集型还是I/O密集型匹配到对应的服务器资源。
- 有鉴于此，本项目旨在构建和学习一套使用RPC通信框架解决单机和集群服务器部署过程中出现的痛点问题。

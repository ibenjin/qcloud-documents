## 什么是 CVM 实例？
**云服务器实例（Cloud Virtual Machine，CVM）**为您提供安全可靠的弹性计算服务。在云端提供服务，来实现计算需求。随着业务需求的变化，可以实时扩展或缩减计算资源，极大降低您的软硬件采购成本，简化 IT 运维工作。

不同的实例类型提供不同的计算和存储能力，适用于不同的应用场景，用户可以基于需要提供的服务规模而选择实例的计算能力、存储空间和网络访问方式。更多实例类型与适用场景，请参阅 [CVM 实例配置](/doc/product/213/2177) 与 [推荐选型](https://www.qcloud.com/act/recommended) 。实例启动后用户即可像使用传统计算机一样使用它，用户对启动的实例有完全的控制权。

## 什么是镜像？
**镜像** 是一种云服务器软件配置（操作系统、预安装程序等）的模板。腾讯云镜像提供启动云服务器实例所需的所有信息。要求用户通过镜像启动实例。镜像可以启动多个实例，供用户反复多次使用。通俗地说，镜像就是云服务器的“装机盘”。

腾讯云提供的镜像包括以下几种：

 - 公有镜像：所有用户均可使用，涵盖大部分主流操作系统；
 - 服务市场镜像：所有用户均可使用，除操作系统外还集成了某些特定应用程序；
 - 自定义镜像：仅创建者和共享对象可以使用，由现有运行的实例创建而来或由外部导入而来；
 - 共享镜像：由其他用户共享而来的镜像，仅能用作创建实例。

更多镜像介绍详见 [镜像概述](/doc/product/213/4940) 与 [镜像类型](/doc/product/213/4941) 。

## 实例的存储
实例的存储类似普通计算机，分为** 系统盘 **和** 数据盘 **：
- 系统盘：类似 Windows 系统下的 C 盘。系统盘中包含用于启动实例的镜像的完全副本，以及实例运行环境。启动时必须选择大于使用镜像的系统盘大小。
- 数据盘：类似 Windows 系统下的其他 D 盘、E 盘。数据盘保存用户数据，支持自由地扩容、挂载和卸载。

系统盘和数据盘都可以使用腾讯云提供的不同存储类型。有关更多信息，请参阅 [存储概述](/doc/product/213/4952) 。

## 实例的安全

- [策略控制](/doc/product/378/4513)：同一组云资源需要被多个不同账户控制时，用户可以使用策略控制管理对云资源的访问权限。
-  [安全组](/doc/product/213/5221)：通过使用安全组允许受信任的地址访问实例来控制访问。
- 登录控制：尽量使用 [SSH 密钥](/doc/product/213/6092) 方式登录用户的 Linux 类型实例，使用 [密码登录](/doc/product/213/6093) 的实例需要不定期修改密码。


# RPC 客户端

服务调用方法，通过使用服务提供方法，提供的lib接口，调用接口实现服务，不需要了解实现细节。

## RPC 服务

通过相同功能的系统称为一个服务，比如用户系统、订单系统。Swoft 框架为每个服务调用提供一个连接池和熔断器，且只有该服务才能使用。每个服务会定义一个名称，用于查询对应的连接池和熔断器。

- 有关连接池和熔断器的概念和介绍，请查看相关章节了解学习。
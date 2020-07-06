RPC通信基础框架

---

- **序列化**

    缺省基于ProtoStuff实现序列化机制，可扩展

- **注册中心**

    默认基于ZooKeeper实现服务注册和服务发现，可扩展

- **负载均衡**

    默认Random访问，可扩展

- **传输**

    基于Netty提供通信基础
    
- **通信协议**

    自定义基础协议格式

...


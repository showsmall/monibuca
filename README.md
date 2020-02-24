[主页](https://monibuca.com)

Monibuca 是一个开源的流媒体服务器开发框架，适用于快速定制化开发流媒体服务器，可以对接CDN厂商，作为回源服务器，也可以自己搭建集群部署环境。 丰富的内置插件提供了流媒体服务器的常见功能，例如rtmp server、http-flv、视频录制、QoS等。除此以外还内置了后台web界面，方便观察服务器运行的状态。 也可以自己开发后台管理界面，通过api方式获取服务器的运行信息。 Monibuca 提供了可供定制化开发的插件机制，可以任意扩展其功能。

⚡高性能
 
针对流媒体服务器独特的性质进行的优化，充分利用Golang的goroutine的性质对大量的连接的读写进行合理的分配计算资源，以及尽可能的减少内存Copy操作。使用对象池减少Golang的GC时间。
 
🔧可扩展
 
流媒体服务器的个性化定制变的更简单，基于Golang语言，开发效率更高，独创的插件机制，可以方便用户定制个性化的功能组合，更高效率的利用服务器资源。
 
📈可视化
 
功能强大的仪表盘可以直观的看到服务器运行的状态、消耗的资源、以及其他统计信息。用户可以利用控制台对服务器进行配置和控制。
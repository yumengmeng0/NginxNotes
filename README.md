# NginxNotes
Nginx Notes

# 1. Nginx优点

1. 占用内存少，并发能力强
2. 支持热部署

# 2. 应用场景

1. http服务器：网页静态资源服务器
2. 虚拟主机：一台服务器虚拟出多个网站
3. 反向代理，负载均衡


# 3. 配置虚拟主机

虚拟主机值在一台服务器中使用Nginx配置多个网站

> 如何区分不同网站：  
   > 1. 端口  
   > 2. 域名

# 4. 反向代理

代理就是一个中介，A和B本来可以直连，中间插入一个C，C就是中介。

## 4.1 正向代理

正向代理的是客户端，服务端不知道实际发起请求的客户端。

## 4.2 反向代理

反向代理代理服务器。

### 4.2.1 Nginx实现反向代理

Nginx作为反向代理服务器安装在服务端，Nginx功能就是把功能转发给后面的应用服务器。


# 5. 负载均衡

将大量请求合理地发送给不同的服务器

## 5.1 负载均衡策略

> 轮询：默认策略，每个请求安装时间顺序逐一分配到不同的服务器，如果某一个服务器下线，能自动剔除
> 权重：    







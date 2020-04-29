#  spring-cloud-family
 spring-cloud-family learn day by day

# 1. Eureka 特殊配置

- [microservice-consumer-movie:8010](http://192.168.31.151:8010/info)
- [DESKTOP-TK9HDOQ:microservice-provider-user:8000](http://192.168.31.151:8000/info)



**客户端 使用相同配置**

```

// autoRegister = false 代表不注册到Eureka Server
//@EnableDiscoveryClient(autoRegister = false)

@EnableEurekaClient

```



## 1.1 @EnableDiscoveryClient(autoRegister = false/true) 启动的区别；

**@EnableDiscoveryClient(autoRegister = false)**

![image-20200429094245181](http://q8xc9za4f.bkt.clouddn.com/cloudflare/image-20200429094245181.png)











![image-20200429094411541](http://q8xc9za4f.bkt.clouddn.com/cloudflare/image-20200429094411541.png)



**@EnableDiscoveryClient**

![image-20200429094838053](http://q8xc9za4f.bkt.clouddn.com/cloudflare/image-20200429094838053.png)

![image-20200429094926275](http://q8xc9za4f.bkt.clouddn.com/cloudflare/image-20200429094926275.png)
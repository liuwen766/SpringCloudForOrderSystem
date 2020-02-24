微服务Spring Cloud学习。
1.（myspringclouddemo）添加父工程依赖。 spring-boot-starter-parent、spring-boot-starter-web
2.（registrycenter）添加注册中心依赖。spring-cloud-starter-netflix-eureka-server
3.（provider）添加服务提供者。spring-cloud-starter-netflix-eureka-client
4.（consumer）添加服务消费者。spring-cloud-starter-netflix-eureka-client
5.（gateway）服务网关。spring-cloud-starter-netflix-eureka-client、spring-cloud-starter-netflix-zuul
6.（ribbon）负载均衡。spring-cloud-starter-netflix-eureka-client
7.（feign）负载均衡。spring-cloud-starter-netflix-eureka-client、spring-cloud-starter-openfeign
8.（hystrix）容错机制。spring-cloud-starter-netflix-eureka-client、spring-cloud-starter-openfeign、spring-boot-starter-actuator、spring-cloud-starter-netflix-hystrix、spring-cloud-starter-netflix-hystrix-dashboard
9.（nativeconfigserver、nativeconfigclient）本地配置中心。spring-cloud-config-server、spring-cloud-starter-config
10.（configserver、configclient）远程配置中心。spring-cloud-config-server、spring-cloud-starter-config
11.（zipkin、zipkinclient）服务跟踪。zipkin-server、zipkin-autoconfigure-ui





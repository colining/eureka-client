# Provider实践
* pom引入，项目入口添加注解
* Provider基本可以理解为是一个restful的后台项目，在Eureka注册了一下，如果还想用
其他spring-cloud的服务，就需要导包，做配置，
* 当前provider中使用了zipkin，需要在yml中配置zipkin的base-url以及其他参数
* 在做熔断，重试时可以让程序休眠，以此测试。
* 服务降级在当前情况下并没有测试
# spring-cloud-config-server
基于spring-cloud-config2.0.3构建的服务配置中心 
</br>eureka的端口默认是8761建议使用默认否者会有坑。
</br>你很倔强就要使用自定义端口时；可以很明确的告诉你恭喜你先遇到了我，这个坑虽说没填上，但给你找到了出坑的路，异常如下： com.sun.jersey.api.client.ClientHandlerException: java.net.ConnectException: Connection refused: connect   java.lang.IllegalStateException: No instances found of configserver (CONFIGSERVER) 该错误已找到解决方式 请看Wiki。

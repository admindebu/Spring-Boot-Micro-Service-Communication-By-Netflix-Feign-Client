# Spring-Boot-Micro-Service-Communication-By-Netflix-Feign-Client
This Example help you to understand communication among micro services with Netflix Feign Client
# Required Software 
1. Java 8 
2. Apache maven configured

# Youtube Video Link : https://youtu.be/1ey-O8Y5YJE

# Download the Employee-producer , Employee-consumer and Eureka Server zip file
# Unzip it and do maven build by mvn clean install
# Just run the main file

Here we are calling employee-producer server in employee-consumer service with Feign client

# Eureka server running on : 8090

# Required annotation : 
@EnableDiscoveryClient
@EnableFeignClients
@FeignClient(name="calling service name")
@EnableEurekaServer




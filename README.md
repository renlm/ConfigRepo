# 配置仓库

#### 介绍
私有配置存储

#### Spring Cloud
```
https://spring.io/projects/spring-cloud
```

#### Spring Cloud CLI 

```
https://repo.spring.io/ui/native/release/org/springframework/boot/spring-boot-cli
```

```
tar xvfz spring-boot-cli-2.6.13-bin.tar.gz
cd spring-2.6.13
export PATH=$PATH:$PWD/bin
```

```
spring install org.springframework.cloud:spring-cloud-cli:2.2.4.RELEASE
```

#### 加密解密

```
$ keytool -genkeypair -alias keyStore -keyalg RSA \
    -dname "CN=Web Server,OU=Unit,O=Organization,L=City,S=Province,C=CN" \
    -keypass 123654 -keystore keyStore.jks -storepass 123654
```
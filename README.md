# 配置仓库

#### 介绍
私有配置存储

#### Spring Cloud

```
https://spring.io/projects/spring-cloud
```

#### 加密解密

```
$ keytool -genkeypair -alias keyStore -keyalg RSA \
    -dname "CN=Web Server,OU=Unit,O=Organization,L=City,S=Province,C=CN" \
    -keypass 123654 -keystore keyStore.jks -storepass 123654
```

```
$ curl localhost:7000/decrypt -s -d {密文}
$ curl localhost:7000/encrypt -s -d {明文}
```
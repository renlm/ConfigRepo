# 配置仓库

#### 介绍
私有配置存储

```
$ keytool -genkeypair -alias keyStore -keyalg RSA \
    -dname "CN=Web Server,OU=Unit,O=Organization,L=City,S=Province,C=CN" \
    -keypass 123654 -keystore keyStore.jks -storepass 123654
```
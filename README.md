# spring-batch-docker
docker上でspring batchを動かします

### 初期設定
* https://start.spring.io/

### ビルド
```
$ docker build --build-arg JAR_FILE=build/libs/\*.jar -t springio/gs-spring-batch-docker .
```

### 実行
```
$ docker run -p 8080:8080 -t springio/gs-spring-batch-docker
```

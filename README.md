# maven-repository
lzz.io maven repository



# 1、配置仓库

```xml
<repositories>
    <repository>
        <id>lzz-github-maven-repo</id>
        <url>https://raw.githubusercontent.com/lzz-io/maven-repository/master/repository</url>
    </repository>
</repositories>
```



# 2、引入jar

```xml
<dependency>
  <groupId>io.lzz</groupId>
  <artifactId>lzzio-core</artifactId>
  <version>x.x.x</version>
</dependency>
```


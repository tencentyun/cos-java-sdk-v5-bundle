# cos-java-sdk-v5-bundle

由于cos-java-sdk-v5中依赖了一些第三方库，例如：Apache Commons Http Client、用于解析回包XML的Jackson库以及用于时间处理的JodaTime库等，考虑到某些使用cos-java-sdk-v5的场景可能也会依赖这些第三方库，而版本与COS的不尽相同。因此，这里提供一个cos java sdk的bundle包，打包SDK的所有依赖。

## Maven坐标

```xml
    <groupId>com.qcloud</groupId>
    <artifactId>cos_api-bundle</artifactId>
    <version>${cos.java.sdk.version}</version>
    
```


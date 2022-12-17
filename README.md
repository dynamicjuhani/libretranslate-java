LibreTranslate Java Restful Client
---
At some point, we had to translate the Java text, but we didn't find comfortable and understandable libraries, so I wrote my decision.
### `Add as depend:`

| **Gradle:**

```groovy
repositories {
    // other repositories
    maven {
        name = "clojars.org"
        url = uri("ttp://clojars.org/repo")
    }
}

dependencies {
    // other depends
    implementation 'net.clojars.suuft:libretranslate-java:1.0.0'
}
```

| **Maven:**

Repository:

```xml
<repository>
    <id>clojars.org</id>
    <url>http://clojars.org/repo</url>
</repository>
```

Depend:

```xml

<dependency>
    <groupId>net.clojars.suuft</groupId>
    <artifactId>libretranslate-java</artifactId>
    <version>1.0.0</version>
</dependency>
```
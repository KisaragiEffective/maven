# The KisaragiEffective's Maven Repository
You can use this repository by those methods:
```xml:pom.xml
<!-- pom.xml -->
<repository>
  <url>https://github.com/KisaragiEffective/maven/</url>
</repository>
```

```groovy
// build.gradle
repositories {
  repository(url = URI("https://github.com/KisaragiEffective/maven/"))
}
```

```kotlin
// build.gradle.kts
repositories {
  /* other repos */
  maven {
    url = java.net.URI("https://github.com/KisaragiEffective/maven/")
  }
}
```

**NOTE ABOUT LICENCE**: LICENSE is different on *each* artifact!

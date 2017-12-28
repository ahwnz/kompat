## Kotlin Compatibility Project (Kompat)

Kompat is a collection of small libraries that provide 'Kompatibility' for Java Libraries.


## Current Kompat Libraries

- [kompat-hk2](https://github.com/ahwnz/kompat-hk2)
- [kompat-json-lib](https://github.com/ahwnz/kompat-json-lib)
- [kompat-time](https://github.com/ahwnz/kompat-time)


## Using Kompat

Kompat libraries are available through the kompat repository hosted on [Bintray](https://bintray.com/ahwnz/kompat). 

To use any Kompat library with Maven, add the following to the repository section of your `pom.xml`:

```xml
<repository>
    <id>bintray-ahwnz-kompat</id>
    <name>bintray-kompat</name>
    <url>https://dl.bintray.com/ahwnz/kompat</url>
</repository>
```

To use any Kompat library with Gradle, add the follwoing to your `build.gradle`:

```groovy
repositories {
    maven {
        url  "https://dl.bintray.com/ahwnz/kompat" 
    }
}
```

## Licensing

All Kompat libraries are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

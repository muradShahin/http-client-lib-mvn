# http-client-lib-mvn

A lightweight, reusable **Spring Boot** library that provides an HTTP client abstraction using `RestTemplate`. Ideal for integrating consistent RESTful API calls across multiple Spring Boot services.

## 🚀 Features

- Preconfigured `RestTemplate` bean
- Easy-to-use HTTP client service
- Can be included as a Maven dependency
- GitHub Package compatible

## 📦 How to Use

### 1. Add Dependency to Your Maven Project

Make sure your `~/.m2/settings.xml` includes your GitHub credentials.

Then add this to your `pom.xml`:

```xml
<dependency>
  <groupId>com.github.muradShahin</groupId>
  <artifactId>http-client-lib-mvn</artifactId>
  <version>0.0.2</version>
</dependency>

<repositories>
  <repository>
    <id>github</id>
    <url>https://maven.pkg.github.com/muradShahin/http-client-lib-mvn</url>
  </repository>
</repositories>

# Fast OpenAPI Generator Maven Plugin (Parent POM)

This project provides a pre-configured **parent POM** to rapidly bootstrap Spring Boot microservices using a custom OpenAPI generator.

It brings together:
- 🧬 **[fast-openapi-generator](https://github.com/youssefehaab/fast-openapi-generator)** as a codegen plugin
- 🧩 Essential Spring Boot and SpringDoc dependencies
- ⚙️ MapStruct and Lombok integration
- ⚡ Fast and opinionated defaults for rapid microservice development

## 📦 Usage

In your microservice project’s `pom.xml`, set this parent:

```xml
<parent>
  <groupId>com.chesterford</groupId>
  <artifactId>fast-openapi-generator-maven-plugin</artifactId>
  <version>1.0.0</version>
</parent>

<repositories>
<repository>
    <id>github</id>
    <url>https://maven.pkg.github.com/youssefehaab/fast-openapi-generator-maven-plugin</url>
</repository>
</repositories>
```
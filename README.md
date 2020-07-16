
Spring Core
=================
![Maven Version][maven-version]  ![Java Version][java-version] [![MIT License][license-shield]][license-url]

![Spring Core][spring-core]  ![[Spring Context]][spring-context]

<!-- Getting Started -->
## Getting Started
1. Create a maven project. (using your favorite IDE like eclipse and Intellij)
2. Copy these dependencies inside the `pom.xml`:
    ```xml
    <dependencies>
    ...
        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-core</artifactId>
            <version>5.2.7.RELEASE</version>
        </dependency>
        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-context</artifactId>
            <version>5.2.7.RELEASE</version>
        </dependency>
    ...
    </dependencies>
    ```
3. Create `bean.xml` file inside resources folder:
    ```xml
    <beans xmlns="http://www.springframework.org/schema/beans"
           xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
           xsi:schemaLocation="http://www.springframework.org/schema/beans
           http://www.springframework.org/schema/beans/spring-beans.xsd">
    
    </beans>
    ```

<!-- LICENSE -->
## License
Distributed under the MIT License. See [LICENSE][license-url] for more information.
   
<!-- MARKDOWN LINKS & IMAGES -->
[maven-version]:    https://img.shields.io/static/v1?label=maven&message=v3.6.3&color=blue&logo=apache%20maven&logoColor=%23fff&style=flat-square
[java-version]:     https://img.shields.io/static/v1?label=java&message=v11.0.7&color=blue&logo=java&logoColor=%23fff&style=flat-square
[spring-core]:      https://img.shields.io/maven-central/v/org.springframework/spring-core/5.2.7.RELEASE?color=orange&label=spring-core&logo=spring&logoColor=%23fff&style=flat-square
[spring-context]:   https://img.shields.io/maven-central/v/org.springframework/spring-context/5.2.7.RELEASE?color=orange&label=spring-context&logo=spring&logoColor=%23fff&style=flat-square
[license-shield]:   https://img.shields.io/github/license/prateek-mureliya/Jigyasa?logoColor=%23fff&style=flat-square
[license-url]:      ./LICENSE
# wo-web-app-server-embedded
An embedded version of wo web application server for application development under Springboot architecture. As to *wo web application server*, please refer to its repository for introduction. User can use this embeddedd web application server for your project development just like some other embedded web application servers,for example,embedded-tomcat, embedded-jetty etc.

## Usage

1. Install all libraries in diretory *./repository/* to your project repository, and add dependencies in your Springboot project pom.xml.

```xml
<dependency>
    <groupId>wo.app.server</groupId>
    <artifactId>annotation</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>

<dependency>
    <groupId>wo.server.spring.boot</groupId>
    <artifactId>starter</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

2. Run *SpringApplication* program to start the embedded wo application server in IDE.  

3. The default port of wo application server is 8080, you can set server port in *application.properties* as below:

   ```properties
   wo.server.port=8082
   ```

   
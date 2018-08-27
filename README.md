# vpc-public-maven

This repository exposes various java projects (binaries and sources) accessible as maven denpendencies.

To use one of these dependencies one have to register the repository in your project's pom.xml by adding the following code :

```xml
<repositories>
   ...
        <repository>
            <id>vpc-public-maven</id>
            <url>https://raw.github.com/thevpc/vpc-public-maven/master</url>
        </repository>
   ...
 </repositories>
```


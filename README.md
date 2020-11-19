# maven-version-rules

Rules to use when executing `mvn versions:display-dependency-updates`

```
        <plugin>
          <groupId>org.codehaus.mojo</groupId>
          <artifactId>versions-maven-plugin</artifactId>
          <version>2.8.1</version>
          <configuration>
            <rulesUri>https://raw.githubusercontent.com/axa-health/maven-version-rules/main/maven-version-rules.xml</rulesUri>
          </configuration>
        </plugin>
```

Fork from https://github.com/fit2cloud/aliyun-oss-plugin

### ChangeLog
1. Upgrade [aliyun-oss-java-sdk](https://github.com/aliyun/aliyun-oss-java-sdk) to 2.8.1
2. Config HTTPS protocol instead of HTTP
3. Print real object URL

### Reference
1. https://stackoverflow.com/a/20457525/3171537  
2. Setting skip InjectedTest. Credit from https://groups.google.com/forum/#!topic/jenkinsci-dev/POdTEQKq89s
```
<plugin> 
  <groupId>org.jenkins-ci.tools</groupId> 
  <artifactId>maven-hpi-plugin</artifactId> 
  <configuration> 
    <disabledTestInjection>true</disabledTestInjection> 
  </configuration> 
</plugin> 
```

![](http://118.89.45.123:999/waffmy/2017/08/20170820174530_0.png)

```
#收集的比较快的maven仓库
http://maven.wso2.org/nexus/content/groups/public/
http://jcenter.bintray.com/
http://maven.antelink.com/content/repositories/central/
http://nexus.openkoala.org/nexus/content/groups/Koala-release/
http://maven.tmatesoft.com/content/groups/public/
http://mavensync.zkoss.org/maven2/
http://maven.springframework.org/release/

```


```
<mirror>
    <id>UK</id>
    <name>UK Central</name>
    <url>http://uk.maven.org/maven2</url>
    <mirrorOf>central</mirrorOf>
</mirror>

<mirror>
    <id>sonatype</id>
    <name>sonatype Central</name>
    <url>http://repository.sonatype.org/content/groups/public/</url>
    <mirrorOf>central</mirrorOf>
</mirror>

<mirror>
    <id>jboss-public-repository-group</id>
    <name>JBoss Public Repository Group</name>
    <url>http://repository.jboss.org/nexus/content/groups/public</url>
    <mirrorOf>central</mirrorOf>
</mirror>

```
# lantaojin-maven-repo
My personal maven repository.

## Usage
pom.xml:
```xml
    <distributionManagement>
        <repository>
            <id>lantaojin-maven-repo.releases</id>
            <url>https://raw.githubusercontent.com/lantaojin/lantaojin-maven-repo/master/releases</url>
        </repository>
        <snapshotRepository>
            <id>lantaojin-maven-repo.snapshots</id>
            <url>https://raw.githubusercontent.com/lantaojin/lantaojin-maven-repo/master/snapshots</url>
        </snapshotRepository>
    </distributionManagement>
```

# mpcli
A Minecraft Plugin Skeleton Builder

### Install

```npm i -g minecraft-plugins-skeleton-builder```


### Example

```
➜ mpcli
project name: Test
package name: moe.satori.plugins
main method: (main):
use Git? (Y/N) : y
Initialized empty Git repository in /Users/satori/IdeaProjects/Test/.git/

Version List:
1 - 1.9.4-R0.1-SNAPSHOT
2 - 1.10.2-R0.1-SNAPSHOT
3 - 1.11-R0.1-SNAPSHOT
4 - 1.11.1-R0.1-SNAPSHOT
5 - 1.11.2-R0.1-SNAPSHOT
6 - 1.12-R0.1-SNAPSHOT
7 - 1.12.1-R0.1-SNAPSHOT
8 - 1.12.2-R0.1-SNAPSHOT
9 - 1.13-pre7-R0.1-SNAPSHOT
10 - 1.13-R0.1-SNAPSHOT
11 - 1.13.1-R0.1-SNAPSHOT
12 - 1.13.2-R0.1-SNAPSHOT
13 - 1.14-R0.1-SNAPSHOT
14 - 1.14.1-R0.1-SNAPSHOT
select PaperSpigot API version: [1.14.1-R0.1-SNAPSHOT]:
SUCCESS

➜ tree Test
Test
├── pom.xml
└── src
    ├── config.yml
    ├── main
    │   └── java
    │       └── moe
    │           └── satori
    │               └── plugins
    │                   └── main.java
    └── plugin.yml

6 directories, 4 files

➜ cat Test/src/plugin.yml
name: Test
main: moe.satori.plugins.main
version: 1.00
```

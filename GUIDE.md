## Building

If you want to try out the cutting-edge features, you can build with the following commands. (Java 1.8 is needed to build the master branch)

  1. 可以直接将/maven_dependencies目录下的maven作为dubbo运行依赖的仓库,解压至操作系统中,idea中同步配置好即可.
     这样做是在网络通信不好或者彻底离线的场景下,也能本地运行调试.
  2. 将源码编译后安装到本地的maven仓库
     ```
     mvn clean install -Dmaven.test.skip=true
     ```
  3. 生成idea项目
     ```
     mvn idea:idea
     ```
## Asserts
   maven&本地依赖仓库
   /maven_dependencies/apache-maven-3.8.7.zip 
